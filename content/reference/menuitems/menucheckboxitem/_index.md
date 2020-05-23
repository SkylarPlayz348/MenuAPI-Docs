---
title: "MenuCheckboxItem"
weight: 2
date: 2020-04-18T16:05:00+02:00
---

## MenuCheckboxItem

A menu item with 'checkbox' functionality and a forced checkbox icon on the right.

----

### Example usage

```cs
// checkedValue: when this is set to true, the checkbox will be 'checked' by default.
bool checkedValue = false;
MenuCheckboxItem item = new MenuCheckboxItem("Checkbox Text", "Checkbox description.", checkedValue);

// Set the style:
item.Style = CheckboxStyle.Cross;

// Add a menu item to a menu:
menu.AddMenuItem(item);
```

----

### Properties

{{% notice note %}}
All standard MenuItem class properties are inherited.
The MenuItem properties **RightIcon** and **Label** are not available for MenuCheckboxItems.
{{% /notice %}}

|Property|Type|Default value|Description|Optional|
|---|---|---|---|---|
|Checked|boolean|false|The checked state for the checkbox.|**No**|
|Style|[CheckboxStyle](#checkbox-styles)|`CheckboxStyle.Tick`|The style of this checkbox item when it is "checked".|**No**|

----

### Methods

_There are no methods available for MenuCheckboxItems._

----

### Checkbox Styles

Available checkbox syltes:

|Style|Available in which game?|Default style|Example|
|-|-|-|:-:|
|CheckboxStyle.Tick|FiveM & RedM|Yes|![Style](https://vespura.com/hi/i/20-04-18_13-31-21_ri30C_3284.png)|
|CheckboxStyle.Cross|FiveM|No|![Style](https://vespura.com/hi/i/20-04-18_13-31-56_yoG5Z_3285.png)|
