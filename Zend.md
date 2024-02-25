## Table of Contents

- [Debug](#Debug)
    - [Code Analyzer Standard](#CodeAnalyzerStandard)
- [Files](#Files)
    - [Closing Tag Standard](#ClosingTagStandard)
- [Naming Conventions](#NamingConventions)
    - [Valid Variable Name Standard](#ValidVariableNameStandard)



</details><details id='Debug'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Debug</summary>
<hr>
<details id='CodeAnalyzerStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Zend Code Analyzer</summary>
PHP Code should pass the zend code analyzer.

<table style="width: 100%">
 <tr>
  <th><b>Valid: Valid PHP Code.</b></th>
  <th><b>Invalid: There is an unused function parameter.</b></th>
 </tr>
 <tr>
<td>

```php
function foo($bar, $baz)
{
    return $bar + $baz;
}
```

</td>
<td>

```php
function foo($bar, $baz)
{
    return $bar + 2;
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
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Closing PHP Tags</summary>
Files should not have closing php tags.

<table style="width: 100%">
 <tr>
  <th><b>Valid: No closing tag at the end of the file.</b></th>
  <th><b>Invalid: A closing php tag is included at the end of the file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
$var = 1;
```

</td>
<td>

```php
<?php
$var = 1;
?>
```

</td>
 </tr>
</table>
</details>
</details><details id='NamingConventions'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Naming Conventions</summary>
<hr>
<details id='ValidVariableNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Variable Names</summary>
Variable names should be camelCased with the first letter lowercase.  Private and protected member variables should begin with an underscore

<table style="width: 100%">
 <tr>
  <th><b>Valid: A multi-word variable uses camel casing.</b></th>
  <th><b>Invalid: A multi-word variable uses underscores and initial capitalization.</b></th>
 </tr>
 <tr>
<td>

```php
$testNumber = 1;
```

</td>
<td>

```php
$Test_Number = 1;
```

</td>
 </tr>
 <tr>
  <th><b>Valid: A private member variable begins with an underscore.</b></th>
  <th><b>Invalid: A private member variable does not begin with an underscore.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    private $_bar;
}
```

</td>
<td>

```php
class Foo
{
    private $bar;
}
```

</td>
 </tr>
</table>
</details>