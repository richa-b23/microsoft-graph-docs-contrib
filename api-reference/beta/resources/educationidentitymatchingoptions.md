---
title: "educationIdentityMatchingOptions resource type (deprecated)"
description: "Provides a mapping between a source property and a target property for matching user accounts. The source property should exist in the source data. The target property should be a valid property in Microsoft Entra ID."
author: "mmast-msft"
ms.localizationpriority: medium
ms.subservice: "education"
doc_type: resourcePageType
---

# educationIdentityMatchingOptions resource type (deprecated)

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

[!INCLUDE [educationsynchronizationprofile-deprecate](../includes/education-deprecate-educationsynchronizationprofile.md)]

Provides a mapping between a source property and a target property for matching user accounts. The source property should exist in the source data. The target property should be a valid property in Microsoft Entra ID.

## Properties

| Property           | Type   | Description                                                                                                                                                    |
| :----------------- | :----- | :------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| appliesTo          | String | The user role type to assign to the license. Possible values are: `student`, `teacher`, `faculty`.                                                             |
| sourcePropertyName | String | The name of the source property, which should be a field name in the source data. This property is case-sensitive.                                             |
| targetPropertyName | String | The name of the target property, which should be a valid property in Microsoft Entra ID. This property is case-sensitive.                                                |
| targetDomain       | String | The domain to suffix with the source property to match on the target. If provided as null, the source property will be used to match with the target property. |

## JSON representation

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.educationIdentityMatchingOptions"
}-->

```json
{
  "appliesTo": { "@odata.type": "microsoft.graph.educationUserRole" },
  "sourcePropertyName": "String",
  "targetPropertyName": "String",
  "targetDomain": "String"
}
```
