## Table of Contents

- [Classes](#Classes)
    - [Class Declaration Standard](#ClassDeclarationStandard)
- [Commenting](#Commenting)
    - [Class Comment Standard](#ClassCommentStandard)
    - [File Comment Standard](#FileCommentStandard)
    - [Function Comment Standard](#FunctionCommentStandard)
    - [Inline Comment Standard](#InlineCommentStandard)
- [Control Structures](#ControlStructures)
    - [Control Signature Standard](#ControlSignatureStandard)
    - [Multi Line Condition Standard](#MultiLineConditionStandard)
- [Files](#Files)
    - [Including File Standard](#IncludingFileStandard)
    - [Line Length Standard](#LineLengthStandard)
- [Formatting](#Formatting)
    - [Multi Line Assignment Standard](#MultiLineAssignmentStandard)
- [Functions](#Functions)
    - [Function Call Signature Standard](#FunctionCallSignatureStandard)
    - [Function Declaration Standard](#FunctionDeclarationStandard)
    - [Valid Default Value Standard](#ValidDefaultValueStandard)
- [Naming Conventions](#NamingConventions)
    - [Valid Class Name Standard](#ValidClassNameStandard)
    - [Valid Function Name Standard](#ValidFunctionNameStandard)
    - [Valid Variable Name Standard](#ValidVariableNameStandard)
- [White Space](#WhiteSpace)
    - [Object Operator Indent Standard](#ObjectOperatorIndentStandard)
    - [Scope Closing Brace Standard](#ScopeClosingBraceStandard)
    - [Scope Indent Standard](#ScopeIndentStandard)



</details><details open id='Classes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Classes</summary>
<hr>
<details open id='ClassDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Declarations</summary>
The opening brace of a class must be on the line after the definition by itself.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Opening brace on the correct line.</b></th>
  <th><b>Invalid: Opening brace on same line as declaration.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
}
```

</td>
<td>

```php
class Foo {
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Commenting'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Commenting</summary>
<hr>
<details open id='ClassCommentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Comments</summary>
Classes and interfaces must have a non-empty doc comment.  The short description must be on the second line of the comment.  Each description must have one blank comment line before and after.  There must be one blank line before the tags in the comments.  A @version tag must be in Release: package_version format.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A doc comment for the class.</b></th>
  <th><b>Invalid: No doc comment for the class.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The Foo class.
 */
class Foo
{
}
```

</td>
<td>

```php
class Foo
{
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: A doc comment for the class.</b></th>
  <th><b>Invalid: Invalid comment type for the class.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The Foo class.
 */
class Foo
{
}
```

</td>
<td>

```php
// The Foo class.
class Foo
{
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: A doc comment for the class.</b></th>
  <th><b>Invalid: The blank line after the comment makes it appear as a file comment, not a class comment.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The Foo class.
 */
class Foo
{
}
```

</td>
<td>

```php
/**
 * The Foo class.
 */

class Foo
{
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Short description is the second line of the comment.</b></th>
  <th><b>Invalid: An extra blank line before the short description.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The Foo class.
 */
class Foo
{
}
```

</td>
<td>

```php
/**
 *
 * The Foo class.
 */
class Foo
{
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Exactly one blank line around descriptions.</b></th>
  <th><b>Invalid: Extra blank lines around the descriptions.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The Foo class.
 *
 * A helper for the Bar class.
 *
 * @see Bar
 */
class Foo
{
}
```

</td>
<td>

```php
/**
 * The Foo class.
 *
 *
 * A helper for the Bar class.
 *
 *
 * @see Bar
 */
class Foo
{
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Exactly one blank line before the tags.</b></th>
  <th><b>Invalid: Extra blank lines before the tags.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The Foo class.
 *
 * @see Bar
 */
class Foo
{
}
```

</td>
<td>

```php
/**
 * The Foo class.
 *
 *
 * @see Bar
 */
class Foo
{
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Version tag is in the correct format.</b></th>
  <th><b>Invalid: No Release: text.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The Foo class.
 *
 * @version Release: 1.0
 */
class Foo
{
}
```

</td>
<td>

```php
/**
 * The Foo class.
 *
 * @version 1.0
 */
class Foo
{
}
```

</td>
 </tr>
</table>
</details><details open id='FileCommentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">File Comments</summary>
Files must have a non-empty doc comment.  The short description must be on the second line of the comment.  Each description must have one blank comment line before and after.  There must be one blank line before the tags in the comments.  There must be a category, package, author, license, and link tag.  There may only be one category, package, subpackage, license, version, since and deprecated tag.  The tags must be in the order category, package, subpackage, author, copyright, license, version, link, see, since, and deprecated.  The php version must be specified.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A file comment is used.</b></th>
  <th><b>Invalid: No doc comment for the class.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Short description is the second line of the comment.</b></th>
  <th><b>Invalid: An extra blank line before the short description.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
/**
 *
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exactly one blank line around descriptions.</b></th>
  <th><b>Invalid: Extra blank lines around the descriptions.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
/**
 * Short description here.
 *
 *
 * PHP version 5
 *
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exactly one blank line before the tags.</b></th>
  <th><b>Invalid: Extra blank lines before the tags.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: All required tags are used.</b></th>
  <th><b>Invalid: Missing an author tag.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Tags that should only be used once are only used once.</b></th>
  <th><b>Invalid: Multiple category tags.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @category Bar
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: PHP version specified.</b></th>
  <th><b>Invalid: Category and package tags are swapped in order.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @package Foo_Helpers
 * @category Foo
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Tags are in the correct order.</b></th>
  <th><b>Invalid: No php version specified.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
/**
 * Short description here.
 *
 * PHP version 5
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
<td>

```php
<?php
/**
 * Short description here.
 *
 * @category Foo
 * @package Foo_Helpers
 * @author Marty McFly <mmcfly@example.com>
 * @copyright 2013-2014 Foo Inc.
 * @license MIT License
 * @link http://example.com
 */
```

</td>
 </tr>
</table>

</details><details open id='FunctionCommentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Comments</summary>
Functions must have a non-empty doc comment.  The short description must be on the second line of the comment.  Each description must have one blank comment line before and after.  There must be one blank line before the tags in the comments.  There must be a tag for each of the parameters in the right order with the right variable names with a comment.  There must be a return tag.  Any throw tag must have an exception class.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A function doc comment is used.</b></th>
  <th><b>Invalid: No doc comment for the function.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * @return void
 */
function foo()
{
}
```

</td>
<td>

```php
function foo()
{
}
```

</td>
 </tr>
    <tr>
  <th><b>Valid: Short description is the second line of the comment.</b></th>
  <th><b>Invalid: An extra blank line before the short description.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * @return void
 */
function foo()
{
}
```

</td>
<td>

```php
/**
 *
 * Short description here.
 *
 * @return void
 */
function foo()
{
}
```

</td>
 </tr>
    <tr>
  <th><b>Valid: Exactly one blank line around descriptions.</b></th>
  <th><b>Invalid: Extra blank lines around the descriptions.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * Long description here.
 *
 * @return void
 */
function foo()
{
}
```

</td>
<td>

```php
/**
 * Short description here.
 *
 *
 * Long description here.
 *
 *
 * @return void
 */
function foo()
{
}
```

</td>
 </tr>
    <tr>
  <th><b>Valid: Exactly one blank line before the tags.</b></th>
  <th><b>Invalid: Extra blank lines before the tags.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * Long description here.
 *
 * @return void
 */
function foo()
{
}
```

</td>
<td>

```php
/**
 * Short description here.
 *
 * Long description here.
 *
 *
 * @return void
 */
function foo()
{
}
```

</td>
 </tr>
    <tr>
  <th><b>Valid: Throws tag has an exception class.</b></th>
  <th><b>Invalid: No exception class given for throws tag.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * @return void
 * @throws FooException
 */
function foo()
{
}
```

</td>
<td>

```php
/**
 * Short description here.
 *
 * @return void
 * @throws
 */
function foo()
{
}
```

</td>
 </tr>
    <tr>
  <th><b>Valid: Return tag present.</b></th>
  <th><b>Invalid: No return tag.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * @return void
 */
function foo()
{
}
```

</td>
<td>

```php
/**
 * Short description here.
 */
function foo()
{
}
```

</td>
 </tr>
    <tr>
  <th><b>Valid: Param names are correct.</b></th>
  <th><b>Invalid: Wrong parameter name doesn't match function signature.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * @param string $foo Foo parameter
 * @param string $bar Bar parameter
 * @return void
 */
function foo($foo, $bar)
{
}
```

</td>
<td>

```php
/**
 * Short description here.
 *
 * @param string $foo Foo parameter
 * @param string $qux Bar parameter
 * @return void
 */
function foo($foo, $bar)
{
}
```

</td>
 </tr>
    <tr>
  <th><b>Valid: Param names are ordered correctly.</b></th>
  <th><b>Invalid: Wrong parameter order.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Short description here.
 *
 * @param string $foo Foo parameter
 * @param string $bar Bar parameter
 * @return void
 */
function foo($foo, $bar)
{
}
```

</td>
<td>

```php
/**
 * Short description here.
 *
 * @param string $bar Bar parameter
 * @param string $foo Foo parameter
 * @return void
 */
function foo($foo, $bar)
{
}
```

</td>
 </tr>
</table>
</details><details open id='InlineCommentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Inline Comments</summary>
Perl-style # comments are not allowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A // style comment.</b></th>
  <th><b>Invalid: A # style comment.</b></th>
 </tr>
 <tr>
<td>

```php
// A comment.
```

</td>
<td>

```php
# A comment.
```

</td>
 </tr>
</table>
</details>
</details><details open id='ControlStructures'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Control Structures</summary>
<hr>
<details open id='ControlSignatureStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Control Structure Signatures</summary>
Control structures should use one space around the parentheses in conditions.  The opening brace should be preceded by one space and should be at the end of the line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing around the condition.</b></th>
  <th><b>Invalid: Incorrect spacing around the condition.</b></th>
 </tr>
 <tr>
<td>

```php
if ($foo) {
}
```

</td>
<td>

```php
if($foo){
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct placement of the opening brace.</b></th>
  <th><b>Invalid: Incorrect placement of the opening brace on a new line.</b></th>
 </tr>
 <tr>
<td>

```php
if ($foo) {
}
```

</td>
<td>

```php
if ($foo)
{
}
```

</td>
 </tr>
</table>
</details><details open id='MultiLineConditionStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Multi-line If Conditions</summary>
Multi-line if conditions should be indented one level and each line should begin with a boolean operator. The end parenthesis should be on a new line.

<table style="width: 100%">
<tr>
<th><b>Valid: Correct indentation.</b></th>
<th><b>Invalid: No indentation used on the condition lines.</b></th>
</tr>
<tr>
<td>

```php
if ($foo
    && $bar
) {
}
```

</td>
<td>

```php
if ($foo
&& $bar
) {
}
```

</td>
</tr>
<tr>
<th><b>Valid: Boolean operator at the start of the line.</b></th>
<th><b>Invalid: Boolean operator at the end of the line.</b></th>
</tr>
<tr>
<td>

```php
if ($foo
    && $bar
) {
}
```

</td>
<td>

```php
if ($foo &&
    $bar
) {
}
```

</td>
</tr>
<tr>
<th><b>Valid: End parenthesis on a new line.</b></th>
<th><b>Invalid: End parenthesis not moved to a new line.</b></th>
</tr>
<tr>
<td>

```php
if ($foo
    && $bar
) {
}
```

</td>
<td>

```php
if ($foo
    && $bar) {
}
```

</td>
</tr>
</table>
</details>
</details><details open id='Files'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Files</summary>
<hr>

<details open id='IncludingFileStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Including Code</summary>
Anywhere you are unconditionally including a class file, use <em>require_once</em>. Anywhere you are conditionally including a class file (for example, factory methods), use <em>include_once</em>. Either of these will ensure that class files are included only once. They share the same file list, so you don't need to worry about mixing them - a file included with <em>require_once</em> will not be included again by <em>include_once</em>.

Note that <em>include_once</em> and <em>require_once</em> are statements, not functions. Parentheses should not surround the subject filename.

<table style="width: 100%">
 <tr>
  <th><b>Valid: used as statement</b></th>
  <th><b>Invalid: used as function</b></th>
 </tr>
 <tr>
<td>

```php
require_once 'PHP/CodeSniffer.php';
```

</td>
<td>

```php
require_once('PHP/CodeSniffer.php');
```

</td>
 </tr>
</table>
</details>
<details open id='LineLengthStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Line Length</summary>
It is recommended to keep lines at approximately 85 characters long for better code readability.
</details>
</details><details open id='Formatting'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Formatting</summary>
<hr>
<details open id='MultiLineAssignmentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Multi-Line Assignment</summary>
Multi-line assignment should have the equals sign be the first item on the second line indented correctly.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Assignment operator at the start of the second line.</b></th>
  <th><b>Invalid: Assignment operator at end of first line.</b></th>
 </tr>
 <tr>
<td>

```php
$foo
    = $bar;
```

</td>
<td>

```php
$foo =
    $bar;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Assignment operator indented one level.</b></th>
  <th><b>Invalid: Assignment operator not indented.</b></th>
 </tr>
 <tr>
<td>

```php
$foo
    = $bar;
```

</td>
<td>

```php
$foo
= $bar;
```

</td>
 </tr>
</table>
</details>
</details><details open id='Functions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Functions</summary>
<hr>
<details open id='FunctionCallSignatureStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Calls</summary>
Functions should be called with no spaces between the function name, the opening parenthesis, and the first parameter; and no space between the last parameter, the closing parenthesis, and the semicolon.

<table style="width: 100%">
 <tr>
  <th><b>Valid: spaces between parameters</b></th>
  <th><b>Invalid: additional spaces used</b></th>
 </tr>
 <tr>
<td>

```php
$var = foo($bar, $baz, $quux);
```

</td>
<td>

```php
$var = foo ( $bar, $baz, $quux );
```

</td>
 </tr>
</table>
</details><details open id='FunctionDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Declarations</summary>
There should be exactly 1 space after the function keyword and 1 space on each side of the use keyword.  Closures should use the Kernighan/Ritchie Brace style and other single-line functions should use the BSD/Allman style.  Multi-line function declarations should have the parameter lists indented one level with the closing parenthesis on a newline followed by a single space and the opening brace of the function.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing around function and use keywords.</b></th>
  <th><b>Invalid: No spacing around function and use keywords.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = function () use ($bar) {
};
```

</td>
<td>

```php
$foo = function()use($bar){
};
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Multi-line function declaration formatted properly.</b></th>
  <th><b>Invalid: Invalid indentation and formatting of closing parenthesis.</b></th>
 </tr>
 <tr>
<td>

```php
function foo(
    $bar,
    $baz
) {
};
```

</td>
<td>

```php
function foo(
$bar,
$baz)
{
};
```

</td>
 </tr>
</table>
</details><details open id='ValidDefaultValueStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Default Values in Function Declarations</summary>
Arguments with default values go at the end of the argument list.

<table style="width: 100%">
 <tr>
  <th><b>Valid: argument with default value at end of declaration.</b></th>
  <th><b>Invalid: argument with default value at start of declaration.</b></th>
 </tr>
 <tr>
<td>

```php
function connect($dsn, <em>$persistent = false</em>)
{
    ...
}
```

</td>
<td>

```php
function connect(<em>$persistent = false</em>, $dsn)
{
    ...
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='NamingConventions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Naming Conventions</summary>
<hr>
<details open id='ValidClassNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Names</summary>
Classes should be given descriptive names. Avoid using abbreviations where possible. Class names should always begin with an uppercase letter. The PEAR class hierarchy is also reflected in the class name, each level of the hierarchy separated with a single underscore.

<table style="width: 100%">
 <tr>
  <th><b>Examples of valid class names</b></th>
  <th><b>Examples of invalid class names</b></th>
 </tr>
 <tr>
<td>

```
Log
Net_Finger
HTML_Upload_Error
```

</td>
<td>

```
log
NetFinger
HTML-Upload-Error
```

</td>
 </tr>
</table>
</details><details open id='ValidFunctionNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function and Method Names</summary>
Functions and methods should be named using the "studly caps" style (also referred to as "bumpy case" or "camel caps"). Functions should in addition have the package name as a prefix, to avoid name collisions between packages. The initial letter of the name (after the prefix) is lowercase, and each letter that starts a new "word" is capitalized.

<table style="width: 100%">
 <tr>
  <th><b>Examples of valid function names</b></th>
  <th><b>Examples of invalid function names</b></th>
 </tr>
 <tr>
<td>

```php
connect()
getData()
buildSomeWidget()
XML_RPC_serializeData()
```

</td>
<td>

```php
Connect()
get_data()
```

</td>
 </tr>
</table>
</details><details open id='ValidVariableNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Variable Names</summary>
Private member variable names should be prefixed with an underscore and public/protected variable names should not.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Proper member variable names.</b></th>
  <th><b>Invalid: underscores used on public/protected variables and not used on private variables.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    public $publicVar;
    protected $protectedVar;
    private $_privateVar;
}
```

</td>
<td>

```php
class Foo
{
    public $_publicVar;
    protected $_protectedVar;
    private $privateVar;
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='WhiteSpace'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">White Space</summary>
<hr>
<details open id='ObjectOperatorIndentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Object Operator Indentation</summary>
Chained object operators when spread out over multiple lines should be the first thing on the line and be indented by 1 level.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Object operator at the start of a new line.</b></th>
  <th><b>Invalid: Object operator at the end of the line.</b></th>
 </tr>
 <tr>
<td>

```php
$foo
    ->bar()
    ->baz();
```

</td>
<td>

```php
$foo->
    bar()->
    baz();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Object operator indented correctly.</b></th>
  <th><b>Invalid: Object operator not indented correctly.</b></th>
 </tr>
 <tr>
<td>

```php
$foo
    ->bar()
    ->baz();
```

</td>
<td>

```php
$foo
->bar()
->baz();
```

</td>
 </tr>
</table>
</details><details open id='ScopeClosingBraceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Closing Brace Indentation</summary>

Closing braces should be indented at the same level as the beginning of the scope.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Consistent indentation level for scope.</b></th>
  <th><b>Invalid: The ending brace is indented further than the if statement.</b></th>
 </tr>
 <tr>
<td>

```php
if ($test) {
    $var = 1;
}
```

</td>
<td>

```php
if ($test) {
    $var = 1;
    }
```

</td>
 </tr>
</table>
</details><details open id='ScopeIndentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Scope Indentation</summary>
Any scope openers except for switch statements should be indented 1 level. This includes classes, functions, and control structures.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Consistent indentation level for scope.</b></th>
  <th><b>Invalid: Indentation is not used for scope.</b></th>
 </tr>
 <tr>
<td>

```php
function foo()
{
    if ($test) {
        $var = 1;
    }
}
```

</td>
<td>

```php
function foo()
{
if ($test) {
$var = 1;
}
}
```

</td>
 </tr>
</table>
</details>