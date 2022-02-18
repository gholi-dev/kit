[Chart.js - v1.0.0-next.278](../README.md) / PrerenderErrorHandler

# Interface: PrerenderErrorHandler

## Callable

### PrerenderErrorHandler

▸ **PrerenderErrorHandler**(`details`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `details` | `Object` |
| `details.path` | `string` |
| `details.referenceType` | ``"linked"`` \| ``"fetched"`` |
| `details.referrer` | ``null`` \| `string` |
| `details.status` | `number` |

#### Returns

`void`

#### Defined in

[config.d.ts:129](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L129)
