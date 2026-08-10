# Function: post()

```ts
function post(
   url: string, 
   json: 
  | object
  | JSON
  | KubeObjectInterface, 
   autoLogoutOnAuthError?: boolean, 
options?: ClusterRequestParams): Promise<any>;
```

Defined in: [lib/k8s/api/v1/clusterRequests.ts:239](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/clusterRequests.ts#L239)

## Parameters

| Parameter | Type | Default value |
| ------ | ------ | ------ |
| `url` | `string` | `undefined` |
| `json` | \| `object` \| `JSON` \| [`KubeObjectInterface`](../../../../KubeObject/interfaces/KubeObjectInterface.md) | `undefined` |
| `autoLogoutOnAuthError` | `boolean` | `true` |
| `options` | [`ClusterRequestParams`](../interfaces/ClusterRequestParams.md) | `{}` |

## Returns

`Promise`\<`any`\>
