---
title: TreeWalker.firstChild()
slug: Web/API/TreeWalker/firstChild
page-type: web-api-instance-method
tags:
  - API
  - DOM
  - DOM Reference
  - Method
  - TreeWalker
browser-compat: api.TreeWalker.firstChild
---

{{ APIRef("DOM") }}

The **`TreeWalker.firstChild()`** method moves the current
{{domxref("Node")}} to the first _visible_ child of the current node, and returns
the found child. It also moves the current node to this child. If no such child exists,
returns `null` and the current node is not changed.

## Syntax

```js
firstChild()
```

### Parameters

None.

### Return value

A {{domxref("Node")}} object or `null`.

## Examples

```js
const treeWalker = document.createTreeWalker(
    document.body,
    NodeFilter.SHOW_ELEMENT,
    { acceptNode(node) { return NodeFilter.FILTER_ACCEPT; } },
    false
);
const node = treeWalker.firstChild(); // returns the first child of the root element, or null if none
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- The {{domxref("TreeWalker")}} interface it belongs to.
