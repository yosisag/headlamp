# Interface: RetryConstraint

Defined in: [lib/k8s/backendTrafficPolicy.ts:57](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/backendTrafficPolicy.ts#L57)

RetryConstraint dynamically constrains client‑side retries using a
percentage‑based budget and a safety‑net minimum rate.

## Properties

### budget?

```ts
optional budget?: BudgetDetails;
```

Defined in: [lib/k8s/backendTrafficPolicy.ts:58](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/backendTrafficPolicy.ts#L58)

***

### minRetryRate?

```ts
optional minRetryRate?: RequestRate;
```

Defined in: [lib/k8s/backendTrafficPolicy.ts:59](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/backendTrafficPolicy.ts#L59)
