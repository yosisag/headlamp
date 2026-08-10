# Function: useErrorState()

```ts
function useErrorState(dependentSetter?: (...args: any) => void): readonly [ApiError | null, Dispatch<SetStateAction<ApiError | null>>];
```

Defined in: [lib/util.ts:334](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/util.ts#L334)

## Parameters

| Parameter | Type |
| ------ | ------ |
| `dependentSetter?` | (...`args`: `any`) => `void` |

## Returns

readonly \[[`ApiError`](../../k8s/api/v2/ApiError/classes/ApiError.md) \| `null`, `Dispatch`\<`SetStateAction`\<[`ApiError`](../../k8s/api/v2/ApiError/classes/ApiError.md) \| `null`\>\>\]
