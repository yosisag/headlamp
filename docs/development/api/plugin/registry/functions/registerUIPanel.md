# Function: registerUIPanel()

```ts
function registerUIPanel(panel: UIPanel): void;
```

Defined in: [plugin/registry.tsx:1089](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L1089)

Registers a UI panel in the application's UI.

See UIPanel for more details on Panel definition

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `panel` | `UIPanel` | The UI panel configuration object to be registered |

## Returns

`void`

## Example

```tsx
registerUIPanel({
  id: 'my-panel',
  location: 'right'
  component: () => <div style={{ width: '100px', flexShrink: 0 }}>Hello world</div>,
});
```
