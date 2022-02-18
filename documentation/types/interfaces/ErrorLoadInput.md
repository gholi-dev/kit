[Chart.js - v1.0.0-next.278](../README.md) / ErrorLoadInput

# Interface: ErrorLoadInput<Params\>

## Type parameters

| Name | Type |
| :------ | :------ |
| `Params` | `Record`<`string`, `string`\> |

## Hierarchy

- [`LoadInput`](LoadInput.md)<`Params`\>

  ↳ **`ErrorLoadInput`**

## Table of contents

### Properties

- [error](ErrorLoadInput.md#error)
- [params](ErrorLoadInput.md#params)
- [props](ErrorLoadInput.md#props)
- [session](ErrorLoadInput.md#session)
- [status](ErrorLoadInput.md#status)
- [stuff](ErrorLoadInput.md#stuff)
- [url](ErrorLoadInput.md#url)

### Methods

- [fetch](ErrorLoadInput.md#fetch)

## Properties

### error

• `Optional` **error**: `Error`

#### Defined in

[page.d.ts:15](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L15)

___

### params

• **params**: `Params`

#### Inherited from

[LoadInput](LoadInput.md).[params](LoadInput.md#params)

#### Defined in

[page.d.ts:6](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L6)

___

### props

• **props**: `Record`<`string`, `any`\>

#### Inherited from

[LoadInput](LoadInput.md).[props](LoadInput.md#props)

#### Defined in

[page.d.ts:7](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L7)

___

### session

• **session**: `Session`

#### Inherited from

[LoadInput](LoadInput.md).[session](LoadInput.md#session)

#### Defined in

[page.d.ts:9](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L9)

___

### status

• `Optional` **status**: `number`

#### Defined in

[page.d.ts:14](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L14)

___

### stuff

• **stuff**: `Partial`<`Stuff`\>

#### Inherited from

[LoadInput](LoadInput.md).[stuff](LoadInput.md#stuff)

#### Defined in

[page.d.ts:10](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L10)

___

### url

• **url**: `URL`

#### Inherited from

[LoadInput](LoadInput.md).[url](LoadInput.md#url)

#### Defined in

[page.d.ts:5](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L5)

## Methods

### fetch

▸ **fetch**(`info`, `init?`): `Promise`<`Response`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `info` | `RequestInfo` |
| `init?` | `RequestInit` |

#### Returns

`Promise`<`Response`\>

#### Inherited from

[LoadInput](LoadInput.md).[fetch](LoadInput.md#fetch)

#### Defined in

[page.d.ts:8](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L8)
