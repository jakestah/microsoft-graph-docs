---
title: "stringKeyObjectValuePair resource type"
description: "Represents a key-value pair where the key is a string and the value is an arbitrary JSON object. This is an OData open type that expects to have a property named `value` that is a valid JSON object."
localization_priority: Normal
---

# stringKeyObjectValuePair resource type

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents a key-value pair where the key is a string and the value is an arbitrary JSON object. This is an OData open type that expects to have a property named `value` that is a valid JSON object.

## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|key|String|Key.|
|value|Json|Arbitrary JSON object.|

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.stringKeyObjectValuePair"
}-->

```json
{
  "key": "String",
  "value":"Json"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "stringKeyObjectValuePair resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": [
    "Error: /api-reference/beta/resources/synchronization-stringkeyobjectvaluepair.md:\r\n      Exception processing links.\r\n    System.ArgumentException: Link Definition was null. Link text: !INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)\r\n      at ApiDoctor.Validation.DocFile.get_LinkDestinations()\r\n      at ApiDoctor.Validation.DocSet.ValidateLinks(Boolean includeWarnings, String[] relativePathForFiles, IssueLogger issues, Boolean requireFilenameCaseMatch, Boolean printOrphanedFiles)"
  ]
}
-->
