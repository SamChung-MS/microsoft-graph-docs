---
title: "synchronization resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# synchronization resource type

Namespace: microsoft.graph

**TODO: Add Description**

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List synchronizations](../api/synchronization-synchronization-list.md)|[synchronization](../resources/synchronization-synchronization.md) collection|Get a list of the [synchronization](../resources/synchronization.md) objects and their properties.|
|[Create synchronization](../api/synchronization-synchronization-create.md)|[synchronization](../resources/synchronization-synchronization.md)|Create a new [synchronization](../resources/synchronization-synchronization.md) object.|
|[Get synchronization](../api/synchronization-synchronization-get.md)|[synchronization](../resources/synchronization-synchronization.md)|Read the properties and relationships of a [synchronization](../resources/synchronization-synchronization.md) object.|
|[Update synchronization](../api/synchronization-synchronization-update.md)|[synchronization](../resources/synchronization-synchronization.md)|Update the properties of a [synchronization](../resources/synchronization-synchronization.md) object.|
|[Delete synchronization](../api/synchronization-synchronization-delete.md)|None|Deletes a [synchronization](../resources/synchronization-synchronization.md) object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|secrets|[synchronizationSecretKeyStringValuePair](../resources/synchronization-synchronizationsecretkeystringvaluepair.md) collection|**TODO: Add Description**|
|version|String|**TODO: Add Description**|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|jobs|[synchronizationJob](../resources/synchronization-synchronizationjob.md) collection|**TODO: Add Description**|
|templates|[synchronizationTemplate](../resources/synchronization-synchronizationtemplate.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.synchronization",
  "baseType": "",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.synchronization",
  "version": "String",
  "secrets": [
    {
      "@odata.type": "microsoft.graph.synchronizationSecretKeyStringValuePair"
    }
  ]
}
```

