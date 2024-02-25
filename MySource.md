## Table of Contents

- [C S S](#CSS)
    - [Browser Specific Styles Sniff](#BrowserSpecificStylesSniff)
- [Channels](#Channels)
    - [Disallow Self Actions Sniff](#DisallowSelfActionsSniff)
    - [Include Own System Sniff](#IncludeOwnSystemSniff)
    - [Include System Sniff](#IncludeSystemSniff)
    - [Unused System Sniff](#UnusedSystemSniff)
- [Commenting](#Commenting)
    - [Function Comment Sniff](#FunctionCommentSniff)
- [Debug](#Debug)
    - [Debug Code Sniff](#DebugCodeSniff)
    - [Firebug Console Sniff](#FirebugConsoleSniff)
- [Objects](#Objects)
    - [Assign This Sniff](#AssignThisSniff)
    - [Create Widget Type Callback Sniff](#CreateWidgetTypeCallbackSniff)
    - [Disallow New Widget Sniff](#DisallowNewWidgetSniff)
- [P H P](#PHP)
    - [Ajax Null Comparison Sniff](#AjaxNullComparisonSniff)
    - [Eval Object Factory Sniff](#EvalObjectFactorySniff)
    - [Get Request Data Sniff](#GetRequestDataSniff)
    - [Return Function Value Sniff](#ReturnFunctionValueSniff)
- [Strings](#Strings)
    - [Join Strings Sniff](#JoinStringsSniff)



</details><details open id='CSS'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">C S S</summary>
<hr>
<details open id='BrowserSpecificStylesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Avoid Browser-Specific Styles</summary>
Browser-specific styles in CSS files should be avoided to ensure styles work across all platforms and devices. This rule checks CSS filenames for browser-specific indicators, such as *_ie.css, *_moz.css, and ignores them, indicating that specialized stylesheets for specific browsers are not recommended for general use.

<table style="width: 100%">
 <tr>
  <th><b>Valid: General CSS without browser-specific suffix.</b></th>
  <th><b>Invalid: Browser-specific suffix used in CSS.</b></th>
 </tr>
 <tr>
<td>

```css
styles.css
```

</td>
<td>

```css
styles_ie8.css
```

</td>
 </tr>
 <tr>
  <th><b>Valid: CSS filename without a browser-specific suffix.</b></th>
  <th><b>Invalid: Browser-specific suffix indicating it's for WebKit browsers only.</b></th>
 </tr>
 <tr>
<td>

```css
responsive.css
```

</td>
<td>

```css
layout_webkit.css
```

</td>
 </tr>
</table>
</details>
</details><details open id='Channels'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Channels</summary>
<hr>
<details open id='DisallowSelfActionsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Self or Static for Public Methods in Action Classes</summary>
In Action classes, static calls to public methods must not use 'self' or 'static'. Instead, directly reference the class name. This ensures clarity in which class the method is being called from, especially in the context of inheritance.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Using 'self' to call a public method.</b></th>
  <th><b>Valid: Use the class name to call a public method.</b></th>
 </tr>
 <tr>
<td>

```php
class SomeActions {
    public function doSomething() {
        // Some code here
    }
    public function execute() {
        self::doSomething();
    }
};
```

</td>
<td>

```php
class SomeActions {
    public function doSomething() {
        // Some code here
    }
    public function execute() {
        SomeActions::doSomething();
    }
};
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Using 'static' to call a public method.</b></th>
  <th><b>Valid: Use the class name to call a public method.</b></th>
 </tr>
 <tr>
<td>

```php
class SomeActions {
    public function doSomething() {
        // Some code here
    }
    public function execute() {
        static::doSomething();
    }
};
```

</td>
<td>

```php
class SomeActions {
    public function doSomething() {
        // Some code here
    }
    public function execute() {
        SomeActions::doSomething();
    }
};
```

</td>
 </tr>
</table>
</details><details open id='IncludeOwnSystemSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Include Own System Prevention</summary>
Ensures that a system does not include itself in the actions file.

<table style="width: 100%">
 <tr>
   <th><b>Invalid: Including own system.</b></th>
   <th><b>Valid: Including different system.</b></th>
 </tr>
 <tr>
<td>

```php
$this->includeSystem('OwnActions'); // OwnActions is the current system, inclusion is unnecessary.
```

</td>
<td>

```php
$this->includeSystem('OtherActions'); // Including other systems is allowed.
```

</td>
 </tr>
 <tr>
   <th><b>Invalid: Including own asset type in asset actions file.</b></th>
   <th><b>Valid: Including different asset type.</b></th>
 </tr>
 <tr>
<td>

```php
$this->includeAsset('OwnAssetType'); // OwnAssetType is the current asset type, inclusion is unnecessary.
```

</td>
<td>

```php
$this->includeAsset('OtherAssetType'); // Including other asset types is allowed.
```

</td>
 </tr>
 <tr>
   <th><b>Invalid: Including own widget type in widget actions file.</b></th>
   <th><b>Valid: Including different widget type.</b></th>
 </tr>
 <tr>
<td>

```php
$this->includeWidget('OwnWidgetType'); // OwnWidgetType is the current widget type, inclusion is unnecessary.
```

</td>
<td>

```php
$this->includeWidget('OtherWidgetType'); // Including other widget types is allowed.
```

</td>
 </tr>
</table>
</details><details open id='IncludeSystemSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Including Systems and Assets</summary>
Ensures systems, asset types, and libraries are explicitly included before they are used. This is particularly relevant in MySource CMS to prevent runtime errors due to missing dependencies.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Including a system using includeSystem.</b></th>
  <th><b>Invalid: Using a system's static method without including it first.</b></th>
 </tr>
 <tr>
<td>

```php
Channels::includeSystem('MySystem');
MySystem::myStaticMethod();
```

</td>
<td>

```php
// Missing: Channels::includeSystem('MySystem');
MySystem::myStaticMethod();
```

</td>
 </tr>

<tr>
  <th><b>Valid: Including an asset type with includeAsset.</b></th>
  <th><b>Invalid: Creating an instance of an asset type without including it first.</b></th>
 </tr>
<tr>
<td>

```php
Channels::includeAsset('MyAssetType');
$asset = new MyAssetType();
```

</td>
<td>

```php
// Missing: Channels::includeAsset('MyAssetType');
$asset = new MyAssetType();
```

</td>
</tr>

<tr>
  <th><b>Valid: Including a library file directly with require_once.</b></th>
  <th><b>Invalid: Calling a function from a library file without including the file.</b></th>
 </tr>
<tr>
<td>

```php
require_once 'path/to/myLibrary.inc';
myLibraryFunction();
```

</td>
<td>

```php
// Missing: require_once 'path/to/myLibrary.inc';
myLibraryFunction();
```

</td>
</tr>

<tr>
  <th><b>Valid: Including a widget type for special cases.</b></th>
  <th><b>Invalid: Creating an instance of a widget type without the special include.</b></th>
 </tr>
<tr>
<td>

```php
Channels::includeWidget('MyWidget');
$widget = new MyWidgetWidgetType();
```

</td>
<td>

```php
// Missing: Channels::includeWidget('MyWidget');
$widget = new MyWidgetWidgetType();
```

</td>
</tr>

</table>
</details><details open id='UnusedSystemSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unused System Include</summary>
Ensures that systems and asset types are used if they are included.

<table style="width: 100%">
 <tr>
  <th><b>Valid: The included system or asset type is used.</b></th>
  <th><b>Invalid: The included system or asset type is never used.</b></th>
 </tr>
 <tr>
<td>

```php
$systemName = 'logger';
Logger::log('Message');
```

</td>
<td>

```php
$systemName = 'logger';
// No reference to Logger or its methods
```

</td>
 </tr>
</table>
<table style="width: 100%">
 <tr>
  <th><b>Valid: The included asset type is used.</b></th>
  <th><b>Invalid: The included asset type is never used.</b></th>
 </tr>
 <tr>
<td>

```php
$systemName = 'imageassettype';
class ImageAsset extends Asset {
}
```

</td>
<td>

```php
$systemName = 'imageassettype';
// No extension or implementation related to ImageAsset
```

</td>
 </tr>
</table>
<table style="width: 100%">
 <tr>
  <th><b>Valid: The included widget type is used in an implementation.</b></th>
  <th><b>Invalid: The included widget type is never used in any implementation.</b></th>
 </tr>
 <tr>
<td>

```php
$systemName = 'sliderwidgettype';
class Slider implements Widget {
}
```

</td>
<td>

```php
$systemName = 'sliderwidgettype';
// No class implements Widget related to Slider
```

</td>
 </tr>
</table>
</details>
</details><details open id='Commenting'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Commenting</summary>
<hr>

<details open id='FunctionCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Proper Use of @api Tags in Function Comments</summary>
The @api tag must come first in the list of @api tags within a function comment. There must be one blank line before the @api tag, and no blank lines before additional @api- prefixed tags. Lastly, @api tags must be the last tags in a function comment.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct @api tag placement and spacing.</b></th>
  <th><b>Invalid: The @api tag is not first.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Example function
 *
 * @param string $param Description
 * @return void
 *
 * @api
 * @api-extra Detail
 */
function example($param) {}
```

</td>
<td>

```php
/**
 * Example function
 *
 * @return void
 * @api  // Invalid: @api tag should come first in the @api tag list
 * @api-extra Detail
 */
function example($param) {}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Incorrect spacing before @api tag.</b></th>
  <th><b>Invalid: Blank line before @api- prefixed tag.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Example function
 *
 * @param string $param Description
 * @api  // Invalid: There should be one blank line before @api tag
 */
function example($param) {}
```

</td>
<td>

```php
/**
 * Example function
 *
 * @param string $param Description
 * @api
 *
 * @api-extra Detail  // Invalid: There should be no blank line before the @api-extra tag
 */
function example($param) {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct order and spacing for multiple @api tags.</b></th>
  <th><b>Invalid: @api tags are not the last tags in comment.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Example function
 *
 * @param string $param Description
 * @return void
 *
 * @api
 * @api-extra Detail1
 * @api-note Note
 */
function example($param) {}
```

</td>
<td>

```php
/**
 * Example function
 *
 * @param string $param Description
 * @api
 * @api-extra Detail
 * @return void  // Invalid: @api tags must be the last tags in a function comment
 */
function example($param) {}
```

</td>
 </tr>
</table>
</details>

</details><details open id='Debug'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Debug</summary>
<hr>
<details open id='DebugCodeSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Debug Code Usage</summary>
Usage of debug code like Debug::methodName() must be removed from production code.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Usage of debug function.</b></th>
  <th><b>Valid: Code without debug function usage.</b></th>
 </tr>
 <tr>
<td>

```php
$debugResult = Debug::<em>someDebugFunction</em>();
```

</td>
<td>

```php
$result = SomeClass::<em>someFunction</em>();
```

</td>
 </tr>
</table>
</details><details open id='FirebugConsoleSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Avoid Console Naming Conflicts</summary>
Variables, functions, and labels must not be named "console" to avoid conflicts with Firebug's internal variable.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Naming a function as 'console'.</b></th>
  <th><b>Valid: Using a different name for the function.</b></th>
 </tr>
 <tr>
<td>

```php
function console() {
    // function body
}
```

</td>
<td>

```php
function debugConsole() {
    // function body
}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Naming a variable as 'console'.</b></th>
  <th><b>Valid: Using a different name for the variable.</b></th>
 </tr>
 <tr>
<td>

```php
$console = 'output';
```

</td>
<td>

```php
$debugOutput = 'output';
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Using 'console' as a label.</b></th>
  <th><b>Valid: Using a different name for the label.</b></th>
 </tr>
 <tr>
<td>

```php
console:
    echo "This is a label";
```

</td>
<td>

```php
debugLabel:
    echo "This is a label";
```

</td>
 </tr>
</table>
</details>
</details><details open id='Objects'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Objects</summary>
<hr>
<details open id='AssignThisSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Assign This to Only 'self' or '_self'</summary>
Ensures "this" is only assigned to variables named "self" or "_self".

<table style="width: 100%">
 <tr>
  <th><b>Valid: 'this' assigned to 'self'.</b></th>
  <th><b>Invalid: 'this' assigned to a variable with a different name.</b></th>
 </tr>
 <tr>
<td>

```php
$this = self;
```

</td>
<td>

```php
$this = someVariable;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: 'this' assigned to '_self'.</b></th>
  <th><b>Invalid: 'this' assigned to a variable not adhering to the naming convention.</b></th>
 </tr>
 <tr>
<td>

```php
$this = _self;
```

</td>
<td>

```php
$this = notSelf;
```

</td>
 </tr>
</table>
</details><details open id='CreateWidgetTypeCallbackSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Create Widget Type Callback Use</summary>
Ensures the create() method of widget types properly uses callbacks. 
The callback function must be the first argument called "callback". 
The create() method must not return a value. 
The first argument passed to the callback function must be "this" or "self". 
All calls to the callback function must be followed by a return statement if not the last statement in the create method.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Properly using callback in create() method.</b></th>
  <th><b>Invalid: First argument not named 'callback'.</b></th>
 </tr>
 <tr>
<td>

```php
class WidgetType {
    public function create(callback $callback) {
        $callback->call($this);
        return;
    }
}
```

</td>
<td>

```php
class WidgetType {
    public function create($notCallback) {
        // Incorrect argument name
    }
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Callback function follows the required structure.</b></th>
  <th><b>Invalid: Callback does not use 'this' or 'self' as the first argument.</b></th>
 </tr>
 <tr>
<td>

```php
class WidgetType {
    public function create(callback $callback) {
        // Some operations
        $callback->call(this);
        return;
    }
}
```

</td>
<td>

```php
class WidgetType {
    public function create(callback $callback) {
        $callback->call(); // Missing 'this' or 'self'
    }
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Callback call is followed by a return statement.</b></th>
  <th><b>Invalid: Callback call is not followed by a return statement.</b></th>
 </tr>
 <tr>
<td>

```php
class WidgetType {
    public function create(callback $callback) {
        $callback->call(this);
        // Some other operations
        return;
    }
}
```

</td>
<td>

```php
class WidgetType {
    public function create(callback $callback) {
        $callback->call(this);
        // Some other operations without a return statement
    }
}
```

</td>
 </tr>
</table>
</details><details open id='DisallowNewWidgetSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Manual Creation of Widgets</summary>
Widgets must not be manually created. Use Widget::getWidget('&lt;widget_name&gt;') instead.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using factory method to get a widget instance.</b></th>
  <th><b>Invalid: Manual creation of widget instance.</b></th>
 </tr>
 <tr>
<td>

```php
Widget::getWidget('exampleWidgetType');
```

</td>
<td>

```php
$widget = new ExampleWidgetType();
```

</td>
 </tr>
</table>
</details>
</details><details open id='PHP'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">P H P</summary>
<hr>
<details open id='AjaxNullComparisonSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Avoid Direct NULL Comparison for AJAX Request Submitted Values</summary>
Avoid comparing values submitted via AJAX directly to NULL; use empty() or another method instead.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Direct comparison to NULL.</b></th>
  <th><b>Valid: Using empty() for the check.</b></th>
 </tr>
 <tr>
<td>

```php
if ($ajaxSubmittedValue === null) {
    // Some action
}
```

</td>
<td>

```php
if (empty($ajaxSubmittedValue)) {
    // Some action
}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Using !== NULL for comparison.</b></th>
  <th><b>Valid: Prefer using !empty() for clarity and consistency.</b></th>
 </tr>
 <tr>
<td>

```php
if ($ajaxData !== null) {
    // Some action
}
```

</td>
<td>

```php
if (!empty($ajaxData)) {
    // Some action
}
```

</td>
 </tr>
</table>
</details><details open id='EvalObjectFactorySniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Eval for Object Creation</summary>
The use of eval() to create objects dynamically is prohibited. Use reflection or another method instead.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Using eval() to create an object.</b></th>
  <th><b>Valid: Creating an object without eval().</b></th>
 </tr>
 <tr>
<td>

```php
eval('$obj = new MyClass();');
```

</td>
<td>

```php
$obj = new MyClass();
```

</td>
 </tr>
</table>
</details><details open id='GetRequestDataSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Superglobal Direct Access</summary>
Superglobals must not be accessed directly; use Security::getRequestData() method instead.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using getRequestData() to access super globals.</b></th>
  <th><b>Invalid: Directly accessing $_POST super global.</b></th>
 </tr>
 <tr>
<td>

```php
Security::getRequestData('key', 'post');
```

</td>
<td>

```php
$_POST['key'];
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using getRequestData() to access super globals.</b></th>
  <th><b>Invalid: Directly accessing $_FILES super global.</b></th>
 </tr>
 <tr>
<td>

```php
Security::getRequestData('file', 'files');
```

</td>
<td>

```php
$_FILES['file'];
```

</td>
 </tr>
</table>
</details><details open id='ReturnFunctionValueSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Return Function Value Assignment</summary>
The result of a function call should be assigned to a variable before being returned.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Returning function value directly.</b></th>
  <th><b>Valid: Assigning function value to a variable before returning.</b></th>
 </tr>
 <tr>
<td>

```php
return someFunction();
```

</td>
<td>

```php
$result = someFunction();
return $result;
```

</td>
 </tr>
</table>
</details>
</details><details open id='Strings'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Strings</summary>
<hr>
<details open id='JoinStringsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">No Inline Array Join for Strings</summary>
Strings must not be joined using array.join(); use the + operator for joining strings instead.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Joining strings using array.join().</b></th>
  <th><b>Valid: Joining strings using the + operator.</b></th>
 </tr>
 <tr>
<td>

```php
$x = ['a', 'b', 'c'].join(', ');
```

</td>
<td>

```php
$x = 'a' + ', ' + 'b' + ', ' + 'c';
```

</td>
 </tr>
</table>
</details>