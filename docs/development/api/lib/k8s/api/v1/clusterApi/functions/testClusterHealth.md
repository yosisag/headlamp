# Function: testClusterHealth()

```ts
function testClusterHealth(cluster?: string): Promise<any[]>;
```

Defined in: [lib/k8s/api/v1/clusterApi.ts:125](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/clusterApi.ts#L125)

Checks cluster health
Will throw an error if the cluster is not healthy.

## Parameters

| Parameter | Type |
| ------ | ------ |
| `cluster?` | `string` |

## Returns

`Promise`\<`any`[]\>
