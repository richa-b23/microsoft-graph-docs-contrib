---
title: "educationExcelResource resource type"
description: "A subclass of educationResource. This resource type represents an Excel document.  "
author: "mmast-msft"
ms.localizationpriority: medium
ms.subservice: "education"
doc_type: resourcePageType
---

# educationExcelResource resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

A subclass of [educationResource](educationresource.md). This resource type represents an Excel document.  
 
>**Note:** The Excel file must be in the resource folder associated with the assignment
or submission object to which this resource belongs.


## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|fileUrl|String|Pointer to the Excel file object.|
|createdBy|String|The display name of the user that created this object.|
|createdDateTime|DateTimeOffset|Date time the resoruce was added.|
|displayName|string|The display name of the resource.|
|lastModifiedBy|[identitySet](identityset.md)|The last user to modify the resource.|
|lastModifiedDateTime|DateTimeOffset|The date and time when the resource was last modified. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`.|

## JSON representation

The following JSON representation shows the resource type.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.educationExcelResource"
}-->

```json
{
  "fileUrl": "String",
  "createdBy": "String (User)",
  "createdDateTime": "String (timestamp)",
  "displayName": "String",
  "lastModifiedBy": "String (User)",
  "lastModifiedDateTime": "String (timestamp)"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "educationExcelResource resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->


