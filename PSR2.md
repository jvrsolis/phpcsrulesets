## Table of Contents

- [Classes](#Classes)
    - [Class Declaration Standard](#ClassDeclarationStandard)
    - [Property Declaration Standard](#PropertyDeclarationStandard)
- [Control Structures](#ControlStructures)
    - [Control Structure Spacing Standard](#ControlStructureSpacingStandard)
    - [Else If Declaration Standard](#ElseIfDeclarationStandard)
    - [Switch Declaration Standard](#SwitchDeclarationStandard)
- [Files](#Files)
    - [Closing Tag Standard](#ClosingTagStandard)
    - [End File Newline Standard](#EndFileNewlineStandard)
- [Methods](#Methods)
    - [Function Call Signature Standard](#FunctionCallSignatureStandard)
    - [Function Closing Brace Standard](#FunctionClosingBraceStandard)
    - [Method Declaration Standard](#MethodDeclarationStandard)
- [Namespaces](#Namespaces)
    - [Namespace Declaration Standard](#NamespaceDeclarationStandard)
    - [Use Declaration Standard](#UseDeclarationStandard)



</details><details id='Classes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Classes</summary>
<hr>
<details id='ClassDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Declarations</summary>
There should be exactly 1 space between the abstract or final keyword and the class keyword and between the class keyword and the class name.  The extends and implements keywords, if present, must be on the same line as the class name.  When interfaces implemented are spread over multiple lines, there should be exactly 1 interface mentioned per line indented by 1 level.  The closing brace of the class must go on the first line after the body of the class and must be on a line by itself.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing around class keyword.</b></th>
  <th><b>Invalid: 2 spaces used around class keyword.</b></th>
 </tr>
 <tr>
<td>

```php
abstract class Foo
{
}
```

</td>
<td>

```php
abstract  class  Foo
{
}
```

</td>
 </tr>
</table>
</details><details id='PropertyDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Property Declarations</summary>
Property names should not be prefixed with an underscore to indicate visibility.  Visibility should be used to declare properties rather than the var keyword.  Only one property should be declared within a statement.  The static declaration must come after the visibility declaration.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct property naming.</b></th>
  <th><b>Invalid: An underscore prefix used to indicate visibility.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    private $bar;
}
```

</td>
<td>

```php
class Foo
{
    private $_bar;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Visibility of property declared.</b></th>
  <th><b>Invalid: Var keyword used to declare property.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    private $bar;
}
```

</td>
<td>

```php
class Foo
{
    var $bar;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: One property declared per statement.</b></th>
  <th><b>Invalid: Multiple properties declared in one statement.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    private $bar;
    private $baz;
}
```

</td>
<td>

```php
class Foo
{
    private $bar, $baz;
}
```

</td>
 </tr>
  <tr>
  <th><b>Valid: If declared as static, the static declaration must come after the visibility declaration.</b></th>
  <th><b>Invalid: Static declaration before the visibility declaration.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    public static $bar;
    private $baz;
}
```

</td>
<td>

```php
class Foo
{
    static protected $bar;
}
```

</td>
 </tr>
</table>
</details>
</details><details id='ControlStructures'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Control Structures</summary>
<hr>
<details id='ControlStructureSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Control Structure Spacing</summary>
Control Structures should have 0 spaces after opening parentheses and 0 spaces before closing parentheses.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing.</b></th>
  <th><b>Invalid: Whitespace used inside the parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
if ($foo) {
    $var = 1;
}
```

</td>
<td>

```php
if ( $foo ) {
    $var = 1;
}
```

</td>
 </tr>
</table>
</details><details id='ElseIfDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Elseif Declarations</summary>
PHP's elseif keyword should be used instead of else if.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single word elseif keyword used.</b></th>
  <th><b>Invalid: Separate else and if keywords used.</b></th>
 </tr>
 <tr>
<td>

```php
if ($foo) {
    $var = 1;
} elseif ($bar) {
    $var = 2;
}
```

</td>
<td>

```php
if ($foo) {
    $var = 1;
} else if ($bar) {
    $var = 2;
}
```

</td>
 </tr>
</table>
</details><details id='SwitchDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Switch Declarations</summary>
Case statements should be indented 4 spaces from the switch keyword.  It should also be followed by a space.  Colons in switch declarations should not be preceded by whitespace.  Break statements should be indented 4 more spaces from the case statement.  There must be a comment when falling through from one case into the next.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Case statement indented correctly.</b></th>
  <th><b>Invalid: Case statement not indented 4 spaces.</b></th>
 </tr>
 <tr>
<td>

```php
switch ($foo) {
    case 'bar':
        break;
}
```

</td>
<td>

```php
switch ($foo) {
case 'bar':
    break;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Case statement followed by 1 space.</b></th>
  <th><b>Invalid: Case statement not followed by 1 space.</b></th>
 </tr>
 <tr>
<td>

```php
switch ($foo) {
    case 'bar':
        break;
}
```

</td>
<td>

```php
switch ($foo) {
    case'bar':
        break;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Colons not prefixed by whitespace.</b></th>
  <th><b>Invalid: Colons prefixed by whitespace.</b></th>
 </tr>
 <tr>
<td>

```php
switch ($foo) {
    case 'bar':
        break;
    default:
        break;
}
```

</td>
<td>

```php
switch ($foo) {
    case 'bar' :
        break;
    default :
        break;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Break statement indented correctly.</b></th>
  <th><b>Invalid: Break statement not indented 4 spaces.</b></th>
 </tr>
 <tr>
<td>

```php
switch ($foo) {
    case 'bar':
        break;
}
```

</td>
<td>

```php
switch ($foo) {
    case 'bar':
    break;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Comment marking intentional fall-through.</b></th>
  <th><b>Invalid: No comment marking intentional fall-through.</b></th>
 </tr>
 <tr>
<td>

```php
switch ($foo) {
    case 'bar':
    // no break
    default:
        break;
}
```

</td>
<td>

```php
switch ($foo) {
    case 'bar':
    default:
        break;
}
```

</td>
 </tr>
</table>
</details>
</details><details id='Files'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Files</summary>
<hr>
<details id='ClosingTagStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Closing Tag</summary>
Checks that the file does not end with a closing tag.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Closing tag not used.</b></th>
  <th><b>Invalid: Closing tag used.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
echo 'Foo';

```

</td>
<td>

```php
<?php
echo 'Foo';
?>
```

</td>
 </tr>
</table>
</details><details id='EndFileNewlineStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">End File Newline</summary>
PHP Files should end with exactly one newline.

<table style="width: 100%">
 <tr>
  <th><b>Valid: File ends with exactly one newline.</b></th>
  <th><b>Invalid: File does not end with a newline or has multiple newlines.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
echo "Hello, world!";
// Newline here
```

</td>
<td>

```php
<?php
echo "Hello, world!"; // No newline or multiple newlines
```

</td>
 </tr>
</table>
</details>
</details><details id='Methods'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Methods</summary>
<hr>
<details id='FunctionCallSignatureStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Call Signature</summary>
Checks that the function call format is correct.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing is used around parentheses.</b></th>
  <th><b>Invalid: Incorrect spacing used, too much space around the parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
foo($bar, $baz);
```

</td>
<td>

```php
foo ( $bar, $baz );
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct number of spaces used for indent in a multi-line function call.</b></th>
  <th><b>Invalid: Incorrect number of spaces used for indent in a multi-line function call.</b></th>
 </tr>
 <tr>
<td>

```php
foo(
    $bar,
    $baz
);
```

</td>
<td>

```php
foo(
  $bar,
      $baz
);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Closing parenthesis for a multi-line function call is on a new line after the last parameter.</b></th>
  <th><b>Invalid: Closing parenthesis for a multi-line function call is not on a new line after the last parameter.</b></th>
 </tr>
 <tr>
<td>

```php
foo(
    $bar,
    $baz
);
```

</td>
<td>

```php
foo(
    $bar,
    $baz);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: The first argument of a multi-line function call is on a new line.</b></th>
  <th><b>Invalid: The first argument of a multi-line function call is not on a new line.</b></th>
 </tr>
 <tr>
<td>

```php
foo(
    $bar,
    $baz
);
```

</td>
<td>

```php
foo($bar,
    $baz
);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Only one argument per line in a multi-line function call.</b></th>
  <th><b>Invalid: Two or more arguments per line in a multi-line function call.</b></th>
 </tr>
 <tr>
<td>

```php
foo(
    $bar,
    $baz
);
```

</td>
<td>

```php
foo(
    $bar, $baz
);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No blank lines in a multi-line function call.</b></th>
  <th><b>Invalid: Blank line in multi-line function call.</b></th>
 </tr>
 <tr>
<td>

```php
foo(
    $bar,
    $baz
);
```

</td>
<td>

```php
foo(
    $bar,

    $baz
);
```

</td>
 </tr>
</table>
</details><details id='FunctionClosingBraceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Closing Brace</summary>
Checks that the closing brace of a function goes directly after the body.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Closing brace directly follows the function body.</b></th>
  <th><b>Invalid: Blank line between the function body and the closing brace.</b></th>
 </tr>
 <tr>
<td>

```php
function foo()
{
    echo 'foo';
}
```

</td>
<td>

```php
function foo()
{
    echo 'foo';

}
```

</td>
 </tr>
</table>
</details><details id='MethodDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Method Declarations</summary>
Method names should not be prefixed with an underscore to indicate visibility.  The static keyword, when present, should come after the visibility declaration, and the final and abstract keywords should come before.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct method naming.</b></th>
  <th><b>Invalid: An underscore prefix used to indicate visibility.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    private function bar()
    {
    }
}
```

</td>
<td>

```php
class Foo
{
    private function _bar()
    {
    }
}
```

</td>
 </tr>
<tr>
  <th><b>Valid: Correct ordering of method prefixes.</b></th>
  <th><b>Invalid: static keyword used before visibility and final used after.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    final public static function bar()
    {
    }
}
```

</td>
<td>

```php
class Foo
{
    static public final function bar()
    {
    }
}
```

</td>
 </tr>
</table>
</details>
</details><details id='Namespaces'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Namespaces</summary>
<hr>
<details id='NamespaceDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Namespace Declarations</summary>
There must be one blank line after the namespace declaration.

<table style="width: 100%">
 <tr>
  <th><b>Valid: One blank line after the namespace declaration.</b></th>
  <th><b>Invalid: No blank line after the namespace declaration.</b></th>
 </tr>
 <tr>
<td>

```php
namespace \Foo\Bar;

use \Baz;
```

</td>
<td>

```php
namespace \Foo\Bar;
use \Baz;
```

</td>
 </tr>
</table>
</details><details id='UseDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Namespace Declarations</summary>
Each use declaration must contain only one namespace and must come after the first namespace declaration.  There should be one blank line after the final use statement.

<table style="width: 100%">
 <tr>
  <th><b>Valid: One use declaration per namespace.</b></th>
  <th><b>Invalid: Multiple namespaces in a use declaration.</b></th>
 </tr>
 <tr>
<td>

```php
use \Foo;
use \Bar;
```

</td>
<td>

```php
use \Foo, \Bar;
```

</td>
 </tr>
<tr>
  <th><b>Valid: Use statements come after first namespace.</b></th>
  <th><b>Invalid: Namespace declared after use.</b></th>
 </tr>
 <tr>
<td>

```php
namespace \Foo;

use \Bar;
```

</td>
<td>

```php
use \Bar;

namespace \Foo;
```

</td>
 </tr>
<tr>
  <th><b>Valid: A single blank line after the final use statement.</b></th>
  <th><b>Invalid: No blank line after the final use statement.</b></th>
 </tr>
 <tr>
<td>

```php
use \Foo;
use \Bar;

class Baz
{
}
```

</td>
<td>

```php
use \Foo;
use \Bar;
class Baz
{
}
```

</td>
 </tr>
</table>
</details>