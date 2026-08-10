# Function: asQuery()

```ts
function asQuery(queryParams?: QueryParameters): string;
```

Defined in: [lib/k8s/api/v1/formatUrl.ts:51](https://github.com/Rucha0901/headlamp/blob/f19a5d7375f3a4adafc52bb2b8999455ae4eeca5/frontend/src/lib/k8s/api/v1/formatUrl.ts#L51)

Converts k8s queryParams to a URL query string.

## Parameters

| Parameter | Type | Description |
| ------ | ------ | ------ |
| `queryParams?` | [`QueryParameters`](../../queryParameters/interfaces/QueryParameters.md) | The k8s API query parameters to convert. |

## Returns

`string`

The query string (starting with '?'), or empty string.
