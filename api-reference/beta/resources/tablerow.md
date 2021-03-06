---
title: "TableRow resource type"
description: "Represents a row in a table."
author: "lumine2008"
localization_priority: Normal
ms.prod: "excel"
---

# TableRow resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents a row in a table.


## Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[Get TableRow](../api/tablerow-get.md) | [TableRow](tablerow.md) |Read properties and relationships of tableRow object.|
|[Update](../api/tablerow-update.md) | [TableRow](tablerow.md)	|Update TableRow object. |
|[Range](../api/tablerow-range.md)|[Range](range.md)|Returns the range object associated with the entire row.|
|[Delete](../api/tablerow-delete.md)|None|Deletes the row from the table.|
|[List](../api/tablerow-list.md) | [TableRow](tablerow.md) collection |Get tableRow object collection. |
|[Itemat](../api/tablerowcollection-itemat.md)|[TableRow](tablerow.md)|Gets a row based on its position in the collection.|
|[Add](../api/tablerowcollection-add.md)|[TableRow](tablerow.md)|Adds a new row to the table.|

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|index|int|Returns the index number of the row within the rows collection of the table. Zero-indexed. Read-only.|
|values|Json|Represents the raw values of the specified range. The data returned could be of type string, number, or a boolean. Cell that contain an error will return the error string.|

## Relationships
None


## JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.tableRow"
}-->

```json
{
  "index": 1024,
  "values": "json"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "TableRow resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": [
    "Error: /api-reference/beta/resources/tablerow.md:\r\n      Exception processing links.\r\n    System.ArgumentException: Link Definition was null. Link text: !INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)\r\n      at ApiDoctor.Validation.DocFile.get_LinkDestinations()\r\n      at ApiDoctor.Validation.DocSet.ValidateLinks(Boolean includeWarnings, String[] relativePathForFiles, IssueLogger issues, Boolean requireFilenameCaseMatch, Boolean printOrphanedFiles)"
  ]
}
-->
