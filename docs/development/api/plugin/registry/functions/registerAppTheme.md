# Function: registerAppTheme()

```ts
function registerAppTheme(theme: AppTheme): void;
```

Defined in: [plugin/registry.tsx:1040](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L1040)

Add a new theme that will be available in the settings.
Theme name should be unique

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `theme` | [`AppTheme`](../../../lib/AppTheme/interfaces/AppTheme.md) | App Theme definition |

## Returns

`void`

## Example

```ts
registerAppTheme({
  name: "My Custom Theme",
  base: "light",
  primary: "#ff0000",
  secondary: "#333",
})
