# Function: singleApiFactory()

```ts
function singleApiFactory<T>(...group: SingleApiFactoryArguments): ApiClient<T>;
```

Defined in: [lib/k8s/api/v1/factories.ts:368](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/factories.ts#L368)

## Type Parameters

| Type Parameter |
| ------ |
| `T` *extends* [`KubeObjectInterface`](../../../../KubeObject/interfaces/KubeObjectInterface.md) |

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| ...`group` | [`SingleApiFactoryArguments`](../type-aliases/SingleApiFactoryArguments.md) | The API group. |

## Returns

[`ApiClient`](../interfaces/ApiClient.md)\<`T`\>

An object with methods for interacting with a single API endpoint.
