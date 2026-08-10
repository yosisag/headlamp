# Type Alias: WorkloadClass

```ts
type WorkloadClass = 
  | typeof Pod
  | typeof DaemonSet
  | typeof ReplicaSet
  | typeof StatefulSet
  | typeof Job
  | typeof CronJob
  | typeof Deployment
  | typeof JobSet
  | typeof LeaderWorkerSet;
```

Defined in: [lib/k8s/Workload.ts:45](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/Workload.ts#L45)
