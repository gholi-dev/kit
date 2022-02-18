[Chart.js - v1.0.0-next.278](../README.md) / LoadInput

# Interface: LoadInput<Params\>

## Type parameters

| Name | Type |
| :------ | :------ |
| `Params` | `Record`<`string`, `string`\> |

## Hierarchy

- **`LoadInput`**

  ↳ [`ErrorLoadInput`](ErrorLoadInput.md)

## Table of contents

### Properties

- [params](LoadInput.md#params)
- [props](LoadInput.md#props)
- [session](LoadInput.md#session)
- [stuff](LoadInput.md#stuff)
- [url](LoadInput.md#url)

### Methods

- [fetch](LoadInput.md#fetch)

## Properties

### params

• **params**: `Params`

#### Defined in

[page.d.ts:6](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L6)

___

### props

• **props**: `Record`<`string`, `any`\>

#### Defined in

[page.d.ts:7](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L7)

___

### session

• **session**: `Session`

#### Defined in

[page.d.ts:9](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L9)

___

### stuff

• **stuff**: `Partial`<`Stuff`\>

#### Defined in

[page.d.ts:10](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L10)

___

### url

• **url**: `URL`

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

#### Defined in

[page.d.ts:8](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/page.d.ts#L8)
