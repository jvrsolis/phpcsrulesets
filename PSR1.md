## Table of Contents

- [Classes](#Classes)
    - [Class Declaration Standard](#ClassDeclarationStandard)
- [Files](#Files)
    - [Side Effects Standard](#SideEffectsStandard)
- [Methods](#Methods)
    - [Camel Caps Method Name Standard](#CamelCapsMethodNameStandard)


<details open id='Classes'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Classes</summary>
<hr>
<details open id='ClassDeclarationStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Class Declaration</summary>
Each class must be in a file by itself and must be under a namespace (a top-level vendor name).

<table style="width: 100%">
 <tr>
  <th><b>Valid: One class in a file.</b></th>
  <th><b>Invalid: Multiple classes in a single file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Foo;

class Bar {
}
```

</td>
<td>

```php
<?php
namespace Foo;

class Bar {
}

class Baz {
}
```

</td>
 </tr>
 <tr>
  <th><b>Valid: A vendor-level namespace is used.</b></th>
  <th><b>Invalid: No namespace used in file.</b></th>
 </tr>
 <tr>
<td>

```php
<?php
namespace Foo;

class Bar {
}
```

</td>
<td>

```php
<?php
class Bar {
}
```

</td>
 </tr>
</table>
</details>
</details><details open id='Files'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Files</summary>
<hr>
<details open id='SideEffectsStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Side Effects</summary>
A php file should either contain declarations with no side effects, or should just have logic (including side effects) with no declarations.

<table style="width: 100%">
 <tr>
  <th><b>Valid: A class defined in a file by itself.</b></th>
  <th><b>Invalid: A class defined in a file with other code.</b></th>
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

echo "Class Foo loaded."
```

</td>
 </tr>
</table>
</details>
</details><details open id='Methods'>
<summary style="font-weight:600;font-size:1.5em;line-height:1.3;margin:0">Methods</summary>
<hr>
<details open id='CamelCapsMethodNameStandard'>
<summary style="font-weight:600;font-size:1.25em;line-height:1.3;margin:0">Method Name</summary>
Method names MUST be declared in camelCase.

<table style="width: 100%">
 <tr>
  <th><b>Valid: method name in camelCase.</b></th>
  <th><b>Invalid: method name not in camelCase.</b></th>
 </tr>
 <tr>
<td>

```php
class Foo
{
    private function doBar()
    {
    }
}
```

</td>
<td>

```php
class Foo
{
    private function do_bar()
    {
    }
}
```

</td>
 </tr>
</table>
</details>