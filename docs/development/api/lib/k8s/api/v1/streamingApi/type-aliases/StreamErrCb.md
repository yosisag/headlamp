# Type Alias: StreamErrCb

```ts
type StreamErrCb = (err: Error & object, cancelStreamFunc?: () => void) => void;
```

Defined in: [lib/k8s/api/v1/streamingApi.ts:43](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/streamingApi.ts#L43)

## Parameters

| Parameter | Type |
| ------ | ------ |
| `err` | `Error` & `object` |
| `cancelStreamFunc?` | () => `void` |

## Returns

`void`
