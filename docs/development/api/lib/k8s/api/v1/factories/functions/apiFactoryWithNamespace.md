# Function: apiFactoryWithNamespace()

```ts
function apiFactoryWithNamespace<T>(...args: ApiFactoryWithNamespaceArguments): ApiWithNamespaceClient<T>;
```

Defined in: [lib/k8s/api/v1/factories.ts:408](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/factories.ts#L408)

## Type Parameters

| Type Parameter |
| ------ |
| `T` *extends* [`KubeObjectInterface`](../../../../KubeObject/interfaces/KubeObjectInterface.md) |

## Parameters

| Parameter | Type |
| ------ | ------ |
| ...`args` | [`ApiFactoryWithNamespaceArguments`](../type-aliases/ApiFactoryWithNamespaceArguments.md) |

## Returns

[`ApiWithNamespaceClient`](../interfaces/ApiWithNamespaceClient.md)\<`T`\>
