# Function: registerCustomCreateProject()

```ts
function registerCustomCreateProject(customCreateProject: CustomCreateProject): void;
```

Defined in: [plugin/registry.tsx:1113](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/plugin/registry.tsx#L1113)

Register a new way to create Headlamp 'Projects'

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `customCreateProject` | `CustomCreateProject` | Definition for custom creator |

## Returns

`void`

## Example

```tsx
registerCustomCreateProject({
  id: "custom-create",
  name: "Create Helm Project",
  description: "Create new project from Helm chart",
  Component: ({onBack}) => <div>
    Create project
    <input name="helm-chart-id" />
    <button>Create</button>
    <button onClick={onBack}>Back</button>
  </div>,
})
```
