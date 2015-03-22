# `Array.prototype.groupBy`

## Status

WIP strawman proposal.

## Summary

[WIP]

**Example:**

```js
[1, 2, 3, 4].groupBy(n => n % 2 ? 'odd' : 'even')
// { 'odd': [1, 3], 'even': [2, 4] }
```

## Motivation

[WIP]

## Design

**Syntax**

```ts
Array.prototype.groupBy(callbackFn: function, thisArg?: any): object
```

**Description**

[WIP]

## Polyfill

[WIP]
