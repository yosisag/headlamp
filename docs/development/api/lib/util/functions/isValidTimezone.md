# Function: isValidTimezone()

```ts
function isValidTimezone(tz: string): boolean;
```

Defined in: [lib/util.ts:214](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/util.ts#L214)

Returns true when tz is a valid IANA timezone string accepted by the
Intl API. Some Linux systems expose TZ=:/etc/localtime which Chrome
resolves to "Etc/Unknown" — an identifier that Node accepts but browsers
reject with a RangeError.

## Parameters

| Parameter | Type |
| ------ | ------ |
| `tz` | `string` |

## Returns

`boolean`
