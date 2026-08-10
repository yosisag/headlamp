# Function: registerSetTokenFunction()

```ts
function registerSetTokenFunction(override: (cluster: string, token: string | null) => void): void;
```

Defined in: [plugin/registry.tsx:713](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L713)

Override headlamp setToken method

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `override` | (`cluster`: `string`, `token`: `string` \| `null`) => `void` | The setToken override method to use. |

## Returns

`void`

## Example

```ts
registerSetTokenFunction((cluster: string, token: string | null) => {
// set token logic here
});
```
