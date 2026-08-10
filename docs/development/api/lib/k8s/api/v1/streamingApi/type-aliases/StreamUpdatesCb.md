# Type Alias: StreamUpdatesCb\<T\>

```ts
type StreamUpdatesCb<T> = (data: T | StreamUpdate<T>) => void;
```

Defined in: [lib/k8s/api/v1/streamingApi.ts:42](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/streamingApi.ts#L42)

## Type Parameters

| Type Parameter | Default type |
| ------ | ------ |
| `T` | `any` |

## Parameters

| Parameter | Type |
| ------ | ------ |
| `data` | `T` \| [`StreamUpdate`](StreamUpdate.md)\<`T`\> |

## Returns

`void`
