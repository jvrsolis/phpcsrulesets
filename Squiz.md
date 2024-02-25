## Table of Contents

- [Arrays](#Arrays)
    - [Array Bracket Spacing Standard](#ArrayBracketSpacingStandard)
    - [Array Declaration Standard](#ArrayDeclarationStandard)
- [Classes](#Classes)
    - [Lowercase Class Keywords Standard](#LowercaseClassKeywordsStandard)
    - [Self Member Reference Standard](#SelfMemberReferenceStandard)
- [Commenting](#Commenting)
    - [Doc Comment Alignment Standard](#DocCommentAlignmentStandard)
    - [Function Comment Throw Tag Standard](#FunctionCommentThrowTagStandard)
- [Control Structures](#ControlStructures)
    - [For Each Loop Declaration Standard](#ForEachLoopDeclarationStandard)
    - [For Loop Declaration Standard](#ForLoopDeclarationStandard)
    - [Lowercase Declaration Standard](#LowercaseDeclarationStandard)
- [Functions](#Functions)
    - [Function Duplicate Argument Standard](#FunctionDuplicateArgumentStandard)
    - [Lowercase Function Keywords Standard](#LowercaseFunctionKeywordsStandard)
- [Scope](#Scope)
    - [Static This Usage Standard](#StaticThisUsageStandard)
- [Strings](#Strings)
    - [Echoed Strings Standard](#EchoedStringsStandard)
- [White Space](#WhiteSpace)
    - [Cast Spacing Standard](#CastSpacingStandard)
    - [Function Opening Brace Standard](#FunctionOpeningBraceStandard)
    - [Language Construct Spacing Standard](#LanguageConstructSpacingStandard)
    - [Object Operator Spacing Standard](#ObjectOperatorSpacingStandard)
    - [Scope Keyword Spacing Standard](#ScopeKeywordSpacingStandard)
    - [Semicolon Spacing Standard](#SemicolonSpacingStandard)



</details><details open id='Arrays'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Arrays</summary>
<hr>
<details open id='ArrayBracketSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Array Bracket Spacing</summary>
When referencing arrays you should not put whitespace around the opening bracket or before the closing bracket.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No spaces around the brackets.</b></th>
  <th><b>Invalid: Spaces around the brackets.</b></th>
 </tr>
 <tr>
<td>

```php
$foo['bar'];
```

</td>
<td>

```php
$foo [ 'bar' ];
```

</td>
 </tr>
</table>
</details><details open id='ArrayDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Array Declarations</summary>
This standard covers all array declarations, regardless of the number and type of values contained within the array.

The <em>array</em> keyword must be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: array keyword lowercase</b></th>
  <th><b>Invalid: first letter capitalised</b></th>
 </tr>
 <tr>
<td>

```php
$array = array('val1', 'val2');
```

</td>
<td>

```php
$array = Array('val1', 'val2');
```

</td>
 </tr>
</table>

The first array key must begin on the line after the <em>array</em> keyword.

<table style="width: 100%">
 <tr>
  <th><b>Valid: first key on second line</b></th>
  <th><b>Invalid: first key on same line</b></th>
 </tr>
 <tr>
<td>

```php
$array = array(
          'key1' => 'value1',
          'key2' => 'value2',
         );
```

</td>
<td>

```php
$array = array('key1' => 'value1',
          'key2' => 'value2',
         );
```

</td>
 </tr>
</table>

All array keys must be indented to one space after the start of the <em>array</em> keyword. The closing parenthesis must be aligned with the start of the <em>array</em> keyword.

<table style="width: 100%">
 <tr>
  <th><b>Valid: aligned correctly</b></th>
  <th><b>Invalid: keys and parenthesis aligned incorrectly</b></th>
 </tr>
 <tr>
<td>

```php
$array = array(
         'key1' => 'value1',
         'key2' => 'value2',
         );
```

</td>
<td>

```php
$array = array(
         'key1' => 'value1',
         'key2' => 'value2',
);
```

</td>
 </tr>
</table>

All double arrow symbols must be aligned to one space after the longest array key. Alignment must be achieved using spaces.

<table style="width: 100%">
 <tr>
  <th><b>Valid: keys and values aligned</b></th>
  <th><b>Invalid: alignment incorrect</b></th>
 </tr>
 <tr>
<td>

```php
$array = array(
          'keyTen'    => 'ValueTen',
          'keyTwenty' => 'ValueTwenty',
         );
```

</td>
<td>

```php
$array = array(
          'keyTen' => 'ValueTen',
          'keyTwenty' => 'ValueTwenty',
         );
```

</td>
 </tr>
</table>

All array values must be followed by a comma, including the final value.

<table style="width: 100%">
 <tr>
  <th><b>Valid: comma after each value</b></th>
  <th><b>Invalid: no comma after last value</b></th>
 </tr>
 <tr>
<td>

```php
$array = array(
          'key1' => 'value1',
          'key2' => 'value2',
          'key3' => 'value3',
         );
```

</td>
<td>

```php
$array = array(
          'key1' => 'value1',
          'key2' => 'value2',
          'key3' => 'value3' 
         );
```

</td>
 </tr>
</table>
</details>
</details><details open id='Classes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Classes</summary>
<hr>
<details open id='LowercaseClassKeywordsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercase Class Keywords</summary>
The php keywords class, interface, trait, extends, implements, abstract, final, var, and const should be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase class keywords.</b></th>
  <th><b>Invalid: Initial capitalization of class keywords.</b></th>
 </tr>
 <tr>
<td>

```php
final class Foo extends Bar
{
}
```

</td>
<td>

```php
Final Class Foo Extends Bar
{
}
```

</td>
 </tr>
</table>
</details><details open id='SelfMemberReferenceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Self Member Reference</summary>
The self keyword should be used instead of the current class name, should be lowercase, and should not have spaces before or after it.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase self used.</b></th>
  <th><b>Invalid: Uppercase self used.</b></th>
 </tr>
 <tr>
<td>

```php
self::foo();
```

</td>
<td>

```php
SELF::foo();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct spacing used.</b></th>
  <th><b>Invalid: Incorrect spacing used.</b></th>
 </tr>
 <tr>
<td>

```php
self::foo();
```

</td>
<td>

```php
self :: foo();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Self used as reference.</b></th>
  <th><b>Invalid: Local class name used as reference.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    public static function bar()
    {
    }

    public static function baz()
    {
        self::bar();
    }
}
```

</td>
<td>

```php
class Foo
{
    public static function bar()
    {
    }

    public static function baz()
    {
        Foo::bar();
    }
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Commenting'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Commenting</summary>
<hr>
<details open id='DocCommentAlignmentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Doc Comment Alignment</summary>
The asterisks in a doc comment should align, and there should be one space between the asterisk and tags.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Asterisks are aligned.</b></th>
  <th><b>Invalid: Asterisks are not aligned.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @see foo()
 */
```

</td>
<td>

```php
/**
  * @see foo()
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: One space between asterisk and tag.</b></th>
  <th><b>Invalid: Incorrect spacing used.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @see foo()
 */
```

</td>
<td>

```php
/**
 *  @see foo()
 */
```

</td>
 </tr>
</table>
</details><details open id='FunctionCommentThrowTagStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Doc Comment Throws Tag</summary>
If a function throws any exceptions, they should be documented in a @throws tag.

<table style="width: 100%">
 <tr>
  <th><b>Valid: @throws tag used.</b></th>
  <th><b>Invalid: No @throws tag used for throwing function.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @throws Exception all the time
 * @return void
 */
function foo()
{
    throw new Exception('Danger!');
}
```

</td>
<td>

```php
/**
 * @return void
 */
function foo()
{
    throw new Exception('Danger!');
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='ControlStructures'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Control Structures</summary>
<hr>
<details open id='ForEachLoopDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Foreach Loop Declarations</summary>
There should be a space between each element of a foreach loop and the as keyword should be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing used.</b></th>
  <th><b>Invalid: Invalid spacing used.</b></th>
 </tr>
 <tr>
<td>

```php
foreach ($foo as $bar => $baz) {
    echo $baz;
}
```

</td>
<td>

```php
foreach ( $foo  as  $bar=>$baz ) {
    echo $baz;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Lowercase as keyword.</b></th>
  <th><b>Invalid: Uppercase as keyword.</b></th>
 </tr>
 <tr>
<td>

```php
foreach ($foo as $bar => $baz) {
    echo $baz;
}
```

</td>
<td>

```php
foreach ($foo AS $bar => $baz) {
    echo $baz;
}
```

</td>
 </tr>
</table>
</details><details open id='ForLoopDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">For Loop Declarations</summary>
In a for loop declaration, there should be no space inside the brackets and there should be 0 spaces before and 1 space after semicolons.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing used.</b></th>
  <th><b>Invalid: Invalid spacing used inside brackets.</b></th>
 </tr>
 <tr>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    echo $i;
}
```

</td>
<td>

```php
for ( $i = 0; $i < 10; $i++ ) {
    echo $i;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct spacing used.</b></th>
  <th><b>Invalid: Invalid spacing used before semicolons.</b></th>
 </tr>
 <tr>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    echo $i;
}
```

</td>
<td>

```php
for ($i = 0 ; $i < 10 ; $i++) {
    echo $i;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct spacing used.</b></th>
  <th><b>Invalid: Invalid spacing used after semicolons.</b></th>
 </tr>
<tr>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    echo $i;
}
```

</td>
<td>

```php
for ($i = 0;$i < 10;$i++) {
    echo $i;
}
```

</td>
 </tr>
</table>
</details><details open id='LowercaseDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercase Control Structure Keywords</summary>
The php keywords if, else, elseif, foreach, for, do, switch, while, try, and catch should be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase if keyword.</b></th>
  <th><b>Invalid: Uppercase if keyword.</b></th>
 </tr>
 <tr>
<td>

```php
if ($foo) {
    $bar = true;
}
```

</td>
<td>

```php
IF ($foo) {
    $bar = true;
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Functions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Functions</summary>
<hr>
<details open id='FunctionDuplicateArgumentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercase Built-In functions</summary>
All PHP built-in functions should be lowercased when called.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase function call.</b></th>
  <th><b>Invalid: isset not called as lowercase.</b></th>
 </tr>
 <tr>
<td>

```php
if (isset($foo)) {
    echo $foo;
}
```

</td>
<td>

```php
if (isSet($foo)) {
    echo $foo;
}
```

</td>
 </tr>
</table>
</details><details open id='LowercaseFunctionKeywordsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercase Function Keywords</summary>
The php keywords function, public, private, protected, and static should be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase function keyword.</b></th>
  <th><b>Invalid: Uppercase function keyword.</b></th>
 </tr>
 <tr>
<td>

```php
function foo()
{
    return true;
}
```

</td>
<td>

```php
FUNCTION foo()
{
    return true;
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Scope'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Scope</summary>
<hr>
<details open id='StaticThisUsageStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Static This Usage</summary>
Static methods should not use $this.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using self:: to access static variables.</b></th>
  <th><b>Invalid: Using $this-> to access static variables.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    static function bar()
    {
        return self::$staticMember;
    }
}
```

</td>
<td>

```php
class Foo
{
    static function bar()
    {
        return $this->$staticMember;
    }
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Strings'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Strings</summary>
<hr>
<details open id='EchoedStringsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Echoed Strings</summary>
Simple strings should not be enclosed in parentheses when being echoed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using echo without parentheses.</b></th>
  <th><b>Invalid: Using echo with parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
echo "Hello";
```

</td>
<td>

```php
echo("Hello");
```

</td>
 </tr>
</table>
</details>
</details><details open id='WhiteSpace'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">White Space</summary>
<hr>
<details open id='CastSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Cast Whitespace</summary>
Casts should not have whitespace inside the parentheses.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No spaces.</b></th>
  <th><b>Invalid: Whitespace used inside parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = (int)'42';
```

</td>
<td>

```php
$foo = ( int )'42';
```

</td>
 </tr>
</table>
</details><details open id='FunctionOpeningBraceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Opening Brace Whitespace</summary>
The opening brace for functions should be on a new line with no blank lines surrounding it.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Opening brace is on a new line.</b></th>
  <th><b>Invalid: Opening brace is on the same line as the function declaration.</b></th>
 </tr>
 <tr>
<td>

```php
function foo()
{
}
```

</td>
<td>

```php
function foo() {
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: No blank lines after the opening brace.</b></th>
  <th><b>Invalid: A blank line after the opening brace.</b></th>
 </tr>
 <tr>
<td>

```php
function foo()
{
    return 42;
}
```

</td>
<td>

```php
function foo()
{
    
    return 42;
}
```

</td>
 </tr>
</table>
</details><details open id='LanguageConstructSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Language Construct Whitespace</summary>
The php constructs echo, print, return, include, include_once, require, require_once, and new should have one space after them.

<table style="width: 100%">
 <tr>
  <th><b>Valid: echo statement with a single space after it.</b></th>
  <th><b>Invalid: echo statement with no space after it.</b></th>
 </tr>
 <tr>
<td>

```php
echo "hi";
```

</td>
<td>

```php
echo"hi";
```

</td>
 </tr>
</table>
</details><details open id='ObjectOperatorSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Object Operator Spacing</summary>
The object operator (->) should not have any space around it.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No spaces around the object operator.</b></th>
  <th><b>Invalid: Whitespace surrounding the object operator.</b></th>
 </tr>
 <tr>
<td>

```php
$foo->bar();
```

</td>
<td>

```php
$foo -> bar();
```

</td>
 </tr>
</table>
</details><details open id='ScopeKeywordSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Scope Keyword Spacing</summary>
The php keywords static, public, private, and protected should have one space after them.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A single space following the keywords.</b></th>
  <th><b>Invalid: Multiple spaces following the keywords.</b></th>
 </tr>
 <tr>
<td>

```php
public static function foo()
{
}
```

</td>
<td>

```php
public  static  function foo()
{
}
```

</td>
 </tr>
</table>
</details>
<details open id='SemicolonSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Semicolon Spacing</summary>
Semicolons should not have spaces before them.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No space before the semicolon.</b></th>
  <th><b>Invalid: Space before the semicolon.</b></th>
 </tr>
 <tr>
<td>

```php
echo "hi";
```

</td>
<td>

```php
echo "hi" ;
```

</td>
 </tr>
</table>
</details>
