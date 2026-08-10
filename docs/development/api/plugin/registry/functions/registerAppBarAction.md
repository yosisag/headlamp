# Function: registerAppBarAction()

```ts
function registerAppBarAction(headerAction: 
  | AppBarAction
  | AppBarActionsProcessor
  | AppBarActionProcessorType
  | AppBarActionType): void;
```

Defined in: [plugin/registry.tsx:574](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L574)

Add a component into the app bar (at the top of the app).

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `headerAction` | \| `AppBarAction` \| `AppBarActionsProcessor` \| [`AppBarActionProcessorType`](../type-aliases/AppBarActionProcessorType.md) \| `AppBarActionType` | The action (link) to put in the app bar. |

## Returns

`void`

## Example

```tsx
import { registerAppBarAction } from '@kinvolk/headlamp-plugin/lib';
import { Button } from '@mui/material';

function ConsoleLogger() {
  return (
    <Button
      onClick={() => {
        console.log('Hello from ConsoleLogger!')
      }}
    >
      Print Log
    </Button>
  );
}

registerAppBarAction(ConsoleLogger);
```
