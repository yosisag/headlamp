# Interface: UsableCRDVersion

Defined in: [lib/k8s/crdSpec.ts:52](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L52)

Strongly typed "valid" subset of a usable version entry. `validateCRDSpec`
narrows the array elements to this shape after the served+name filter.

## Properties

### name

```ts
name: string;
```

Defined in: [lib/k8s/crdSpec.ts:53](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L53)

***

### served

```ts
served: true;
```

Defined in: [lib/k8s/crdSpec.ts:54](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L54)

***

### storage?

```ts
optional storage?: boolean;
```

Defined in: [lib/k8s/crdSpec.ts:55](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/crdSpec.ts#L55)
