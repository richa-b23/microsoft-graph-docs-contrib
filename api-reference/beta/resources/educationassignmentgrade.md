---
title: "educationAssignmentGrade resource type"
description: "Represents the **Grade** object on a Submission."
ms.localizationpriority: medium
author: "dipakboyed"
ms.subservice: "education"
doc_type: resourcePageType
---

# educationAssignmentGrade resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Represents the **Grade** object on a Submission. 

This is an abstract type that will never be instantiated; however, all types of grading (points, pass/fail, and so on) are subclasses of this
resource type. This object also tracks who is doing the grading. This is used in the **submission.grade** property.


## Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|gradedBy|[identitySet](identityset.md)| User who did the grading. |
|gradedDateTime|DateTimeOffset| Moment in time when the grade was applied to this submission object. The Timestamp type represents date and time information using ISO 8601 format and is always in UTC time. For example, midnight UTC on Jan 1, 2014 is `2014-01-01T00:00:00Z`|

## JSON representation

The following JSON representation shows the resource type.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.educationAssignmentGrade"
}-->

```json
{
  "gradedBy": {"@odata.type": "microsoft.graph.identitySet"},
  "gradedDateTime": "String (timestamp)"
}

```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!--
{
  "type": "#page.annotation",
  "description": "educationAssignmentGrade resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": "",
  "suppressions": []
}
-->


