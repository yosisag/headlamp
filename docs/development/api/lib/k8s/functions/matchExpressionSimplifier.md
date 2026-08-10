# Function: matchExpressionSimplifier()

```ts
function matchExpressionSimplifier(matchExpressions: object[] | undefined): "" | string[];
```

Defined in: [lib/k8s/index.ts:205](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/index.ts#L205)

Simplifies a matchExpressions array into an array of string representations.

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `matchExpressions` | `object`[] \| `undefined` | the matchExpressionss array from a LabelSelector. |

## Returns

`""` \| `string`[]

an array of simplified expression strings, or an empty string.
