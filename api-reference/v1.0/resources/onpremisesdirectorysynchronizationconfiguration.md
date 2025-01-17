---
title: "onPremisesDirectorySynchronizationConfiguration resource type"
description: "Consists of configurations that can be fine-tuned and impact the on-premises directory synchronization process for a tenant."
author: "dkershaw10"
ms.reviewer: adam.lassman, daradwan
ms.localizationpriority: medium
ms.subservice: "entra-directory-management"
doc_type: resourcePageType
---

# onPremisesDirectorySynchronizationConfiguration resource type

Namespace: microsoft.graph

Consists of configurations that can be fine-tuned and impact the [on-premises directory synchronization](../resources/onpremisesdirectorysynchronization.md) process for a tenant.

## Properties

| Property                     | Type                                                                                             | Description                                                             |
| :--------------------------- | :----------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------- |
| accidentalDeletionPrevention | [onPremisesAccidentalDeletionPrevention](../resources/onpremisesaccidentaldeletionprevention.md) | Contains the accidental deletion prevention configuration for a tenant. |

## Relationships

None.

## JSON representation

The following JSON representation shows the resource type.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.onPremisesDirectorySynchronizationConfiguration"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.onPremisesDirectorySynchronizationConfiguration",
  "accidentalDeletionPrevention": {
    "@odata.type": "microsoft.graph.onPremisesAccidentalDeletionPrevention"
  }
}
```
