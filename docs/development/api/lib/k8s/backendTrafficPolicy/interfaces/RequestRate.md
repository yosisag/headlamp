# Interface: RequestRate

Defined in: [lib/k8s/backendTrafficPolicy.ts:46](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/backendTrafficPolicy.ts#L46)

RequestRate expresses “X requests per Y time‑interval”.

## Properties

### count?

```ts
optional count?: number;
```

Defined in: [lib/k8s/backendTrafficPolicy.ts:48](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/backendTrafficPolicy.ts#L48)

Number of requests allowed within the interval.

***

### interval?

```ts
optional interval?: string;
```

Defined in: [lib/k8s/backendTrafficPolicy.ts:50](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/backendTrafficPolicy.ts#L50)

Duration string (e.g. "1s") that forms the divisor of the rate.
