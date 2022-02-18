[Chart.js - v1.0.0-next.278](../README.md) / RequestHandler

# Interface: RequestHandler<Output\>

## Type parameters

| Name | Type |
| :------ | :------ |
| `Output` | extends `Body` = `Body` |

## Callable

### RequestHandler

▸ **RequestHandler**(`event`): `MaybePromise`<`Either`<`Output` extends `Response` ? `Response` : [`EndpointOutput`](EndpointOutput.md)<`Output`\>, `Fallthrough`\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | [`RequestEvent`](RequestEvent.md) |

#### Returns

`MaybePromise`<`Either`<`Output` extends `Response` ? `Response` : [`EndpointOutput`](EndpointOutput.md)<`Output`\>, `Fallthrough`\>\>

#### Defined in

[endpoint.d.ts:17](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/endpoint.d.ts#L17)
