[Chart.js - v1.0.0-next.278](../README.md) / Handle

# Interface: Handle

## Callable

### Handle

▸ **Handle**(`input`): `MaybePromise`<`Response`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `input` | `Object` |
| `input.event` | [`RequestEvent`](RequestEvent.md) |
| `input.resolve` | (`event`: [`RequestEvent`](RequestEvent.md), `opts?`: `Partial`<`RequiredResolveOptions`\>) => `MaybePromise`<`Response`\> |

#### Returns

`MaybePromise`<`Response`\>

#### Defined in

[hooks.d.ts:25](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/hooks.d.ts#L25)
