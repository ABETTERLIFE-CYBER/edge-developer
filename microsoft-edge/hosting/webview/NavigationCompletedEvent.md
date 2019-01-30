---
description: Contains information about the completed webview navigation
title: NavigationCompletedEvent object
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 05/26/2018
ms.topic: reference
ms.prod: microsoft-edge
keywords: webview, windows 10 apps, uwp, edge
---

# NavigationCompletedEvent object

An object that represents an event fired when the [webview](../webview.md) has finished loading the current content or if navigation has failed.

## Properties
    
### uri

The Uniform Resource Identifier (URI) of the navigation.

This property is read-only.

```js
var uri = NavigationCompletedEvent.uri;
```

#### Property value
Type: **DOMString**

### isSuccess

Gets a value that indicates whether the navigation completed successfully.

This property is read-only

```js
var isSuccess = NavigationCompletedEvent.isSuccess;
```

#### Property value
Type: **Boolean**

### webErrorStatus

If the navigation was unsuccessful, gets a value that indicates why.

This property is read-only

```js
var webErrorStatus = NavigationCompletedEvent.webErrorStatus;
```

#### Property value
Type: **unsigned long**
