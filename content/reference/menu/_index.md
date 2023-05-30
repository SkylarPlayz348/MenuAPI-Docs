---
title: "Menu"
date: 2020-04-18T16:05:00+02:00
---

## Menu

```cs
Menu menu = new Menu("Menu Title", "Menu Subtitle")

```
|Property|Type|Default value|Description|Optional|
|---|---|---|---|---|
|Title|string|null|The Title that will be displayed|false|
|Subtitle|string|null|The Subtitle that will be displayed|false|

{{% notice warning %}}
Menus can be made without a title and just a subtitle will show. To do this put `null` in the title property
{{% /notice%}}

### Methods

- SetMaxItemsOnScreen

- RefreshHindex

- GetMenuItems

- GetCurrentMenuItem

- ClearMenuItems

- AddMenuItem

- RemoveMenuItem

- CloseMenu

- OpenMenu

- GoUp

- GoDown

- GoLeft

- GoRight

- SortMenuItems

- FilterMenuItems

- ResetFilter

- SetWeaponStats

- SetWeaponComponantStats

- SetVehicleStats

- SetVehicleComponantStats

### Events

{{% notice warning %}}
All code in here is similar to the code [Here](https://github.com/TomGrobbe/MenuAPI/blob/master/TestMenu/ExampleMenu.cs#LL272C14-L272C14)
{{% /notice%}}

- OnItemSelect

#### Example:
```cs
menu.OnItemSelect(_menu, _item, _index)
{

};
```

- OnCheckboxChange

#### Example:
```cs
menu.OnCheckboxChange(_menu, _item, _index, _checked)
{

};
```
- OnListItemSelect

#### Example:
```cs
menu.OnListItemSelect(_menu, _listItem, _listIndex, _itemIndex)
{

};
```
- OnListItemIndexChange

#### Example:
```cs
menu.OnListItemIndexChange(_menu, _listItem, _oldIndex, _newIndex, _itemIndex){

};
```

- OnMenuClose

#### Example:

- OnMenuOpen

#### Example:

- OnIndexChange

#### Example:

- OnSliderPositionChange

#### Example:

- OnSliderItemSelect

#### Example:

- OnDynamicListItemCurrentItemChange

#### Example:

- OnDynamicListItemSelect

#### Example: