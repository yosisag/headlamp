# Function: combineClusterListErrors()

```ts
function combineClusterListErrors(...args: (
  | {
[cluster: string]: ApiError | null;
}
  | null)[]): 
  | {
[cluster: string]: ApiError | null;
}
  | null;
```

Defined in: [lib/util.ts:372](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/util.ts#L372)

Combines errors per cluster.

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| ...`args` | ( \| \{ \[`cluster`: `string`\]: [`ApiError`](../../k8s/api/v2/ApiError/classes/ApiError.md) \| `null`; \} \| `null`)[] | The list of errors per cluster to join. |

## Returns

  \| \{
\[`cluster`: `string`\]: [`ApiError`](../../k8s/api/v2/ApiError/classes/ApiError.md) \| `null`;
\}
  \| `null`

The joint list of errors, or null if there are no errors.
