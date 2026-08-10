# Interface: LabelSelector

Defined in: [lib/k8s/cluster.ts:518](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/cluster.ts#L518)

## Properties

### matchExpressions?

```ts
optional matchExpressions?: object[];
```

Defined in: [lib/k8s/cluster.ts:519](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/cluster.ts#L519)

#### key

```ts
key: string;
```

#### operator

```ts
operator: string;
```

#### values

```ts
values: string[];
```

***

### matchLabels?

```ts
optional matchLabels?: object;
```

Defined in: [lib/k8s/cluster.ts:524](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/cluster.ts#L524)

#### Index Signature

```ts
[key: string]: string
```
