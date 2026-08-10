# Type Alias: ConditionLike

```ts
type ConditionLike = Pick<KubeCondition, "type" | "status">;
```

Defined in: [lib/k8s/conditions.ts:24](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/conditions.ts#L24)

The part of a status condition these helpers rely on. Kept structural so it
accepts both [KubeCondition](../../cluster/interfaces/KubeCondition.md) and the looser condition types custom
resources declare for themselves.
