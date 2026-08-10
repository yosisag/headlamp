# Function: formatDuration()

```ts
function formatDuration(duration: number, options?: TimeAgoOptions): string;
```

Defined in: [lib/util.ts:196](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/util.ts#L196)

Format a duration in milliseconds using either compact or detailed style.

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `duration` | `number` | Duration in milliseconds. |
| `options` | [`TimeAgoOptions`](../interfaces/TimeAgoOptions.md) | Options object: - format: 'brief' | 'mini' (default: 'brief') - 'brief': single-unit output (e.g. "5s", "12m", "3h", "2d", "2y") - 'mini': multi-unit output (e.g. "2m30s", "1h15m", "2y2d") |

## Returns

`string`

Formatted duration string.
