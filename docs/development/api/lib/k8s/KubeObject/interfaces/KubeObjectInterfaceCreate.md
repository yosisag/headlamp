# Interface: KubeObjectInterfaceCreate

Defined in: [lib/k8s/KubeObject.ts:805](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/KubeObject.ts#L805)

KubeObjectInterfaceCreate is a version of KubeObjectInterface for creating objects
where uid, creationTimestamp, etc. are optional

## Extends

- `Omit`\<[`KubeObjectInterface`](KubeObjectInterface.md), `"metadata"`\>

## Indexable

```ts
[key: string]: any
```

```ts
[key: number]: any
```

## Properties

### metadata

```ts
metadata: KubeMetadataCreate;
```

Defined in: [lib/k8s/KubeObject.ts:806](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/KubeObject.ts#L806)
