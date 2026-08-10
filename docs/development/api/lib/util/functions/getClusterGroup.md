# Function: getClusterGroup()

```ts
function getClusterGroup(returnWhenNoClusters?: string[]): string[];
```

Defined in: [lib/cluster.ts:95](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/cluster.ts#L95)

Gets clusters.

## Parameters

| Parameter | Type | Default value | Description |
| ------ | ------ | ------ | ------ |
| `returnWhenNoClusters` | `string`[] | `[]` | return this value when no clusters are found. |

## Returns

`string`[]

the cluster group from the URL.
