# Function: registerMapSource()

```ts
function registerMapSource(source: GraphSource): void;
```

Defined in: [plugin/registry.tsx:857](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L857)

Registers a new graph source in the store.

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `source` | [`GraphSource`](../type-aliases/GraphSource.md) | The graph source to be registered. |

## Returns

`void`

## Example

```tsx
const mySource = {
  id: 'my-source',
  label: 'Sample source',
  useData() {
    return {
      nodes: [{ id: 'my-node', type: 'kubeObject', data: { resource: myCustomResource } }],
      edges: []
    };
  }
}

registerMapSource(mySource);
```
