## Table of Contents

- [Classes](#Classes)
    - [Class Instantiation Standard](#ClassInstantiationStandard)
    - [Closing Brace Standard](#ClosingBraceStandard)
    - [Opening Brace Space Standard](#OpeningBraceSpaceStandard)
- [Control Structures](#ControlStructures)
    - [Boolean Operator Placement Standard](#BooleanOperatorPlacementStandard)
    - [Control Structure Spacing Standard](#ControlStructureSpacingStandard)
- [Files](#Files)
    - [Import Statement Standard](#ImportStatementStandard)
    - [Open Tag Standard](#OpenTagStandard)
- [Functions](#Functions)
    - [Nullable Type Declaration Standard](#NullableTypeDeclarationStandard)
    - [Return Type Declaration Standard](#ReturnTypeDeclarationStandard)
- [Keywords](#Keywords)
    - [Short Form Type Keywords Standard](#ShortFormTypeKeywordsStandard)
- [Namespaces](#Namespaces)
    - [Compound Namespace Depth Standard](#CompoundNamespaceDepthStandard)
- [Operators](#Operators)
    - [Operator Spacing Standard](#OperatorSpacingStandard)
- [Properties](#Properties)
    - [Constant Visibility Standard](#ConstantVisibilityStandard)



</details><details open id='Classes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Classes</summary>
<hr>
<details open id='ClassInstantiationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Instantiation</summary>
When instantiating a new class, parenthesis MUST always be present even when there are no arguments passed to the constructor.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Parenthesis used.</b></th>
  <th><b>Invalid: Parenthesis not used.</b></th>
 </tr>
 <tr>
<td>

```php
new Foo();
```

</td>
<td>

```php
new Foo;
```

</td>
 </tr>
</table>
</details><details open id='ClosingBraceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Closing Brace</summary>
The closing brace of object-oriented constructs and functions must not be followed by any comment or statement on the same line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Closing brace is the last content on the line.</b></th>
  <th><b>Invalid: Comment or statement following the closing brace on the same line.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    // Class content.
}

function bar()
{
    // Function content.
}
```

</td>
<td>

```php
interface Foo2
{
    // Interface content.
} echo 'Hello!';

function bar()
{
    // Function content.
} //end bar()
```

</td>
 </tr>
</table>
</details><details open id='OpeningBraceSpaceStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Opening Brace Space</summary>
The opening brace of an object-oriented construct must not be followed by a blank line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No blank lines after opening brace.</b></th>
  <th><b>Invalid: Blank line after opening brace.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{<em></em>
    public function bar()
    {
        // Method content.
    }
}
```

</td>
<td>

```php
class Foo
{
<em></em>
    public function bar()
    {
        // Method content.
    }
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='ControlStructures'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Control Structures</summary>
<hr>
<details open id='BooleanOperatorPlacementStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Boolean Operator Placement</summary>
Boolean operators between conditions in control structures must always be at the beginning or at the end of the line, not a mix of both.

This rule applies to if/else conditions, while loops and switch/match statements.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Boolean operator between conditions consistently at the beginning of the line.</b></th>
  <th><b>Invalid: Mix of boolean operators at the beginning and the end of the line.</b></th>
 </tr>
 <tr>
<td>

```php
if (
    $expr1
    && $expr2
    && ($expr3
    || $expr4)
    && $expr5
) {
    // if body.
}
```

</td>
<td>

```php
if (
    $expr1 &&
    ($expr2 || $expr3)
    && $expr4
) {
    // if body.
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Boolean operator between conditions consistently at the end of the line.</b></th>
  <th><b>Invalid: Mix of boolean operators at the beginning and the end of the line.</b></th>
 </tr>
 <tr>
<td>

```php
if (
    $expr1 ||
    ($expr2 || $expr3) &&
    $expr4
) {
    // if body.
}
```

</td>
<td>

```php
match (
    $expr1
    && $expr2 ||
    $expr3
) {
    // structure body.
};
```

</td>
 </tr>
</table>
</details><details open id='ControlStructureSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Control Structure Spacing</summary>
Single line control structures must have no spaces after the condition opening parenthesis and before the condition closing parenthesis.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No space after the opening parenthesis in a single-line condition.</b></th>
  <th><b>Invalid: Space after the opening parenthesis in a single-line condition.</b></th>
 </tr>
 <tr>
<td>

```php
if ($expr) {
}
```

</td>
<td>

```php
if ( $expr) {
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: No space before the closing parenthesis in a single-line condition.</b></th>
  <th><b>Invalid: Space before the closing parenthesis in a single-line condition.</b></th>
 </tr>
 <tr>
<td>

```php
if ($expr) {
}
```

</td>
<td>

```php
if ($expr ) {
}
```

</td>
 </tr>
</table>

The condition of the multi-line control structure must be indented once, placing the first expression on the next line after the opening parenthesis.

<table style="width: 100%">
 <tr>
  <th><b>Valid: First expression of a multi-line control structure condition block is on the line after the opening parenthesis.</b></th>
  <th><b>Invalid: First expression of a multi-line control structure condition block is on the same line as the opening parenthesis.</b></th>
 </tr>
 <tr>
<td>

```php
while (
    $expr1
    && $expr2
) {
}
```

</td>
<td>

```php
while ($expr1
    && $expr2
) {
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Each line in a multi-line control structure condition block indented at least once. Default indentation is 4 spaces.</b></th>
  <th><b>Invalid: Some lines in a multi-line control structure condition block not indented correctly.</b></th>
 </tr>
 <tr>
<td>

```php
while (
    $expr1
    && $expr2
) {
}
```

</td>
<td>

```php
while (
$expr1
    && $expr2
  && $expr3
) {
}
```

</td>
 </tr>
</table>

The closing parenthesis of the multi-line control structure must be on the next line after the last condition, indented to the same level as the start of the control structure.

<table style="width: 100%">
 <tr>
  <th><b>Valid: The closing parenthesis of a multi-line control structure condition block is on the line after the last expression.</b></th>
  <th><b>Invalid: The closing parenthesis of a multi-line control structure condition block is on the same line as the last expression.</b></th>
 </tr>
 <tr>
<td>

```php
while (
    $expr1
    && $expr2
) {
}
```

</td>
<td>

```php
while (
    $expr1
    && $expr2) {
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: The closing parenthesis of a multi-line control structure condition block is indented to the same level as start of the control structure.</b></th>
  <th><b>Invalid: The closing parenthesis of a multi-line control structure condition block is not indented to the same level as start of the control structure.</b></th>
 </tr>
 <tr>
<td>

```php
while (
    $expr1
    && $expr2
) {
}
```

</td>
<td>

```php
while (
    $expr1
    && $expr2
  ) {
}
```

</td>
 </tr>
</table>

</details>
</details><details open id='Files'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Files</summary>
<hr>
<details open id='ImportStatementStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Import Statement</summary>
Import use statements must not begin with a leading backslash.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Import statement doesn't begin with a leading backslash.</b></th>
  <th><b>Invalid: Import statement begins with a leading backslash.</b></th>
 </tr>
 <tr>
<td>

```php
<?php

use Vendor\Package\ClassA as A;

class FooBar extends A
{
    // Class content.
}
```

</td>
<td>

```php
<?php

use \Vendor\Package\ClassA as A;

class FooBar extends A
{
    // Class content.
}
```

</td>
 </tr>
</table>
</details><details open id='OpenTagStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Open PHP Tag</summary>
When the opening <?php tag is on the first line of the file, it must be on its own line with no other statements unless it is a file containing markup outside of PHP opening and closing tags.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Opening PHP tag on a line by itself.</b></th>
  <th><b>Invalid: Opening PHP tag not on a line by itself.</b></th>
 </tr>
 <tr>
<td>

```php
<?php

echo 'hi';
```

</td>
<td>

```php
<?php echo 'hi';
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Opening PHP tag not on a line by itself, but has markup outside the closing PHP tag.</b></th>
  <th><b>Invalid: Opening PHP tag not on a line by itself without any markup in the file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php declare(strict_types=1); ?>
<html>
<body>
    <?php
        // ... additional PHP code ...
    ?>
</body>
</html>
```

</td>
<td>

```php
<?php declare(strict_types=1); ?>
```

</td>
 </tr>
</table>
</details>
</details><details open id='Functions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Functions</summary>
<hr>
<details open id='NullableTypeDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Nullable Type Declarations Functions</summary>
In nullable type declarations there MUST NOT be a space between the question mark and the type.

<table style="width: 100%">
 <tr>
  <th><b>Valid: no whitespace used.</b></th>
  <th><b>Invalid: superfluous whitespace used.</b></th>
 </tr>
 <tr>
<td>

```php
public function functionName(
    ?string $arg1,
    ?int $arg2
): ?string {
}
```

</td>
<td>

```php
public function functionName(
    ? string $arg1,
    ? int $arg2
): ? string {
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: no unexpected characters.</b></th>
  <th><b>Invalid: unexpected characters used.</b></th>
 </tr>
 <tr>
<td>

```php
public function foo(?int $arg): ?string
{
}
```

</td>
<td>

```php
public function bar(? /* comment */ int $arg): ?
    // nullable for a reason
    string
{
}
```

</td>
 </tr>
</table>
</details><details open id='ReturnTypeDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Return Type Declaration</summary>
For function and closure return type declarations, there must be one space after the colon followed by the type declaration, and no space before the colon.

The colon and the return type declaration have to be on the same line as the argument list closing parenthesis.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A single space between the colon and type in a return type declaration.</b></th>
  <th><b>Invalid: No space between the colon and the type in a return type declaration.</b></th>
 </tr>
 <tr>
<td>

```php
$closure = function ( $arg ): string {
   // Closure body.
};
```

</td>
<td>

```php
$closure = function ( $arg ):string {
   // Closure body.
};
```

</td>
 </tr>
<tr>
  <th><b>Valid: No space before the colon in a return type declaration.</b></th>
  <th><b>Invalid: One or more spaces before the colon in a return type declaration.</b></th>
 </tr>
 <tr>
<td>

```php
function someFunction( $arg ): string {
   // Function body.
};
```

</td>
<td>

```php
function someFunction( $arg )   : string {
   // Function body.
};
```

</td>
 </tr>
</table>
</details>
</details><details open id='Keywords'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Keywords</summary>
<hr>
<details open id='ShortFormTypeKeywordsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Short Form Type Keywords</summary>
Short form of type keywords MUST be used i.e. bool instead of boolean, int instead of integer etc.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Short form type used.</b></th>
  <th><b>Invalid: Long form type used.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = (bool) $isValid;
```

</td>
<td>

```php
$foo = (boolean) $isValid;
```

</td>
 </tr>
</table>
</details>
</details><details open id='Namespaces'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Namespaces</summary>
<hr>
<details open id='CompoundNamespaceDepthStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Compound Namespace Depth</summary>
Compound namespaces with a depth of more than two MUST NOT be used.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Max depth of 2.</b></th>
  <th><b>Invalid: Max depth of 3.</b></th>
 </tr>
 <tr>
<td>

```php
use Vendor\Package\SomeNamespace\{
    SubnamespaceOne\ClassA,
    SubnamespaceOne\ClassB,
    SubnamespaceTwo\ClassY,
    ClassZ,
};
```

</td>
<td>

```php
use Vendor\Package\SomeNamespace\{
    SubnamespaceOne\AnotherNamespace\ClassA,
    SubnamespaceOne\ClassB,
    ClassZ,
};
```

</td>
 </tr>
</table>
</details>
</details><details open id='Operators'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Operators</summary>
<hr>
<details open id='OperatorSpacingStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Operator Spacing</summary>
All binary and ternary (but not unary) operators MUST be preceded and followed by at least one space. This includes all arithmetic, comparison, assignment, bitwise, logical (excluding ! which is unary), string concatenation, type operators, trait operators (insteadof and as), and the single pipe operator (e.g. ExceptionType1 | ExceptionType2 $e).

<table style="width: 100%">
 <tr>
  <th><b>Valid: At least 1 space used.</b></th>
  <th><b>Invalid: No spacing used.</b></th>
 </tr>
 <tr>
<td>

```php
if ($a === $b) {
    $foo = $bar ?? $a ?? $b;
} elseif ($a > $b) {
    $variable = $foo ? 'foo' : 'bar';
}
```

</td>
<td>

```php
if ($a===$b) {
    $foo=$bar??$a??$b;
} elseif ($a>$b) {
    $variable=$foo?'foo':'bar';
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Properties'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Properties</summary>
<hr>

<details open id='ConstantVisibilityStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Constant Visibility</summary>
Visibility must be declared on all class constants if your project PHP minimum version supports constant visibilities (PHP 7.1 or later).

The term "class" refers to all classes, interfaces, enums and traits.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Constant visibility declared.</b></th>
  <th><b>Invalid: Constant visibility not declared.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    private const BAR = 'bar';
}
```

</td>
<td>

```php
class Foo
{
    const BAR = 'bar';
}
```

</td>
 </tr>
</table>
</details>
