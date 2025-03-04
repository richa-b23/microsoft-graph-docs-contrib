---
title: "deviceAndAppManagementAssignmentTarget resource type"
description: "Base type for assignment targets."
author: "jaiprakashmb"
localization_priority: Normal
ms.subservice: "intune"
doc_type: resourcePageType
---

# deviceAndAppManagementAssignmentTarget resource type

Namespace: microsoft.graph
> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.


Base type for assignment targets.

## Properties
|Property|Type|Description|
|:---|:---|:---|
|deviceAndAppManagementAssignmentFilterId|String|The Id of the filter for the target assignment.|
|deviceAndAppManagementAssignmentFilterType|[deviceAndAppManagementAssignmentFilterType](../resources/intune-shared-deviceandappmanagementassignmentfiltertype.md)|The type of filter of the target assignment i.e. Exclude or Include. Possible values are: `none`, `include`, `exclude`.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.deviceAndAppManagementAssignmentTarget"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceAndAppManagementAssignmentTarget",
  "deviceAndAppManagementAssignmentFilterId": "String",
  "deviceAndAppManagementAssignmentFilterType": "String"
}
```
