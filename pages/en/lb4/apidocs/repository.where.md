---
lang: en
title: 'API docs: repository.where'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.where.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [Where](./repository.where.md)

## Where type

Where clause

<b>Signature:</b>

```typescript
export declare type Where<MT extends object = AnyObject> = Condition<MT> | AndClause<MT> | OrClause<MT>;
```

## Example


```ts
{
  name: {inq: ['John', 'Mary']},
  status: 'ACTIVE'
  and: [...],
  or: [...],
}

```


