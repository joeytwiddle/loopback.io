---
lang: en
title: 'API docs: rest.requestcontext'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.rest.requestcontext.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/rest](./rest.md) &gt; [RequestContext](./rest.requestcontext.md)

## RequestContext class

A per-request Context combining an IoC container with handler context (request, response, etc.).

<b>Signature:</b>

```typescript
export declare class RequestContext extends Context implements HandlerContext 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(request, response, parent, serverConfig, name)](./rest.requestcontext._constructor_.md) |  | Constructs a new instance of the <code>RequestContext</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [request](./rest.requestcontext.request.md) |  | <code>Request</code> |  |
|  [response](./rest.requestcontext.response.md) |  | <code>Response</code> |  |
|  [serverConfig](./rest.requestcontext.serverconfig.md) |  | <code>RestServerResolvedConfig</code> |  |


