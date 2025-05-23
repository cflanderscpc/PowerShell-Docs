---
description: SelectionSetName Element for EntrySelectedBy for TableControl
ms.date: 08/25/2021
title: SelectionSetName Element for EntrySelectedBy for TableControl
---
# SelectionSetName Element for EntrySelectedBy for TableControl

Specifies a set of .NET types the use this entry of the table view. There is no limit to the number
of selection sets that can be specified for an entry.

## Schema

- Configuration Element
- ViewDefinitions Element
- View Element
- TableControl Element
- TableRowEntries Element
- TableRowEntry Element
- EntrySelectedBy Element
- SelectionSetName Element

## Syntax

```xml
<SelectionSetName>NameofSelectionSet</SelectionSetName>
```

## Attributes and Elements

The following sections describe attributes, child elements, and parent elements.

### Attributes

None.

### Child Elements

None.

### Parent Elements

|Element|Description|
|-------------|-----------------|
|[EntrySelectedBy Element](./entryselectedby-element-for-tablerowentry-for-tablecontrol-format.md)|Defines the .NET types that use this entry or the condition that must exist for this entry to be used.|

## Text Value

Specify the name of the selection set.

## Remarks

Selection sets are typically used when you want to define a group of objects that are used in
multiple views. For example, you might want to create a table view and a list view for the same set
of objects. For more information about defining selection sets, see [Defining Sets of objects for a View](./defining-selection-sets.md).

If you specify a selection set for an entry, you cannot specify a type name. For more information
about how to specify a .NET type, see [TypeName Element for EntrySelectedBy for TableRowEntry](./typename-element-for-entryselectedby-for-tablecontrol-format.md).

For more information about the components of a table view, see [Creating a Table View](./creating-a-table-view.md).

## See Also

[EntrySelectedBy Element](./entryselectedby-element-for-tablerowentry-for-tablecontrol-format.md)

[Defining Sets of objects for a View](./defining-selection-sets.md)

[Creating a Table View](./creating-a-table-view.md)

[Writing a PowerShell Formatting File](./writing-a-powershell-formatting-file.md)
