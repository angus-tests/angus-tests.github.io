---
layout: default
title: Python
parent: Coding standards
---


# Python
{: .no_toc }

<details markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---
The SDX Python coding standards should follow [PEP 8](https://www.python.org/dev/peps/pep-0008/). This is usually automatically checked when using Jetbrains IDE's such as Pycharm.

## Casing reminder
{: .py-4 }
<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Casing</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Function names</td>
      <td>snake_case</td>
    </tr>
    <tr>
      <td>Function parameters</td>
      <td>snake_case</td>
    </tr>
    <tr>
      <td>Variables</td>
      <td>snake_case</td>
    </tr>
    <tr>
      <td>Classes</td>
      <td>PascalCase</td>
    </tr>
    <tr>
      <td>Class methods</td>
      <td>snake_case</td>
    </tr>
    <tr>
      <td>Global constants</td>
      <td>UPPER_SNAKE_CASE</td>
    </tr>
  </tbody>
</table>

## Indentation
**4** spaces per indention level should be used and spaces should be preferred over tabs, this can easily be configured in most IDE's by using "Smart Tabs" 

## Strings
Unless required all strings should double quotes, a common exception to this might be if a double quoted sentence is needed inside a string (see code below)

```python
# Standard string
name = "Nigel"
# Embedded strings
my_sentence = 'Jon calmly asked Luke "Why did you delete the prod environment?"'
```
