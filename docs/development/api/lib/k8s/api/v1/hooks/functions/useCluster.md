# Function: useCluster()

```ts
function useCluster(): string | null;
```

Defined in: [lib/k8s/api/v1/hooks.ts:35](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/hooks.ts#L35)

Get the currently selected cluster name.

If more than one cluster is selected it will return:
 - On details pages: the cluster of the currently viewed resource
 - On any other page: one of the selected clusters

To get all currently selected clusters please use [useSelectedClusters](useSelectedClusters.md)

## Returns

`string` \| `null`

currently selected cluster
