## Table of Contents

- [Arrays](#Arrays)
    - [Disallow Long Array Syntax Standard](#DisallowLongArraySyntaxStandard)
    - [Disallow Short Array Syntax Standard](#DisallowShortArraySyntaxStandard)
- [Classes](#Classes)
    - [Duplicate Class Name Standard](#DuplicateClassNameStandard)
    - [Opening Brace Same Line Standard](#OpeningBraceSameLineStandard)
- [Code Analysis](#CodeAnalysis)
    - [Assignment In Condition Standard](#AssignmentInConditionStandard)
    - [Empty P H P Statement Standard](#EmptyPHPStatementStandard)
    - [Empty Statement Standard](#EmptyStatementStandard)
    - [For Loop Should Be While Loop Standard](#ForLoopShouldBeWhileLoopStandard)
    - [For Loop With Test Function Call Standard](#ForLoopWithTestFunctionCallStandard)
    - [Jumbled Incrementer Standard](#JumbledIncrementerStandard)
    - [Require Explicit Boolean Operator Precedence Standard](#RequireExplicitBooleanOperatorPrecedenceStandard)
    - [Unconditional If Statement Standard](#UnconditionalIfStatementStandard)
    - [Unnecessary Final Modifier Standard](#UnnecessaryFinalModifierStandard)
    - [Unused Function Parameter Standard](#UnusedFunctionParameterStandard)
    - [Useless Overriding Method Standard](#UselessOverridingMethodStandard)
- [Commenting](#Commenting)
    - [Fixme Standard](#FixmeStandard)
    - [Todo Standard](#TodoStandard)
- [Control Structures](#ControlStructures)
    - [Disallow Yoda Conditions Standard](#DisallowYodaConditionsStandard)
    - [Inline Control Structure Standard](#InlineControlStructureStandard)
- [Debug](#Debug)
    - [C S S Lint Standard](#CSSLintStandard)
    - [Closure Linter Standard](#ClosureLinterStandard)
    - [J S Hint Standard](#JSHintStandard)
- [Files](#Files)
    - [Byte Order Mark Standard](#ByteOrderMarkStandard)
    - [End File Newline Standard](#EndFileNewlineStandard)
    - [End File No Newline Standard](#EndFileNoNewlineStandard)
    - [Executable File Standard](#ExecutableFileStandard)
    - [Inline H T M L Standard](#InlineHTMLStandard)
    - [Line Endings Standard](#LineEndingsStandard)
    - [Line Length Standard](#LineLengthStandard)
    - [Lowercased Filename Standard](#LowercasedFilenameStandard)
    - [One Class Per File Standard](#OneClassPerFileStandard)
    - [One Interface Per File Standard](#OneInterfacePerFileStandard)
    - [One Object Structure Per File Standard](#OneObjectStructurePerFileStandard)
    - [One Trait Per File Standard](#OneTraitPerFileStandard)
- [Formatting](#Formatting)
    - [Disallow Multiple Statements Standard](#DisallowMultipleStatementsStandard)
    - [Multiple Statement Alignment Standard](#MultipleStatementAlignmentStandard)
    - [No Space After Cast Standard](#NoSpaceAfterCastStandard)
    - [Space After Cast Standard](#SpaceAfterCastStandard)
    - [Space After Not Standard](#SpaceAfterNotStandard)
    - [Space Before Cast Standard](#SpaceBeforeCastStandard)
- [Functions](#Functions)
    - [Call Time Pass By Reference Standard](#CallTimePassByReferenceStandard)
    - [Function Call Argument Spacing Standard](#FunctionCallArgumentSpacingStandard)
    - [Opening Function Brace Bsd Allman Standard](#OpeningFunctionBraceBsdAllmanStandard)
    - [Opening Function Brace Kernighan Ritchie Standard](#OpeningFunctionBraceKernighanRitchieStandard)
- [Metrics](#Metrics)
    - [Cyclomatic Complexity Standard](#CyclomaticComplexityStandard)
    - [Nesting Level Standard](#NestingLevelStandard)
- [Naming Conventions](#NamingConventions)
    - [Abstract Class Name Prefix Standard](#AbstractClassNamePrefixStandard)
    - [Camel Caps Function Name Standard](#CamelCapsFunctionNameStandard)
    - [Constructor Name Standard](#ConstructorNameStandard)
    - [Interface Name Suffix Standard](#InterfaceNameSuffixStandard)
    - [Trait Name Suffix Standard](#TraitNameSuffixStandard)
    - [Upper Case Constant Name Standard](#UpperCaseConstantNameStandard)
- [P H P](#PHP)
    - [Backtick Operator Standard](#BacktickOperatorStandard)
    - [Character Before P H P Opening Tag Standard](#CharacterBeforePHPOpeningTagStandard)
    - [Closing P H P Tag Standard](#ClosingPHPTagStandard)
    - [Deprecated Functions Standard](#DeprecatedFunctionsStandard)
    - [Disallow Alternative P H P Tags Standard](#DisallowAlternativePHPTagsStandard)
    - [Disallow Request Superglobal Standard](#DisallowRequestSuperglobalStandard)
    - [Disallow Short Open Tag Standard](#DisallowShortOpenTagStandard)
    - [Discourage Goto Standard](#DiscourageGotoStandard)
    - [Forbidden Functions Standard](#ForbiddenFunctionsStandard)
    - [Lower Case Constant Standard](#LowerCaseConstantStandard)
    - [Lower Case Keyword Standard](#LowerCaseKeywordStandard)
    - [Lower Case Type Standard](#LowerCaseTypeStandard)
    - [No Silenced Errors Standard](#NoSilencedErrorsStandard)
    - [S A P I Usage Standard](#SAPIUsageStandard)
    - [Syntax Standard](#SyntaxStandard)
    - [Upper Case Constant Standard](#UpperCaseConstantStandard)
- [Strings](#Strings)
    - [Unnecessary String Concat Standard](#UnnecessaryStringConcatStandard)
- [Version Control](#VersionControl)
    - [Subversion Properties Standard](#SubversionPropertiesStandard)
- [White Space](#WhiteSpace)
    - [Arbitrary Parentheses Spacing Standard](#ArbitraryParenthesesSpacingStandard)
    - [Disallow Space Indent Standard](#DisallowSpaceIndentStandard)
    - [Disallow Tab Indent Standard](#DisallowTabIndentStandard)
    - [Increment Decrement Spacing Standard](#IncrementDecrementSpacingStandard)
    - [Language Construct Spacing Standard](#LanguageConstructSpacingStandard)
    - [Scope Indent Standard](#ScopeIndentStandard)
    - [Spread Operator Spacing After Standard](#SpreadOperatorSpacingAfterStandard)


<details open id='Arrays'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Arrays</summary>
<hr>
<details open id='DisallowLongArraySyntaxStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Short Array Syntax</summary>
Short array syntax must be used to define arrays.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Short form of array.</b></th>
  <th><b>Invalid: Long form of array.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = [
    'foo' => 'bar',
];
```

</td>
<td>

```php
$arr = array(
    'foo' => 'bar',
);
```

</td>
 </tr>
</table>
</details><details open id='DisallowShortArraySyntaxStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Long Array Syntax</summary>
Long array syntax must be used to define arrays.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Long form of array.</b></th>
  <th><b>Invalid: Short form of array.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = array(
    'foo' => 'bar',
);
```

</td>
<td>

```php
$arr = [
    'foo' => 'bar',
];
```

</td>
 </tr>
</table>
</details>
</details><details open id='Classes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Classes</summary>
<hr>
<details open id='DuplicateClassNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Duplicate Class Names</summary>
Class and Interface names should be unique in a project.  They should never be duplicated.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A unique class name.</b></th>
  <th><b>Invalid: A class duplicated (including across multiple files).</b></th>
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
class Foo
{
}

class Foo
{
}
```

</td>
 </tr>
</table>
</details><details open id='OpeningBraceSameLineStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Opening Brace on Same Line</summary>
The opening brace of a class must be on the same line after the definition and must be the last thing on that line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Opening brace on the same line.</b></th>
  <th><b>Invalid: Opening brace on the next line.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo {
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
  <th><b>Valid: Opening brace is the last thing on the line.</b></th>
  <th><b>Invalid: Opening brace not last thing on the line.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo {
}
```

</td>
<td>

```php
class Foo { // Start of class.
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='CodeAnalysis'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Code Analysis</summary>
<hr>
<details open id='AssignmentInConditionStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Assignment In Condition</summary>
Variable assignments should not be made within conditions.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A variable comparison being executed within a condition.</b></th>
  <th><b>Invalid: A variable assignment being made within a condition.</b></th>
 </tr>
 <tr>
<td>

```php
if ($test === 'abc') {
    // Code.
}
```

</td>
<td>

```php
if ($test = 'abc') {
    // Code.
}
```

</td>
 </tr>
</table>
</details><details open id='EmptyPHPStatementStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Empty PHP Statement</summary>
Empty PHP tags are not allowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: There is at least one statement inside the PHP tag pair.</b></th>
  <th><b>Invalid: There is no statement inside the PHP tag pair.</b></th>
 </tr>
 <tr>
<td>

```php
<?php echo 'Hello World'; ?>
<?= 'Hello World'; ?>
```

</td>
<td>

```php
<?php ; ?>
<?=  ?>
```

</td>
 </tr>
</table>

Superfluous semi-colons are not allowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: There is no superfluous semi-colon after a PHP statement.</b></th>
  <th><b>Invalid: There are one or more superfluous semi-colons after a PHP statement.</b></th>
 </tr>
 <tr>
<td>

```php
function_call();
if (true) {
    echo 'Hello World';
}
```

</td>
<td>

```php
function_call();;;
if (true) {
    echo 'Hello World';
};
```

</td>
 </tr>
</table>
</details><details open id='EmptyStatementStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Empty Statements</summary>
Control Structures must have at least one statement inside of the body.

<table style="width: 100%">
 <tr>
  <th><b>Valid: There is a statement inside the control structure.</b></th>
  <th><b>Invalid: The control structure has no statements.</b></th>
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
    // do nothing
}
```

</td>
 </tr>
</table>
</details><details open id='ForLoopShouldBeWhileLoopStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Condition-Only For Loops</summary>
For loops that have only a second expression (the condition) should be converted to while loops.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A for loop is used with all three expressions.</b></th>
  <th><b>Invalid: A for loop is used without a first or third expression.</b></th>
 </tr>
 <tr>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    echo "{$i}\n";
}
```

</td>
<td>

```php
for (;$test;) {
    $test = doSomething();
}
```

</td>
 </tr>
</table>
</details><details open id='ForLoopWithTestFunctionCallStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">For Loops With Function Calls in the Test</summary>
For loops should not call functions inside the test for the loop when they can be computed beforehand.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A for loop that determines its end condition before the loop starts.</b></th>
  <th><b>Invalid: A for loop that unnecessarily computes the same value on every iteration.</b></th>
 </tr>
 <tr>
<td>

```php
$end = count($foo);
for ($i = 0; $i < $end; $i++) {
    echo $foo[$i]."\n";
}
```

</td>
<td>

```php
for ($i = 0; $i < count($foo); $i++) {
    echo $foo[$i]."\n";
}
```

</td>
 </tr>
</table>
</details><details open id='JumbledIncrementerStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Jumbled Incrementers</summary>
Incrementers in nested loops should use different variable names.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Two different variables being used to increment.</b></th>
  <th><b>Invalid: Inner incrementer is the same variable name as the outer one.</b></th>
 </tr>
 <tr>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    for ($j = 0; $j < 10; $j++) {
    }
}
```

</td>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    for ($j = 0; $j < 10; $i++) {
    }
}
```

</td>
 </tr>
</table>
</details><details open id='RequireExplicitBooleanOperatorPrecedenceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Explicit Boolean Operator Precedence</summary>
Forbids mixing different binary boolean operators (&&, ||, and, or, xor) within a single expression without making precedence clear using parentheses.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Making precedence clear with parentheses.</b></th>
  <th><b>Invalid: Not using parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$one = false;
$two = false;
$three = true;

$result = ($one && $two) || $three;
$result2 = $one && ($two || $three);
$result3 = ($one && !$two) xor $three;
$result4 = $one && (!$two xor $three);

if (
    ($result && !$result3)
    || (!$result && $result3)
) {}
```

</td>
<td>

```php
$one = false;
$two = false;
$three = true;

$result = $one && $two || $three;

$result3 = $one && !$two xor $three;


if (
    $result && !$result3
    || !$result && $result3
) {}
```

</td>
 </tr>
</table>
</details><details open id='UnconditionalIfStatementStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unconditional If Statements</summary>
If statements that are always evaluated should not be used.

<table style="width: 100%">
 <tr>
  <th><b>Valid: An if statement that only executes conditionally.</b></th>
  <th><b>Invalid: An if statement that is always performed.</b></th>
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
if (true) {
    $var = 1;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: An if statement that only executes conditionally.</b></th>
  <th><b>Invalid: An if statement that is never performed.</b></th>
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
if (false) {
    $var = 1;
}
```

</td>
 </tr>
</table>
</details><details open id='UnnecessaryFinalModifierStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unnecessary Final Modifiers</summary>
Methods should not be declared final inside of classes that are declared final.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A method in a final class is not marked final.</b></th>
  <th><b>Invalid: A method in a final class is also marked final.</b></th>
 </tr>
 <tr>
<td>

```php
final class Foo
{
    public function bar()
    {
    }
}
```

</td>
<td>

```php
final class Foo
{
    public final function bar()
    {
    }
}
```

</td>
 </tr>
</table>
</details><details open id='UnusedFunctionParameterStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unused function parameters</summary>
All parameters in a functions signature should be used within the function.

<table style="width: 100%">
 <tr>
  <th><b>Valid: All the parameters are used.</b></th>
  <th><b>Invalid: One of the parameters is not being used.</b></th>
 </tr>
 <tr>
<td>

```php
function addThree($a, $b, $c)
{
    return $a + $b + $c;
}
```

</td>
<td>

```php
function addThree($a, $b, $c)
{
    return $a + $b;
}
```

</td>
 </tr>
</table>
</details><details open id='UselessOverridingMethodStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Overriding Methods</summary>
Methods should not be defined that only call the parent method.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A method that extends functionality on a parent method.</b></th>
  <th><b>Invalid: An overriding method that only calls the parent.</b></th>
 </tr>
 <tr>
<td>

```php
final class Foo
{
    public function bar()
    {
        parent::bar();
        $this->doSomethingElse();
    }
}
```

</td>
<td>

```php
final class Foo
{
    public function bar()
    {
        parent::bar();
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
<details open id='FixmeStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Fixme Comments</summary>
FIXME Statements should be taken care of.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A comment without a fixme.</b></th>
  <th><b>Invalid: A fixme comment.</b></th>
 </tr>
 <tr>
<td>

```php
// Handle strange case
if ($test) {
    $var = 1;
}
```

</td>
<td>

```php
// FIXME: This needs to be fixed!
if ($test) {
    $var = 1;
}
```

</td>
 </tr>
</table>
</details><details open id='TodoStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Todo Comments</summary>
TODO Statements should be taken care of.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A comment without a todo.</b></th>
  <th><b>Invalid: A todo comment.</b></th>
 </tr>
 <tr>
<td>

```php
// Handle strange case
if ($test) {
    $var = 1;
}
```

</td>
<td>

```php
// TODO: This needs to be fixed!
if ($test) {
    $var = 1;
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='ControlStructures'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Control Structures</summary>
<hr>
<details open id='DisallowYodaConditionsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Yoda conditions</summary>
Yoda conditions are disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: value to be asserted must go on the right side of the comparison.</b></th>
  <th><b>Invalid: value to be asserted must not be on the left.</b></th>
 </tr>
 <tr>
<td>

```php
if ($test === null) {
    $var = 1;
}
```

</td>
<td>

```php
if (null === $test) {
    $var = 1;
}
```

</td>
 </tr>
</table>
</details><details open id='InlineControlStructureStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Inline Control Structures</summary>
Control Structures should use braces.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Braces are used around the control structure.</b></th>
  <th><b>Invalid: No braces are used for the control structure.</b></th>
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
if ($test)
    $var = 1;
```

</td>
 </tr>
</table>
</details>
</details><details open id='Debug'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Debug</summary>
<hr>
<details open id='CSSLintStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">CSSLint</summary>
All css files should pass the basic csslint tests.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Valid CSS Syntax is used.</b></th>
  <th><b>Invalid: The CSS has a typo in it.</b></th>
 </tr>
 <tr>
<td>

```css
.foo { width: 100%; }
```

</td>
<td>

```css
.foo: { width: 100 %; }
```

</td>
 </tr>
</table>
</details><details open id='ClosureLinterStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Closure Linter</summary>
All javascript files should pass basic Closure Linter tests.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Valid JS Syntax is used.</b></th>
  <th><b>Invalid: Trailing comma in a javascript array.</b></th>
 </tr>
 <tr>
<td>

```javascript
var foo = [1, 2];
```

</td>
<td>

```javascript
var foo = [1, 2,];
```

</td>
 </tr>
</table>
</details><details open id='JSHintStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">JSHint</summary>
All javascript files should pass basic JSHint tests.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Valid JS Syntax is used.</b></th>
  <th><b>Invalid: The Javascript is using an undefined variable.</b></th>
 </tr>
 <tr>
<td>

```javascript
var foo = 5;
```

</td>
<td>

```javascript
foo = 5;
```

</td>
 </tr>
</table>
</details>
</details><details open id='Files'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Files</summary>
<hr>
<details open id='ByteOrderMarkStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Byte Order Marks</summary>
Byte Order Marks that may corrupt your application should not be used. These include `0xefbbbf` (UTF-8), `0xfeff` (UTF-16 BE) and `0xfffe` (UTF-16 LE).

<table style="width: 100%">
 <tr>
  <th><b>Valid: Without Byte Order Mark.</b></th>
  <th><b>Invalid: With Byte Order Mark.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
echo 'Hello World';
```

</td>
<td>

```php
<?php // Here assuming the file starts with a BOM
echo 'Hello World';
```

</td>
 </tr>
</table>
</details>
<details open id='EndFileNewlineStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">End of File Newline</summary>
Files should end with a newline character.
</details>
<details open id='EndFileNoNewlineStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">No End of File Newline</summary>
Files should not end with a newline character.

</details><details open id='ExecutableFileStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Executable Files</summary>
Files should not be executable.

</details><details open id='InlineHTMLStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Inline HTML</summary>
Files that contain php code should only have php code and should not have any "inline html".

<table style="width: 100%">
 <tr>
  <th><b>Valid: A php file with only php code in it.</b></th>
  <th><b>Invalid: A php file with html in it outside of the php tags.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
$foo = 'bar';
echo $foo . 'baz';
```

</td>
<td>

```php
<em>some string here</em>
<?php
$foo = 'bar';
echo $foo . 'baz';
```

</td>
 </tr>
</table>
</details><details open id='LineEndingsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Line Endings</summary>
Unix-style line endings are preferred ("\n" instead of "\r\n").

<table style="width: 100%">
 <tr>
  <th><b>Valid: Unix-style line ending.</b></th>
  <th><b>Invalid: Windows-style line ending.</b></th>
 </tr>
 <tr>
<td>

```php
// Using Unix-style line ending
echo "Hello, World!\n";
```

</td>
<td>

```php
// Using Windows-style line ending
echo "Hello, World!\r\n";
```

</td>
 </tr>
</table>
</details>
<details open id='LineLengthStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Line Length</summary>
It is recommended to keep lines at approximately 80 characters long for better code readability.

</details>
<details open id='LowercasedFilenameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercased Filenames</summary>
Lowercase filenames are required.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase filename.</b></th>
  <th><b>Invalid: Uppercase or mixed case filename.</b></th>
 </tr>
 <tr>
<td>

```plaintext
example.php
```

</td>
<td>

```plaintext
Example.php
EXAMPLE.php
ExAmPlE.php
```

</td>
 </tr>
</table>
</details><details open id='OneClassPerFileStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">One Class Per File</summary>
There should only be one class defined in a file.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Only one class in the file.</b></th>
  <th><b>Invalid: Multiple classes defined in one file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
class Foo
{
}
```

</td>
<td>

```php
<?php
class Foo
{
}

class Bar
{
}
```

</td>
 </tr>
</table>
</details><details open id='OneInterfacePerFileStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">One Interface Per File</summary>
There should only be one interface defined in a file.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Only one interface in the file.</b></th>
  <th><b>Invalid: Multiple interfaces defined in one file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
interface Foo
{
}
```

</td>
<td>

```php
<?php
interface Foo
{
}

interface Bar
{
}
```

</td>
 </tr>
</table>
</details><details open id='OneObjectStructurePerFileStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">One Object Structure Per File</summary>
There should only be one class or interface or trait defined in a file.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Only one object structure in the file.</b></th>
  <th><b>Invalid: Multiple object structures defined in one file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
trait Foo
{
}
```

</td>
<td>

```php
<?php
trait Foo
{
}

class Bar
{
}
```

</td>
 </tr>
</table>
</details><details open id='OneTraitPerFileStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">One Trait Per File</summary>
There should only be one trait defined in a file.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Only one trait in the file.</b></th>
  <th><b>Invalid: Multiple traits defined in one file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
trait Foo
{
}
```

</td>
<td>

```php
<?php
trait Foo
{
}

trait Bar
{
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Formatting'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Formatting</summary>
<hr>
<details open id='DisallowMultipleStatementsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Multiple Statements On a Single Line</summary>
Multiple statements are not allowed on a single line.

<table style="width: 100%">
<tr>
<th><b>Valid: Two statements are spread out on two separate lines.</b></th>
<th><b>Invalid: Two statements are combined onto one line.</b></th>
</tr>
<tr>
<td>

```php
$foo = 1;
$bar = 2;
```

</td>
<td>

```php
$foo = 1; $bar = 2;
```

</td>
</tr>
</table>
</details><details open id='MultipleStatementAlignmentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Aligning Blocks of Assignments</summary>
There should be one space on either side of an equals sign used to assign a value to a variable. In the case of a block of related assignments, more space may be inserted to promote readability.

<table style="width: 100%">
 <tr>
  <th><b>Equals signs aligned</b></th>
  <th><b>Not aligned; harder to read</b></th>
 </tr>
 <tr>
<td>

```php
$shortVar        = (1 + 2);
$veryLongVarName = 'string';
$var             = foo($bar, $baz);
```

</td>
<td>

```php
$shortVar = (1 + 2);
$veryLongVarName = 'string';
$var = foo($bar, $baz);
```

</td>
</tr>
</table>

When using plus-equals, minus-equals etc. still ensure the equals signs are aligned to one space after the longest variable name.

<table style="width: 100%">
 <tr>
  <th><b>Equals signs aligned; only one space after longest var name</b></th>
  <th><b>Two spaces after longest var name</b></th>
 </tr>
 <tr>
<td>

```php
$shortVar        += 1;
$veryLongVarName  = 1;
```

</td>
<td>

```php
$shortVar         += 1;
$veryLongVarName   = 1;
```

</td>
</tr>
 <tr>
  <th><b>Equals signs aligned</b></th>
  <th><b>Equals signs not aligned</b></th>
 </tr>
<tr>
<td>

```php
$shortVar         = 1;
$veryLongVarName -= 1;
```

</td>
<td>

```php
$shortVar        = 1;
$veryLongVarName -= 1;
```

</td>
</tr>
</table>
</details>
<details open id='NoSpaceAfterCastStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Space After Casts</summary>
Spaces are not allowed after casting operators.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A cast operator is immediately before its value.</b></th>
  <th><b>Invalid: A cast operator is followed by whitespace.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = (string)1;
```

</td>
<td>

```php
$foo = (string) 1;
```

</td>
 </tr>
</table>
</details>
<details open id='SpaceAfterCastStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Space After Casts</summary>
Exactly one space is allowed after a cast.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A cast operator is followed by one space.</b></th>
  <th><b>Invalid: A cast operator is not followed by whitespace.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = (string) 1;
```

</td>
<td>

```php
$foo = (string)1;
```

</td>
 </tr>
</table>
</details><details open id='SpaceAfterNotStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Space After NOT operator</summary>
Exactly one space is allowed after the NOT operator.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A NOT operator followed by one space.</b></th>
  <th><b>Invalid: A NOT operator not followed by whitespace or followed by too much whitespace.</b></th>
 </tr>
 <tr>
<td>

```php
if (!$someVar || !$x instanceOf stdClass) {};
```

</td>
<td>

```php
if (!$someVar || !$x instanceOf stdClass) {};

if (!    $someVar || !
    $x instanceOf stdClass) {};
```

</td>
 </tr>
</table>
</details><details open id='SpaceBeforeCastStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Space Before Cast</summary>
There should be exactly one space before a cast operator.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single space before a cast operator.</b></th>
  <th><b>Invalid: No space or multiple spaces before a cast operator.</b></th>
 </tr>
 <tr>
<td>

```php
$integer = (int) $string;
$c = $a . (string) $b;
```

</td>
<td>

```php
$integer =(int) $string;
$c = $a .   (string) $b;
```

</td>
 </tr>
</table>
</details>
</details><details open id='Functions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Functions</summary>
<hr>
<details open id='CallTimePassByReferenceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Call-Time Pass-By-Reference</summary>
Call-time pass-by-reference is not allowed. It should be declared in the function definition.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Pass-by-reference is specified in the function definition.</b></th>
  <th><b>Invalid: Pass-by-reference is done in the call to a function.</b></th>
 </tr>
 <tr>
<td>

```php
function foo(&$bar)
{
    $bar++;
}

$baz = 1;
foo($baz);
```

</td>
<td>

```php
function foo($bar)
{
    $bar++;
}

$baz = 1;
foo(&$baz);
```

</td>
 </tr>
</table>
</details><details open id='FunctionCallArgumentSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Argument Spacing</summary>
Function arguments should have one space after a comma, and single spaces surrounding the equals sign for default values.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single spaces after a comma.</b></th>
  <th><b>Invalid: No spaces after a comma.</b></th>
 </tr>
 <tr>
<td>

```php
function foo($bar, $baz)
{
}
```

</td>
<td>

```php
function foo($bar,$baz)
{
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Single spaces around an equals sign in function declaration.</b></th>
  <th><b>Invalid: No spaces around an equals sign in function declaration.</b></th>
 </tr>
 <tr>
<td>

```php
function foo($bar, $baz = true)
{
}
```

</td>
<td>

```php
function foo($bar, $baz=true)
{
}
```

</td>
 </tr>
</table>
</details><details open id='OpeningFunctionBraceBsdAllmanStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Opening Brace in Function Declarations</summary>
Function declarations follow the "BSD/Allman style". The function brace is on the line following the function declaration and is indented to the same column as the start of the function declaration.

<table style="width: 100%">
 <tr>
  <th><b>Valid: brace on next line</b></th>
  <th><b>Invalid: brace on same line</b></th>
 </tr>
 <tr>
<td>

```php
function fooFunction($arg1, $arg2 = '')
{
    ...
}
```

</td>
<td>

```php
function fooFunction($arg1, $arg2 = '') {
    ...
}
```

</td>
 </tr>
</table>
</details><details open id='OpeningFunctionBraceKernighanRitchieStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Opening Brace in Function Declarations</summary>

Function declarations follow the "Kernighan/Ritchie style". The function brace is on the same line as the function declaration. One space is required between the closing parenthesis and the brace.

<table style="width: 100%">
 <tr>
  <th><b>Valid: brace on same line</b></th>
  <th><b>Invalid: brace on next line</b></th>
 </tr>
 <tr>
<td>

```php
function fooFunction($arg1, $arg2 = '') {
    ...
}
```

</td>
<td>

```php
function fooFunction($arg1, $arg2 = '')
{
    ...
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Metrics'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Metrics</summary>
<hr>

<details open id='CyclomaticComplexityStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Cyclomatic Complexity</summary>
Functions should not have a cyclomatic complexity greater than 20, and should try to stay below a complexity of 10.

</details>

<details open id='NestingLevelStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Nesting Level</summary>
Functions should not have a nesting level greater than 10, and should try to stay below 5.
</details>

</details><details open id='NamingConventions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Naming Conventions</summary>
<hr>
<details open id='AbstractClassNamePrefixStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Abstract class name</summary>
Abstract class names must be prefixed with "Abstract", e.g. AbstractBar.

<table style="width: 100%">
 <tr>
  <th><b>Valid:</b></th>
  <th><b>Invalid:</b></th>
 </tr>
 <tr>
<td>

```php
abstract class AbstractBar
{
}
```

</td>
<td>

```php
abstract class Bar
{
}
```

</td>
 </tr>
</table>
</details>
<details open id='CamelCapsFunctionNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">camelCaps Function Names</summary>

Functions should use camelCaps format for their names. Only PHP's magic methods should use a double underscore prefix.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A function in camelCaps format.</b></th>
  <th><b>Invalid: A function in snake_case format.</b></th>
 </tr>
 <tr>
<td>

```php
function doSomething()
{
}
```

</td>
<td>

```php
function do_something()
{
}
```

</td>
 </tr>
</table>
</details>
<details open id='ConstructorNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Constructor name</summary>
Constructors should be named __construct, not after the class.

<table style="width: 100%">
 <tr>
  <th><b>Valid: The constructor is named __construct.</b></th>
  <th><b>Invalid: The old style class name constructor is used.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    function __construct()
    {
    }
}
```

</td>
<td>

```php
class Foo
{
    function Foo()
    {
    }
}
```

</td>
 </tr>
</table>
</details><details open id='InterfaceNameSuffixStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Interface name suffix</summary>
Interface names must be suffixed with "Interface", e.g. BarInterface.

<table style="width: 100%">
 <tr>
  <th><b>Valid: </b></th>
  <th><b>Invalid: </b></th>
 </tr>
 <tr>
<td>

```php
interface BarInterface
{
}
```

</td>
<td>

```php
interface Bar
{
}
```

</td>
 </tr>
</table>
</details><details open id='TraitNameSuffixStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Trait name suffix</summary>
Trait names must be suffixed with "Trait", e.g. BarTrait.

<table style="width: 100%">
 <tr>
  <th><b>Valid: </b></th>
  <th><b>Invalid: </b></th>
 </tr>
 <tr>
<td>

```php
trait BarTrait
{
}
```

</td>
<td>

```php
trait Bar
{
}
```

</td>
 </tr>
</table>
</details><details open id='UpperCaseConstantNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Constant Names</summary>
Constants should always be all-uppercase, with underscores to separate words.

<table style="width: 100%">
 <tr>
  <th><b>Valid: all uppercase</b></th>
  <th><b>Invalid: mixed case</b></th>
 </tr>
 <tr>
<td>

```php
define('FOO_CONSTANT', 'foo');

class FooClass
{
    const FOO_CONSTANT = 'foo';
}
```

</td>
<td>

```php
define('Foo_Constant', 'foo');

class FooClass
{
    const foo_constant = 'foo';
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='PHP'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">P H P</summary>
<hr>
<details open id='BacktickOperatorStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Backtick Operator</summary>
Disallow the use of the backtick operator for execution of shell commands.
</details><details open id='CharacterBeforePHPOpeningTagStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Opening Tag at Start of File</summary>
The opening php tag should be the first item in the file.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A file starting with an opening php tag.</b></th>
  <th><b>Invalid: A file with content before the opening php tag.</b></th>
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
Beginning content
<?php
echo 'Foo';
```

</td>
 </tr>
</table>
</details><details open id='ClosingPHPTagStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Closing PHP Tags</summary>
All opening php tags should have a corresponding closing tag.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A closing tag paired with it's opening tag.</b></th>
  <th><b>Invalid: No closing tag paired with the opening tag.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
echo 'Foo';
?>
```

</td>
<td>

```php
<?php
echo 'Foo';
```

</td>
 </tr>
</table>
</details><details open id='DeprecatedFunctionsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Deprecated Functions</summary>
Deprecated functions should not be used.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A non-deprecated function is used.</b></th>
  <th><b>Invalid: A deprecated function is used.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = explode('a', $bar);
```

</td>
<td>

```php
$foo = split('a', $bar);
```

</td>
 </tr>
</table>
</details>
<details open id='DisallowAlternativePHPTagsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Alternative PHP Code Tags</summary>
Always use `<?php ?>` to delimit PHP code, do not use the ASP `<% %>` style tags nor the `<script language="php"></script>` tags. This is the most portable way to include PHP code on differing operating systems and setups.
</details>
<details open id='DisallowRequestSuperglobalStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">$_REQUEST Superglobal</summary>
$_REQUEST should never be used due to the ambiguity created as to where the data is coming from. Use $_POST, $_GET, or $_COOKIE instead.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Use specific superglobals.</b></th>
  <th><b>Invalid: Using $_REQUEST.</b></th>
 </tr>
 <tr>
<td>

```php
// Using $_GET
if (isset($_GET['id'])) {
    $id = $_GET['id'];
}

// Using $_POST
if (isset($_POST['name'])) {
    $name = $_POST['name'];
}
```

</td>
<td>

```php
// Using $_REQUEST
if (isset($_REQUEST['data'])) {
    $data = $_REQUEST['data'];
}
```

</td>
 </tr>
</table>
</details>
<details open id='DisallowShortOpenTagStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">PHP Code Tags</summary>
Always use `<?php ?>` to delimit PHP code, not the `<? ?>` shorthand. This is the most portable way to include PHP code on differing operating systems and setups.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Use standard PHP tags.</b></th>
  <th><b>Invalid: Use of short tags.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
// PHP code here
?>
```

</td>
<td>

```php
<?
// PHP code here
?>
```

</td>
 </tr>
</table>
</details>

<details open id='DiscourageGotoStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Goto</summary>
Discourage the use of the PHP `goto` language construct.

</details>
<details open id='ForbiddenFunctionsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Forbidden Functions</summary>
The forbidden functions sizeof() and delete() should not be used.

<table style="width: 100%">
 <tr>
  <th><b>Valid: count() is used in place of sizeof().</b></th>
  <th><b>Invalid: sizeof() is used.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = count($bar);
```

</td>
<td>

```php
$foo = sizeof($bar);
```

</td>
 </tr>
</table>
</details><details open id='LowerCaseConstantStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercase PHP Constants</summary>
The <em>true</em>, <em>false</em> and <em>null</em> constants must always be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: lowercase constants</b></th>
  <th><b>Invalid: uppercase constants</b></th>
 </tr>
 <tr>
<td>

```php
if ($var === false || $var === null) {
    $var = true;
}
```

</td>
<td>

```php
if ($var === FALSE || $var === NULL) {
    $var = TRUE;
}
```

</td>
 </tr>
</table>
</details><details open id='LowerCaseKeywordStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercase Keywords</summary>
All PHP keywords should be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase array keyword used.</b></th>
  <th><b>Invalid: Non-lowercase array keyword used.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = array();
```

</td>
<td>

```php
$foo = Array();
```

</td>
 </tr>
</table>
</details><details open id='LowerCaseTypeStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Lowercase PHP Types</summary>
All PHP types used for parameter type and return type declarations should be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase type declarations used.</b></th>
  <th><b>Invalid: Non-lowercase type declarations used.</b></th>
 </tr>
 <tr>
<td>

```php
function myFunction(int $foo) : string {
}
```

</td>
<td>

```php
function myFunction(<em>Int</em> $foo) : <em>STRING</em> {
}
```

</td>
 </tr>
</table>
All PHP types used for type casting should be lowercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Lowercase type used.</b></th>
  <th><b>Invalid: Non-lowercase type used.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = (bool) $isValid;
```

</td>
<td>

```php
$foo = <em>(BOOL)</em> $isValid;
```

</td>
 </tr>
</table>
</details><details open id='NoSilencedErrorsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Silenced Errors</summary>
Suppressing Errors is not allowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: isset() is used to verify that a variable exists before trying to use it.</b></th>
  <th><b>Invalid: Errors are suppressed.</b></th>
 </tr>
 <tr>
<td>

```php
if (isset($foo) && $foo) {
    echo "Hello\n";
}
```

</td>
<td>

```php
if (@$foo) {
    echo "Hello\n";
}
```

</td>
 </tr>
</table>
</details><details open id='SAPIUsageStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">SAPI Usage</summary>
The PHP_SAPI constant should be used instead of php_sapi_name().

<table style="width: 100%">
 <tr>
  <th><b>Valid: PHP_SAPI is used.</b></th>
  <th><b>Invalid: php_sapi_name() is used.</b></th>
 </tr>
 <tr>
<td>

```php
if (PHP_SAPI === 'cli') {
    echo "Hello, CLI user.";
}
```

</td>
<td>

```php
if (php_sapi_name() === 'cli') {
    echo "Hello, CLI user.";
}
```

</td>
 </tr>
</table>
</details><details open id='SyntaxStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">PHP Syntax</summary>
The code should use valid PHP syntax.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No PHP syntax errors.</b></th>
  <th><b>Invalid: Code contains PHP syntax errors.</b></th>
 </tr>
 <tr>
<td>

```php
echo "Hello!";
$array = [1, 2, 3];
```

</td>
<td>

```php
echo "Hello!" // Missing semicolon.
$array = [1, 2, 3; // Missing closing bracket.
```

</td>
 </tr>
</table>
</details><details open id='UpperCaseConstantStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Uppercase PHP Constants</summary>

The *true*, *false* and *null* constants must always be uppercase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: uppercase constants</b></th>
  <th><b>Invalid: lowercase constants</b></th>
 </tr>
 <tr>
<td>

```php
if ($var === FALSE || $var === NULL) {
    $var = TRUE;
}
```

</td>
<td>

```php
if ($var === false || $var === null) {
    $var = true;
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Strings'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Strings</summary>
<hr>
<details open id='UnnecessaryStringConcatStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unnecessary String Concatenation</summary>
Strings should not be concatenated together.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A string can be concatenated with an expression.</b></th>
  <th><b>Invalid: Strings should not be concatenated together.</b></th>
 </tr>
 <tr>
<td>

```php
echo '5 + 2 = ' . (5 + 2);
```

</td>
<td>

```php
echo 'Hello' . ' ' . 'World';
```

</td>
 </tr>
</table>
</details>
</details><details open id='VersionControl'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Version Control</summary>
<hr>
<details open id='SubversionPropertiesStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Subversion Properties</summary>
All php files in a subversion repository should have the svn:keywords property set to 'Author Id Revision' and the svn:eol-style property set to 'native'.
</details>
</details><details open id='WhiteSpace'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">White Space</summary>
<hr>
<details open id='ArbitraryParenthesesSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Arbitrary Parentheses Spacing</summary>
Arbitrary sets of parentheses should have no spaces inside.

<table style="width: 100%">
 <tr>
  <th><b>Valid: no spaces on the inside of a set of arbitrary parentheses.</b></th>
  <th><b>Invalid: spaces or new lines on the inside of a set of arbitrary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$a = (null !== $extra);
```

</td>
<td>

```php
$a = ( null !== $extra );

$a = (
    null !== $extra
);
```

</td>
 </tr>
</table>
</details>
<details open id='DisallowSpaceIndentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">No Space Indentation</summary>
Tabs should be used for indentation instead of spaces.

</details>
<details open id='DisallowTabIndentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">No Tab Indentation</summary>
Spaces should be used for indentation instead of tabs.

</details><details open id='IncrementDecrementSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Increment Decrement Spacing</summary>
There should be no whitespace between variables and increment/decrement operators.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No whitespace between variables and increment/decrement operators.</b></th>
  <th><b>Invalid: Whitespace between variables and increment/decrement operators.</b></th>
 </tr>
 <tr>
<td>

```php
++$i;
--$i['key']['id'];
ClassName::$prop++;
$obj->prop--;
```

</td>
<td>

```php
++ $i;
--   $i['key']['id'];
ClassName::$prop    ++;
$obj->prop
--;
```

</td>
 </tr>
</table>
</details><details open id='LanguageConstructSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Language Construct Spacing</summary>
Language constructs that can be used without parentheses, must have a single space between the language construct keyword and its content.

A single space must be used between the "yield" and "from" keywords for a "yield from" expression.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single space after language construct.</b></th>
  <th><b>Invalid: No space, more than one space or newline after language construct.</b></th>
 </tr>
 <tr>
<td>

```php
echo 'Hello, World!';
throw new Exception();
return $newLine;
```

</td>
<td>

```php
echo'Hello, World!';
throw  new  Exception();
return
$newLine;
```

</td>
 </tr>
<tr>
  <th><b>Valid: Single space between yield and from.</b></th>
  <th><b>Invalid: No space, more than one space or newline between yield and from.</b></th>
 </tr>
 <tr>
<td>

```php
yield from [1, 2, 3];
```

</td>
<td>

```php
yieldfrom [1, 2, 3];
yield  from [1, 2, 3];
yield
from [1, 2, 3];
```

</td>
 </tr>
</table>
</details><details open id='ScopeIndentStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Scope Indentation</summary>
Indentation for control structures, classes, and functions should be 4 spaces per level.

<table style="width: 100%">
 <tr>
  <th><b>Valid: 4 spaces are used to indent a control structure.</b></th>
  <th><b>Invalid: 8 spaces are used to indent a control structure.</b></th>
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
</details><details open id='SpreadOperatorSpacingAfterStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Spacing After Spread Operator</summary>
There should be no space between the spread operator and the variable/function call it applies to.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No space between the spread operator and the variable/function call it applies to.</b></th>
  <th><b>Invalid: space found between the spread operator and the variable/function call it applies to.</b></th>
 </tr>
 <tr>
<td>

```php
function foo(&...$spread) {
    bar(...$spread);

    bar(
        [...$foo],
        ...array_values($keyedArray)
    );
}
```

</td>
<td>

```php
function bar(... $spread) {
    bar(...
        $spread
    );

    bar(
        [...  $foo ],.../*comment*/array_values($keyedArray)
    );
}
```

</td>
 </tr>
</table>
</details>