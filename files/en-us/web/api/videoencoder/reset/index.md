---
title: VideoEncoder.reset()
slug: Web/API/VideoEncoder/reset
page-type: web-api-instance-method
tags:
  - API
  - Method
  - Reference
  - reset
  - VideoEncoder
browser-compat: api.VideoEncoder.reset
---
{{securecontext_header}}{{DefaultAPISidebar("WebCodecs API")}}

The **`reset()`** method of the {{domxref("VideoEncoder")}} interface resets all states including configuration, control messages in the control message queue, and all pending callbacks.

## Syntax

```js
reset()
```

### Parameters

None.

### Return value

{{jsxref("Undefined")}}.

## Examples

The following example resets the `VideoEncoder`.

```js
VideoEncoder.reset();
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
