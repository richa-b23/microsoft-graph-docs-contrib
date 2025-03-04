---
title: "workbookCommentReply resource type"
description: "Definition of workbookCommentReply resource type"
ms.localizationpriority: medium
author: "grangeryy"
ms.subservice: "excel"
doc_type: "resourcePageType"
toc.title: Chart comment reply
---

# workbookCommentReply resource type

Namespace: microsoft.graph

Represents a reply to an Excel comment.

## Methods

| Method       | Return Type | Description |
|:-------------|:------------|:------------|
| [List replies](../api/workbookcomment-list-replies.md) | [workbookCommentReply](workbookcommentreply.md) collection | Retrieve a list of workbookcommentreply objects. |
| [Get reply](../api/workbookcommentreply-get.md) | [workbookCommentReply](workbookcommentreply.md) | Read properties and relationships of workbookCommentReply object. |
| [Create workbookCommentReply](../api/workbookcomment-post-replies.md) | [workbookCommentReply](workbookcommentreply.md) | Create a new workbookCommentReply. |
## Properties

| Property     | Type        | Description |
|:-------------|:------------|:------------|
|content|String|The content of a comment reply.|
|contentType|String|Indicates the type for the comment reply.|
|id|String|Represents the comment identifier. Read-only.|


## Relationships

None.

## JSON representation

The following JSON representation shows the resource type.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.workbookCommentReply",
  "keyProperty": "id"
}-->

```json
{
  "content": "String",
  "contentType": "String",
  "id": "String (identifier)"
}
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "workbookCommentReply resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->

