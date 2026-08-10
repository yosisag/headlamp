# Function: registerHomeSidebarEntryFilter()

```ts
function registerHomeSidebarEntryFilter(filterFunc: (entry: SidebarEntryProps) => SidebarEntryProps | null): void;
```

Defined in: [plugin/registry.tsx:401](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L401)

Filter HOME sidebar menu items (return null to remove, or return a modified entry to update it).

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `filterFunc` | (`entry`: [`SidebarEntryProps`](../interfaces/SidebarEntryProps.md)) => [`SidebarEntryProps`](../interfaces/SidebarEntryProps.md) \| `null` | a function for filtering or modifying HOME sidebar entries. Return null to remove the entry, or the (optionally modified) entry to keep it. |

## Returns

`void`

## Example

```tsx
import { registerHomeSidebarEntryFilter } from '@kinvolk/headlamp-plugin/lib';

registerHomeSidebarEntryFilter(entry => (entry.name === 'settings' ? null : entry));
```
