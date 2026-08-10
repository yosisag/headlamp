# Function: registerRouteFilter()

```ts
function registerRouteFilter(filterFunc: (entry: Route) => Route | null): void;
```

Defined in: [plugin/registry.tsx:420](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L420)

Filter or modify routes.

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `filterFunc` | (`entry`: `Route`) => `Route` \| `null` | a function for filtering or modifying routes. Return null to remove the route, or the (optionally modified) route to keep it. |

## Returns

`void`

## Example

```tsx
import { registerRouteFilter } from '@kinvolk/headlamp-plugin/lib';

registerRouteFilter(route => (route.path === '/workloads' ? null : route));
```
