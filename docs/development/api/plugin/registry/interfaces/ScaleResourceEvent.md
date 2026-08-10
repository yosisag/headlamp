# Interface: ScaleResourceEvent

Defined in: [redux/headlampEventSlice.ts:147](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/redux/headlampEventSlice.ts#L147)

Event fired when scaling a resource.

## Properties

### data

```ts
data: object;
```

Defined in: [redux/headlampEventSlice.ts:149](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/redux/headlampEventSlice.ts#L149)

#### resource

```ts
resource: KubeObject;
```

The resource for which the deletion was called.

#### status

```ts
status: CONFIRMED;
```

What exactly this event represents. 'CONFIRMED' when the scaling is selected by the user.
For now only 'CONFIRMED' is sent.

***

### type

```ts
type: SCALE_RESOURCE;
```

Defined in: [redux/headlampEventSlice.ts:148](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/redux/headlampEventSlice.ts#L148)
