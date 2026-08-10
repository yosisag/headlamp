# Function: getClusterAuthType()

```ts
function getClusterAuthType(cluster: string): string;
```

Defined in: [lib/k8s/api/v1/clusterRequests.ts:76](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/clusterRequests.ts#L76)

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `cluster` | `string` | Name of the cluster. |

## Returns

`string`

Auth type of the cluster, or an empty string if the cluster is not found.
It could return 'oidc' or '' for example.
