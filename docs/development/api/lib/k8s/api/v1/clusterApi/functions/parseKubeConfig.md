# Function: parseKubeConfig()

```ts
function parseKubeConfig(clusterReq: ClusterRequest): Promise<any>;
```

Defined in: [lib/k8s/api/v1/clusterApi.ts:313](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/clusterApi.ts#L313)

parseKubeConfig sends a kubeconfig to the backend to parse and returns
the resulting clusters.

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `clusterReq` | [`ClusterRequest`](../../clusterRequests/interfaces/ClusterRequest.md) | The cluster request object. |

## Returns

`Promise`\<`any`\>
