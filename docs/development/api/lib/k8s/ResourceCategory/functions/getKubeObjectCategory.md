# Function: getKubeObjectCategory()

```ts
function getKubeObjectCategory(resource: KubeObject): ResourceCategory;
```

Defined in: [lib/k8s/ResourceCategory.tsx:98](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/ResourceCategory.tsx#L98)

Get category of the given kubernetes object

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `resource` | [`KubeObject`](../../KubeObject/classes/KubeObject.md) | Kubernetes object |

## Returns

[`ResourceCategory`](../interfaces/ResourceCategory.md)

resource category
