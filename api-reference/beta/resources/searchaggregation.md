---
title: "searchAggregation resource type"
description: "Provides the details of the search aggregation in the search response."
ms.localizationpriority: medium
author: "njerigrevious"
ms.subservice: "search"
doc_type: "resourcePageType"
---

# searchAggregation resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Provides the details of the search aggregation in the search response.

## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|displayName|String| The friendly name of the aggregation. This value was provided in the input.|
|field|String| Defines on which field the aggregation was computed on.|
|buckets|[searchBucket](searchbucket.md) collection| Defines the actual buckets of the computed aggregation.|

## JSON representation

The following JSON representation shows the resource type.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.searchAggregation",
  "baseType": null
}-->

```json
{
  "displayName": "String",
  "field": "String",  
  "buckets": [{"@odata.type": "microsoft.graph.searchBucket"}]
}
```
