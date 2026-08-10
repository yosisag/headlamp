# Function: useSelectedClusters()

```ts
function useSelectedClusters(): string[];
```

Defined in: [lib/k8s/api/v1/hooks.ts:59](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/hooks.ts#L59)

Get a list of selected clusters. Updates when the cluster changes.

## Returns

`string`[]

list of selected clusters. if no clusters are selected, an empty list is returned.
