# Interface: CRDApiGroupSource

Defined in: [lib/k8s/crdSpec.ts:190](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L190)

Duck-typed surface a CRD instance might expose. New in-tree code has both
methods; older plugin bundles only ship `getMainAPIGroup()`.

## Properties

### getMainAPIGroup?

```ts
optional getMainAPIGroup?: () => [string, string, string] | null | undefined;
```

Defined in: [lib/k8s/crdSpec.ts:192](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L192)

#### Returns

\[`string`, `string`, `string`\] \| `null` \| `undefined`

***

### getMainAPIGroupOrNull?

```ts
optional getMainAPIGroupOrNull?: () => [string, string, string] | null;
```

Defined in: [lib/k8s/crdSpec.ts:191](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L191)

#### Returns

\[`string`, `string`, `string`\] \| `null`
