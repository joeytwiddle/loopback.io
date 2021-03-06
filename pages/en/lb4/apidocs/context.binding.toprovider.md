---
lang: en
title: 'API docs: context.binding.toprovider'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.context.binding.toprovider.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [Binding](./context.binding.md) &gt; [toProvider](./context.binding.toprovider.md)

## Binding.toProvider() method

Bind the key to a value computed by a Provider.

\*

<b>Signature:</b>

```typescript
toProvider(providerClass: Constructor<Provider<T>>): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  providerClass | <code>Constructor&lt;Provider&lt;T&gt;&gt;</code> |  |

<b>Returns:</b>

`this`

## Example


```ts
export class DateProvider implements Provider<Date> {
  constructor(@inject('stringDate') private param: String){}
  value(): Date {
    return new Date(param);
  }
}

```


