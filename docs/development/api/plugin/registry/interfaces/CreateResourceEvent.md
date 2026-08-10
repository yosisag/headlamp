# Interface: CreateResourceEvent

Defined in: [redux/headlampEventSlice.ts:268](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/redux/headlampEventSlice.ts#L268)

Event fired when creating a resource.

## Properties

### data

```ts
data: object;
```

Defined in: [redux/headlampEventSlice.ts:270](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/redux/headlampEventSlice.ts#L270)

#### status

```ts
status: CONFIRMED;
```

What exactly this event represents. 'CONFIRMED' when the user chooses to apply the new resource.
For now only 'CONFIRMED' is sent.

***

### type

```ts
type: CREATE_RESOURCE;
```

Defined in: [redux/headlampEventSlice.ts:269](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/redux/headlampEventSlice.ts#L269)
