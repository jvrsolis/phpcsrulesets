## Table of Contents

- [Arrays](#Arrays)
    - [Arrays. Alphabetically Sorted By Keys Sniff](#Arrays.AlphabeticallySortedByKeysSniff)
    - [Arrays. Array Access Sniff](#Arrays.ArrayAccessSniff)
    - [Arrays. Disallow Implicit Array Creation Sniff](#Arrays.DisallowImplicitArrayCreationSniff)
    - [Arrays. Disallow Partially Keyed Sniff](#Arrays.DisallowPartiallyKeyedSniff)
    - [Arrays. Multi Line Array End Bracket Placement Sniff](#Arrays.MultiLineArrayEndBracketPlacementSniff)
    - [Arrays. Single Line Array Whitespace Sniff](#Arrays.SingleLineArrayWhitespaceSniff)
    - [Arrays. Trailing Array Comma Sniff](#Arrays.TrailingArrayCommaSniff)
- [Attributes](#Attributes)
    - [Attributes. Attribute And Target Spacing Sniff](#Attributes.AttributeAndTargetSpacingSniff)
    - [Attributes. Attributes Order Sniff](#Attributes.AttributesOrderSniff)
    - [Attributes. Disallow Attributes Joining Sniff](#Attributes.DisallowAttributesJoiningSniff)
    - [Attributes. Disallow Multiple Attributes Per Line Sniff](#Attributes.DisallowMultipleAttributesPerLineSniff)
    - [Attributes. Require Attribute After Doc Comment Sniff](#Attributes.RequireAttributeAfterDocCommentSniff)
- [Classes](#Classes)
    - [Classes. Abstract Method Signature](#Classes.AbstractMethodSignature)
    - [Classes. Abstract Property Constant And Enum Case Spacing](#Classes.AbstractPropertyConstantAndEnumCaseSpacing)
    - [Classes. Backed Enum Type Spacing Sniff](#Classes.BackedEnumTypeSpacingSniff)
    - [Classes. Class Constant Visibility Sniff](#Classes.ClassConstantVisibilitySniff)
    - [Classes. Class Length Sniff](#Classes.ClassLengthSniff)
    - [Classes. Class Member Spacing Sniff](#Classes.ClassMemberSpacingSniff)
    - [Classes. Class Structure Sniff](#Classes.ClassStructureSniff)
    - [Classes. Constant Spacing Sniff](#Classes.ConstantSpacingSniff)
    - [Classes. Disallow Constructor Property Promotion Sniff](#Classes.DisallowConstructorPropertyPromotionSniff)
    - [Classes. Disallow Late Static Binding For Constants Sniff](#Classes.DisallowLateStaticBindingForConstantsSniff)
    - [Classes. Disallow Multi Constant Definition Sniff](#Classes.DisallowMultiConstantDefinitionSniff)
    - [Classes. Disallow Multi Property Definition Sniff](#Classes.DisallowMultiPropertyDefinitionSniff)
    - [Classes. Disallow String Expression Property Fetch Sniff](#Classes.DisallowStringExpressionPropertyFetchSniff)
    - [Classes. Empty Lines Around Class Braces Sniff](#Classes.EmptyLinesAroundClassBracesSniff)
    - [Classes. Enum Case Spacing Sniff](#Classes.EnumCaseSpacingSniff)
    - [Classes. Forbidden Public Property Sniff](#Classes.ForbiddenPublicPropertySniff)
    - [Classes. Method Spacing Sniff](#Classes.MethodSpacingSniff)
    - [Classes. Missing Class Groups Exception](#Classes.MissingClassGroupsException)
    - [Classes. Modern Class Name Reference Sniff](#Classes.ModernClassNameReferenceSniff)
    - [Classes. Parent Call Spacing Sniff](#Classes.ParentCallSpacingSniff)
    - [Classes. Require Abstract Or Final Sniff](#Classes.RequireAbstractOrFinalSniff)
    - [Classes. Require Constructor Property Promotion Sniff](#Classes.RequireConstructorPropertyPromotionSniff)
    - [Classes. Require Multi Line Method Signature Sniff](#Classes.RequireMultiLineMethodSignatureSniff)
    - [Classes. Require Self Reference Sniff](#Classes.RequireSelfReferenceSniff)
    - [Classes. Require Single Line Method Signature Sniff](#Classes.RequireSingleLineMethodSignatureSniff)
    - [Classes. Superfluous Abstract Class Naming Sniff](#Classes.SuperfluousAbstractClassNamingSniff)
    - [Classes. Superfluous Error Naming Sniff](#Classes.SuperfluousErrorNamingSniff)
    - [Classes. Superfluous Exception Naming Sniff](#Classes.SuperfluousExceptionNamingSniff)
    - [Classes. Superfluous Interface Naming Sniff](#Classes.SuperfluousInterfaceNamingSniff)
    - [Classes. Superfluous Trait Naming Sniff](#Classes.SuperfluousTraitNamingSniff)
    - [Classes. Trait Use Declaration Sniff](#Classes.TraitUseDeclarationSniff)
    - [Classes. Trait Use Spacing Sniff](#Classes.TraitUseSpacingSniff)
    - [Classes. Unsupported Class Group Exception](#Classes.UnsupportedClassGroupException)
    - [Classes. Useless Late Static Binding Sniff](#Classes.UselessLateStaticBindingSniff)
- [Commenting](#Commenting)
    - [Commenting. Abstract Require One Line Doc Comment](#Commenting.AbstractRequireOneLineDocComment)
    - [Commenting. Annotation Name Sniff](#Commenting.AnnotationNameSniff)
    - [Commenting. Deprecated Annotation Declaration Sniff](#Commenting.DeprecatedAnnotationDeclarationSniff)
    - [Commenting. Disallow Comment After Code Sniff](#Commenting.DisallowCommentAfterCodeSniff)
    - [Commenting. Disallow One Line Property Doc Comment Sniff](#Commenting.DisallowOneLinePropertyDocCommentSniff)
    - [Commenting. Empty Comment Sniff](#Commenting.EmptyCommentSniff)
    - [Commenting. Forbidden Annotations Sniff](#Commenting.ForbiddenAnnotationsSniff)
    - [Commenting. Forbidden Comments Sniff](#Commenting.ForbiddenCommentsSniff)
    - [Commenting. Inline Doc Comment Declaration Sniff](#Commenting.InlineDocCommentDeclarationSniff)
    - [Commenting. Require One Line Doc Comment Sniff](#Commenting.RequireOneLineDocCommentSniff)
    - [Commenting. Require One Line Property Doc Comment Sniff](#Commenting.RequireOneLinePropertyDocCommentSniff)
    - [Commenting. Useless Function Doc Comment Sniff](#Commenting.UselessFunctionDocCommentSniff)
    - [Commenting. Useless Inherit Doc Comment Sniff](#Commenting.UselessInheritDocCommentSniff)
- [Complexity](#Complexity)
    - [Complexity. Cognitive Sniff](#Complexity.CognitiveSniff)
- [Control Structures](#ControlStructures)
    - [Control Structures. Abstract Control Structure Spacing](#ControlStructures.AbstractControlStructureSpacing)
    - [Control Structures. Abstract Line Condition](#ControlStructures.AbstractLineCondition)
    - [Control Structures. Assignment In Condition Sniff](#ControlStructures.AssignmentInConditionSniff)
    - [Control Structures. Block Control Structure Spacing Sniff](#ControlStructures.BlockControlStructureSpacingSniff)
    - [Control Structures. Disallow Continue Without Integer Operand In Switch Sniff](#ControlStructures.DisallowContinueWithoutIntegerOperandInSwitchSniff)
    - [Control Structures. Disallow Empty Sniff](#ControlStructures.DisallowEmptySniff)
    - [Control Structures. Disallow Null Safe Object Operator Sniff](#ControlStructures.DisallowNullSafeObjectOperatorSniff)
    - [Control Structures. Disallow Short Ternary Operator Sniff](#ControlStructures.DisallowShortTernaryOperatorSniff)
    - [Control Structures. Disallow Trailing Multi Line Ternary Operator Sniff](#ControlStructures.DisallowTrailingMultiLineTernaryOperatorSniff)
    - [Control Structures. Disallow Yoda Comparison Sniff](#ControlStructures.DisallowYodaComparisonSniff)
    - [Control Structures. Early Exit Sniff](#ControlStructures.EarlyExitSniff)
    - [Control Structures. Jump Statements Spacing Sniff](#ControlStructures.JumpStatementsSpacingSniff)
    - [Control Structures. Language Construct With Parentheses Sniff](#ControlStructures.LanguageConstructWithParenthesesSniff)
    - [Control Structures. New With Parentheses Sniff](#ControlStructures.NewWithParenthesesSniff)
    - [Control Structures. New Without Parentheses Sniff](#ControlStructures.NewWithoutParenthesesSniff)
    - [Control Structures. Require Multi Line Condition Sniff](#ControlStructures.RequireMultiLineConditionSniff)
    - [Control Structures. Require Multi Line Ternary Operator Sniff](#ControlStructures.RequireMultiLineTernaryOperatorSniff)
    - [Control Structures. Require Null Coalesce Equal Operator Sniff](#ControlStructures.RequireNullCoalesceEqualOperatorSniff)
    - [Control Structures. Require Null Safe Object Operator Sniff](#ControlStructures.RequireNullSafeObjectOperatorSniff)
    - [Control Structures. Require Short Ternary Operator Sniff](#ControlStructures.RequireShortTernaryOperatorSniff)
    - [Control Structures. Require Single Line Condition Sniff](#ControlStructures.RequireSingleLineConditionSniff)
    - [Control Structures. Require Ternary Operator Sniff](#ControlStructures.RequireTernaryOperatorSniff)
    - [Control Structures. Require Yoda Comparison Sniff](#ControlStructures.RequireYodaComparisonSniff)
    - [Control Structures. Unsupported Keyword Exception](#ControlStructures.UnsupportedKeywordException)
    - [Control Structures. Useless If Condition With Return Sniff](#ControlStructures.UselessIfConditionWithReturnSniff)
    - [Control Structures. Useless Ternary Operator Sniff](#ControlStructures.UselessTernaryOperatorSniff)
- [Exceptions](#Exceptions)
    - [Exceptions. Dead Catch Sniff](#Exceptions.DeadCatchSniff)
    - [Exceptions. Disallow Non Capturing Catch Sniff](#Exceptions.DisallowNonCapturingCatchSniff)
    - [Exceptions. Reference Throwable Only Sniff](#Exceptions.ReferenceThrowableOnlySniff)
- [Files](#Files)
    - [Files. File Length Sniff](#Files.FileLengthSniff)
    - [Files. Function Length Sniff](#Files.FunctionLengthSniff)
    - [Files. Line Length Sniff](#Files.LineLengthSniff)
    - [Files. Type Name Matches File Name Sniff](#Files.TypeNameMatchesFileNameSniff)
- [Functions](#Functions)
    - [Functions. Abstract Line Call](#Functions.AbstractLineCall)
    - [Functions. Arrow Function Declaration Sniff](#Functions.ArrowFunctionDeclarationSniff)
    - [Functions. Disallow Arrow Function Sniff](#Functions.DisallowArrowFunctionSniff)
    - [Functions. Disallow Empty Function Sniff](#Functions.DisallowEmptyFunctionSniff)
    - [Functions. Disallow Named Arguments Sniff](#Functions.DisallowNamedArgumentsSniff)
    - [Functions. Disallow Trailing Comma In Call Sniff](#Functions.DisallowTrailingCommaInCallSniff)
    - [Functions. Disallow Trailing Comma In Closure Use Sniff](#Functions.DisallowTrailingCommaInClosureUseSniff)
    - [Functions. Disallow Trailing Comma In Declaration Sniff](#Functions.DisallowTrailingCommaInDeclarationSniff)
    - [Functions. Function Length Sniff](#Functions.FunctionLengthSniff)
    - [Functions. Named Argument Spacing Sniff](#Functions.NamedArgumentSpacingSniff)
    - [Functions. Require Arrow Function Sniff](#Functions.RequireArrowFunctionSniff)
    - [Functions. Require Multi Line Call Sniff](#Functions.RequireMultiLineCallSniff)
    - [Functions. Require Single Line Call Sniff](#Functions.RequireSingleLineCallSniff)
    - [Functions. Require Trailing Comma In Call Sniff](#Functions.RequireTrailingCommaInCallSniff)
    - [Functions. Require Trailing Comma In Closure Use Sniff](#Functions.RequireTrailingCommaInClosureUseSniff)
    - [Functions. Require Trailing Comma In Declaration Sniff](#Functions.RequireTrailingCommaInDeclarationSniff)
    - [Functions. Static Closure Sniff](#Functions.StaticClosureSniff)
    - [Functions. Strict Call Sniff](#Functions.StrictCallSniff)
    - [Functions. Unused Inherited Variable Passed To Closure Sniff](#Functions.UnusedInheritedVariablePassedToClosureSniff)
    - [Functions. Unused Parameter Sniff](#Functions.UnusedParameterSniff)
    - [Functions. Useless Parameter Default Value Sniff](#Functions.UselessParameterDefaultValueSniff)
- [Namespaces](#Namespaces)
    - [Namespaces. Abstract Fully Qualified Global Reference](#Namespaces.AbstractFullyQualifiedGlobalReference)
    - [Namespaces. Alphabetically Sorted Uses Sniff](#Namespaces.AlphabeticallySortedUsesSniff)
    - [Namespaces. Disallow Group Use Sniff](#Namespaces.DisallowGroupUseSniff)
    - [Namespaces. Fully Qualified Class Name In Annotation Sniff](#Namespaces.FullyQualifiedClassNameInAnnotationSniff)
    - [Namespaces. Fully Qualified Global Constants Sniff](#Namespaces.FullyQualifiedGlobalConstantsSniff)
    - [Namespaces. Fully Qualified Global Functions Sniff](#Namespaces.FullyQualifiedGlobalFunctionsSniff)
    - [Namespaces. Multiple Uses Per Line Sniff](#Namespaces.MultipleUsesPerLineSniff)
    - [Namespaces. Namespace Declaration Sniff](#Namespaces.NamespaceDeclarationSniff)
    - [Namespaces. Namespace Spacing Sniff](#Namespaces.NamespaceSpacingSniff)
    - [Namespaces. Reference Used Names Only Sniff](#Namespaces.ReferenceUsedNamesOnlySniff)
    - [Namespaces. Require One Namespace In File Sniff](#Namespaces.RequireOneNamespaceInFileSniff)
    - [Namespaces. Unused Uses Sniff](#Namespaces.UnusedUsesSniff)
    - [Namespaces. Use Does Not Start With Backslash Sniff](#Namespaces.UseDoesNotStartWithBackslashSniff)
    - [Namespaces. Use From Same Namespace Sniff](#Namespaces.UseFromSameNamespaceSniff)
    - [Namespaces. Use Only Whitelisted Namespaces Sniff](#Namespaces.UseOnlyWhitelistedNamespacesSniff)
    - [Namespaces. Use Spacing Sniff](#Namespaces.UseSpacingSniff)
    - [Namespaces. Useless Alias Sniff](#Namespaces.UselessAliasSniff)
- [Numbers](#Numbers)
    - [Numbers. Disallow Numeric Literal Separator Sniff](#Numbers.DisallowNumericLiteralSeparatorSniff)
    - [Numbers. Require Numeric Literal Separator Sniff](#Numbers.RequireNumericLiteralSeparatorSniff)
- [Operators](#Operators)
    - [Operators. Disallow Equal Operators Sniff](#Operators.DisallowEqualOperatorsSniff)
    - [Operators. Disallow Increment And Decrement Operators Sniff](#Operators.DisallowIncrementAndDecrementOperatorsSniff)
    - [Operators. Negation Operator Spacing Sniff](#Operators.NegationOperatorSpacingSniff)
    - [Operators. Require Only Standalone Increment And Decrement Operators Sniff](#Operators.RequireOnlyStandaloneIncrementAndDecrementOperatorsSniff)
    - [Operators. Spread Operator Spacing Sniff](#Operators.SpreadOperatorSpacingSniff)
- [P H P](#PHP)
    - [P H P. Disallow Direct Magic Invoke Call Sniff](#PHP.DisallowDirectMagicInvokeCallSniff)
    - [P H P. Disallow Reference Sniff](#PHP.DisallowReferenceSniff)
    - [P H P. Forbidden Classes Sniff](#PHP.ForbiddenClassesSniff)
    - [P H P. Optimized Functions Without Unpacking Sniff](#PHP.OptimizedFunctionsWithoutUnpackingSniff)
    - [P H P. Reference Spacing Sniff](#PHP.ReferenceSpacingSniff)
    - [P H P. Require Explicit Assertion Sniff](#PHP.RequireExplicitAssertionSniff)
    - [P H P. Require Nowdoc Sniff](#PHP.RequireNowdocSniff)
    - [P H P. Short List Sniff](#PHP.ShortListSniff)
    - [P H P. Type Cast Sniff](#PHP.TypeCastSniff)
    - [P H P. Useless Parentheses Sniff](#PHP.UselessParenthesesSniff)
    - [P H P. Useless Semicolon Sniff](#PHP.UselessSemicolonSniff)
- [Strings](#Strings)
    - [Strings. Disallow Variable Parsing Sniff](#Strings.DisallowVariableParsingSniff)
- [Type Hints](#TypeHints)
    - [Type Hints. Declare Strict Types Sniff](#TypeHints.DeclareStrictTypesSniff)
    - [Type Hints. Disallow Array Type Hint Syntax Sniff](#TypeHints.DisallowArrayTypeHintSyntaxSniff)
    - [Type Hints. Disallow Mixed Type Hint Sniff](#TypeHints.DisallowMixedTypeHintSniff)
    - [Type Hints. Long Type Hints Sniff](#TypeHints.LongTypeHintsSniff)
    - [Type Hints. Null Type Hint On Last Position Sniff](#TypeHints.NullTypeHintOnLastPositionSniff)
    - [Type Hints. Nullable Type For Null Default Value Sniff](#TypeHints.NullableTypeForNullDefaultValueSniff)
    - [Type Hints. Parameter Type Hint Spacing Sniff](#TypeHints.ParameterTypeHintSpacingSniff)
    - [Type Hints. Property Type Hint Sniff](#TypeHints.PropertyTypeHintSniff)
    - [Type Hints. Return Type Hint Sniff](#TypeHints.ReturnTypeHintSniff)
    - [Type Hints. Return Type Hint Spacing Sniff](#TypeHints.ReturnTypeHintSpacingSniff)
    - [Type Hints. Union Type Hint Format Sniff](#TypeHints.UnionTypeHintFormatSniff)
    - [Type Hints. Useless Constant Type Hint Sniff](#TypeHints.UselessConstantTypeHintSniff)
- [Variables](#Variables)
    - [Variables. Disallow Super Global Variable Sniff](#Variables.DisallowSuperGlobalVariableSniff)
    - [Variables. Disallow Variable Variable Sniff](#Variables.DisallowVariableVariableSniff)
    - [Variables. Duplicate Assignment To Variable Sniff](#Variables.DuplicateAssignmentToVariableSniff)
    - [Variables. Unused Variable Sniff](#Variables.UnusedVariableSniff)
    - [Variables. Useless Variable Sniff](#Variables.UselessVariableSniff)
- [Whitespaces](#Whitespaces)
    - [Whitespaces. Duplicate Spaces Sniff](#Whitespaces.DuplicateSpacesSniff)


<details id='Arrays'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Arrays</summary>
<hr>
<details id='Arrays.AlphabeticallySortedByKeysSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Alphabetically Sorted by Keys</summary>
Keyed multi-line arrays must be sorted alphabetically by their keys.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Keys are sorted alphabetically.</b></th>
  <th><b>Invalid: Keys are not sorted alphabetically.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = [
    'a' => 'value1',
    'b' => 'value2',
    'c' => 'value3',
];
```

</td>
<td>

```php
$arr = [
    'c' => 'value3',
    'a' => 'value1',
    'b' => 'value2',
];
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Associative array keys are sorted alphabetically, regardless of case.</b></th>
  <th><b>Invalid: Associative array keys are not sorted in a case-insensitive manner.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = [
    'Apple' => 'value1',
    'banana' => 'value2',
    'Cherry' => 'value3',
];
```

</td>
<td>

```php
$arr = [
    'banana' => 'value2',
    'Cherry' => 'value3',
    'Apple' => 'value1',
];
```

</td>
 </tr>
</table>
</details><details id='Arrays.ArrayAccessSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Array Access Spaces</summary>
There should be no space between the array variable and the array access operator, as well as no space between array access operators.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No space before or between array access brackets.</b></th>
  <th><b>Invalid: Space before the array access bracket.</b></th>
 </tr>
 <tr>
<td>

```php
$element = $array[0];
$element = $array[0][1];
```

</td>
<td>

```php
$element = $array [0];
$element = $array[0] [ 1];
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No space between nested array access brackets.</b></th>
  <th><b>Invalid: Space between nested array access brackets.</b></th>
 </tr>
 <tr>
<td>

```php
$element = $array[0][1];
```

</td>
<td>

```php
$element = $array[0] [ 1];
```

</td>
 </tr>
</table>
</details><details id='Arrays.DisallowImplicitArrayCreationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Implicit Array Creation</summary>
Implicit array creation is disallowed. All arrays must be explicitly defined.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Explicitly defined array.</b></th>
  <th><b>Invalid: Implicit array creation through assignment.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = ['key' => 'value',];
```

</td>
<td>

```php
$arr['key'] = 'value';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Explicitly created array inside a function.</b></th>
  <th><b>Invalid: Implicitly created array inside a function.</b></th>
 </tr>
 <tr>
<td>

```php
function example() { 
  $arr = ['key' => 'value',]; 
  return $arr; 
}
```

</td>
<td>

```php
function example() { 
  $arr['key'] = 'value'; 
  return $arr; 
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Explicit array creation with static keyword.</b></th>
  <th><b>Invalid: Implicit array creation with static keyword.</b></th>
 </tr>
 <tr>
<td>

```php
static $arr = ['key' => 'value',];
```

</td>
<td>

```php
static $arr['key'] = 'value';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Explicit array creation in a class property.</b></th>
  <th><b>Invalid: Implicit array creation as class property assignment.</b></th>
 </tr>
 <tr>
<td>

```php
class Example { 
  private $arr = ['key' => 'value',]; 
}
```

</td>
<td>

```php
class Example { 
  private $arr; 
  public function add() { 
    $this->arr['key'] = 'value'; 
  } 
}
```

</td>
 </tr>
</table>
</details><details id='Arrays.DisallowPartiallyKeyedSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Partially Keyed Arrays</summary>
Arrays must not be partially keyed. Either use all keys or no keys.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Fully keyed array.</b></th>
  <th><b>Invalid: Partially keyed array.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = ['foo' => 'bar', 'baz' => 'qux'];
```

</td>
<td>

```php
$arr = ['foo', 'bar' => 'baz', 'qux'];
```

</td>
 </tr>
<tr>
  <th><b>Valid: Fully unkeyed array.</b></th>
  <th><b>Invalid: Partially keyed array again.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = ['foo', 'bar', 'baz'];
```

</td>
<td>

```php
$arr = ['foo' => 'bar', 'baz', 'qux' => 'quux'];
```

</td>
 </tr>
</table>
</details><details id='Arrays.MultiLineArrayEndBracketPlacementSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Multi-Line Array End Bracket Placement</summary>
For multi-line arrays, the end bracket must be placed correctly in relation to the nested array's start and end positioning. 
If a nested array is present, the closing bracket of the parent array must be on the same line as the closing bracket of the nested array 
or the nested array's start must be on its own line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: End bracket of parent array is on the same line as nested array's end.</b></th>
  <th><b>Invalid: Nested array's end bracket does not align with parent's end bracket and the nested array start is not on its own line.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = [
    'foo' => 'bar',
    'nested' => [<em>1, 2, 3</em>],
];
```

</td>
<td>

```php
$arr = [
    'foo' => 'bar',
    'nested' => [<em>
        1, 2, 3
    </em>]
];
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Nested array's start is on its own line, making it acceptable for the end brackets to not align.</b></th>
  <th><b>Invalid: End bracket of nested array wrongly placed when considering parent's end bracket alignment without its start on a new line.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = [
    'foo' => 'bar',
    'nested' => 
    [<em>
        1, 2, 3
    </em>],
];
```

</td>
<td>

```php
$arr = [
    'foo' => 'bar',
    'nested' => [1, 2, 3<em>
    </em>],
];
```

</td>
 </tr>
</table>
</details><details id='Arrays.SingleLineArrayWhitespaceSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Single Line Array Whitespace</summary>
Enforces whitespace conventions for single line arrays.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No spaces inside empty array.</b></th>
  <th><b>Invalid: Spaces inside empty array.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = []; // Valid: No spaces inside empty array.
```

</td>
<td>

```php
$arr = [ ]; // Invalid: Spaces inside empty array.
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct space after opening bracket and before closing bracket.</b></th>
  <th><b>Invalid: Incorrect space after opening bracket or before closing bracket.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = ['foo', 'bar']; // Valid: Correct space after opening bracket and before closing bracket.
```

</td>
<td>

```php
$arr = [ 'foo', 'bar' ]; // Invalid: Incorrect space after opening bracket or before closing bracket.
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No space before comma, and one space after comma.</b></th>
  <th><b>Invalid: Space before comma or incorrect space after comma.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = ['foo', 'bar']; // Valid: No space before comma, and one space after comma.
```

</td>
<td>

```php
$arr = ['foo' ,'bar']; // Invalid: Space before comma or incorrect space after comma.
```

</td>
 </tr>
</table>
</details><details id='Arrays.TrailingArrayCommaSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Trailing Array Comma</summary>
Multi-line arrays must have a trailing comma after the last element.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Multi-line array with a trailing comma.</b></th>
  <th><b>Invalid: Multi-line array without a trailing comma.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = [
    'foo' => 'bar',
    ]
;
```

</td>
<td>

```php
$arr = [
    'foo' => 'bar'
    ]
;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Multi-line array with a trailing comma after HEREDOC/NOWDOC.</b></th>
  <th><b>Invalid: Multi-line array without a trailing comma after HEREDOC/NOWDOC.</b></th>
 </tr>
 <tr>
<td>

```php
$arr = [
    <<<EOD
Example of a string
spanning multiple lines
using heredoc syntax.
EOD
,
    ]
;
```

</td>
<td>

```php
$arr = [
    <<<EOD
Example of a string
spanning multiple lines
using heredoc syntax.
EOD
    ]
;
```

</td>
 </tr>
</table>
</details>
</details><details id='Attributes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Attributes</summary>
<hr>

<details id='Attributes.AttributeAndTargetSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Attribute and Target Spacing</summary>
This rule checks for the correct number of blank lines between an attribute and its target based on the configured `linesCount`. If `allowOnSameLine` is set to true, an attribute and its target may be on the same line; otherwise, a specific amount of blank lines as defined by `linesCount` is required.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct number of blank lines between attribute and target.</b></th>
  <th><b>Invalid: Incorrect number of blank lines between attribute and target.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
#[ExampleAttribute]

class ExampleClass
{
}
```

</td>
<td>

```php
<?php
#[ExampleAttribute]
// No blank line follows
class ExampleClass
{
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Attribute and target on the same line (when allowOnSameLine is true).</b></th>
  <th><b>Invalid: Attribute and target on the same line (when allowOnSameLine is false).</b></th>
 </tr>
 <tr>
<td>

```php
<?php
#[ExampleAttribute] class ExampleClass
{
}
```

</td>
<td>

```php
<?php
#[ExampleAttribute] class ExampleClass
{
}
```

</td>
 </tr>
</table>
</details>
<details id='Attributes.AttributesOrderSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Attributes Order</summary>
Attributes must be ordered based on the configuration provided either manually or alphabetically.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Attributes ordered alphabetically.</b></th>
  <th><b>Invalid: Attributes not ordered alphabetically.</b></th>
 </tr>
 <tr>
<td>

```php
#[A]
#[B]
class Example {}
```

</td>
<td>

```php
#[B]
#[A]
class Example {}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Attributes ordered manually as ['A', 'B'].</b></th>
  <th><b>Invalid: Attributes not following the manual order ['A', 'B'].</b></th>
 </tr>
 <tr>
<td>

```php
#[A]
#[B]
class Example {}
```

</td>
<td>

```php
#[B]
#[A]
class Example {}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Attributes on the same line and ordered alphabetically.</b></th>
  <th><b>Invalid: Attributes on the same line but not ordered alphabetically.</b></th>
 </tr>
 <tr>
<td>

```php
#[A] #[B] class Example {}
```

</td>
<td>

```php
#[B] #[A] class Example {}
```

</td>
 </tr>
</table>
</details><details id='Attributes.DisallowAttributesJoiningSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Attributes Joining</summary>
Individual attributes must not be joined. Each attribute must be declared separately.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Attributes declared separately.</b></th>
  <th><b>Invalid: Attributes joined together.</b></th>
 </tr>
 <tr>
<td>

```php
#[
    AttributeOne,
    AttributeTwo
]
class Example {
}
```

</td>
<td>

```php
#[
    AttributeOne, AttributeTwo
]
class Example {
}
```

</td>
 </tr>
</table>
</details>
<details id='Attributes.DisallowMultipleAttributesPerLineSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Multiple Attributes Per Line</summary>
Each attribute must be declared on its own line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single attribute per line.</b></th>
  <th><b>Invalid: Multiple attributes on the same line.</b></th>
 </tr>
 <tr>
<td>

```php
#[Attribute]
private $property;

#[AnotherAttribute]
private $anotherProperty;
```

</td>
<td>

```php
#[Attribute] #[AnotherAttribute]
private $property;
```

</td>
 </tr>
</table>
</details>
<details id='Attributes.RequireAttributeAfterDocCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Attribute After Doc Comment</summary>
Attributes must be placed after the documentation comment.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Attribute after the documentation comment.</b></th>
  <th><b>Invalid: Attribute before the documentation comment.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Some description here.
 */
#[SomeAttribute]
public function someMethod() {}
```

</td>
<td>

```php
#[SomeAttribute]
/**
 * Some description here.
 */
public function someMethod() {}
```

</td>
 </tr>
</table>
</details>
</details><details id='Classes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Classes</summary>
<hr>
<details id='Classes.AbstractMethodSignature'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Method Signature Spacing</summary>
Ensure there is consistent spacing in method signatures: one space after the method name and before the opening parenthesis, and no spaces around parentheses enclosing parameters.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Proper spacing around method signature.</b></th>
  <th><b>Invalid: Incorrect spacing around method signature.</b></th>
 </tr>
 <tr>
<td>

```php
class Example
{
    public function foo($arg1, $arg2)
    {
        // method body
    }
}
```

</td>
<td>

```php
class Example
{
    public function foo( $arg1 , $arg2 )
    {
        // method body
    }
}
```

</td>
 </tr>
<tr>
  <th><b>Valid: Proper spacing with type declarations.</b></th>
  <th><b>Invalid: Incorrect spacing with type declarations.</b></th>
 </tr>
 <tr>
<td>

```php
class Example
{
    public function bar(int $arg1, string $arg2): void
    {
        // method body
    }
}
```

</td>
<td>

```php
class Example
{
    public function bar ( int $arg1 , string $arg2 ) : void
    {
        // method body
    }
}
```

</td>
 </tr>
</table>
</details><details id='Classes.AbstractPropertyConstantAndEnumCaseSpacing'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Property, Constant, and Enum Case Spacing</summary>
Proper spacing before class properties, constants, and enum cases is required to maintain readability.
The spacing varies depending on whether the member is preceded by a comment.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing with comment.</b></th>
  <th><b>Invalid: Incorrect spacing with comment.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    /**
     * Description for const.
     */
    const FOO = 'bar';

    /**
     * Description for property.
     */
    private $value;
}
```

</td>
<td>

```php
class Example {
    /**
     * Description for const.
     */
    const FOO = 'bar';
    /**
     * Description for property.
     */
    private $value;
}
```

</td>
 </tr>
 <tr>
   <th><b>Valid: Correct spacing without comment.</b></th>
   <th><b>Invalid: Incorrect spacing without comment.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    public $propertyA;

    public static $propertyB;
}
```

</td>
<td>

```php
class Example {
    public $propertyA;
    public static $propertyB;
}
```

</td>
 </tr>
  <tr>
   <th><b>Valid: Minimum and maximum lines before member with comments are respected.</b></th>
   <th><b>Invalid: Not adhering to min/max lines before member with comments.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    /**
     * The following must have space due to comment.
     */
    private int $withComment = 1;

    /**
     * Another member with proper spacing.
     */
    private static $anotherWithComment;
}
```

</td>
<td>

```php
class Example {
    /**
     * Needs appropriate spacing defined by rules.
     */
    private int $withComment = 1;
    /**
     * This does not follow the spacing rules.
     */
    private static $anotherWithComment;
}
```

</td>
 </tr>
  <tr>
   <th><b>Valid: Minimum and maximum lines before member without comments are respected.</b></th>
   <th><b>Invalid: Not adhering to min/max lines before member without comments.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    public $first;

    protected static $second;
}
```

</td>
<td>

```php
class Example {
    public $first;
    protected static $second;
}
```

</td>
 </tr>
</table>

The sniff enforces spacing rules between class members to enhance readability. Members must be separated by 
one or more lines if preceded by a comment, and strictly one line otherwise, but these values are configurable.
Ensuring consistent spacing helps in maintaining a neat and understandable code structure.
</details><details id='Classes.BackedEnumTypeSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Backed Enum Type Spacing</summary>
Proper spacing is required for backed enums. There must be a specific number of spaces before the colon that separates the enum name from its type, and before the type itself.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spaces before colon and type, based on configuration.</b></th>
  <th><b>Invalid: Incorrect spaces before colon and/or type.</b></th>
 </tr>
 <tr>
<td>

```php
enum Suit: string {
    case Hearts = 'H';
} // Assume spacesCountBeforeColon = 0 and spacesCountBeforeType = 1
```

</td>
<td>

```php
enum Suit : string {
    case Hearts = 'H';
} // Incorrect spaces found or spaces not matching the required configuration
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No space before colon, single space before type.</b></th>
  <th><b>Invalid: Space before colon, no space before type.</b></th>
 </tr>
 <tr>
<td>

```php
enum Suit: string {
    case Hearts = 'H';
} // Assume spacesCountBeforeColon = 0 and spacesCountBeforeType = 1
```

</td>
<td>

```php
enum Suit :string {
    case Hearts = 'H';
} // Spaces do not match required configuration
```

</td>
 </tr>
</table>
</details><details id='Classes.ClassConstantVisibilitySniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Constant Visibility</summary>
Class constants must have visibility declared.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Visibility declared for the class constant.</b></th>
  <th><b>Invalid: Visibility missing for the class constant.</b></th>
 </tr>
 <tr>
<td>

```php
class MyClass {
    public const FOO = 'value';
}
```

</td>
<td>

```php
class MyClass {
    const FOO = 'value';
}
```

</td>
 </tr>
</table>
</details><details id='Classes.ClassLengthSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Length</summary>
Classes must not exceed a specific number of lines.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Class within the allowed line length.</b></th>
  <th><b>Invalid: Class exceeding the allowed line length.</b></th>
 </tr>
 <tr>
<td>

```php
class ShortClass {
    protected $name;

    public function getName() {
        return $this->name;
    }
}
```

</td>
<td>

```php
class LongClass {
    protected $name;
    protected $age;
    protected $email;
    protected $address;
    protected $phoneNumber;
    protected $dateOfBirth;
    protected $registrationDate;
    protected $lastLoginDate;
    protected $roles;
    // Imagine more properties and methods ...

    public function getName() {
        return $this->name;
    }
    // Imagine more getters and setters ...
}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.ClassMemberSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Member Spacing</summary>
There must be a specified number of blank lines between class members.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct number of blank lines between members.</b></th>
  <th><b>Invalid: Incorrect number of blank lines between members.</b></th>
 </tr>
 <tr>
<td>

```php
<?php

class Example
{
    public $property1;
    
    public function method1()
    {
    }
    
    protected $property2;
    
    private function method2()
    {
    }
}

?>
```

</td>
<td>

```php
<?php

class Example
{
    public $property1;
    public function method1()
    {
    }
    protected $property2;
    private function method2()
    {
    }
}

?>
```

</td>
 </tr>
</table>

To maintain readability and a clean structure within class definitions, it is important to follow a standard for spacing between class members. This includes properties, methods, constants, etc. The PHP CodeSniffer rule checks whether the specified number of blank lines exists between each class member and reports deviations from this standard.

You can automatically fix violations of this rule by running PHP CodeSniffer with the autofix option, which will adjust the number of blank lines between class members to meet the expected standard.
</details>
<details id='Classes.ClassStructureSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Structure Order</summary>
The structure within a class must follow a specific order. The order is determined by groups such as constants, properties, and methods (including special methods like constructors). Each group has further subdivisions based on visibility (public, protected, private) and other attributes (static, abstract, final).

<table style="width: 100%">
 <tr>
  <th><b>Valid: Properly ordered class elements.</b></th>
  <th><b>Invalid: Incorrectly ordered class elements.</b></th>
 </tr>
 <tr>
<td>

```php
class SampleClass
{
    use SomeTrait;

    public const VERSION = '1.0';
    protected const FEATURE_ENABLED = false;

    public static $instanceCount = 0;

    public $id;
    protected $name;

    public function __construct($id, $name)
    {
        $this->id = $id;
        $this->name = $name;
    }

    public static function getInstanceCount(): int
    {
        return self::$instanceCount;
    }

    protected function getName(): string
    {
        return $this->name;
    }
}
```

</td>
<td>

```php
class SampleClass
{
    use SomeTrait;

    public $id;
    public const VERSION = '1.0'; // Constants should come before properties.

    protected $name;
    protected const FEATURE_ENABLED = false; // Ordering violation.

    public static function getInstanceCount(): int
    {
        return self::$instanceCount;
    }

    public static $instanceCount = 0; // Static properties should be defined before instance properties.

    public function __construct($id, $name)
    {
        $this->id = $id;
        $this->name = $name;
    }

    protected function getName(): string
    {
        return $this->name;
    }
}
```

</td>
 </tr>
</table>
</details><details id='Classes.ConstantSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Constant Spacing</summary>
Constants must be followed by a configurable number of blank lines.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct number of blank lines after constant.</b></th>
  <th><b>Invalid: Incorrect number of blank lines after constant.</b></th>
 </tr>
 <tr>
<td>

```php
const EXAMPLE = 'value';

// Correct number of blank lines follows

public function exampleMethod() {}
```

</td>
<td>

```php
const EXAMPLE = 'value';
// Incorrect number of blank lines follows
public function exampleMethod() {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct number of blank lines after multiple constants.</b></th>
  <th><b>Invalid: Incorrect number of blank lines after multiple constants.</b></th>
 </tr>
<tr>
<td>

```php
const FIRST = 1;

const SECOND = 2;

public function exampleMethod() {}
```

</td>
<td>

```php
const FIRST = 1;
const SECOND = 2;
// Incorrect number of blank lines follows
public function exampleMethod() {}
```

</td>
</tr>
</table>
</details><details id='Classes.DisallowConstructorPropertyPromotionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Constructor Property Promotion</summary>
Constructor property promotion must not be used in classes.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Regular constructor without property promotion.</b></th>
  <th><b>Invalid: Constructor with property promotion.</b></th>
 </tr>
 <tr>
<td>

```php
public function __construct($property) {
    $this->property = $property;
}
```

</td>
<td>

```php
public function __construct(public $property) {
}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.DisallowLateStaticBindingForConstantsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Late Static Binding for Constants</summary>
Using late static binding for constants is disallowed. Instead, 'self::' should be used.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using 'self::' to access constants.</b></th>
  <th><b>Invalid: Using 'static::' to access constants.</b></th>
 </tr>
 <tr>
<td>

```php
$value = self::CONSTANT;
```

</td>
<td>

```php
$value = static::CONSTANT;
```

</td>
 </tr>
</table>
</details>
<details id='Classes.DisallowMultiConstantDefinitionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Multi Constant Definition</summary>
Defining multiple constants in a single statement is disallowed. Each constant must be declared in its own statement.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single constant declaration.</b></th>
  <th><b>Invalid: Multiple constants declared in a single statement.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
class Foo
{
    public const BAR = 'bar';
    private const BAZ = 'baz';
}
```

</td>
<td>

```php
<?php
class Foo
{
    public const BAR = 'bar',
                 BAZ = 'baz';
}
```

</td>
 </tr>
</table>
</details><details id='Classes.DisallowMultiPropertyDefinitionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Multi Property Definition</summary>
Each property must be declared in its own statement.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Each property is declared in its own statement.</b></th>
  <th><b>Invalid: Multiple properties are declared in a single statement.</b></th>
 </tr>
 <tr>
<td>

```php
private $firstProperty;

private $secondProperty;
```

</td>
<td>

```php
private $firstProperty, $secondProperty;
```

</td>
 </tr>
</table>
</details><details id='Classes.DisallowStringExpressionPropertyFetchSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow String Expression Property Fetch</summary>
String expression property fetch is disallowed, use identifier property fetch instead. This means accessing object properties should be done using identifier directly instead of a string that gets evaluated.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Identifier property fetch.</b></th>
  <th><b>Invalid: String expression property fetch.</b></th>
 </tr>
 <tr>
<td>

```php
$object->propertyName;
```

</td>
<td>

```php
$object->{'propertyName'};
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using a direct property name.</b></th>
  <th><b>Invalid: Property name as a string expression.</b></th>
 </tr>
 <tr>
<td>

```php
$user->name;
```

</td>
<td>

```php
$user->{'name'};
```

</td>
 </tr>
</table>
</details><details id='Classes.EmptyLinesAroundClassBracesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Empty Lines Around Class Braces</summary>
There must be exactly the specified number of empty lines around class braces.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct number of empty lines after opening brace.</b></th>
  <th><b>Invalid: No empty line after opening brace.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    
public function foo() {}
}
```

</td>
<td>

```php
class Example {
public function foo() {}
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct number of empty lines before closing brace.</b></th>
  <th><b>Invalid: No empty line before closing brace.</b></th>
 </tr>
<tr>
<td>

```php
class Example {
    public function foo() {}

}
```

</td>
<td>

```php
class Example {
    public function foo() {}
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: One empty line after opening brace and before closing brace, as configured.</b></th>
  <th><b>Invalid: Multiple empty lines after opening brace and before closing brace.</b></th>
 </tr>
<tr>
<td>

```php
class Example {
    
    public function foo() {}

}
```

</td>
<td>

```php
class Example {
    

    public function foo() {}

    
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Configured number of empty lines after opening brace.</b></th>
  <th><b>Invalid: Incorrect empty lines after opening brace according to configuration.</b></th>
 </tr>
<tr>
<td>

```php
class CustomSpacingExample {
    
    // Two empty lines after opening brace if configured as such
    
    public function bar() {}
}
```

</td>
<td>

```php
class CustomSpacingExample {
    
    public function bar() {}
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Configured number of empty lines before closing brace.</b></th>
  <th><b>Invalid: Incorrect empty lines before closing brace according to configuration.</b></th>
 </tr>
<tr>
<td>

```php
class CustomSpacingExample {
    public function bar() {}
    
    // Two empty lines before closing brace if configured as such
    

}
```

</td>
<td>

```php
class CustomSpacingExample {
    public function bar() {}
}
```

</td>
 </tr>
</table>
</details><details id='Classes.EnumCaseSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Enum Case Spacing</summary>
Proper spacing must be maintained after enum cases. Variable number of blank lines may be configured, but a consistent style is enforced.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct number of blank lines after enum case.</b></th>
  <th><b>Invalid: Incorrect number of blank lines after enum case.</b></th>
 </tr>
 <tr>
<td>

```php
enum Suit {
    case Hearts;
    
    case Diamonds;
    
    case Clubs;
    
    case Spades;
}
```

</td>
<td>

```php
enum Suit {
    case Hearts;
    
    case Diamonds;
    
    case Clubs;
    
    case Spades;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: 1 blank line after enum case if configured as such.</b></th>
  <th><b>Invalid: No blank lines or more than configured after enum case.</b></th>
 </tr>
 <tr>
<td>

```php
enum Status {
    case Pending;
    
    case Confirmed;
    
    case Cancelled;
}
```

</td>
<td>

```php
enum Status {
    case Pending;
    
    case Confirmed;
    case Cancelled;
}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.ForbiddenPublicPropertySniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Forbidden Public Property</summary>
Using public properties in classes is forbidden. Use method access instead.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Public property usage.</b></th>
  <th><b>Valid: Private property with method access.</b></th>
 </tr>
 <tr>
<td>

```php
class MyClass {
    public $property = 'value';
}
```

</td>
<td>

```php
class MyClass {
    private $property = 'value';

    public function getProperty() {
        return $this->property;
    }

    public function setProperty($value) {
        $this->property = $value;
    }
}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.MethodSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Method Spacing</summary>
There must be a specific number of blank lines between method declarations within a class. This can be adjusted by setting the minimum and maximum number of allowed blank lines.

<table style="width: 100%">
 <tr>
  <th><b>Valid: The correct number of blank lines between methods.</b></th>
  <th><b>Invalid: Too many/few blank lines between methods.</b></th>
 </tr>
 <tr>
<td>

```php
class Example
{
    public function firstMethod()
    {
    }
    
    // 1 blank line
    
    public function secondMethod()
    {
    }
}
```

</td>
<td>

```php
class Example
{
    public function firstMethod()
    {
    }
    
    
    // 2 blank lines
    
    
    public function secondMethod()
    {
    }
}
```

</td>
 </tr>
</table>
<table style="width: 100%">
 <tr>
  <th><b>Valid: Methods with the maximum allowed blank lines.</b></th>
  <th><b>Invalid: Methods with more than the maximum allowed blank lines.</b></th>
 </tr>
 <tr>
<td>

```php
class Example
{
    public function firstMethod()
    {
    }
    
    // Maximum allowed blank lines
    
    public function secondMethod()
    {
    }
}
```

</td>
<td>

```php
class Example
{
    public function firstMethod()
    {
    }
    
    
    
    
    // More than the maximum allowed blank lines
    
    
    
    public function secondMethod()
    {
    }
}
```

</td>
 </tr>
</table>
</details><details id='Classes.MissingClassGroupsException'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Proper Class Grouping Documentation</summary>
All custom exception classes must properly document missing class groups in configuration through a descriptive exception message.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exception class properly documents missing class groups.</b></th>
  <th><b>Invalid: Exception class lacks descriptive message for missing class groups.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace SlevomatCodingStandard\Sniffs\Classes;

use Exception;

class MissingClassGroupsException extends Exception
{
    /** @param list<string> $groups */
    public function __construct(array $groups)
    {
        parent::__construct(
            sprintf(
                'You need to configure all class groups. These groups are missing from your configuration: %s.',
                implode(', ', $groups)
            )
        );
    }
}
?>
```

</td>
<td>

```php
<?php
namespace SlevomatCodingStandard\Sniffs\Classes;

use Exception;

class MissingClassGroupsException extends Exception
{
    public function __construct(array $groups)
    {
        parent::__construct('Missing class groups.');
    }
}
?>
```

</td>
 </tr>
</table>
</details><details id='Classes.ModernClassNameReferenceSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Modern Class Name Reference</summary>
Instead of using magic constants or functions like get_class(), get_parent_class(), or get_called_class(), directly use the ::class syntax for cleaner and more straightforward class name references.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using ::class for the current class.</b></th>
  <th><b>Invalid: Using magic constant for the current class.</b></th>
 </tr>
 <tr>
<td>

```php
$className = self::class;
```

</td>
<td>

```php
$className = __CLASS__;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using ::class for parent class reference.</b></th>
  <th><b>Invalid: Using get_parent_class() with 'this'.</b></th>
 </tr>
 <tr>
<td>

```php
$parentClassName = parent::class;
```

</td>
<td>

```php
$parentClassName = get_parent_class($this);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using ::class with dynamic class reference.</b></th>
  <th><b>Invalid: Using get_class() with an object.</b></th>
 </tr>
 <tr>
<td>

```php
$className = $object::class;
```

</td>
<td>

```php
$className = get_class($object);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using static::class for late static binding.</b></th>
  <th><b>Invalid: Using get_called_class() for late static binding.</b></th>
 </tr>
 <tr>
<td>

```php
$className = static::class;
```

</td>
<td>

```php
$className = get_called_class();
```

</td>
 </tr>
</table>
</details><details id='Classes.ParentCallSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Parent Call Spacing</summary>
Correct spacing around a parent:: call is enforced. 
This includes spacing before and after the call, 
as given by the rules of linesCountBefore, linesCountBeforeFirst, linesCountAfter, and linesCountAfterLast properties.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing around parent:: call.</b></th>
  <th><b>Invalid: Incorrect spacing before parent:: call.</b></th>
 </tr>
 <tr>
<td>

```php
class Example extends ParentClass {
    public function exampleMethod() {
        <em>parent::exampleMethod();</em>
    }
}
```

</td>
<td>

```php
class Example extends ParentClass {
    public function exampleMethod()
    {
<em>
        parent::exampleMethod();</em>
    }
}
```

</td>
 </tr>
<tr>
 <th><b>Valid: Custom defined lines before the first parent:: call meet requirements.</b></th>
 <th><b>Invalid: Missing required new lines before the first parent:: call.</b></th>
</tr>
<tr>
<td>

```php
class Example extends ParentClass {
    public function exampleMethod() {
<em>        parent::exampleMethod();</em>
    }
}
```

</td>
<td>

```php
class Example extends ParentClass {
    public function exampleMethod() {<em>
        parent::exampleMethod();</em>
    }
}
```

</td>
</tr>

<tr>
 <th><b>Valid: Correct spacing after parent:: call matches linesCountAfter setting.</b></th>
 <th><b>Invalid: Incorrect spacing after parent:: call.</b></th>
</tr>
<tr>
<td>

```php
class Example extends ParentClass {
    public function exampleMethod() {
        <em>parent::exampleMethod();</em>
    }
}
```

</td>
<td>

```php
class Example extends ParentClass {
    public function exampleMethod() {
        <em>parent::exampleMethod();
</em>    }
}
```

</td>
</tr>
</table>
</details><details id='Classes.RequireAbstractOrFinalSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Abstract or Final Class Declaration</summary>
All classes should be declared using either the "abstract" or "final" keyword to enforce a clear object inheritance policy. This ensures classes are designed with inheritance in mind or explicitly marked as final to prevent inheritance.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Abstract class declaration.</b></th>
  <th><b>Invalid: Class missing 'abstract' or 'final' keyword.</b></th>
 </tr>
 <tr>
<td>

```php
abstract class MyAbstractClass {
    // Class definition
}
```

</td>
<td>

```php
class MyClass {
    // Class definition
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Final class declaration.</b></th>
  <th><b>Invalid: Class missing 'abstract' or 'final' keyword.</b></th>
 </tr>
 <tr>
<td>

```php
final class MyFinalClass {
    // Class definition
}
```

</td>
<td>

```php
class MyClass {
    // Class definition
}
```

</td>
 </tr>
</table>
</details><details id='Classes.RequireConstructorPropertyPromotionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Required Constructor Property Promotion</summary>
Constructor properties must be promoted when conditions are met (PHP 8.0+).

<table style="width: 100%">
 <tr>
  <th><b>Valid: Property promotion used.</b></th>
  <th><b>Invalid: Property promotion not used where applicable.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    public function __construct(
        private string $property
    ) {}
}
```

</td>
<td>

```php
class Example {
    private string $property;
    
    public function __construct(
        string $property
    ) {
        $this->property = $property;
    }
}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.RequireMultiLineMethodSignatureSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Multi-Line Method Signature</summary>
Method signatures must be split into multiple lines when they exceed a certain length or parameter count, ensuring each parameter is on its own line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Method signature with each parameter on its own line.</b></th>
  <th><b>Invalid: Method signature on a single line.</b></th>
 </tr>
 <tr>
<td>

```php
class ExampleClass 
{
    public function exampleMethod(
        string $firstParameter, 
        int $secondParameter, 
        bool $thirdParameter
    ) : void {
        // Method body
    }
}
```

</td>
<td>

```php
class ExampleClass 
{
    public function exampleMethod(string $firstParameter, int $secondParameter, bool $thirdParameter) : void {
        // Method body
    }
}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.RequireSelfReferenceSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Self Reference</summary>
When referencing the current class, 'self' should be used instead of the class name.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Use 'self' for local class reference.</b></th>
  <th><b>Invalid: Using the class name for local reference.</b></th>
 </tr>
 <tr>
<td>

```php
class ExampleClass {
    public function exampleMethod() {
        return self::class;
    }
}
```

</td>
<td>

```php
class ExampleClass {
    public function exampleMethod() {
        return ExampleClass::class;
    }
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Use 'self' for local static method call.</b></th>
  <th><b>Invalid: Using the class name for local static method call.</b></th>
 </tr>
 <tr>
<td>

```php
class AnotherExample {
    public static function doSomething() {
        // doing something
    }

    public static function execute() {
        self::doSomething();
    }
}
```

</td>
<td>

```php
class AnotherExample {
    public static function doSomething() {
        // doing something
    }

    public static function execute() {
        AnotherExample::doSomething();
    }
}
```

</td>
 </tr>
</table>
</details><details id='Classes.RequireSingleLineMethodSignatureSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Single Line Method Signature</summary>
The signature of a method must be placed on a single line if it does not exceed the configured maximum line length. This promotes better readability and consistency across the codebase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Method signature is within one line and under the maximum line length.</b></th>
  <th><b>Invalid: Method signature spans multiple lines.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    public function aVeryLongMethodName($parameter1, $parameter2) {}
}
```

</td>
<td>

```php
class Example {
    public function aVeryLongMethodName(
        $parameter1, 
        $parameter2
    ) {}
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Method signature with multiple parameters is within one line and under the maximum line length.</b></th>
  <th><b>Invalid: Method signature with multiple parameters spans multiple lines.</b></th>
</tr>
<tr>
<td>

```php
class Example {
    public function short($param1, $param2, $param3) {}
}
```

</td>
<td>

```php
class Example {
    public function short(
        $param1, 
        $param2, 
        $param3
    ) {}
}
```

</td>
 </tr>
</table>
</details><details id='Classes.SuperfluousAbstractClassNamingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Superfluous Abstract Class Naming</summary>
Abstract classes must not have a prefix or suffix of "abstract" in their names. The presence of "abstract" in the class name is considered superfluous since the class is already declared as abstract.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Abstract class without 'Abstract' prefix or suffix.</b></th>
  <th><b>Invalid: Abstract class with 'Abstract' prefix.</b></th>
 </tr>
 <tr>
<td>

```php
class ExampleClass extends AbstractSomething
{
    // class body
}
```

</td>
<td>

```php
abstract class AbstractExampleClass
{
    // class body
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Abstract class named appropriately.</b></th>
  <th><b>Invalid: Abstract class with 'Abstract' suffix.</b></th>
 </tr>
 <tr>
<td>

```php
abstract class Car implements VehicleInterface
{
    // class body
}
```

</td>
<td>

```php
abstract class CarAbstract
{
    // class body
}
```

</td>
 </tr>
</table>
</details><details id='Classes.SuperfluousErrorNamingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Superfluous Error Naming</summary>
Class names ending with the suffix "Error" are considered superfluous unless the class name is exactly "Error".

<table style="width: 100%">
 <tr>
  <th><b>Valid: Class name without the 'Error' suffix.</b></th>
  <th><b>Invalid: Class name with the 'Error' suffix.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
class MyCustomException {
}
```

</td>
<td>

```php
<?php
class MyCustomErrorException {
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Abstract class name without the 'Error' suffix.</b></th>
  <th><b>Invalid: Abstract class name with the 'Error' suffix.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
abstract class AbstractException {
}
```

</td>
<td>

```php
<?php
abstract class AbstractErrorException {
}
```

</td>
</tr>
 <tr>
  <th><b>Valid: The exact class name 'Error'.</b></th>
  <th><b>Invalid: Any class name with 'Error' as a suffix, except 'Error'.</b></th>
 </tr>
<tr>
<td>

```php
<?php
class Error {
}
```

</td>
<td>

```php
<?php
class DatabaseError {
}
```

</td>
</tr>
</table>
</details><details id='Classes.SuperfluousExceptionNamingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Superfluous Exception Naming</summary>
Exception class names should not have a superfluous "Exception" suffix.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exception class without a superfluous 'Exception' suffix.</b></th>
  <th><b>Invalid: Exception class with a superfluous 'Exception' suffix.</b></th>
 </tr>
 <tr>
<td>

```php
class UserNotFound {
}
```

</td>
<td>

```php
class UserNotFoundException<em>Exception</em> {
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Abstract class without a superfluous 'Exception' suffix.</b></th>
  <th><b>Invalid: Abstract class with a superfluous 'Exception' suffix.</b></th>
 </tr>
 <tr>
<td>

```php
abstract class NotFound {
}
```

</td>
<td>

```php
abstract class NotFoundException<em>Exception</em> {
}
```

</td>
 </tr>
</table>
</details><details id='Classes.SuperfluousInterfaceNamingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Superfluous Interface Naming</summary>
Interface names must not have a prefix or suffix of 'interface'.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Interface name without 'interface' prefix or suffix.</b></th>
  <th><b>Invalid: Interface name with 'Interface' prefix.</b></th>
 </tr>
 <tr>
<td>

```php
interface User {}
```

</td>
<td>

```php
interface InterfaceUser {}
```

</td>
 </tr>
<tr>
  <th><b>Valid: Interface name without 'interface' prefix or suffix.</b></th>
  <th><b>Invalid: Interface name with 'Interface' suffix.</b></th>
 </tr>
 <tr>
<td>

```php
interface Authorization {}
```

</td>
<td>

```php
interface AuthorizationInterface {}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.SuperfluousTraitNamingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Superfluous Trait Naming</summary>
Superfluous suffix "Trait" in the trait names must be avoided. It should be clear from the namespace or context that the class is a trait without needing a suffix.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Trait name without superfluous suffix.</b></th>
  <th><b>Invalid: Trait name with superfluous 'Trait' suffix.</b></th>
 </tr>
 <tr>
<td>

```php
namespace ExampleNamespace\Traits;

trait Example
{
    // Trait content
}
```

</td>
<td>

```php
namespace ExampleNamespace\Traits;

trait ExampleTrait
{
    // Trait content
}
```

</td>
 </tr>
</table>
</details>
<details id='Classes.TraitUseDeclarationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Trait Use Declaration</summary>
Only one trait should be used per declaration. Multiple traits per use statement are forbidden.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single trait per use statement.</b></th>
  <th><b>Invalid: Multiple traits per use statement.</b></th>
 </tr>
 <tr>
<td>

```php
use TraitName1;

use TraitName2;
```

</td>
<td>

```php
use TraitName1, TraitName2;
```

</td>
 </tr>
</table>
</details><details id='Classes.TraitUseSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Trait Use Spacing</summary>
This rule specifies the required number of blank lines before the first use statement, between use statements, and after the last use statement in a class, trait, or enum. 
The configuration properties are:
- linesCountBeforeFirstUse: Number of blank lines before the first use statement.
- linesCountBeforeFirstUseWhenFirstInClass: Number of blank lines before the first use statement if it's the first element inside a class/trait/enum.
- linesCountBetweenUses: Number of blank lines between use statements.
- linesCountAfterLastUse: Number of blank lines after the last use statement.
- linesCountAfterLastUseWhenLastInClass: Number of blank lines after the last use statement if it's the last element inside a class/trait/enum.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct lines before first use, between uses, and after last use</b></th>
  <th><b>Invalid: Incorrect number of lines before, between, and after use statements</b></th>
 </tr>
 <tr>
<td>

```php
<?php
class Example {
    use FirstTrait;

    use SecondTrait;
    use ThirdTrait;

}
```

</td>
<td>

```php
<?php
class Example {
    use FirstTrait;
    use SecondTrait;
    use ThirdTrait;

}
```

</td>
 </tr>
  <tr>
  <th><b>Valid: Custom lines setting applied correctly</b></th>
  <th><b>Invalid: Not adhering to custom lines settings</b></th>
 </tr>
<tr>
<td>

```php
<?php
class Example {
    use FirstTrait;

    use SecondTrait;

    use ThirdTrait;
}
```

</td>
<td>

```php
<?php
class Example {
    use FirstTrait;
    use SecondTrait;
    use ThirdTrait;

}
```

</td>
 </tr>
  <tr>
  <th><b>Valid: Correct lines when use is the first in class with custom setting</b></th>
  <th><b>Invalid: Incorrect lines when use is the first in class even with a custom setting</b></th>
 </tr>
<tr>
<td>

```php
<?php
class Example {

    use FirstTrait;
    use SecondTrait;

    use ThirdTrait;
}
```

</td>
<td>

```php
<?php
class Example {
    use FirstTrait;
    use SecondTrait;
    use ThirdTrait;

}
```

</td>
 </tr>
</table>
</details><details id='Classes.UnsupportedClassGroupException'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unsupported Class Group Exception</summary>
Exceptions must be thrown for unsupported class groups with a clear message.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Throwing an exception for an unsupported class group.</b></th>
  <th><b>Invalid: Using a generic exception for an unsupported class group.</b></th>
 </tr>
 <tr>
<td>

```php
try {
    // Assuming 'Widgets' is not a supported class group
    throw new \SlevomatCodingStandard\Sniffs\Classes\UnsupportedClassGroupException('Widgets');
} catch (\SlevomatCodingStandard\Sniffs\Classes\UnsupportedClassGroupException $e) {
    // Handle the exception
}
```

</td>
<td>

```php
try {
    // Assuming 'Widgets' is not a supported class group
    throw new \Exception('Unsupported class group "Widgets".');
} catch (\Exception $e) {
    // Handle the exception
}
```

</td>
 </tr>
</table>
</details><details id='Classes.UselessLateStaticBindingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Late Static Binding</summary>
Useless late static binding should be avoided when the class is declared as final.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Use of 'static::' when class is final.</b></th>
  <th><b>Valid: Use of 'self::' in final class.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
final class SampleClass {
    public function example() {
        return static::class;
    }
}
```

</td>
<td>

```php
<?php
final class SampleClass {
    public function example() {
        return self::class;
    }
}
```

</td>
 </tr>
</table>
</details>
</details><details id='Commenting'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Commenting</summary>
<hr>
<details id='Commenting.AbstractRequireOneLineDocComment'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require One-Line Doc Comment</summary>
Doc comments for properties without description must be one-line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: One-line doc comment.</b></th>
  <th><b>Invalid: Multi-line doc comment for property without description.</b></th>
 </tr>
 <tr>
<td>

```php
/** @var string $example */
```

</td>
<td>

```php
/**
 * @var string $example
 */
```

</td>
 </tr>
</table>
</details><details id='Commenting.AnnotationNameSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Correct Annotation Names</summary>
Annotation names must follow the defined standards for naming conventions.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using a correct annotation name.</b></th>
  <th><b>Invalid: Using an incorrect annotation name.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @param string $example
 */
function exampleFunction($example) {}
```

</td>
<td>

```php
/**
 * @Parm string $example
 */
function exampleFunction($example) {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using the standardized annotation name.</b></th>
  <th><b>Invalid: Incorrect capitalization of annotation name.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @throws Exception When an error occurs.
 */
function anotherExample() {
    throw new Exception('Error');
}
```

</td>
<td>

```php
/**
 * @Throws Exception When an error occurs.
 */
function anotherExample() {
    throw new Exception('Error');
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correctly using a PHPUnit annotation.</b></th>
  <th><b>Invalid: Misspelling a PHPUnit annotation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @covers ClassName::Method
 */
class TestClass extends TestCase
{
}
```

</td>
<td>

```php
/**
 * @Cover ClassName::Method
 */
class TestClass extends TestCase
{
}
```

</td>
 </tr>
</table>
</details>
<details id='Commenting.DeprecatedAnnotationDeclarationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Deprecated Annotation Description</summary>
When using the "@deprecated" annotation, a description must be provided to explain the deprecation reason or to suggest an alternative.

<table style="width: 100%">
 <tr>
  <th><b>Valid: @deprecated tag with a description.</b></th>
  <th><b>Invalid: @deprecated tag without a description.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @deprecated Use the newInterfaceFunction() instead.
 */
function oldInterfaceFunction() {}
```

</td>
<td>

```php
/**
 * @deprecated
 */
function oldInterfaceFunction() {}
```

</td>
 </tr>
</table>
</details>
<details id='Commenting.DisallowCommentAfterCodeSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Comment After Code</summary>
Comments directly following code on the same line are disallowed. Comments must either precede the code block or be on their own line following the code block, adhering to proper indentation and code style guidelines.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Comment is on its own line, following the code block.</b></th>
  <th><b>Invalid: Comment follows code on the same line.</b></th>
 </tr>
 <tr>
<td>

```php
$variable = 'value'; // This is not allowed
// Properly placed comment
$anotherVariable = 'anotherValue';
```

</td>
<td>

```php
$variable = 'value'; // This is not allowed
$anotherVariable = 'anotherValue'; // This comment is also improperly placed
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Comment is correctly placed before the code block.</b></th>
  <th><b>Invalid: Comment is after code on the same line.</b></th>
 </tr>
 <tr>
<td>

```php
// This is a properly placed comment
$variable = 'value';
```

</td>
<td>

```php
$variable = 'value'; // Improperly placed comment
```

</td>
 </tr>
</table>
</details>
<details id='Commenting.DisallowOneLinePropertyDocCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow One Line Property Doc Comment</summary>
Property doc comments must not be one-liners. Multi-line doc comments should be used instead.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: One-line comment for property.</b></th>
  <th><b>Valid: Multi-line comment for property.</b></th>
 </tr>
 <tr>
<td>

```php
/** @var int $example */
```

</td>
<td>

```php
/**
 * @var int $example
 */
```

</td>
 </tr>
</table>
</details>
<details id='Commenting.EmptyCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Empty Comment</summary>
Comments must not be empty. Empty comments are considered as clutter in the code and should be removed.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Empty multiline comment.</b></th>
  <th><b>Valid: Non-empty multiline comment.</b></th>
 </tr>
 <tr>
<td>

```php
/*
*
*/
```

</td>
<td>

```php
/*
 * Some meaningful comment here
 */
```

</td>
 </tr>
<tr>
  <th><b>Invalid: Empty single line comment.</b></th>
  <th><b>Valid: Non-empty single line comment.</b></th>
</tr>
<tr>
<td>

```php
//
```

</td>
<td>

```php
// This is a comment
```

</td>
</tr>
<tr>
  <th><b>Invalid: Empty comment block with multiple asterisks.</b></th>
  <th><b>Valid: Comment block with content.</b></th>
</tr>
<tr>
<td>

```php
/**
 *
 */
```

</td>
<td>

```php
/**
 * Description or annotations here
 */
```

</td>
</tr>
</table>
</details><details id='Commenting.ForbiddenAnnotationsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Forbidden Annotations</summary>
Usage of specific annotations is forbidden within documentation comments.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Usage of a forbidden annotation.</b></th>
  <th><b>Valid: Without the forbidden annotation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @<em>forbiddenAnnotation</em>
 */
function exampleFunction() {

}
```

</td>
<td>

```php
/**
 * Some valid documentation here.
 */
function exampleFunction() {

}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Another example with a different forbidden annotation.</b></th>
  <th><b>Valid: The class documentation without the forbidden annotation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @<em>anotherForbidden</em> This shouldn't be used.
 */
class ExampleClass {

}
```

</td>
<td>

```php
/**
 * Proper class documentation here.
 */
class ExampleClass {

}
```

</td>
 </tr>
</table>
</details><details id='Commenting.ForbiddenCommentsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Forbidden Comments</summary>
Documentation comments must not contain forbidden comments as defined by the forbiddenCommentPatterns configuration.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No forbidden comments present.</b></th>
  <th><b>Invalid: Forbidden comment present.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * This is a permitted comment.
 */
class ExampleClass {
    // class body
}
```

</td>
<td>

```php
/**
 * This is a forbidden comment according to the given patterns.
 */
class ExampleClass {
    // class body
}
```

</td>
 </tr>
</table>
</details><details id='Commenting.InlineDocCommentDeclarationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Inline Doc Comment Declaration</summary>
Inline documentation comments must follow a specific format for `@var` annotations.
It should be "/** @var type $variableName */" directly above the variable declaration or the line of code it describes.
The comment must start with "/**", followed by a space, then the @var keyword, the variable type, the variable name, and closed with "*/".

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct inline documentation comment format.</b></th>
  <th><b>Invalid: Using /* */ for inline documentation comment.</b></th>
 </tr>
 <tr>
<td>

```php
/** @var string $name */
$name = 'John Doe';
```

</td>
<td>

```php
/* @var string $name */
$name = 'John Doe';
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Missing variable type in documentation comment.</b></th>
  <th><b>Valid: Inline documentation above a property with proper format.</b></th>
 </tr>
 <tr>
<td>

```php
/** @var $name */
$name = 'John Doe';
```

</td>
<td>

```php
/**
 * User's age
 * @var int $age
 */
private $age = 30;
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Missing @var tag in the documentation comment.</b></th>
  <th><b>Valid: Inline documentation comment with type and variable name.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * User's age
 */
private $age = 30;
```

</td>
<td>

```php
/** @var DateTimeImmutable $expirationDate */
$expirationDate = new DateTimeImmutable('+1 week');
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Inline documentation comment with invalid format (missing variable name).</b></th>
 </tr>
 <tr>
<td>

```php
/** @var DateTimeImmutable */
$expirationDate = new DateTimeImmutable('+1 week');
```

</td>
</tr>
</table>
</details>
<details id='Commenting.RequireOneLineDocCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require One Line Doc Comment</summary>
Found multi-line doc comment with single line content, use one-line doc comment instead.

<table style="width: 100%">
 <tr>
  <th><b>Valid: One-line doc comment.</b></th>
  <th><b>Invalid: Multi-line doc comment for single line content.</b></th>
 </tr>
 <tr>
<td>

```php
/** @var string $example This is an example. */
```

</td>
<td>

```php
/**
 * @var string $example This is an example.
 */
```

</td>
 </tr>
</table>
</details>
<details id='Commenting.RequireOneLinePropertyDocCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require One Line Property DocComment</summary>
Property DocComments must be written in a one-line format if they do not contain a description.

<table style="width: 100%">
 <tr>
  <th><b>Valid: One-line property DocComment.</b></th>
  <th><b>Invalid: Multi-line property DocComment for property with single line content.</b></th>
 </tr>
 <tr>
<td>

```php
/** @var string $name */
$name = 'John Doe';
```

</td>
<td>

```php
/**
 * @var string $name
 */
$name = 'John Doe';
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Property with a description in the DocComment.</b></th>
  <th><b>Valid: Multi-line DocComment with description is allowed.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * The name of the person.
 * 
 * @var string
 */
$name = 'John Doe';
```

</td>
<td>

```php
/**
 * The name of the person.
 *
 * @var string
 */
$name = 'John Doe';
```

</td>
 </tr>
</table>
<!-- It's important to ensure that each example with a Valid case has a corresponding Invalid case if applicable based on the rule logic. 
         Since the rule specifically targets properties without a description in their DocComment for conversion to one-liner, 
         the second example showcases a scenario where multi-line comments are allowed (and thus both are marked as 'Valid')." -->
</details><details id='Commenting.UselessFunctionDocCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Function DocComment</summary>
Function docComments that do not provide additional information beyond what is already type hinted are considered useless. This includes functions with no parameters, no return type, or when all parameter and return types are fully type hinted in the function declaration itself, making the docComment redundant.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Function with type hints and no docComment.</b></th>
  <th><b>Invalid: Function with type hints but with a redundant docComment.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

class SomeClass
{
    public function processData(int $data, array $options): void
    {
        // implementation...
    }
}
```

</td>
<td>

```php
<?php
namespace Example;

class SomeClass
{
    /**
     * Processes data.
     *
     * @param int $data
     * @param array $options
     */
    public function processData(int $data, array $options): void
    {
        // implementation...
    }
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Function without parameters or return type and no docComment.</b></th>
  <th><b>Invalid: Function without parameters or return type but with a redundant docComment.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

class SomeClass
{
    public function doSomething(): void
    {
        // implementation...
    }
}
```

</td>
<td>

```php
<?php
namespace Example;

class SomeClass
{
    /**
     * Does something.
     */
    public function doSomething(): void
    {
        // implementation...
    }
}
```

</td>
 </tr>
</table>
</details><details id='Commenting.UselessInheritDocCommentSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless InheritDoc Comment</summary>
Documentation comments with only @inheritDoc are considered useless.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Useless inheritDoc comment.</b></th>
  <th><b>Valid: Proper documentation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * {@inheritDoc}
 */
public function myFunction() {
    // function body
}
```

</td>
<td>

```php
/**
 * Extends parent myFunction to add custom functionality.
 */
public function myFunction() {
    // function body
}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Useless inheritDoc comment.</b></th>
  <th><b>Valid: Proper documentation or no comment.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @inheritDoc
 */
protected $myProperty;
```

</td>
<td>

```php
protected $myProperty;
```

</td>
 </tr>
</table>
</details>
</details><details id='Complexity'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Complexity</summary>
<hr>
<details id='Complexity.CognitiveSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Cognitive Complexity</summary>

Cognitive complexity of functions and methods must be managed to maintain code readability and maintainability. Cognitive Complexity is a measure of how difficult a unit of code is to intuitively understand.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Function with low cognitive complexity.</b></th>
  <th><b>Invalid: Function with high cognitive complexity due to nested control structures and boolean logic.</b></th>
 </tr>
 <tr>
<td>

```php
function simpleFunction() {
    if ($x > 0) {
        echo "Positive";
    } else {
        echo "Not positive";
    }
}
```

</td>
<td>

```php
function complexFunction() {
    if ($x > 0 && $y > 0) {
        if ($z > 0) {
            while ($a > 0) {
                // Nested loops and conditions
            }
        } else if ($z < 0) {
            // More nested conditions
        }
    } else {
        // Additional complexity
    }
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Simple loop without additional nesting or complexity.</b></th>
  <th><b>Invalid: Complex loop with multiple branching and nesting levels.</b></th>
 </tr>
 <tr>
<td>

```php
foreach ($items as $item) {
    processItem($item);
}
```

</td>
<td>

```php
foreach ($items as $item) {
    if ($item->status === 'active') {
        foreach ($item->children as $child) {
            if ($child->status === 'active') {
                // Additional nested logic
            }
        }
    }
}
```

</td>
 </tr>
</table>
</details>
</details><details id='ControlStructures'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Control Structures</summary>
<hr>
<details id='ControlStructures.AbstractControlStructureSpacing'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Control Structures Spacing</summary>
Proper spacing in control structures is required for code readability. Before and after each control structure, a specific number of blank lines must be maintained as defined by this standard.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing for an 'if' statement.</b></th>
  <th><b>Invalid: Incorrect spacing for an 'if' statement.</b></th>
 </tr>
 <tr>
<td>

```php
if ($condition) {
    // code block
}

// Next code block
```

</td>
<td>

```php
if ($condition) {
    // code block
}// Next code block
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct spacing for a 'for' loop.</b></th>
  <th><b>Invalid: Incorrect spacing for a 'for' loop.</b></th>
 </tr>
 <tr>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    // code block
}

// Next code block
```

</td>
<td>

```php
for ($i = 0; $i < 10; $i++) {
    // code block
}// Next code block
```

</td>
 </tr>
  <tr>
  <th><b>Valid: Correct spacing after control structure with comment.</b></th>
  <th><b>Invalid: Incorrect spacing after control structure with comment on the same line.</b></th>
 </tr>
 <tr>
<td>

```php
if ($condition) {
    // code block
}
// This is a comment

// Next code block
```

</td>
<td>

```php
if ($condition) {
    // code block
} // This is a comment
// Next code block
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.AbstractLineCondition'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Control Structures Condition Integrity</summary>
Control structures (if, while, do-while) must have properly structured conditions. 
This includes the usage of consistent control structures as specified by the checkedControlStructures property.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using `if` as a checked control structure.</b></th>
  <th><b>Invalid: Missing control structure condition.</b></th>
 </tr>
 <tr>
<td>

```php
if ($condition) {
    // code...
}
```

</td>
<td>

```php
if () {
    // code...
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using `while` as a checked control structure.</b></th>
  <th><b>Invalid: Improper `while` condition structure.</b></th>
 </tr>
 <tr>
<td>

```php
while ($condition) {
    // code...
}
```

</td>
<td>

```php
while () {
    // code...
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using `do-while` as a checked control structure with proper condition.</b></th>
  <th><b>Invalid: `do-while` structure without a condition.</b></th>
 </tr>
 <tr>
<td>

```php
do {
    // code...
} while ($condition);
```

</td>
<td>

```php
do {
    // code...
} while ();
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.AssignmentInConditionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Assignment In Condition</summary>
Assignment in condition statements like if, elseif, or do-while is not allowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Comparison instead of assignment in if condition.</b></th>
  <th><b>Invalid: Assignment in if condition.</b></th>
 </tr>
 <tr>
<td>

```php
if ($a === $b) {
    // Do something when $a is equal to $b
}
```

</td>
<td>

```php
if ($a = $b) {
    // Do something
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Comparison instead of assignment in elseif condition.</b></th>
  <th><b>Invalid: Assignment in elseif condition.</b></th>
 </tr>
 <tr>
<td>

```php
if ($a === $b) {
    // Do something
} elseif ($c === $d) {
    // Do something else
}
```

</td>
<td>

```php
if ($a === $b) {
    // Do something
} elseif ($c = $d) {
    // Do something else
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Comparison instead of assignment in do-while condition.</b></th>
  <th><b>Invalid: Assignment in do-while condition.</b></th>
 </tr>
 <tr>
<td>

```php
do {
    // Do something
} while ($a !== $b);
```

</td>
<td>

```php
do {
    // Do something
} while ($a = $b);
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.BlockControlStructureSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Block Control Structure Spacing</summary>
Ensures proper spacing around block control structures.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Proper spacing around control structure.</b></th>
  <th><b>Invalid: Incorrect spacing around control structure.</b></th>
 </tr>
 <tr>
<td>

```php
if ($condition) {
    // code to execute
}
```

</td>
<td>

```php
if($condition){
    // code to execute
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Customizable number of blank lines before and after control structures.</b></th>
  <th><b>Invalid: Does not adhere to the specified number of blank lines.</b></th>
 </tr>
 <tr>
<td>

```php
// Given $linesCountBefore = 1 and $linesCountAfter = 1

// Some code here

if ($condition) {
    // code to execute
}

// Some code here
```

</td>
<td>

```php
// Given $linesCountBefore = 1 and $linesCountAfter = 1

// Some code here
if ($condition) {
    // code to execute
}
// Some code here
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Respects lines count settings for the first and last control structures.</b></th>
  <th><b>Invalid: Incorrect lines count before the first or after the last control structure.</b></th>
 </tr>
 <tr>
<td>

```php
// Given $linesCountBeforeFirst = 0 and $linesCountAfterLast = 0

if ($condition) {
    // code to execute
}
```

</td>
<td>

```php

if ($condition) {
    // code to execute
}

```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct application of control structure spacing for configured structures.</b></th>
  <th><b>Invalid: Incorrect spacing for configured control structures.</b></th>
 </tr>
 <tr>
<td>

```php
// Given controlled structures are 'if', 'while'

if ($condition) {
    // if code to execute
}

while ($condition) {
    // while code to execute
}
```

</td>
<td>

```php
// Given controlled structures are 'if', 'while'

if($condition){
    // if code to execute
}

while($condition){
    // while code to execute
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.DisallowContinueWithoutIntegerOperandInSwitchSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Continue Without Integer Operand In Switch</summary>
Usage of "continue" without an integer operand in a "switch" statement is disallowed; use "break" instead.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Using 'continue' without an integer operand in a 'switch' statement.</b></th>
  <th><b>Valid: Using 'break' in a 'switch' statement or 'continue' with an integer operand.</b></th>
 </tr>
 <tr>
<td>

```php
switch ($variable) {
    case 1:
        continue;
    break;
}
```

</td>
<td>

```php
switch ($variable) {
    case 1:
        break;
    // or
    case 2:
        continue 2;
    break;
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.DisallowEmptySniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow use of empty()</summary>
Use of empty() is disallowed. Instead, consider using more specific conditions or isset() where appropriate.

<table style="width: 100%">
 <tr>
   <th><b>Invalid: Use of empty()</b></th>
   <th><b>Valid: Alternative condition checking</b></th>
 </tr>
 <tr>
<td>

```php
$isEmpty = empty($value);
```

</td>
<td>

```php
$isEmpty = $value === null || $value === ''; // Example alternative condition.
```

</td>
 </tr>
  <tr>
   <th><b>Invalid: Use of empty() in a conditional</b></th>
   <th><b>Valid: Using isset() and checking condition explicitly</b></th>
 </tr>
 <tr>
<td>

```php
if (empty($value)) {
    // do something
}
```

</td>
<td>

```php
if (!isset($value) || $value === '') {
    // do something
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.DisallowNullSafeObjectOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Null-Safe Object Operator</summary>
The null-safe operator (?->) is disallowed. Use regular null check mechanisms instead.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using null check before method call.</b></th>
  <th><b>Invalid: Using null-safe object operator.</b></th>
 </tr>
 <tr>
<td>

```php
$object = new ClassName();
if ($object !== null) {
    $value = $object->getValue();
}
```

</td>
<td>

```php
$object = new ClassName();
$value = $object?->getValue();
```

</td>
 </tr>
</table>
</details>
<details id='ControlStructures.DisallowShortTernaryOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Short Ternary Operator</summary>
The use of short ternary operators is disallowed. Regular ternary operators should be used instead.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Regular ternary operator.</b></th>
  <th><b>Invalid: Short ternary operator.</b></th>
 </tr>
 <tr>
<td>

```php
$value = $condition ? 'trueValue' : 'falseValue';
```

</td>
<td>

```php
$value = $condition ?: 'falseValue';
```

</td>
 </tr>
</table>
</details>
<details id='ControlStructures.DisallowTrailingMultiLineTernaryOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Trailing Multi-line Ternary Operator</summary>
Trailing multi-line ternary operators must be avoided. Prefer leading the line with the ternary operator.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Ternary operator formatted with leading the line.</b></th>
  <th><b>Invalid: Trailing multi-line ternary operator.</b></th>
 </tr>
 <tr>
<td>

```php
$variable = $condition
    ? $ifTrue
    : $ifFalse;
```

</td>
<td>

```php
$variable = $condition ?
    $ifTrue :
    $ifFalse;
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.DisallowYodaComparisonSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Yoda Comparison</summary>
Yoda comparisons are disallowed. Bigger or equal values must be on the left side of the comparison for better readability. This includes comparisons against all scalar values, class constants, and function return values.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Bigger value or result on the left side</b></th>
  <th><b>Invalid: Yoda comparison</b></th>
 </tr>
 <tr>
<td>

```php
if ($variable === Foo::BAR) {}
```

</td>
<td>

```php
if (Foo::BAR === $variable) {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Null comparison with function result</b></th>
  <th><b>Invalid: Yoda comparison with null</b></th>
 </tr>
 <tr>
<td>

```php
if (foo() === null) {}
```

</td>
<td>

```php
if (null === foo()) {}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.EarlyExitSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Early Exit</summary>
Code blocks should use early exits to reduce code nesting and improve readability.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using early exit.</b></th>
  <th><b>Invalid: Unnecessary else block after an early exit.</b></th>
 </tr>
 <tr>
<td>

```php
function example($data) {
    if ($data === null) {
        return;
    }
    // Process $data
}
```

</td>
<td>

```php
function example($data) {
    if ($data === null) {
        return;
    } else {
        // Process $data
    }
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using early exit with `continue` in loops.</b></th>
  <th><b>Invalid: Unnecessary else block after an early exit in loops.</b></th>
 </tr>
 <tr>
<td>

```php
foreach ($items as $item) {
    if ($item->isInvalid()) {
        continue;
    }
    // Process $item
}
```

</td>
<td>

```php
foreach ($items as $item) {
    if ($item->isInvalid()) {
        continue;
    } else {
        // Process $item
    }
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Early return instead of nested if.</b></th>
  <th><b>Invalid: Nested if-else structures.</b></th>
 </tr>
 <tr>
<td>

```php
function example($data) {
    if ($data === null) {
        return 'No data';
    }
    if (!$data->isValid()) {
        return 'Invalid data';
    }
    return 'Valid data';
}
```

</td>
<td>

```php
function example($data) {
    if ($data === null) {
        return 'No data';
    } else {
        if (!$data->isValid()) {
            return 'Invalid data';
        } else {
            return 'Valid data';
        }
    }
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.JumpStatementsSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Jump Statements Spacing</summary>
Proper spacing around jump statements (such as return, throw, yield) must be maintained. This includes a specific number of blank lines before and after the jump statements to ensure code readability and maintainability.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Proper spacing before a jump statement.</b></th>
  <th><b>Invalid: Insufficient spacing before a jump statement.</b></th>
 </tr>
 <tr>
<td>

```php
// Assuming the configuration requires one blank line before jump statements
$variable = 'value';

return $variable;
```

</td>
<td>

```php
// Assuming the configuration requires one blank line before jump statements
$variable = 'value';
return $variable;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Proper spacing after a jump statement.</b></th>
  <th><b>Invalid: No spacing after a jump statement.</b></th>
 </tr>
 <tr>
<td>

```php
// Assuming the configuration requires one blank line after jump statements
return $variable;

$anotherAction = doSomething();
```

</td>
<td>

```php
// Assuming the configuration requires one blank line after jump statements
return $variable;
$anotherAction = doSomething();
```

</td>
 </tr>
</table>

Additional configurations allow fine-tuning the required spacing, such as different rules for the first or last jump statement in a case or default branch of a switch statement, or when allowing single-line yield stacking. These configurations ensure the code adheres to the desired readability standards while providing enough flexibility to accommodate various coding styles.
</details><details id='ControlStructures.LanguageConstructWithParenthesesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Language Construct With Parentheses</summary>
Language constructs should not be used with parentheses.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using language construct without parentheses.</b></th>
  <th><b>Invalid: Using language construct with parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
<em>include</em> 'file.php';
<em>require</em> 'library.php';
<em>echo</em> 'Hello world';
<em>return</em> $value;
```

</td>
<td>

```php
<em>include(</em>'file.php'<em>)</em>;
<em>require(</em>'library.php'<em>)</em>;
<em>echo(</em>'Hello world'<em>)</em>;
<em>return(</em>$value<em>)</em>;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using 'exit' and 'yield' constructs without parentheses in contexts where parentheses are optional.</b></th>
  <th><b>Invalid: Using 'exit' and 'yield' constructs with unnecessary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
<em>exit</em>; // No parameters
yield $value; // Yield without parentheses
```

</td>
<td>

```php
<em>exit(</em><em>)</em>; // Empty parentheses
<em>yield(</em>$value<em>)</em>; // Yield with unnecessary parentheses
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.NewWithParenthesesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">New With Parentheses</summary>
The "new" keyword must be followed by parentheses even when no arguments are passed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: 'new' followed by parentheses.</b></th>
  <th><b>Invalid: 'new' without parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$obj = new ClassName();
```

</td>
<td>

```php
$obj = new ClassName;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: 'new' followed by parentheses with parameters.</b></th>
  <th><b>Invalid: 'new' without parentheses, should not omit parentheses even with parameters.</b></th>
 </tr>
 <tr>
<td>

```php
$obj = new ClassName('param1', 'param2');
```

</td>
<td>

```php
$obj = new ClassName  'param1', 'param2';
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.NewWithoutParenthesesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">New Without Parentheses</summary>
Omitting parentheses when instantiating a new class object without arguments is recommended.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Instantiation without parentheses.</b></th>
  <th><b>Invalid: Instantiation with unnecessary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$object = new ClassName;
```

</td>
<td>

```php
$object = new ClassName();
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireMultiLineConditionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Multi-Line Condition</summary>
Conditions in control structures must be split into multiple lines for readability when they are too long or complex.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Condition split across multiple lines.</b></th>
  <th><b>Invalid: Condition on a single line that exceeds the minimum line length.</b></th>
 </tr>
 <tr>
<td>

```php
if ($user->isActive() &&
    $user->hasRole('admin') &&
    $user->isVerified()) {
    // Do something
}
```

</td>
<td>

```php
if ($user->isActive() && $user->hasRole('admin') && $user->isVerified()) {
    // Do something
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Complex condition split across multiple lines.</b></th>
  <th><b>Invalid: Complex condition on a single line.</b></th>
 </tr>
 <tr>
<td>

```php
if (($user->isActive() || $user->isPending()) &&
    ($user->hasRole('admin') || $user->hasRole('editor')) &&
    $user->isVerified()) {
    // Do something
}
```

</td>
<td>

```php
if (($user->isActive() || $user->isPending()) && ($user->hasRole('admin') || $user->hasRole('editor')) && $user->isVerified()) {
    // Do something
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Boolean operator on previous line, with parts of the condition on new lines.</b></th>
  <th><b>Invalid: Condition on multiple lines but without proper splitting and alignment.</b></th>
 </tr>
 <tr>
<td>

```php
if ($user->isActive() 
    && $user->hasRole('admin') 
    && $user->isVerified()) {
    // Do something
}
```

</td>
<td>

```php
if ($user->isActive() && 
$user->hasRole('admin') && 
$user->isVerified()) {
    // Do something
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireMultiLineTernaryOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Multi-Line Ternary Operator</summary>
Ternary operators must be formatted over multiple lines if the line length exceeds the predefined limit or the expressions length meets certain conditions.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Ternary operator formatted over multiple lines.</b></th>
  <th><b>Invalid: Ternary operator in a single line that exceeds the length limit or meets the expressions length condition.</b></th>
 </tr>
 <tr>
<td>

```php
$foo = ($condition)
    ? 'result for true'
    : 'result for false';
```

</td>
<td>

```php
$foo = $condition ? 'result for true' : 'result for false';
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireNullCoalesceEqualOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Null Coalesce Equal Operator</summary>
When applicable, the "??=" operator must be used instead of combining "=" and "??" to simplify the assignment operation when dealing with null values.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using ??= operator.</b></th>
  <th><b>Invalid: Using = and ?? operators separately.</b></th>
 </tr>
 <tr>
<td>

```php
$variable ??= 'default';
```

</td>
<td>

```php
$variable = $variable ?? 'default';
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireNullSafeObjectOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Null Safe Object Operator</summary>
Null safe object operator `?->` is required when accessing properties or methods on a potentially null object to avoid runtime errors.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using null safe object operator for potentially null objects.</b></th>
  <th><b>Invalid: Using standard object operator which can lead to runtime errors if the object is null.</b></th>
 </tr>
 <tr>
<td>

```php
$user?->getProfile()?->getName();
```

</td>
<td>

```php
$user->getProfile()->getName();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Checking for null before property access or method call.</b></th>
  <th><b>Invalid: Direct property access or method call without checking for null.</b></th>
 </tr>
 <tr>
<td>

```php
if ($user !== null) {
    $name = $user->getProfile()->getName();
}
```

</td>
<td>

```php
$name = $user->getProfile()->getName();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using ternary operator for null check before property access or method call.</b></th>
  <th><b>Invalid: Direct property access or method call without null safe operator or null check.</b></th>
 </tr>
 <tr>
<td>

```php
$name = $user !== null ? $user->getProfile()->getName() : 'default';
```

</td>
<td>

```php
$name = $user->getProfile()->getName();
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireShortTernaryOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Short Ternary Operator</summary>
Short ternary operator must be used where applicable.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using short ternary operator.</b></th>
  <th><b>Invalid: Not using short ternary operator when possible.</b></th>
 </tr>
 <tr>
<td>

```php
$value = $condition ? : 'default';
```

</td>
<td>

```php
$value = $condition ? $condition : 'default';
```

</td>
 </tr>
  <tr>
  <th><b>Valid: Using short ternary operator with negation.</b></th>
  <th><b>Invalid: Not using short ternary operator with negation when possible.</b></th>
 </tr>
 <tr>
<td>

```php
$value = !$condition ? : 'not true';
```

</td>
<td>

```php
$value = !$condition ? 'not true' : $condition;
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireSingleLineConditionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Single Line Condition</summary>
Conditions must be placed on a single line when they do not exceed the maximum line length or are marked as simple conditions.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Condition fits in a single line and does not exceed maximum line length.</b></th>
  <th><b>Invalid: Condition spans multiple lines.</b></th>
 </tr>
 <tr>
<td>

```php
if ($a === $b) {
    // Do something
}
```

</td>
<td>

```php
if (
    $a === $b
) {
    // Do something
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Simple condition, enforced to be on a single line.</b></th>
  <th><b>Invalid: Simple condition, but split across multiple lines.</b></th>
 </tr>
 <tr>
<td>

```php
while ($i < 10) {
    // Do something
}
```

</td>
<td>

```php
while (
    $i < 10
) {
    // Do something
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireTernaryOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Ternary Operator</summary>
Use ternary operator instead of if-else when returning a value or assigning a value to a variable.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using ternary operator for return.</b></th>
  <th><b>Invalid: Using if-else structure for return.</b></th>
 </tr>
 <tr>
<td>

```php
return $condition ? $valueIfTrue : $valueIfFalse;
```

</td>
<td>

```php
if ($condition) {
    return $valueIfTrue;
} else {
    return $valueIfFalse;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using ternary operator for assignment.</b></th>
  <th><b>Invalid: Using if-else structure for assignment.</b></th>
 </tr>
 <tr>
<td>

```php
$result = $condition ? $valueIfTrue : $valueIfFalse;
```

</td>
<td>

```php
if ($condition) {
    $result = $valueIfTrue;
} else {
    $result = $valueIfFalse;
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.RequireYodaComparisonSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Yoda Comparison</summary>
Bigger value must be on the right side of comparisons. This ensures that the variable part of the condition is always on the left and the static value (like a constant or literal) is on the right. This practice is intended to prevent accidental assignment in place of comparison.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using Yoda conditions for comparison.</b></th>
  <th><b>Invalid: The variable is on the right side of the comparison, which is not Yoda style.</b></th>
 </tr>
 <tr>
<td>

```php
if (true === $variable) { /* ... */ }
```

</td>
<td>

```php
if ($variable === true) { /* ... */ }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Yoda conditions with class constants.</b></th>
  <th><b>Invalid: The variable comes after the class constant.</b></th>
 </tr>
 <tr>
<td>

```php
if (Foo::BAR === $variable) { /* ... */ }
```

</td>
<td>

```php
if ($variable === Foo::BAR) { /* ... */ }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using Yoda condition with function return.</b></th>
  <th><b>Invalid: Variable positioned after the function call.</b></th>
 </tr>
 <tr>
<td>

```php
if (foo() === $variable) { /* ... */ }
```

</td>
<td>

```php
if ($variable === foo()) { /* ... */ }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Comparing with null in Yoda style.</b></th>
  <th><b>Invalid: Null check without Yoda style.</b></th>
 </tr>
 <tr>
<td>

```php
if (null === $variable) { /* ... */ }
```

</td>
<td>

```php
if ($variable === null) { /* ... */ }
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.UnsupportedKeywordException'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unsupported Keyword Exception</summary>
Exception must be thrown with a specific message format for unsupported keywords.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Throwing UnsupportedKeywordException with formatted message.</b></th>
  <th><b>Invalid: Throwing exception without a specific message format.</b></th>
 </tr>
 <tr>
<td>

```php
throw new UnsupportedKeywordException('keyword');
```

</td>
<td>

```php
throw new Exception('Unsupported operation.');
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.UselessIfConditionWithReturnSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless If Condition With Return</summary>
Avoid using an if condition that only returns true or false without performing any additional operations. Simplify the code by directly returning the condition evaluation result.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Direct return of condition.</b></th>
  <th><b>Invalid: Useless if condition with return.</b></th>
 </tr>
 <tr>
<td>

```php
if ($condition) {
    return true;
} else {
    return false;
}
// Can be simplified to:
return $condition;
```

</td>
<td>

```php
if ($condition) {
    return true;
} else {
    return false;
}
```

</td>
 </tr>
</table>
<table style="width: 100%">
 <tr>
  <th><b>Valid: Return the negated condition directly.</b></th>
  <th><b>Invalid: Useless if condition with return of negated value.</b></th>
 </tr>
 <tr>
<td>

```php
if ($condition) {
    return false;
} else {
    return true;
}
// Can be simplified to:
return !$condition;
```

</td>
<td>

```php
if ($condition) {
    return false;
} else {
    return true;
}
```

</td>
 </tr>
</table>
</details><details id='ControlStructures.UselessTernaryOperatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Ternary Operator</summary>
Useless ternary operators should be avoided. This rule identifies ternary operators that can be simplified or are unnecessary because the condition expression already returns a boolean value.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Simplified condition expression.</b></th>
  <th><b>Invalid: Useless ternary operator for condition already returning a boolean value.</b></th>
 </tr>
 <tr>
<td>

```php
$canAccess = $this->checkAccess();
if ($canAccess) {
    // logic here
}
```

</td>
<td>

```php
$canAccess = $this->checkAccess() ? true : false;
if ($canAccess) {
    // logic here
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Direct usage of a boolean condition.</b></th>
  <th><b>Invalid: Unnecessary ternary operator with a boolean condition.</b></th>
 </tr>
 <tr>
<td>

```php
$isEnabled = true;
if ($isEnabled) {
    // logic here
}
```

</td>
<td>

```php
$isEnabled = true ? true : false;
if ($isEnabled) {
    // logic here
}
```

</td>
 </tr>
</table>
</details>
</details><details id='Exceptions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Exceptions</summary>
<hr>
<details id='Exceptions.DeadCatchSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Dead Catch Block</summary>
A catch block that follows a catch block catching \Throwable is unreachable and thus considered dead code. This happens because \Throwable is the base interface for all exceptions in PHP, meaning any exception is caught by catching \Throwable, making any subsequent catch blocks dead code.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Catch block after catching \Throwable is unreachable.</b></th>
  <th><b>Valid: Catch specific exception types before \Throwable.</b></th>
 </tr>
 <tr>
<td>

```php
try {
    // Code that may throw exceptions
} catch (\Throwable $exception) {
    // Handle exception
} catch (\Exception $e) {
    // <em>Unreachable catch block</em>
}
```

</td>
<td>

```php
try {
    // Code that may throw exceptions
} catch (\SpecificException $specificException) {
    // Handle specific exception
} catch (\Throwable $exception) {
    // Handle any exception
}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Multiple catch blocks after a catch block for \Throwable.</b></th>
  <th><b>Valid: Only one catch block for \Throwable at the end.</b></th>
 </tr>
 <tr>
<td>

```php
try {
    // Code that may throw exceptions
} catch (\Throwable $exception) {
    // Handle exception
} catch (\SpecificException $specificException) {
    // <em>Unreachable catch block</em>
} catch (\AnotherException $anotherException) {
    // <em>Unreachable catch block</em>
}
```

</td>
<td>

```php
try {
    // Code that may throw exceptions
} catch (\SpecificException $specificException) {
    // Handle specific exception
} catch (\AnotherException $anotherException) {
    // Handle another specific exception
} catch (\Throwable $exception) {
    // Handle any exception
}
```

</td>
 </tr>
</table>
</details><details id='Exceptions.DisallowNonCapturingCatchSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Non-Capturing Catch</summary>
Non-capturing catch blocks are disallowed. Exceptions must be caught into a variable.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Catch with variable capturing.</b></th>
  <th><b>Invalid: Non-capturing catch block.</b></th>
 </tr>
 <tr>
<td>

```php
try {
    // Code that may throw an exception
} catch (Exception $e) {
    // Handle the exception
}
```

</td>
<td>

```php
try {
    // Code that may throw an exception
} catch (Exception) {
    // Attempt to handle the exception without capturing it
}
```

</td>
 </tr>
</table>
</details><details id='Exceptions.ReferenceThrowableOnlySniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">ReferenceThrowableOnly</summary>
Only \Throwable should be referenced for catching exceptions, instead of the general \Exception. This ensures that all types of errors can be caught, not just those that extend from \Exception.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Referencing \Throwable.</b></th>
  <th><b>Invalid: Referencing the general \Exception.</b></th>
 </tr>
 <tr>
<td>

```php
try {
    // Code that may throw an exception
} catch (\Throwable $e) {
    // Handle the exception or error
}
```

</td>
<td>

```php
try {
    // Code that may throw an exception
} catch (\Exception $e) {
    // Only handles exceptions, missing errors like TypeError
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Extends from another class, not referencing \Exception.</b></th>
  <th><b>Invalid: Extends directly from \Exception.</b></th>
 </tr>
 <tr>
<td>

```php
class MyException extends AnotherException {
    // Custom exception logic
}
```

</td>
<td>

```php
class MyException extends \Exception {
    // Direct extension from general exception class
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Catching with a variable catch block that includes \Throwable.</b></th>
  <th><b>Invalid: Catching with a variable catch block that references \Exception only.</b></th>
 </tr>
 <tr>
<td>

```php
try {
    // Code that might throw multiple types of exceptions
} catch (FirstException | \Throwable $e) {
    // Handles FirstException and any other Errors/Exceptions
}
```

</td>
<td>

```php
try {
    // Code might throw different exceptions
} catch (FirstException | \Exception $e) {
    // Misses handling non-Exception errors
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Instantiating a new class that is not \Exception.</b></th>
  <th><b>Invalid: Instantiating \Exception directly.</b></th>
 </tr>
 <tr>
<td>

```php
$myError = new MyCustomError('An error occurred');
```

</td>
<td>

```php
$generalError = new \Exception('A general exception');
```

</td>
 </tr>
</table>
</details>
</details><details id='Files'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Files</summary>
<hr>
<details id='Files.FileLengthSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">File Length</summary>
File length must not exceed a specific number of lines.

<table style="width: 100%">
 <tr>
  <th><b>Valid: File with acceptable length.</b></th>
  <th><b>Invalid: File exceeding the length limit.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
// A file with less than or equal to 250 lines.
// This file length is within the acceptable limit as defined by the standard.

namespace Example;

class GoodExample {
    // Code goes here
}
?>
```

</td>
<td>

```php
<?php
// A file with more than 250 lines.
// This file length exceeds the acceptable limit and must be shortened or refactored into multiple files.

namespace Example;

class BadExample {
    // A lot of lines of code here, surpassing the 250 lines limit.
}
?>
```

</td>
 </tr>
</table>
</details><details id='Files.FunctionLengthSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Length</summary>
FunctionLengthSniff is deprecated and should not be used. It has been moved and is now part of a different namespace.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using the updated FunctionLengthSniff.</b></th>
  <th><b>Invalid: Using the deprecated FunctionLengthSniff.</b></th>
 </tr>
 <tr>
<td>

```php
<?php

namespace Your\Namespace\Here;

use SlevomatCodingStandard\Sniffs\Functions\FunctionLengthSniff;

// Your code utilizing the updated FunctionLengthSniff
```

</td>
<td>

```php
<?php

namespace Your\Namespace\Here;

use SlevomatCodingStandard\Sniffs\Files\FunctionLengthSniff;

// Your code attempting to utilize the deprecated FunctionLengthSniff
```

</td>
 </tr>
</table>
</details><details id='Files.LineLengthSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Line Length</summary>
Lines must not exceed the specified maximum length limit.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Line within the length limit.</b></th>
  <th><b>Invalid: Line exceeds the length limit.</b></th>
 </tr>
 <tr>
<td>

```php
$validLine = 'This line is within the acceptable length limit set by the standard.';
```

</td>
<td>

```php
$longLine = 'This line exceeds the acceptable length limit set by the standard, making it non-compliant with the rules.';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Short comment within the limit.</b></th>
  <th><b>Invalid: Long comment exceeds the limit.</b></th>
 </tr>
 <tr>
<td>

```php
// This is a short comment within the length limit
```

</td>
<td>

```php
// This comment is way too long and exceeds the acceptable length limit set by the coding standard, thus it is considered non-compliant.
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Import statement within the limit.</b></th>
  <th><b>Invalid: Import statement exceeds the limit when considering extreme cases with very long namespaces.</b></th>
 </tr>
 <tr>
<td>

```php
use SlevomatCodingStandard\Helpers\UseStatementHelper;
```

</td>
<td>

```php
use Some\Very\Long\Namespace\That\Exceeds\The\Usual\Length\Limit\And\Makes\The\Line\Too\Long;
```

</td>
 </tr>
</table>
</details><details id='Files.TypeNameMatchesFileNameSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Type Name Matches File Name</summary>
Class, interface, or trait names must match their file paths according to the configured namespace and autoloading standards.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Class name matches its file path.</b></th>
  <th><b>Invalid: Class name does not match its file path.</b></th>
 </tr>
 <tr>
<td>

```php
// File path: src/Model/User.php
namespace Model;

class User
{
    // Class content
}
```

</td>
<td>

```php
// File path: src/Model/Person.php
namespace Model;

class User
{
    // Class content
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Interface name matches its file path.</b></th>
  <th><b>Invalid: Interface name does not match its file path.</b></th>
 </tr>
 <tr>
<td>

```php
// File path: src/Contract/Manageable.php
namespace Contract;

interface Manageable
{
    // Interface content
}
```

</td>
<td>

```php
// File path: src/Contract/Management.php
namespace Contract;

interface Manageable
{
    // Interface content
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Trait name matches its file path.</b></th>
  <th><b>Invalid: Trait name does not match its file path.</b></th>
 </tr>
 <tr>
<td>

```php
// File path: src/Traits/Loggable.php
namespace Traits;

trait Loggable
{
    // Trait content
}
```

</td>
<td>

```php
// File path: src/Traits/Logger.php
namespace Traits;

trait Loggable
{
    // Trait content
}
```

</td>
 </tr>
</table>
</details>
</details><details id='Functions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Functions</summary>
<hr>
<details id='Functions.AbstractLineCall'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Space Before Function Call Parenthesis</summary>
There must be a space before the opening parenthesis of a function call.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Space before opening parenthesis.</b></th>
  <th><b>Invalid: No space before opening parenthesis.</b></th>
 </tr>
 <tr>
<td>

```php
$result = myFunction ( 'arg1', 'arg2');
```

</td>
<td>

```php
$result = myFunction('arg1', 'arg2');
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Space before opening parenthesis with static methods.</b></th>
  <th><b>Invalid: No space before opening parenthesis with static methods.</b></th>
 </tr>
 <tr>
<td>

```php
$result = MyClass::myMethod ( 'arg1', 'arg2');
```

</td>
<td>

```php
$result = MyClass::myMethod('arg1', 'arg2');
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Space before opening parenthesis with function variables.</b></th>
  <th><b>Invalid: No space before opening parenthesis with function variables.</b></th>
 </tr>
 <tr>
<td>

```php
$call = 'myFunction'; $result = $call ( 'arg1', 'arg2');
```

</td>
<td>

```php
$call = 'myFunction'; $result = $call('arg1', 'arg2');
```

</td>
 </tr>
</table>
</details><details id='Functions.ArrowFunctionDeclarationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Arrow Function Declaration Spacing</summary>
Correct spacing around arrow functions is required. There must be exactly one space after the "fn" keyword, one space before the "=>" arrow, and one space after the "=>" arrow. Multi-line arrow functions can optionally bypass these rules.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct spacing for arrow function.</b></th>
  <th><b>Invalid: Incorrect spacing after the 'fn' keyword.</b></th>
 </tr>
 <tr>
<td>

```php
$fn = fn() <em>=></em> 'test';
```

</td>
<td>

```php
$fn = fn <em>=></em> 'test';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct spacing with specified spaces around '=>'.</b></th>
  <th><b>Invalid: Missing space before '='.</b></th>
 </tr>
 <tr>
<td>

```php
$fn = fn() <em>=></em> 'test';
```

</td>
<td>

```php
$fn = fn()<em>=></em> 'test';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct spacing with allowed multi-line.</b></th>
  <th><b>Invalid: Incorrect spaces after '=>'.</b></th>
 </tr>
 <tr>
<td>

```php
$fn = fn() 
    <em>=></em> 'test';
```

</td>
<td>

```php
$fn = fn() <em>=></em>'test';
```

</td>
 </tr>
</table>
</details><details id='Functions.DisallowArrowFunctionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Arrow Function</summary>
Use of arrow function is disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Use of arrow function.</b></th>
  <th><b>Valid: Use regular function instead.</b></th>
 </tr>
 <tr>
<td>

```php
$fn = fn($x) => $x + 1;
```

</td>
<td>

```php
$fn = function($x) { return $x + 1; };
```

</td>
 </tr>
</table>
</details><details id='Functions.DisallowEmptyFunctionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Empty Function</summary>
Empty function body must have at least a comment to explain why it is empty.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Function with a body or a comment.</b></th>
  <th><b>Invalid: Empty function body without a comment.</b></th>
 </tr>
 <tr>
<td>

```php
function example() {
    // This function is intentionally left empty
}
```

</td>
<td>

```php
function example() {
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Constructor with property promotion.</b></th>
  <th><b>Invalid: Empty constructor without property promotion or comment.</b></th>
 </tr>
 <tr>
<td>

```php
public function __construct(private $example) {
    // Constructor can be empty due to property promotion
}
```

</td>
<td>

```php
public function __construct() {
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Abstract function.</b></th>
  <th><b>Invalid: Concrete function without a body or explanatory comment.</b></th>
 </tr>
 <tr>
<td>

```php
abstract class Example {
    abstract protected function example();
}
```

</td>
<td>

```php
class Example {
    public function example() {
    }
}
```

</td>
 </tr>
</table>
</details><details id='Functions.DisallowNamedArgumentsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Named Arguments</summary>
Named arguments are disallowed in function or method calls.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Usage of named argument.</b></th>
  <th><b>Valid: Without named arguments.</b></th>
 </tr>
 <tr>
<td>

```php
$example->functionName(argumentName: 'value');
```

</td>
<td>

```php
$example->functionName('value');
```

</td>
 </tr>
</table>
</details><details id='Functions.DisallowTrailingCommaInCallSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Trailing Comma in Call</summary>
Trailing comma after the last parameter in a function call is disallowed. This applies to both single-line and multi-line function calls, depending on the configuration. When `onlySingleLine` is set to true, the rule only applies to single-line function calls.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No trailing comma in single-line function call.</b></th>
  <th><b>Invalid: Trailing comma in single-line function call.</b></th>
 </tr>
 <tr>
<td>

```php
myFunction('arg1', 'arg2');
```

</td>
<td>

```php
myFunction('arg1', 'arg2',);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No trailing comma in multi-line function call when onlySingleLine is true.</b></th>
  <th><b>Invalid: Trailing comma in multi-line function call when onlySingleLine is true.</b></th>
 </tr>
 <tr>
<td>

```php
myFunction(
    'arg1',
    'arg2'
);
```

</td>
<td>

```php
myFunction(
    'arg1',
    'arg2',
);
```

</td>
 </tr>
  <tr>
  <th><b>Valid: No trailing comma in single-line method call.</b></th>
  <th><b>Invalid: Trailing comma in single-line method call.</b></th>
 </tr>
 <tr>
<td>

```php
$this->myMethod('arg1', 'arg2');
```

</td>
<td>

```php
$this->myMethod('arg1', 'arg2',);
```

</td>
 </tr>
  <tr>
  <th><b>Valid: Function call without parameters does not have a comma.</b></th>
  <th><b>Invalid: Function call without parameters but with a trailing comma.</b></th>
 </tr>
 <tr>
<td>

```php
myFunction();
```

</td>
<td>

```php
myFunction(,);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: When onlySingleLine is false, multi-line function call without trailing comma.</b></th>
  <th><b>Invalid: When onlySingleLine is false, trailing comma in multi-line function call.</b></th>
 </tr>
 <tr>
<td>

```php
myFunction(
    'arg1',
    'arg2'
);
```

</td>
<td>

```php
myFunction(
    'arg1',
    'arg2',
);
```

</td>
 </tr>
</table>
</details>
<details id='Functions.DisallowTrailingCommaInClosureUseSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Trailing Comma in Closure 'use' Syntax</summary>
Trailing comma after the last inherited variable in "use" of closure declaration is disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No trailing comma in 'use' of closure.</b></th>
  <th><b>Invalid: Trailing comma in 'use' of closure.</b></th>
 </tr>
 <tr>
<td>

```php
$example = function() use ($foo, $bar) {
    // function body
};
```

</td>
<td>

```php
$example = function() use ($foo, $bar,) {
    // function body
};
```

</td>
 </tr>
</table>
</details>
<details id='Functions.DisallowTrailingCommaInDeclarationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Trailing Comma in Function Declaration</summary>
Trailing comma after the last parameter in function declaration is disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Trailing comma in single-line function declaration.</b></th>
  <th><b>Valid: No trailing comma in single-line function declaration.</b></th>
 </tr>
 <tr>
<td>

```php
function example($a, $b,) {}
```

</td>
<td>

```php
function example($a, $b) {}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Trailing comma in multi-line function declaration.</b></th>
  <th><b>Valid: No trailing comma in multi-line function declaration.</b></th>
 </tr>
<tr>
<td>

```php
function example(
    $a, 
    $b,
) {}
```

</td>
<td>

```php
function example(
    $a, 
    $b
) {}
```

</td>
 </tr>
</table>
</details><details id='Functions.FunctionLengthSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Function Length</summary>
Functions must not exceed a specific number of lines (default is 20 lines).

<table style="width: 100%">
 <tr>
  <th><b>Valid: Function within the maximum line length.</b></th>
  <th><b>Invalid: Function exceeding the maximum line length.</b></th>
 </tr>
 <tr>
<td>

```php
function example() {
    // Function body
    // Total lines: <= 20
}
```

</td>
<td>

```php
function tooLongExample() {
    // Very long function body
    // ...
    // Total lines: > 20
}
```

</td>
 </tr>
</table>

- **maxLinesLength**: The maximum number of lines a function can have. Default is 20.
- **includeComments**: Determines if comments should be included in the line count. Default is false.
- **includeWhitespace**: Determines if whitespace lines should be included in the line count. Default is false.
</details><details id='Functions.NamedArgumentSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Named Argument Spacing</summary>
Ensure the correct spacing around named arguments: no whitespace before the colon and exactly one space after the colon.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No whitespace before colon and one space after.</b></th>
  <th><b>Invalid: Whitespace before colon.</b></th>
 </tr>
 <tr>
<td>

```php
foo(bar: 'value');
```

</td>
<td>

```php
foo(bar  : 'value');
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No whitespace before colon and one space after.</b></th>
  <th><b>Invalid: No space after colon.</b></th>
 </tr>
 <tr>
<td>

```php
example(argument: 123);
```

</td>
<td>

```php
example(argument:123);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No whitespace before colon and one space after.</b></th>
  <th><b>Invalid: Multiple spaces after colon.</b></th>
 </tr>
 <tr>
<td>

```php
doSomething(with: [1, 2, 3]);
```

</td>
<td>

```php
doSomething(with:   [1, 2, 3]);
```

</td>
 </tr>
</table>
</details><details id='Functions.RequireArrowFunctionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Arrow Function</summary>
Arrow functions should be used whenever possible.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Arrow function with implicit return.</b></th>
  <th><b>Invalid: Closure instead of arrow function.</b></th>
 </tr>
 <tr>
<td>

```php
$fn = fn($x) => $x + 1;
```

</td>
<td>

```php
$fn = function($x) { return $x + 1; };
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Arrow function without parameters.</b></th>
  <th><b>Invalid: Closure instead of arrow function.</b></th>
 </tr>
 <tr>
<td>

```php
$fn = fn() => 'hello';
```

</td>
<td>

```php
$fn = function() { return 'hello'; };
```

</td>
 </tr>
</table>
</details><details id='Functions.RequireMultiLineCallSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Multi Line Call</summary>
Multi line call syntax must be used when defining or calling functions, methods, or constructors if the line length exceeds the configured minimum line length, or parameters exceed a single line.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Multi line method call.</b></th>
  <th><b>Invalid: Single line method call.</b></th>
 </tr>
 <tr>
<td>

```php
$example = $object
    ->setFirst('value1')
    ->setSecond('value2')
    ->setThird('value3');
```

</td>
<td>

```php
$example = $object->setFirst('value1')->setSecond('value2')->setThird('value3');
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Multi line function call.</b></th>
  <th><b>Invalid: Single line function call.</b></th>
 </tr>
<tr>
<td>

```php
$result = myFunction(
    'arg1',
    'arg2',
    'arg3'
);
```

</td>
<td>

```php
$result = myFunction('arg1', 'arg2', 'arg3');
```

</td>
</tr>
<tr>
  <th><b>Valid: Multi line constructor call.</b></th>
  <th><b>Invalid: Single line constructor call.</b></th>
 </tr>
<tr>
<td>

```php
$object = new ClassName(
    'arg1',
    'arg2',
    'arg3'
);
```

</td>
<td>

```php
$object = new ClassName('arg1', 'arg2', 'arg3');
```

</td>
</tr>
</table>
</details><details id='Functions.RequireSingleLineCallSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Single Line Call</summary>
Method and function calls should be placed on a single line when they meet certain criteria, such as not exceeding a specific line length, not having a closure or an array definition as parameters, and not having inner method or function calls. This ensures that the code is clean and readable.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Method call on a single line.</b></th>
  <th><b>Invalid: Method call spread across multiple lines.</b></th>
 </tr>
 <tr>
<td>

```php
$object->methodName($parameter);
```

</td>
<td>

```php
$object->methodName(
    $parameter
);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Function call on a single line.</b></th>
  <th><b>Invalid: Function call spread across multiple lines.</b></th>
 </tr>
 <tr>
<td>

```php
$result = functionName($arg1, $arg2);
```

</td>
<td>

```php
$result = functionName(
    $arg1, 
    $arg2
);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Short constructor call on a single line.</b></th>
  <th><b>Invalid: Constructor call spread across multiple lines.</b></th>
 </tr>
 <tr>
<td>

```php
$object = new ClassName($arg);
```

</td>
<td>

```php
$object = new ClassName(
    $arg
);
```

</td>
 </tr>
</table>
</details><details id='Functions.RequireTrailingCommaInCallSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Trailing Comma in Call</summary>
Multi-line function calls must have a trailing comma after the last parameter. This ensures easier version control changes and more readable code.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Trailing comma is present.</b></th>
  <th><b>Invalid: Missing trailing comma.</b></th>
 </tr>
 <tr>
<td>

```php
someFunction(
    $firstParameter,
    $secondParameter,
    $thirdParameter,
);
```

</td>
<td>

```php
someFunction(
    $firstParameter,
    $secondParameter,
    $thirdParameter
);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Single-line function call does not require a trailing comma.</b></th>
  <th><b>Invalid: Multi-line function call without trailing comma.</b></th>
 </tr>
 <tr>
<td>

```php
someFunction($firstParameter, $secondParameter, $thirdParameter);
```

</td>
<td>

```php
someFunction(
    $firstParameter,
    $secondParameter
    $thirdParameter
);
```

</td>
 </tr>
</table>
</details><details id='Functions.RequireTrailingCommaInClosureUseSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Trailing Comma In Closure 'use'</summary>
Multi-line "use" of closure declaration must have a trailing comma after the last inherited variable.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Closure 'use' with trailing comma.</b></th>
  <th><b>Invalid: Closure 'use' without trailing comma.</b></th>
 </tr>
 <tr>
<td>

```php
$example = function () use (
    $var1,
    $var2,
) {};
```

</td>
<td>

```php
$example = function () use (
    $var1,
    $var2
) {};
```

</td>
 </tr>
</table>
</details><details id='Functions.RequireTrailingCommaInDeclarationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Trailing Comma in Multi-line Function Declarations</summary>
Multi-line function declarations must have a trailing comma after the last parameter.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Multi-line function declaration with trailing comma.</b></th>
  <th><b>Invalid: Multi-line function declaration without trailing comma.</b></th>
 </tr>
 <tr>
<td>

```php
function example(
    $param1,
    $param2,
) {
    // function body
}
```

</td>
<td>

```php
function example(
    $param1,
    $param2) {
    // function body
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Multi-line method declaration with trailing comma in class.</b></th>
  <th><b>Invalid: Multi-line method declaration without trailing comma in class.</b></th>
 </tr>
 <tr>
<td>

```php
class Example {
    public function foo(
        $arg1,
        $arg2,
    ) {
        // method body
    }
}
```

</td>
<td>

```php
class Example {
    public function foo(
        $arg1,
        $arg2) {
        // method body
    }
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Multi-line function call with trailing comma.</b></th>
  <th><b>Invalid: Multi-line function call without trailing comma.</b></th>
 </tr>
 <tr>
<td>

```php
example(
    $arg1,
    $arg2,
);
```

</td>
<td>

```php
example(
    $arg1,
    $arg2);
```

</td>
 </tr>
</table>
</details><details id='Functions.StaticClosureSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Static Closure</summary>
Closures not using "$this" should be declared as static for better performance.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Closure declared as static.</b></th>
  <th><b>Invalid: Closure not declared as static but not using $this.</b></th>
 </tr>
 <tr>
<td>

```php
static function () {
    // code
};
```

</td>
<td>

```php
function () {
    // code
};
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Closure using $this not declared as static.</b></th>
  <th><b>Invalid: Closure should be declared as static when not using $this.</b></th>
 </tr>
 <tr>
<td>

```php
function () use ($foo) {
    return $this->bar;
};
```

</td>
<td>

```php
function () use ($foo) {
    return $foo->bar;
};
```

</td>
 </tr>
</table>
</details>
<details id='Functions.StrictCallSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Strict Call Parameters</summary>
Strict parameter must be set to true for functions that support a strict comparison mode.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Strict parameter set to true.</b></th>
  <th><b>Invalid: Strict parameter missing or set to false.</b></th>
 </tr>
 <tr>
<td>

```php
$found = in_array($needle, $haystack, true);
$index = array_search($needle, $haystack, true);
$result = base64_decode($data, true);
$keys = array_keys($input, $search_value, true);
```

</td>
<td>

```php
$found = in_array($needle, $haystack, false);
$index = array_search($needle, $haystack);
$result = base64_decode($data, false);
$keys = array_keys($input, $search_value);
```

</td>
 </tr>
</table>
</details>
<details id='Functions.UnusedInheritedVariablePassedToClosureSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unused Inherited Variable Passed To Closure</summary>
Unused inherited variables passed to closures must be removed.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Unused inherited variable passed to closure.</b></th>
  <th><b>Valid: No unused inherited variables.</b></th>
 </tr>
 <tr>
<td>

```php
$a = 10;
$example = function () use ($a) {
    // $a is not used inside the closure.
};
```

</td>
<td>

```php
$a = 10;
$b = 5;
$example = function () use ($a, $b) {
    echo $b;
};
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Multiple unused inherited variables passed to closure.</b></th>
  <th><b>Valid: Only used inherited variables passed to closure.</b></th>
 </tr>
 <tr>
<td>

```php
$a = 10; $b = 5;
$example = function () use ($a, $b) {
    // Neither $a nor $b is used inside the closure.
};
```

</td>
<td>

```php
$a = 10; $b = 5;
$example = function () use ($b) {
    echo $b;
};
```

</td>
 </tr>
</table>
</details><details id='Functions.UnusedParameterSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unused Parameter</summary>
Parameters that are declared but not used inside functions/methods should be removed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: All parameters are used.</b></th>
  <th><b>Invalid: The parameter $c is not used.</b></th>
 </tr>
 <tr>
<td>

```php
function add($a, $b) {
    return $a + $b;
}
```

</td>
<td>

```php
function add($a, $b, $c) {
    return $a + $b;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: The parameter is used in the function body.</b></th>
  <th><b>Invalid: The parameter $name is unused.</b></th>
 </tr>
 <tr>
<td>

```php
function greet($name) {
    echo "Hello, " . $name;
}
```

</td>
<td>

```php
function greet($name) {
    echo "Hello, World!";
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: All parameters are utilized.</b></th>
  <th><b>Invalid: Parameter $name is declared but not used.</b></th>
 </tr>
 <tr>
<td>

```php
class Greeter {
    public function greet($name) {
        echo "Hi, " . $name;
    }
}
```

</td>
<td>

```php
class Greeter {
    public function greet($name) {
        echo "Hi there!";
    }
}
```

</td>
 </tr>
</table>
</details>
<details id='Functions.UselessParameterDefaultValueSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Parameter Default Value</summary>

Parameter default values should not be specified unless necessary. If a parameter has a default value, all subsequent parameters must also have default values. Avoid using a default value for a parameter if it does not make sense or if it could lead to incorrect function behavior.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Parameter without a default value when followed by a parameter with no default value.</b></th>
  <th><b>Invalid: Parameter with a useless default value when the next parameter does not have a default value.</b></th>
 </tr>
 <tr>
<td>

```php
function example($param1, $param2) {
}
```

</td>
<td>

```php
function example($param1 = null, $param2) {
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: All parameters have default values.</b></th>
  <th><b>Invalid: Useless default value for the first parameter as the second parameter does not have a default value.</b></th>
 </tr>
 <tr>
<td>

```php
function example($param1 = null, $param2 = []) {
}
```

</td>
<td>

```php
function example($param1 = null, $param2) {
}
```

</td>
 </tr>
</table>
</details>

</details><details id='Namespaces'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Namespaces</summary>
<hr>
<details id='Namespaces.AbstractFullyQualifiedGlobalReference'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">NonFullyQualifiedGlobalReference</summary>
Global references (like functions, constants, and classes) must be fully qualified.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Fully Qualified Namespace</b></th>
  <th><b>Invalid: Non-Fully Qualified Namespace</b></th>
 </tr>
 <tr>
<td>

```php
use Some\Package\Class;
$object = new \DateTime();
```

</td>
<td>

```php
use Some\Package\Class;
$object = new DateTime(); // Should be \DateTime()
```

</td>
 </tr>
<tr>
  <th><b>Valid: Using 'use' statement for including classes.</b></th>
  <th><b>Invalid: Not using 'use' statement for including classes.</b></th>
</tr>
<tr>
<td>

```php
use \Some\Package\Class;
$object = new Class();
```

</td>
<td>

```php
// Missing use statement
$object = new Some\Package\Class();
```

</td>
</tr>
<tr>
  <th><b>Valid: Fully Qualified Global Function Call</b></th>
  <th><b>Invalid: Non-Fully Qualified Global Function Call</b></th>
</tr>
<tr>
<td>

```php
$result = \strlen('text');
```

</td>
<td>

```php
$result = strlen('text'); // Should be \strlen('text')
```

</td>
 </tr>
<tr>
  <th><b>Valid: Fully Qualified Global Constant Access</b></th>
  <th><b>Invalid: Non-Fully Qualified Global Constant Access</b></th>
</tr>
<tr>
<td>

```php
$value = \PHP_INT_MAX;
```

</td>
<td>

```php
$value = PHP_INT_MAX; // Should be \PHP_INT_MAX
```

</td>
 </tr>
</table>
</details><details id='Namespaces.AlphabeticallySortedUsesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Alphabetically Sorted Uses</summary>
Use statements should be sorted alphabetically within the same type.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Alphabetically sorted use statements.</b></th>
  <th><b>Invalid: Unsorted use statements.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
use A\Zebra;
use B\Apple;
use function C\str_pad;
use const D\EOL;
```

</td>
<td>

```php
<?php
use B\Apple;
use A\Zebra; // Incorrect order
use const D\EOL;
use function C\str_pad; // Incorrect order due to different type being mixed without PSR-12 compatibility
```

</td>
 </tr>
  <tr>
  <th><b>Valid: Alphabetically sorted use statements with PSR-12 compatibility.</b></th>
  <th><b>Invalid: Unsorted use statements with PSR-12 compatibility.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
use A\Zebra;
use B\Apple;
use function C\str_pad;
use const D\EOL;
```

</td>
<td>

```php
<?php
use B\Apple;
use A\Zebra; // Incorrect order
use function C\str_pad;
use const D\EOL; // Incorrect order due to PSR-12 compatibility, expecting functions before constants
```

</td>
 </tr>
</table>
</details><details id='Namespaces.DisallowGroupUseSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Group Use</summary>
Group use declaration is disallowed, use single use declaration for every import.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Group use declaration.</b></th>
  <th><b>Valid: Single use declaration for every import.</b></th>
 </tr>
 <tr>
<td>

```php
use SlevomatCodingStandard\<em>{</em>Sniffs\Namespaces\DisallowGroupUseSniff, Sniffs\Arrays\ShortArraySyntaxSniff<em>}</em>;
```

</td>
<td>

```php
use SlevomatCodingStandard\Sniffs\Namespaces\DisallowGroupUseSniff;
use SlevomatCodingStandard\Sniffs\Arrays\ShortArraySyntaxSniff;
```

</td>
 </tr>
</table>
</details><details id='Namespaces.FullyQualifiedClassNameInAnnotationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Fully Qualified Class Name In Annotation</summary>
A class name in annotations should be referenced via a fully qualified name. This includes PHPDoc annotations where classes are not imported via use statements but are directly referenced in the annotations.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Fully qualified class name in annotation.</b></th>
  <th><b>Invalid: Class name not fully qualified in annotation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @param \SlevomatCodingStandard\Helpers\AnnotationHelper $annotationHelper
 */
```

</td>
<td>

```php
/**
 * @param AnnotationHelper $annotationHelper
 */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Fully qualified constant name in annotation.</b></th>
  <th><b>Invalid: Constant name not fully qualified in annotation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * Uses constant \SlevomatCodingStandard\Helpers\FixerHelper::SOME_CONSTANT
 */
```

</td>
<td>

```php
/**
 * Uses constant SOME_CONSTANT
 */
```

</td>
 </tr>
</table>
</details><details id='Namespaces.FullyQualifiedGlobalConstantsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Fully Qualified Global Constants</summary>
Constant should be referenced via a fully qualified name.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using fully qualified global constant name.</b></th>
  <th><b>Invalid: Not using fully qualified global constant name.</b></th>
 </tr>
 <tr>
<td>

```php
echo \PHP_VERSION;
```

</td>
<td>

```php
echo PHP_VERSION;
```

</td>
 </tr>
</table>
</details><details id='Namespaces.FullyQualifiedGlobalFunctionsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Fully Qualified Global Functions</summary>
Global functions must be referenced via a fully qualified name to improve performance by bypassing the resolution of functions at runtime.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using a fully qualified global function name.</b></th>
  <th><b>Invalid: Using a global function name without a fully qualified name.</b></th>
 </tr>
 <tr>
<td>

```php
\array_merge($array1, $array2);
```

</td>
<td>

```php
array_merge($array1, $array2);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using a fully qualified global special function name when includeSpecialFunctions is true.</b></th>
  <th><b>Invalid: Using a global special function name without a fully qualified name.</b></th>
 </tr>
 <tr>
<td>

```php
\count($items);
```

</td>
<td>

```php
count($items);
```

</td>
 </tr>
</table>
</details><details id='Namespaces.MultipleUsesPerLineSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Multiple Uses Per Line</summary>
Each use statement must have a single used type. Multiple used types per use statement are forbidden.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Single use per line.</b></th>
  <th><b>Invalid: Multiple uses per line.</b></th>
 </tr>
 <tr>
<td>

```php
use SlevomatCodingStandard\Helpers\TokenHelper;
use SlevomatCodingStandard\Helpers\UseStatementHelper;
```

</td>
<td>

```php
use SlevomatCodingStandard\Helpers\TokenHelper, SlevomatCodingStandard\Helpers\UseStatementHelper;
```

</td>
 </tr>
</table>
</details><details id='Namespaces.NamespaceDeclarationSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Namespace Declaration Formatting</summary>
Ensures proper spacing and syntax are used for namespace declarations.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Proper namespace declaration with one space after namespace statement.</b></th>
  <th><b>Invalid: Missing space after namespace statement.</b></th>
 </tr>
 <tr>
<td>

```php
namespace SlevomatCodingStandard\Sniffs\Namespaces;
```

</td>
<td>

```php
namespaceSlevomatCodingStandard\Sniffs\Namespaces;
```

</td>
 </tr>
<table style="width: 100%">
 <tr>
  <th><b>Valid: No content between namespace name and semicolon.</b></th>
  <th><b>Invalid: Disallowed content between namespace name and semicolon.</b></th>
 </tr>
 <tr>
<td>

```php
namespace SlevomatCodingStandard\Sniffs\Namespaces;
```

</td>
<td>

```php
namespace SlevomatCodingStandard\Sniffs\Namespaces { // extra content
```

</td>
 </tr>
<table style="width: 100%">
 <tr>
  <th><b>Valid: Namespace declaration without braces.</b></th>
  <th><b>Invalid: Bracketed syntax for namespaces is disallowed.</b></th>
 </tr>
 <tr>
<td>

```php
namespace SlevomatCodingStandard\Sniffs\Namespaces;
```

</td>
<td>

```php
namespace SlevomatCodingStandard\Sniffs\Namespaces {
    // Code here is not allowed
}
```

</td>
 </tr>
</table>
</details><details id='Namespaces.NamespaceSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Namespace Spacing</summary>
There MUST be a specific number of blank lines before and after the namespace declaration. By default, one blank line is required before and after the namespace declaration. This number can be adjusted by configuring the <code>linesCountBeforeNamespace</code> and <code>linesCountAfterNamespace</code> properties.

<table style="width: 100%">
 <tr>
  <th><b>Valid: One blank line before and after the namespace declaration.</b></th>
  <th><b>Invalid: No blank lines before the namespace declaration.</b></th>
 </tr>
 <tr>
<td>

```php
<?php

namespace Example;

class MyClass {}
```

</td>
<td>

```php
<?php
namespace Example;

class MyClass {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Two blank lines before and after the namespace declaration (when configured).</b></th>
  <th><b>Invalid: Incorrect number of blank lines before or after the namespace declaration.</b></th>
 </tr>
 <tr>
<td>

```php
<?php


namespace Example;


class MyClass {}
```

</td>
<td>

```php
<?php


namespace Example;
class MyClass {}
```

</td>
 </tr>
</table>
</details><details id='Namespaces.ReferenceUsedNamesOnlySniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Reference Used Names Only</summary>
References to classes, constants, and functions within a namespace must use `use` statements instead of fully qualified names or falling back to global names. This includes avoiding partial use statements and referencing global classes, functions, and constants without a leading backslash when not necessary.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using use statements for classes.</b></th>
  <th><b>Invalid: Referencing a class via its fully qualified name within a namespace.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

use DateTime;

$dateTime = new DateTime();
```

</td>
<td>

```php
<?php
namespace Example;

$dateTime = new \DateTime();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using use statements for functions.</b></th>
  <th><b>Invalid: Referencing a function via its fully qualified name.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

use function strlen;

$length = strlen('example');
```

</td>
<td>

```php
<?php
namespace Example;

$length = \strlen('example');
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using use statements for constants.</b></th>
  <th><b>Invalid: Referencing a constant via its fully qualified name.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

use const PHP_VERSION;

echo PHP_VERSION;
```

</td>
<td>

```php
<?php
namespace Example;

echo \PHP_VERSION;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Avoiding partial use statements.</b></th>
  <th><b>Invalid: Using partial use statements.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

use Some\Long\Namespace\ClassName;

$obj = new ClassName();
```

</td>
<td>

```php
<?php
namespace Example;

use Some\Long\Namespace;

$obj = new Namespace\ClassName();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Not referencing global classes without a leading backslash in a namespaced file.</b></th>
  <th><b>Invalid: Referencing global classes without a leading backslash in a namespaced file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

use RuntimeException;

throw new RuntimeException('Error');
```

</td>
<td>

```php
<?php
namespace Example;

throw new \RuntimeException('Error');
```

</td>
 </tr>
</table>
</details><details id='Namespaces.RequireOneNamespaceInFileSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require One Namespace In File</summary>
Only one namespace declaration is allowed per file.

<table style="width: 100%">
 <tr>
  <th><b>Valid: File with a single namespace.</b></th>
  <th><b>Invalid: File with multiple namespaces.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace SlevomatCodingStandard\Sniffs\Namespaces;

class ExampleClass {}
```

</td>
<td>

```php
<?php
namespace SlevomatCodingStandard\Sniffs\Namespaces;

class FirstClass {}

namespace Another\Namespace;

class SecondClass {}
```

</td>
 </tr>
</table>
</details><details id='Namespaces.UnusedUsesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unused Uses</summary>
All use statements in a namespace must be used within the file. Unused use statements should be removed to improve code readability and maintainability.

<table style="width: 100%">
 <tr>
  <th><b>Valid: All use statements are used.</b></th>
  <th><b>Invalid: The 'ArrayObject' use statement is unused.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Example;

use DateTime;
use Exception;

$date = new DateTime();
throw new Exception('Error');
```

</td>
<td>

```php
<?php
namespace Example;

use DateTime;
use Exception;
use ArrayObject; // Unused use statement

$date = new DateTime();
throw new Exception('Error');
```

</td>
 </tr>
<tr>
  <th><b>Valid: Use statement is used within annotations.</b></th>
  <th><b>Invalid: The 'Useless' annotation is never used.</b></th>
</tr>
<tr>
<td>

```php
<?php
namespace Example;

use MyAnnotations\Important;

/**
 * @Important("This class does something important")
 */
class MyClass {}
```

</td>
<td>

```php
<?php
namespace Example;

use MyAnnotations\Important;
use MyAnnotations\Useless; // Unused use statement

/**
 * @Important("This class does something important")
 */
class MyClass {}
```

</td>
 </tr>
<tr>
  <th><b>Valid: Use statements are used in type hints and annotations.</b></th>
  <th><b>Invalid: The 'UnusedClass' and 'unused_function' are unused.</b></th>
</tr>
<tr>
<td>

```php
<?php
namespace Example;

use Entities\Person;
use function array_map;

/**
 * @param Person[] $people
 */
function processPeople(array $people): void {
    array_map(function(Person $p) { echo $p->getName(); }, $people);
}
```

</td>
<td>

```php
<?php
namespace Example;

use Entities\Person;
use Entities\UnusedClass; // Unused
use function array_map;
use function array_filter as unused_function; // Unused

/**
 * @param Person[] $people
 */
function processPeople(array $people): void {
    array_map(function(Person $p) { echo $p->getName(); }, $people);
}
```

</td>
 </tr>
</table>
</details><details id='Namespaces.UseDoesNotStartWithBackslashSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Use Does Not Start With Backslash</summary>
Use statements must not start with a backslash.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Use statement without a leading backslash.</b></th>
  <th><b>Invalid: Use statement with a leading backslash.</b></th>
 </tr>
 <tr>
<td>

```php
use Some\Namespace\ClassName;
```

</td>
<td>

```php
use \Some\Namespace\ClassName;
```

</td>
 </tr>
</table>
</details><details id='Namespaces.UseFromSameNamespaceSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">No Use From Same Namespace</summary>
Using elements from the same namespace by the `use` statement is prohibited. When a class or a function is part of the same namespace, it should be used directly without the `use` statement.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using a class from another namespace.</b></th>
  <th><b>Invalid: Using a class from the same namespace.</b></th>
 </tr>
 <tr>
<td>

```php
<?php

namespace My\Namespaces;

use Another\Namespace\SomeClass;

// Some code...
```

</td>
<td>

```php
<?php

namespace My\Namespaces;

use My\Namespaces\SomeClass; // This line is unnecessary and incorrect.

// Some code...
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Directly using a class from the same namespace.</b></th>
  <th><b>Invalid: Using a `use` statement for a class in the same namespace.</b></th>
 </tr>
 <tr>
<td>

```php
<?php

namespace My\Namespaces;

// Direct use without the 'use' statement.
$example = new SomeClass();

// Some code...
```

</td>
<td>

```php
<?php

namespace My\Namespaces;

use My\Namespaces\SomeClass; // Incorrect due to being in the same namespace.

$example = new SomeClass();

// Some code...
```

</td>
 </tr>
</table>
</details><details id='Namespaces.UseOnlyWhitelistedNamespacesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Use Only Whitelisted Namespaces</summary>
Only namespaces that are whitelisted should be used. Fully qualify other types without importing them.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using a type from a whitelisted namespace.</b></th>
  <th><b>Invalid: Using a type that is not fully qualified or from a non-whitelisted namespace.</b></th>
 </tr>
 <tr>
<td>

```php
use App\Models\User;

$user = new User();
```

</td>
<td>

```php
use App\Ext\NonWhitelisted;

$item = new NonWhitelisted();
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Referencing a fully qualified name from a non-whitelisted namespace.</b></th>
  <th><b>Invalid: Importing and using a non-whitelisted namespace.</b></th>
 </tr>
 <tr>
<td>

```php
$item = new \App\Ext\NonWhitelisted();
```

</td>
<td>

```php
use App\Ext\NonWhitelisted;

$item = new NonWhitelisted();
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Allowing use from the root namespace with configuration.</b></th>
  <th><b>Invalid: Using a type from an unwhitelisted namespace when root namespace use is allowed.</b></th>
 </tr>
 <tr>
<td>

```php
use \DateTime;

$date = new DateTime();
```

</td>
<td>

```php
use App\Ext\Unwhitelisted;

$item = new Unwhitelisted();
```

</td>
 </tr>
</table>
</details><details id='Namespaces.UseSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Use Statement Spacing</summary>

This sniff ensures there are correct amounts of blank lines before the first use statement, between use statements of the same type, between use statements of different types, and after the last use statement.
- There must be exactly one blank line before the first use statement.
- There must not be any blank lines between use statements of the same type.
- There must be exactly zero or a configurable blank line between use statements of different types.
- There must be exactly one blank line after the last use statement.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct lines before first use, between same types of use, between different types of use, and after last use.</b></th>
  <th><b>Invalid: Incorrect lines before first use, between same types of use, between different types of use, and after last use.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Sample;

use SomeNamespace\ClassA;
use SomeNamespace\ClassB;

class SampleClass {}
```

</td>
<td>

```php
<?php
namespace Sample;
use SomeNamespace\ClassA;
use SomeNamespace\ClassB;
class SampleClass {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No blank line between use statements of the same type.</b></th>
  <th><b>Invalid: Blank line between use statements of the same type.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Sample;

use SomeNamespace\ClassA;
use SomeNamespace\ClassB;
use AnotherNamespace\ClassC;

class SampleClass {}
```

</td>
<td>

```php
<?php
namespace Sample;

use SomeNamespace\ClassA;

use SomeNamespace\ClassB;
use AnotherNamespace\ClassC;

class SampleClass {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Configurable blank lines between different types of use statements.</b></th>
  <th><b>Invalid: Incorrect blank lines between different types of use statements.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Sample;

use FunctionNamespace\FunctionA;
use ConstNamespace\CONST_A;

class SampleClass {}
```

</td>
<td>

```php
<?php
namespace Sample;

use FunctionNamespace\FunctionA;

use ConstNamespace\CONST_A;

class SampleClass {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: One line after the last use statement.</b></th>
  <th><b>Invalid: No line after the last use statement.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Sample;

use SomeNamespace\ClassA;

class SampleClass {}
```

</td>
<td>

```php
<?php
namespace Sample;
use SomeNamespace\ClassA;
class SampleClass {}
```

</td>
 </tr>
</table>
</details><details id='Namespaces.UselessAliasSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Alias in Use Statements</summary>
Aliases for use statements must not be redundant. If the alias is the same as the last part of the fully qualified name, it should not be used.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Use without a redundant alias.</b></th>
  <th><b>Invalid: Use with a redundant alias.</b></th>
 </tr>
 <tr>
<td>

```php
use SlevomatCodingStandard\Sniffs\Namespaces\UselessAliasSniff;
```

</td>
<td>

```php
use SlevomatCodingStandard\Sniffs\Namespaces\UselessAliasSniff <em>as UselessAliasSniff</em>;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Use with a necessary alias.</b></th>
  <th><b>Invalid: Alias same as the original name.</b></th>
 </tr>
 <tr>
<td>

```php
use SlevomatCodingStandard\Helpers\FixerHelper <em>as Helper</em>;
```

</td>
<td>

```php
use SlevomatCodingStandard\Helpers\FixerHelper <em>as FixerHelper</em>;
```

</td>
 </tr>
</table>
</details>
</details><details id='Numbers'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Numbers</summary>
<hr>
<details id='Numbers.DisallowNumericLiteralSeparatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Numeric Literal Separator</summary>
Use of numeric literal separator is disallowed in numeric literals to maintain code clarity and consistency.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Numeric literal without separator.</b></th>
  <th><b>Invalid: Numeric literal with separator.</b></th>
 </tr>
 <tr>
<td>

```php
$num = 1000000;
```

</td>
<td>

```php
$num = 1_000_000;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Floating point number without separator.</b></th>
  <th><b>Invalid: Floating point number with separator.</b></th>
 </tr>
 <tr>
<td>

```php
$num = 10.5;
```

</td>
<td>

```php
$num = 10.5_00;
```

</td>
 </tr>
</table>
</details><details id='Numbers.RequireNumericLiteralSeparatorSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Numeric Literal Separator</summary>
Numeric literal separators must be used for numbers longer than the specified digits before and after the decimal point. 
This improves the readability of numeric literals. 
Use an underscore (_) as a separator for every thousand in large numbers and after every 4 digits in fractions.

<table style="width: 100%">
 <tr>
  <th><b>Valid: With separator for readability.</b></th>
  <th><b>Invalid: Without separator in large numbers.</b></th>
 </tr>
 <tr>
<td>

```php
$value = 1_000; // Thousand separator
$value = 13.0001_0001; // Decimal and fraction separator
```

</td>
<td>

```php
$value = 1000; // Missing thousand separator
$value = 130000.00010001; // Missing decimal and fraction separator
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Ignoring octal numbers when specified.</b></th>
  <th><b>Invalid: Non-octal number that requires separators.</b></th>
 </tr>
 <tr>
<td>

```php
$value = 0123; // Valid octal number
```

</td>
<td>

```php
$value = 10000; // Should have a separator
```

</td>
 </tr>
</table>
</details>
</details><details id='Operators'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Operators</summary>
<hr>
<details id='Operators.DisallowEqualOperatorsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Equal Operators</summary>
Operators '==' and '!=' are disallowed. Use '===' and '!==' instead.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using strict equality operator.</b></th>
  <th><b>Invalid: Using non-strict equality operator.</b></th>
 </tr>
 <tr>
<td>

```php
if ($value === 'example') {
    // Do something
}
```

</td>
<td>

```php
if ($value == 'example') {
    // Do something
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using strict non-equality operator.</b></th>
  <th><b>Invalid: Using non-strict non-equality operator.</b></th>
 </tr>
 <tr>
<td>

```php
if ($value !== 'example') {
    // Do something
}
```

</td>
<td>

```php
if ($value != 'example') {
    // Do something
}
```

</td>
 </tr>
</table>
</details><details id='Operators.DisallowIncrementAndDecrementOperatorsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Increment and Decrement Operators</summary>
Increment and decrement operators must not be used.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Post-increment operator.</b></th>
  <th><b>Valid: Equivalent without using post-increment.</b></th>
 </tr>
 <tr>
<td>

```php
$i++;
```

</td>
<td>

```php
$i = $i + 1;
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Pre-increment operator.</b></th>
  <th><b>Valid: Equivalent without using pre-increment.</b></th>
 </tr>
 <tr>
<td>

```php
++$i;
```

</td>
<td>

```php
$i = $i + 1;
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Post-decrement operator.</b></th>
  <th><b>Valid: Equivalent without using post-decrement.</b></th>
 </tr>
 <tr>
<td>

```php
$i--;
```

</td>
<td>

```php
$i = $i - 1;
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Pre-decrement operator.</b></th>
  <th><b>Valid: Equivalent without using pre-decrement.</b></th>
 </tr>
 <tr>
<td>

```php
--$i;
```

</td>
<td>

```php
$i = $i - 1;
```

</td>
 </tr>
</table>
</details><details id='Operators.NegationOperatorSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Negation Operator Spacing</summary>
There MUST be exactly the configured number of spaces after the negation operator (minus sign).

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct number of spaces after minus sign.</b></th>
  <th><b>Invalid: Incorrect number of spaces after minus sign.</b></th>
 </tr>
 <tr>
<td>

```php
$value = -$a;
```

</td>
<td>

```php
$value = -  $a;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No space when configured as such.</b></th>
  <th><b>Invalid: Space found when none expected.</b></th>
 </tr>
 <tr>
<td>

```php
$value = -$a;
```

</td>
<td>

```php
$value = - $a;
```

</td>
 </tr>
</table>
</details><details id='Operators.RequireOnlyStandaloneIncrementAndDecrementOperatorsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Only Standalone Increment and Decrement Operators</summary>
Increment (++) and decrement (--) operators must be used only as standalone instructions.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Pre-increment operator used as a standalone instruction.</b></th>
  <th><b>Invalid: Pre-increment operator not used as a standalone instruction.</b></th>
 </tr>
 <tr>
<td>

```php
$i++;
```

</td>
<td>

```php
if ($i++ === 10) {
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Pre-decrement operator used as a standalone instruction.</b></th>
  <th><b>Invalid: Pre-decrement operator not used as a standalone instruction.</b></th>
 </tr>
 <tr>
<td>

```php
$i--;
```

</td>
<td>

```php
while ($i-- > 0) {
```

</td>
 </tr>
  <tr>
  <th><b>Valid: Post-increment operator used as a standalone instruction.</b></th>
  <th><b>Invalid: Post-increment operator not used as a standalone instruction.</b></th>
 </tr>
 <tr>
<td>

```php
$i++;
```

</td>
<td>

```php
echo $array[$i++];
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Post-decrement operator used as a standalone instruction.</b></th>
  <th><b>Invalid: Post-decrement operator not used as a standalone instruction.</b></th>
 </tr>
 <tr>
<td>

```php
$i--;
```

</td>
<td>

```php
$sum += $array[$i--];
```

</td>
 </tr>
</table>
</details><details id='Operators.SpreadOperatorSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Spread Operator Spacing</summary>
There must be a specific number of spaces (defined by the coding standard) after the spread operator.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct number of spaces after the spread operator when configured to 0.</b></th>
  <th><b>Invalid: Incorrect spacing after the spread operator when configured to 0.</b></th>
 </tr>
 <tr>
<td>

```php
$values = [...$items];
```

</td>
<td>

```php
$values = [... $items];
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct number of spaces after the spread operator when configured to 1.</b></th>
  <th><b>Invalid: No spacing after the spread operator when configured to 1.</b></th>
 </tr>
 <tr>
<td>

```php
$values = [... $items];
```

</td>
<td>

```php
$values = [.. .$items];
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct number of spaces after the spread operator when configured to 2.</b></th>
  <th><b>Invalid: Incorrect number (1 space) of spaces after the spread operator when configured to 2.</b></th>
 </tr>
 <tr>
<td>

```php
$values = [...  $items];
```

</td>
<td>

```php
$values = [... $items];
```

</td>
 </tr>
</table>
</details>
</details><details id='PHP'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">P H P</summary>
<hr>
<details id='PHP.DisallowDirectMagicInvokeCallSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Direct Magic Invoke Call</summary>
Direct calls of __invoke() are disallowed. Instead, instantiate the object and call the method without explicitly using __invoke().

<table style="width: 100%">
 <tr>
  <th><b>Valid: Calling an object's __invoke method without using __invoke</b></th>
  <th><b>Invalid: Directly calling the __invoke method</b></th>
 </tr>
 <tr>
<td>

```php
$obj = new ClassName();
$obj(parameters);
```

</td>
<td>

```php
$obj = new ClassName();
$obj->__invoke(parameters);
```

</td>
 </tr>
</table>
</details><details id='PHP.DisallowReferenceSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Reference</summary>
References (&) in assignments, function returns, function calls, and use declarations are disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Returning reference.</b></th>
  <th><b>Valid: Regular function return.</b></th>
 </tr>
 <tr>
<td>

```php
function &foo() {
    // Disallowed return reference.
}
```

</td>
<td>

```php
function foo() {
    // Allowed return.
}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Passing by reference.</b></th>
  <th><b>Valid: Passing by value.</b></th>
 </tr>
 <tr>
<td>

```php
function foo(&$var) {
    // Disallowed passing by reference.
}
```

</td>
<td>

```php
function foo($var) {
    // Allowed passing by value.
}
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Inheriting variable by reference in use declaration.</b></th>
  <th><b>Valid: Inheriting variable by value in use declaration.</b></th>
 </tr>
 <tr>
<td>

```php
$var = 1;
$foo = function () use (&$var) {
    // Disallowed inheriting by reference.
};
```

</td>
<td>

```php
$var = 1;
$foo = function () use ($var) {
    // Allowed inheriting by value.
};
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Assigning by reference.</b></th>
  <th><b>Valid: Assigning by value.</b></th>
 </tr>
 <tr>
<td>

```php
$foo =& $bar;
// Disallowed assigning by reference.
```

</td>
<td>

```php
$foo = $bar;
// Allowed assigning by value.
```

</td>
 </tr>
</table>
</details><details id='PHP.ForbiddenClassesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Forbidden Classes, Parent Classes, Interfaces, and Traits</summary>
Usage of specific classes, parent classes, interfaces, and traits is forbidden within the code. Configuration properties allow defining which specific names are forbidden. Forbidden entities can be replaced with alternatives if configured.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using allowed class.</b></th>
  <th><b>Invalid: Using forbidden class.</b></th>
 </tr>
 <tr>
<td>

```php
$user = new AllowedClass();
```

</td>
<td>

```php
$user = new ForbiddenClass();
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Extending allowed class.</b></th>
  <th><b>Invalid: Extending forbidden parent class.</b></th>
 </tr>
 <tr>
<td>

```php
class User extends AllowedClass {}
```

</td>
<td>

```php
class User extends ForbiddenParentClass {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Implementing allowed interfaces.</b></th>
  <th><b>Invalid: Implementing forbidden interfaces.</b></th>
 </tr>
 <tr>
<td>

```php
class User implements AllowedInterface {}
```

</td>
<td>

```php
class User implements ForbiddenInterface {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using allowed traits.</b></th>
  <th><b>Invalid: Using forbidden traits.</b></th>
 </tr>
 <tr>
<td>

```php
class User { use AllowedTrait; }
```

</td>
<td>

```php
class User { use ForbiddenTrait; }
```

</td>
 </tr>
</table>
</details><details id='PHP.OptimizedFunctionsWithoutUnpackingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Optimized Functions Without Unpacking</summary>
Functions that are optimized by PHP should not use argument unpacking.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Function call without unpacking.</b></th>
  <th><b>Invalid: Function call with unpacking.</b></th>
 </tr>
 <tr>
<td>

```php
$sum = array_sum($array);
```

</td>
<td>

```php
$sum = array_sum(...$array);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Instantiation without unpacking.</b></th>
  <th><b>Invalid: Instantiation with unpacking.</b></th>
 </tr>
 <tr>
<td>

```php
$instance = new ClassName($param1, $param2);
```

</td>
<td>

```php
$instance = new ClassName(...$params);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Method call without unpacking.</b></th>
  <th><b>Invalid: Method call with unpacking.</b></th>
 </tr>
 <tr>
<td>

```php
$result = $object->methodName($param1, $param2);
```

</td>
<td>

```php
$result = $object->methodName(...$params);
```

</td>
 </tr>
</table>
</details><details id='PHP.ReferenceSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Reference Spacing</summary>
Correct spacing after references must be adhered to.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No spaces after reference as configured.</b></th>
  <th><b>Invalid: Unexpected space after reference.</b></th>
 </tr>
 <tr>
<td>

```php
function &<em>$value</em> {}
```

</td>
<td>

```php
function &<em> </em>$value {}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exactly one space after reference when configured to 1.</b></th>
  <th><b>Invalid: No space after reference when configured to 1.</b></th>
 </tr>
 <tr>
<td>

```php
$value = &<em> </em>$anotherValue;
```

</td>
<td>

```php
$value = &<em></em>$anotherValue;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Three spaces after reference if configured to 3.</b></th>
  <th><b>Invalid: Incorrect number of spaces after reference if configured to 3.</b></th>
 </tr>
 <tr>
<td>

```php
$callback = function &<em>   </em>() use ($value) {};
```

</td>
<td>

```php
$callback = function &<em> </em>() use ($value) {};
```

</td>
 </tr>
</table>
</details><details id='PHP.RequireExplicitAssertionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Explicit Assertions</summary>
Instead of using inline documentation comments for type checks, explicit assertions must be used. This helps in maintaining type safety in a more robust and clear manner.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using explicit assertion for type check</b></th>
  <th><b>Invalid: Relying on inline documentation comment for type</b></th>
 </tr>
 <tr>
<td>

```php
// Assuming $value is documented to be of type int
\assert(\is_int($value));
```

</td>
<td>

```php
/** @var int $value */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Explicit assertion for multiple type checks using logical operators</b></th>
  <th><b>Invalid: Multiple type hints only in inline documentation</b></th>
 </tr>
 <tr>
<td>

```php
// For a variable that can be int or string
\assert(\is_int($value) || \is_string($value));
```

</td>
<td>

```php
/** @var int|string $value */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Assertion for object type</b></th>
  <th><b>Invalid: Only using inline documentation comment for object type</b></th>
 </tr>
 <tr>
<td>

```php
// If $obj is supposed to be an instance of MyClass
\assert($obj instanceof MyClass);
```

</td>
<td>

```php
/** @var MyClass $obj */
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using explicit assertion for nullable type</b></th>
  <th><b>Invalid: Only using inline documentation for nullable type</b></th>
 </tr>
 <tr>
<td>

```php
// Nullable int type
\assert($value === null || \is_int($value));
```

</td>
<td>

```php
/** @var int|null $value */
```

</td>
 </tr>
</table>

Using explicit assertions not only clarifies the intended types at runtime but also aids static analysis tools in understanding the code better.

Assertions will throw an AssertionError if the condition evaluated is false, providing a clear indicator of type mismatches during development.

</details><details id='PHP.RequireNowdocSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Require Nowdoc Syntax</summary>
Nowdoc syntax must be used instead of heredoc when variables and escape sequences are not required in the string.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using nowdoc syntax.</b></th>
  <th><b>Invalid: Using heredoc syntax when nowdoc is required.</b></th>
 </tr>
 <tr>
<td>

```php
$str = <<<'TEXT'
Hello World
TEXT;
```

</td>
<td>

```php
$str = <<<TEXT
Hello World
TEXT;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using nowdoc for multiline strings without variables.</b></th>
  <th><b>Invalid: Using heredoc for multiline strings without variables.</b></th>
 </tr>
 <tr>
<td>

```php
$str = <<<'EOD'
Example of string
spanning multiple lines
using nowdoc syntax.
EOD;
```

</td>
<td>

```php
$str = <<<EOD
Example of string
spanning multiple lines
using heredoc syntax.
EOD;
```

</td>
 </tr>
</table>
</details><details id='PHP.ShortListSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Short List Syntax</summary>
The short list syntax ([]) must be used instead of list(...).

<table style="width: 100%">
 <tr>
  <th><b>Valid: Short form of list.</b></th>
  <th><b>Invalid: Long form of list.</b></th>
 </tr>
 <tr>
<td>

```php
list($a, $b) = [1, 2];
```

</td>
<td>

```php
list($a, $b) = array(1, 2);
```

</td>
 </tr>
</table>
</details><details id='PHP.TypeCastSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Type Casts</summary>
Correct type casting must be used. Forbidden type casts must be avoided and replaced with valid alternatives where applicable.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Correct type cast.</b></th>
  <th><b>Invalid: Using forbidden real cast.</b></th>
 </tr>
 <tr>
<td>

```php
$number = (int)'123';
```

</td>
<td>

```php
$number = (real)'123';
```

</td>
 </tr>
<tr>
  <th><b>Valid: Correct type cast.</b></th>
  <th><b>Invalid: Using forbidden double cast.</b></th>
 </tr>
 <tr>
<td>

```php
$number = (float)'123.45';
```

</td>
<td>

```php
$number = (double)'123.45';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correct type cast.</b></th>
  <th><b>Invalid: Using forbidden boolean cast.</b></th>
 </tr>
 <tr>
<td>

```php
$flag = (bool)'true';
```

</td>
<td>

```php
$flag = (boolean)'true';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Setting null directly.</b></th>
  <th><b>Invalid: Using forbidden unset cast.</b></th>
 </tr>
 <tr>
<td>

```php
$variable = null;
```

</td>
<td>

```php
$variable = (unset)$variable;
```

</td>
 </tr>
</table>

The use of "binary" cast is forbidden and has no effect. Instead of "unset", use direct null assignment or the unset function. Replace deprecated type casts (real, double, boolean, integer) with their preferred form (float, bool, int) respectively.
</details><details id='PHP.UselessParenthesesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Parentheses</summary>
Useless parentheses around expressions must not be used.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Without unnecessary parentheses around variable.</b></th>
  <th><b>Invalid: With unnecessary parentheses around variable.</b></th>
 </tr>
 <tr>
<td>

```php
$value = $a + $b;
```

</td>
<td>

```php
$value = ($a + $b);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Without unnecessary parentheses around the string.</b></th>
  <th><b>Invalid: With unnecessary parentheses around the string.</b></th>
 </tr>
 <tr>
<td>

```php
$string = 'text';
```

</td>
<td>

```php
$string = ('text');
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Without unnecessary parentheses around a variable.</b></th>
  <th><b>Invalid: With unnecessary parentheses around a variable.</b></th>
 </tr>
 <tr>
<td>

```php
$result = $value * 2;
```

</td>
<td>

```php
$result = ($value) * 2;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Without unnecessary parentheses around a function call.</b></th>
  <th><b>Invalid: With unnecessary parentheses around a function call.</b></th>
 </tr>
 <tr>
<td>

```php
$length = strlen($text);
```

</td>
<td>

```php
$length = (strlen($text));
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Without unnecessary parentheses in a ternary operation.</b></th>
  <th><b>Invalid: With unnecessary parentheses in a ternary operation.</b></th>
 </tr>
 <tr>
<td>

```php
$status = $is_valid ? 'valid' : 'invalid';
```

</td>
<td>

```php
$status = ($is_valid) ? 'valid' : 'invalid';
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Direct assignment without unnecessary parentheses.</b></th>
  <th><b>Invalid: Assignment within unnecessary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$a = $b + $c;
```

</td>
<td>

```php
$a = ($b + $c);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Direct comparison without unnecessary parentheses.</b></th>
  <th><b>Invalid: Comparison within unnecessary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
if ($a > $b) { ... }
```

</td>
<td>

```php
if (($a > $b)) { ... }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Function call without unnecessary parentheses.</b></th>
  <th><b>Invalid: Function call within unnecessary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$result = max($a, $b);
```

</td>
<td>

```php
$result = (max($a, $b));
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Instantiation without unnecessary parentheses.</b></th>
  <th><b>Invalid: Instantiation within unnecessary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$obj = new ClassName;
```

</td>
<td>

```php
$obj = (new ClassName);
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Array access without unnecessary parentheses.</b></th>
  <th><b>Invalid: Array access within unnecessary parentheses.</b></th>
 </tr>
 <tr>
<td>

```php
$item = $list[$key];
```

</td>
<td>

```php
$item = ($list[$key]);
```

</td>
 </tr>
</table>
</details><details id='PHP.UselessSemicolonSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Semicolon</summary>
Useless semicolons should be removed from the code.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No extra semicolon.</b></th>
  <th><b>Invalid: Extra semicolon after assignment.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
function doSomething() {
    $a = 5;
}
```

</td>
<td>

```php
<?php
function doSomething() {
    $a = 5;;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No semicolon before closing bracket of the scope.</b></th>
  <th><b>Invalid: Useless semicolon before the closing bracket of the scope.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
function anotherExample() {
    $b = 10;
}
```

</td>
<td>

```php
<?php
function anotherExample() {
    $b = 10;;
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Correctly placed semicolon in for loop.</b></th>
  <th><b>Invalid: Extra semicolon in for loop causing a syntax error.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
for ($i = 0; $i < 10; $i++) {
    echo $i;
}
```

</td>
<td>

```php
<?php
for ($i = 0; $i < 10; $i++); {
    echo $i;
}
```

</td>
 </tr>
</table>
</details>
</details><details id='Strings'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Strings</summary>
<hr>
<details id='Strings.DisallowVariableParsingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Variable Parsing in Strings</summary>
Disallow various forms of variable parsing in strings. Options include disallowing the following syntaxes within strings: - "${...}" (Dollar Curly Syntax) - "{$...}" (Curly Dollar Syntax) - Simple syntax "$variable" The use of these variable parsing syntaxes can lead to unclear code and potential issues, especially with deprecation of "${...}" syntax as of PHP 8.2.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Without any disallowed variable parsing.</b></th>
  <th><b>Invalid: Using the disallowed simple syntax.</b></th>
 </tr>
 <tr>
<td>

```php
$var = 'world';
echo "Hello $var!";
```

</td>
<td>

```php
$var = 'world';
echo "<em>$var</em> says hello";
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Without any disallowed dollar curly syntax.</b></th>
  <th><b>Invalid: Using the disallowed dollar curly syntax.</b></th>
 </tr>
 <tr>
<td>

```php
$var = 'world';
echo "Hello {$var}!";
```

</td>
<td>

```php
$var = 'world';
echo "Hello <em>${var}</em>!";
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Without using the disallowed curly dollar syntax.</b></th>
  <th><b>Invalid: Using the disallowed curly dollar syntax.</b></th>
 </tr>
 <tr>
<td>

```php
$var = 'world';
echo "Hello " . $var . "!";
```

</td>
<td>

```php
$var = 'world';
echo "Hello <em>{$var}</em>!";
```

</td>
 </tr>
</table>
</details>
</details><details id='TypeHints'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Type Hints</summary>
<hr>
<details id='TypeHints.DeclareStrictTypesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Declare Strict Types</summary>
The declare(strict_types=1); statement must be present, correctly formatted, and properly positioned.

<table style="width: 100%">
<tr>
<th><b>Valid: declare(strict_types=1); present and correctly formatted.</b></th>
<th><b>Invalid: Missing declare(strict_types=1); statement.</b></th>
</tr>
<tr>
<td>

```php
<?php declare(strict_types=1);

namespace Example;

class Foo {
    // class body
}
```

</td>
<td>

```php
<?php

namespace Example;

class Foo {
    // class body
}
```

</td>
</tr>
<tr>
<th><b>Valid: Correct spacing around equals sign in declare statement.</b></th>
<th><b>Invalid: Incorrect spacing around equals sign in declare statement.</b></th>
</tr>
<tr>
<td>

```php
<?php declare(strict_types = 1);

namespace Example;

class Foo {
    // class body
}
```

</td>
<td>

```php
<?php declare(strict_types=1);

namespace Example;

class Foo {
    // class body
}
```

</td>
</tr>
<tr>
<th><b>Valid: Correct number of lines before and after the declare statement, based on configuration.</b></th>
<th><b>Invalid: Incorrect number of lines after the declare statement.</b></th>
</tr>
<tr>
<td>

```php
<?php declare(strict_types=1);

// Following configured blank lines
namespace Example;

class Foo {
    // class body
}
```

</td>
<td>

```php
<?php declare(strict_types=1);
namespace Example;

class Foo {
    // class body
}
```

</td>
</tr>
</table>
</details><details id='TypeHints.DisallowArrayTypeHintSyntaxSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Array Type Hint Syntax</summary>
Usage of array type hint syntax in phpDoc is disallowed. Generic type hint syntax should be used instead. 
This includes both standalone array type hints and those in union types.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Generic type hint syntax.</b></th>
  <th><b>Invalid: Array type hint syntax.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @param array<string> $items
 */
public function setItems(array $items): void {
    // Implementation
}
```

</td>
<td>

```php
/**
 * @param string[] $items
 */
public function setItems(array $items): void {
    // Implementation
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Generic type hint syntax within union type.</b></th>
  <th><b>Invalid: Array type hint syntax within union type.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @param array<string>|null $items
 */
public function setItems(?array $items): void {
    // Implementation
}
```

</td>
<td>

```php
/**
 * @param string[]|null $items
 */
public function setItems(?array $items): void {
    // Implementation
}
```

</td>
 </tr>
</table>
</details>
<details id='TypeHints.DisallowMixedTypeHintSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Mixed Type Hint</summary>
Usage of "mixed" type hint in annotations is disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Usage of a specific type hint.</b></th>
  <th><b>Invalid: Usage of 'mixed' type hint.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @param string $variable
 */
```

</td>
<td>

```php
/**
 * @param mixed $variable
 */
```

</td>
 </tr>
</table>
</details>
<details id='TypeHints.LongTypeHintsSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Long Type Hints Replacement</summary>
Short form of type hints must be used for 'int' and 'bool' types.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using 'int' as type hint.</b></th>
  <th><b>Invalid: Using 'integer' as type hint.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @var int
 */
```

</td>
<td>

```php
/**
 * @var integer
 */
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Using 'bool' as type hint.</b></th>
  <th><b>Invalid: Using 'boolean' as type hint.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @var bool
 */
```

</td>
<td>

```php
/**
 * @var boolean
 */
```

</td>
 </tr>
</table>
</details><details id='TypeHints.NullTypeHintOnLastPositionSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Null Type Hint On Last Position</summary>
The null type hint should always be in the last position when used in union type hints.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Null type hint in the last position.</b></th>
  <th><b>Invalid: Null type hint not in the last position.</b></th>
 </tr>
 <tr>
<td>

```php
/** 
 * @param string|null $value
 */
function setValue($value) {}
```

</td>
<td>

```php
/** 
 * @param null|string $value
 */
function setValue($value) {}
```

</td>
 </tr>
</table>
</details><details id='TypeHints.NullableTypeForNullDefaultValueSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Nullable Type for Null Default Value</summary>
A parameter with a null default value must be explicitly marked as nullable.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Parameter with null default value is marked as nullable.</b></th>
  <th><b>Invalid: Parameter with null default value is not marked as nullable.</b></th>
 </tr>
 <tr>
<td>

```php
function example(?string $param = null) {}
```

</td>
<td>

```php
function example(string $param = null) {}
```

</td>
 </tr>
<tr>
  <th><b>Valid: Parameter with union type including null.</b></th>
  <th><b>Invalid: Parameter has union type but not including null explicitly.</b></th>
 </tr>
 <tr>
<td>

```php
function example(string|null $param = null) {}
```

</td>
<td>

```php
function example(string|int $param = null) {}
```

</td>
 </tr>
</table>
</details><details id='TypeHints.ParameterTypeHintSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Parameter Type Hint Spacing</summary>
Ensures proper spacing around parameter type hints.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exactly one space between type hint and parameter.</b></th>
  <th><b>Invalid: No space between type hint and parameter.</b></th>
 </tr>
 <tr>
<td>

```php
function example(string $parameter): void;
```

</td>
<td>

```php
function example(string$parameter): void;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: No whitespace between nullability symbol and type hint.</b></th>
  <th><b>Invalid: Whitespace between nullability symbol and type hint.</b></th>
 </tr>
 <tr>
<td>

```php
function example(?string $parameter): void;
```

</td>
<td>

```php
function example(? string $parameter): void;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exactly one space between reference sign and type hint.</b></th>
  <th><b>Invalid: No space between reference sign and type hint.</b></th>
 </tr>
 <tr>
<td>

```php
function example(&string $parameter): void;
```

</td>
<td>

```php
function example(&string$parameter): void;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exactly one space between varadic symbol and type hint.</b></th>
  <th><b>Invalid: No space between varadic symbol and type hint.</b></th>
 </tr>
 <tr>
<td>

```php
function example(...string $parameters): void;
```

</td>
<td>

```php
function example(...string$parameters): void;
```

</td>
 </tr>
</table>
</details><details id='TypeHints.PropertyTypeHintSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Property Type Hint</summary>
Type hints for properties must be provided when possible. The sniff checks for missing type hints,
including native type hints, nullable type hints, union and intersection type hints, as well as type hints for traversable properties. 
It also checks for unnecessary annotations when type hints are provided and can be inferred.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Property with native type hint.</b></th>
  <th><b>Invalid: Property missing native type hint.</b></th>
 </tr>
 <tr>
<td>

```php
private string $name;
```

</td>
<td>

```php
/** @var string */ private $name;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Property with nullable type hint.</b></th>
  <th><b>Invalid: Property missing nullable type hint.</b></th>
 </tr>
 <tr>
<td>

```php
private ?string $name = null;
```

</td>
<td>

```php
/** @var string|null */ private $name;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Property with union type hint.</b></th>
  <th><b>Invalid: Property missing union type hint.</b></th>
 </tr>
 <tr>
<td>

```php
private int|string $value;
```

</td>
<td>

```php
/** @var int|string */ private $value;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Property with intersection type hint (PHP 8.1+).</b></th>
  <th><b>Invalid: Property missing intersection type hint.</b></th>
 </tr>
 <tr>
<td>

```php
private Iterator&Countable $iterator;
```

</td>
<td>

```php
/** @var Iterator&Countable */ private $iterator;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Property with traversable type hint specification.</b></th>
  <th><b>Invalid: Property missing traversable type hint specification.</b></th>
 </tr>
 <tr>
<td>

```php
/** @var array<int, string> */ private array $values;
```

</td>
<td>

```php
/** @var array */ private array $values;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Property with all type hints and no unnecessary annotations.</b></th>
  <th><b>Invalid: Unnecessary @var annotation when type hint is provided.</b></th>
 </tr>
 <tr>
<td>

```php
private array $data = [];
```

</td>
<td>

```php
/** @var array */ private array $data = [];
```

</td>
 </tr>
</table>
</details><details id='TypeHints.ReturnTypeHintSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">ReturnTypeHint</summary>
Functions and methods must declare return types. When possible, native return types should be used instead of annotations.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Native return type hint.</b></th>
  <th><b>Invalid: Missing native return type hint, only annotation.</b></th>
 </tr>
 <tr>
<td>

```php
public function foo(): string { return 'bar'; }
```

</td>
<td>

```php
/**
 * @return string
 */
public function foo() { return 'bar'; }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Union type hint as per PHP 8.0+.</b></th>
  <th><b>Invalid: Missing union return type hint, only annotation.</b></th>
 </tr>
 <tr>
<td>

```php
public function getData(): string|array { /* ... */ }
```

</td>
<td>

```php
/**
 * @return string|array
 */
public function getData() { /* ... */ }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: void return type for constructor.</b></th>
  <th><b>Invalid: Constructor with incorrect return type annotation.</b></th>
 </tr>
 <tr>
<td>

```php
public function __construct() { /* ... */ }
```

</td>
<td>

```php
/**
 * @return void
 */
public function __construct() { /* ... */ } // Constructors should not have a return type annotation.
```

</td>
 </tr>
 <tr>
  <th><b>Valid: nullable return type hint.</b></th>
  <th><b>Invalid: Missing nullable return type hint, only annotation.</b></th>
 </tr>
 <tr>
<td>

```php
public function getSomething(): ?string { /* ... */ }
```

</td>
<td>

```php
/**
 * @return string|null
 */
public function getSomething() { /* ... */ }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: never return type hint for PHP 8.1+.</b></th>
  <th><b>Invalid: Function that should use never return type hint.</b></th>
 </tr>
 <tr>
<td>

```php
public function throwError(): never { throw new Exception(); }
```

</td>
<td>

```php
public function throwError() { throw new Exception(); } // Missing never return type hint.
```

</td>
 </tr>
 <tr>
  <th><b>Valid: mixed return type hint for PHP 8.0+.</b></th>
  <th><b>Invalid: Functions without mixed return type hint, only annotation.</b></th>
 </tr>
 <tr>
<td>

```php
public function fetch(): mixed { /* ... */ }
```

</td>
<td>

```php
/**
 * @return mixed
 */
public function fetch() { /* ... */ }
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Return type hint for traversable types.</b></th>
  <th><b>Invalid: Missing detailed type hint for traversable return value, only annotation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @return string[]
 */
public function getItems(): array { /* ... */ }
```

</td>
<td>

```php
/**
 * @return array
 */
public function getItems() { /* ... */ } // Should specify the type of elements in the array.
```

</td>
 </tr>
</table>
</details><details id='TypeHints.ReturnTypeHintSpacingSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">ReturnTypeHintSpacing</summary>
Proper spacing is required around the return type declarations.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Exactly one space between colon and return type hint.</b></th>
  <th><b>Invalid: No space between colon and return type hint.</b></th>
 </tr>
 <tr>
<td>

```php
function foo(): int {}
```

</td>
<td>

```php
function foo():int {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Exactly one space between colon and return type hint with nullability symbol.</b></th>
  <th><b>Invalid: Multiple spaces between colon and return type hint with nullability symbol.</b></th>
 </tr>
 <tr>
<td>

```php
function foo(): ?int {}
```

</td>
<td>

```php
function foo():   ?int {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No whitespace between return type hint nullability symbol and return type hint.</b></th>
  <th><b>Invalid: Whitespace between return type hint nullability symbol and return type hint.</b></th>
 </tr>
 <tr>
<td>

```php
function foo(): ?int {}
```

</td>
<td>

```php
function foo(): ? int {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: No space between closing parenthesis and return type colon (when configured as such).</b></th>
  <th><b>Invalid: Space between closing parenthesis and return type colon (when zero spaces are configured).</b></th>
 </tr>
 <tr>
<td>

```php
function foo(): int {}
```

</td>
<td>

```php
function foo() : int {}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Configured number of spaces between closing parenthesis and return type colon.</b></th>
  <th><b>Invalid: Incorrect number of spaces between closing parenthesis and return type colon.</b></th>
 </tr>
<tr>
<td>

```php
function foo() : int {}
```

</td>
<td>

```php
function foo()    : int {}
```

</td>
 </tr>
</table>
</details><details id='TypeHints.UnionTypeHintFormatSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Union Type Hint Format</summary>
Union type hints must adhere to specific formatting rules based on configuration. This includes handling whitespaces around the union symbol (|), enforcing or forbidding short nullable type hints, and controlling the position of null in union types.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No spaces around union symbol '|' when withSpaces is set to 'no'.</b></th>
  <th><b>Invalid: Spaces found around union symbol '|' when withSpaces is set to 'no'.</b></th>
 </tr>
 <tr>
<td>

```php
public function example(): string|int;
```

</td>
<td>

```php
public function example() : string | int;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Spaces around union symbol '|' when withSpaces is set to 'yes'.</b></th>
  <th><b>Invalid: No spaces around union symbol '|' when withSpaces is set to 'yes'.</b></th>
 </tr>
 <tr>
<td>

```php
public function example(): string | int;
```

</td>
<td>

```php
public function example(): string|int;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Short nullable type hint when shortNullable is set to 'yes'.</b></th>
  <th><b>Invalid: Long form nullable type hint when shortNullable is set to 'yes'.</b></th>
 </tr>
<tr>
<td>

```php
public function example(): ?string;
```

</td>
<td>

```php
public function example(): string|null;
```

</td>
</tr>
<tr>
<th><b>Valid: Long form nullable type hint when shortNullable is set to 'no'.</b></th>
<th><b>Invalid: Short nullable type hint when shortNullable is set to 'no'.</b></th>
</tr>
<tr>
<td>

```php
public function example(): string|null;
```

</td>
<td>

```php
public function example(): ?string;
```

</td>
</tr>
<tr>
<th><b>Valid: Null type hint in first position when nullPosition is set to 'first'.</b></th>
<th><b>Invalid: Null type hint not in the first position when nullPosition is set to 'first'.</b></th>
</tr>
<tr>
<td>

```php
public function example(): null|string;
```

</td>
<td>

```php
public function example(): string|null;
```

</td>
</tr>
<tr>
<th><b>Valid: Null type hint in last position when nullPosition is set to 'last'.</b></th>
<th><b>Invalid: Null type hint not in the last position when nullPosition is set to 'last'.</b></th>
</tr>
<tr>
<td>

```php
public function example(): string|null;
```

</td>
<td>

```php
public function example(): null|string;
```

</td>
</tr>
</table>
</details><details id='TypeHints.UselessConstantTypeHintSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Constant Type Hint</summary>
Documentation comments and @var annotations for constants must be meaningful. Useless comments or @var annotations should be avoided.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Useless documentation comment with no description.</b></th>
  <th><b>Valid: Documentation comment with description.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @var int
 */
const MAX_VALUE = 10;
```

</td>
<td>

```php
/**
 * Maximum value allowed.
 *
 * @var int
 */
const MAX_VALUE = 10;
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Useless @var annotation with no additional information.</b></th>
  <th><b>Valid: No unnecessary documentation.</b></th>
 </tr>
 <tr>
<td>

```php
/**
 * @var int
 */
const MIN_VALUE = 0;
```

</td>
<td>

```php
const MIN_VALUE = 0;
```

</td>
 </tr>
</table>
</details>
</details><details id='Variables'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Variables</summary>
<hr>
<details id='Variables.DisallowSuperGlobalVariableSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Super Global Variable</summary>
Use of super global variable is disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Use of a super global variable.</b></th>
  <th><b>Valid: Using a method to access request values instead.</b></th>
 </tr>
 <tr>
<td>

```php
$value = $_POST['key'];
```

</td>
<td>

```php
$value = $request->getPost('key');
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Accessing super global variable directly.</b></th>
  <th><b>Valid: Passing data through parameters or using a service.</b></th>
 </tr>
<tr>
<td>

```php
$globalData = $GLOBALS['data'];
```

</td>
<td>

```php
$globalData = getData('data');
```

</td>
</tr>
 <tr>
  <th><b>Invalid: Reading environment variables directly via super globals.</b></th>
  <th><b>Valid: Using a dedicated environment variable access method.</b></th>
 </tr>
<tr>
<td>

```php
$environment = $_ENV['stage'];
```

</td>
<td>

```php
$environment = getenv('stage');
```

</td>
</tr>
 <tr>
  <th><b>Invalid: Directly accessing session variable.</b></th>
  <th><b>Valid: Using a session management class.</b></th>
 </tr>
<tr>
<td>

```php
$userID = $_SESSION['user_id'];
```

</td>
<td>

```php
$userID = $session->get('user_id');
```

</td>
</tr>
 <tr>
  <th><b>Invalid: Using super global for server information.</b></th>
  <th><b>Valid: Accessing server data through a request object.</b></th>
 </tr>
<tr>
<td>

```php
$userAgent = $_SERVER['HTTP_USER_AGENT'];
```

</td>
<td>

```php
$userAgent = $request->getServer('HTTP_USER_AGENT');
```

</td>
</tr>
</table>
</details><details id='Variables.DisallowVariableVariableSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Disallow Variable Variable</summary>
Use of variable variable is disallowed.

<table style="width: 100%">
 <tr>
  <th><b>Invalid: Use of variable variable.</b></th>
  <th><b>Valid: Direct variable usage.</b></th>
 </tr>
 <tr>
<td>

```php
$name = 'foo';
$$name = 'bar';
```

</td>
<td>

```php
$name = 'foo';
$name = 'bar';
```

</td>
 </tr>
 <tr>
  <th><b>Invalid: Use of variable variable with curly braces.</b></th>
  <th><b>Valid: Direct variable usage with curly braces.</b></th>
 </tr>
 <tr>
<td>

```php
$name = 'foo';
${$name} = 'bar';
```

</td>
<td>

```php
$name = 'foo';
${'name'} = 'bar';
```

</td>
 </tr>
</table>
</details><details id='Variables.DuplicateAssignmentToVariableSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Duplicate Assignment To Variable</summary>
A variable should not be assigned more than once in a row without using the assigned value between the assignments.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Using variable between assignments.</b></th>
  <th><b>Invalid: Duplicate assignment without usage.</b></th>
 </tr>
 <tr>
<td>

```php
$a = 1;

$b = 2;

$a = $b;
```

</td>
<td>

```php
$a = 1;

$a = 2;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Assignment using object operator or static property access between.</b></th>
  <th><b>Invalid: Direct duplicate assignment.</b></th>
 </tr>
 <tr>
<td>

```php
$obj->prop = 1;

$another = 2;

$obj->prop = $another;
```

</td>
<td>

```php
$obj->prop = 1;

$obj->prop = 2;
```

</td>
 </tr>
</table>
</details><details id='Variables.UnusedVariableSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Unused Variable</summary>
Variables defined in the code must be used. Unused variables can indicate a logical error and should be removed to improve code readability and performance.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Variable used in a return statement.</b></th>
  <th><b>Invalid: Variable defined but not used.</b></th>
 </tr>
 <tr>
<td>

```php
function example() {
    $foo = 'value';
    return $foo;
}
```

</td>
<td>

```php
function example() {
    $foo = 'value';
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Variable used within a loop condition.</b></th>
  <th><b>Invalid: Variable defined within a loop but unused.</b></th>
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
for ($i = 0; $i < 10; $i++) {
    $unusedVar = true;
}
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Variable passed by reference and used.</b></th>
  <th><b>Invalid: Variable passed by reference but unused.</b></th>
 </tr>
 <tr>
<td>

```php
function modify(&$variable) {
    $variable = 'changed';
}
$exampleVar = 'original';
modify($exampleVar);
echo $exampleVar; // outputs 'changed'
```

</td>
<td>

```php
function modify(&$variable) {
    $unusedVar = 'value';
}
$exampleVar = 'original';
modify($exampleVar);
```

</td>
 </tr>
</table>

<table style="width: 100%">
 <tr>
  <th><b>Valid: Variable used in a conditional statement.</b></th>
  <th><b>Invalid: Variable defined but not used in any logic.</b></th>
 </tr>
 <tr>
<td>

```php
$value = 10;
if ($value > 5) {
    echo 'Greater than 5';
}
```

</td>
<td>

```php
$value = 10;
$unusedVariable = true;
```

</td>
 </tr>
</table>
</details><details id='Variables.UselessVariableSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Useless Variable Detection</summary>
Identifies instances where a variable is immediately returned after its definition and can be simplified to a direct return statement.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Direct return of a value without a preceding variable assignment.</b></th>
  <th><b>Invalid: Useless variable assignment before return.</b></th>
 </tr>
 <tr>
<td>

```php
function example() {
    return 'direct value';
}
```

</td>
<td>

```php
function example() {
    $value = 'direct value';
    return $value;
}
```

</td>
 </tr>

 <tr>
  <th><b>Valid: Direct return of a calculated value without a preceding variable assignment.</b></th>
  <th><b>Invalid: Useless variable assignment for a calculation before return.</b></th>
 </tr>
 <tr>
<td>

```php
function sum($a, $b) {
    return $a + $b;
}
```

</td>
<td>

```php
function sum($a, $b) {
    $result = $a + $b;
    return $result;
}
```

</td>
 </tr>

 <tr>
  <th><b>Valid: Direct return in a ternary operation without a preceding variable assignment.</b></th>
  <th><b>Invalid: Useless variable assignment in a ternary operation before return.</b></th>
 </tr>
 <tr>
<td>

```php
function check($value) {
    return $value ? 'Yes' : 'No';
}
```

</td>
<td>

```php
function check($value) {
    $response = $value ? 'Yes' : 'No';
    return $response;
}
```

</td>
 </tr>
 
 <tr>
  <th><b>Valid: Returning the result of a function directly.</b></th>
  <th><b>Invalid: Assigning the result of a function to a variable only to return it.</b></th>
 </tr>
 <tr>
<td>

```php
function proxy($value) {
    return otherFunction($value);
}
```

</td>
<td>

```php
function proxy($value) {
    $result = otherFunction($value);
    return $result;
}
```

</td>
 </tr>
</table>
</details>
</details><details id='Whitespaces'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Whitespaces</summary>
<hr>
<details id='Whitespaces.DuplicateSpacesSniff'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Duplicate Spaces</summary>

Duplicate spaces within the code are not allowed, except for specific cases defined by configurable exceptions.

Duplicate spaces can lead to less readable code and inconsistencies.

- **Configurable Exceptions**:
  - `ignoreSpacesBeforeAssignment`: Allows duplicate spaces before assignment operators.
  - `ignoreSpacesInAnnotation`: Allows duplicate spaces within annotations.
  - `ignoreSpacesInComment`: Allows duplicate spaces within comments.
  - `ignoreSpacesInParameters`: Allows duplicate spaces in parameters list.
  - `ignoreSpacesInMatch`: Allows duplicate spaces in match expressions.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Properly spaced code with single space.</b></th>
  <th><b>Invalid: Code with duplicate spaces around operator.</b></th>
 </tr>
 <tr>
<td>

```php
$x = $a + $b;
// Single space around the operator
```

</td>
<td>

```php
$x = $a  +  $b;
//     ^^  ^^ Duplicate spaces around the operator
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Ignored duplicate spaces in a comment (if ignoreSpacesInComment=true).</b></th>
  <th><b>Invalid: Duplicate spaces in a comment (if ignoreSpacesInComment=false).</b></th>
 </tr>
 <tr>
<td>

```php
// This  is a  comment with  extra spaces.
```

</td>
<td>

```php
// This  is a  comment with  extra spaces.
//     ^^    ^^              ^^ Duplicate spaces in comment
```

</td>
 </tr>
 <tr>
  <th><b>Valid: Ignored spaces before assignment (if ignoreSpacesBeforeAssignment=true).</b></th>
  <th><b>Invalid: Spaces before assignment (if ignoreSpacesBeforeAssignment=false).</b></th>
 </tr>
 <tr>
<td>

```php
$x  = $a + $b; // Ignored duplicate spaces before assignment
```

</td>
<td>

```php
$x  = $a + $b;
// ^^ Duplicate spaces before assignment
```

</td>
 </tr>
</table>
</details>