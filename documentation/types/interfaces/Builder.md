[Chart.js - v1.0.0-next.278](../README.md) / Builder

# Interface: Builder

## Table of contents

### Properties

- [appDir](Builder.md#appdir)
- [log](Builder.md#log)
- [trailingSlash](Builder.md#trailingslash)

### Methods

- [copy](Builder.md#copy)
- [createEntries](Builder.md#createentries)
- [generateManifest](Builder.md#generatemanifest)
- [getBuildDirectory](Builder.md#getbuilddirectory)
- [getClientDirectory](Builder.md#getclientdirectory)
- [getServerDirectory](Builder.md#getserverdirectory)
- [getStaticDirectory](Builder.md#getstaticdirectory)
- [mkdirp](Builder.md#mkdirp)
- [prerender](Builder.md#prerender)
- [rimraf](Builder.md#rimraf)
- [writeClient](Builder.md#writeclient)
- [writeServer](Builder.md#writeserver)
- [writeStatic](Builder.md#writestatic)

## Properties

### appDir

• **appDir**: `string`

#### Defined in

[config.d.ts:69](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L69)

___

### log

• **log**: `Logger`

#### Defined in

[config.d.ts:65](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L65)

___

### trailingSlash

• **trailingSlash**: ``"always"`` \| ``"never"`` \| ``"ignore"``

#### Defined in

[config.d.ts:70](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L70)

## Methods

### copy

▸ **copy**(`from`, `to`, `opts?`): `string`[]

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `from` | `string` | the source file or folder |
| `to` | `string` | the destination file or folder |
| `opts?` | `Object` | - |
| `opts.replace?` | `Record`<`string`, `string`\> | a map of strings to replace |
| `opts.filter?` | (`basename`: `string`) => `boolean` | - |

#### Returns

`string`[]

an array of paths corresponding to the files that have been created by the copy

#### Defined in

[config.d.ts:107](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L107)

___

### createEntries

▸ **createEntries**(`fn`): `void`

Create entry points that map to individual functions

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `fn` | (`route`: `RouteDefinition`) => `AdapterEntry` | A function that groups a set of routes into an entry point |

#### Returns

`void`

#### Defined in

[config.d.ts:76](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L76)

___

### generateManifest

▸ **generateManifest**(`opts`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `opts` | `Object` |
| `opts.format?` | ``"esm"`` \| ``"cjs"`` |
| `opts.relativePath` | `string` |

#### Returns

`string`

#### Defined in

[config.d.ts:78](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L78)

___

### getBuildDirectory

▸ **getBuildDirectory**(`name`): `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`string`

#### Defined in

[config.d.ts:80](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L80)

___

### getClientDirectory

▸ **getClientDirectory**(): `string`

#### Returns

`string`

#### Defined in

[config.d.ts:81](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L81)

___

### getServerDirectory

▸ **getServerDirectory**(): `string`

#### Returns

`string`

#### Defined in

[config.d.ts:82](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L82)

___

### getStaticDirectory

▸ **getStaticDirectory**(): `string`

#### Returns

`string`

#### Defined in

[config.d.ts:83](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L83)

___

### mkdirp

▸ **mkdirp**(`dir`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `dir` | `string` |

#### Returns

`void`

#### Defined in

[config.d.ts:67](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L67)

___

### prerender

▸ **prerender**(`options`): `Promise`<[`Prerendered`](Prerendered.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `options` | `Object` |
| `options.all?` | `boolean` |
| `options.dest` | `string` |
| `options.fallback?` | `string` |

#### Returns

`Promise`<[`Prerendered`](Prerendered.md)\>

#### Defined in

[config.d.ts:116](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L116)

___

### rimraf

▸ **rimraf**(`dir`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `dir` | `string` |

#### Returns

`void`

#### Defined in

[config.d.ts:66](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L66)

___

### writeClient

▸ **writeClient**(`dest`): `string`[]

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `dest` | `string` | the destination folder to which files should be copied |

#### Returns

`string`[]

an array of paths corresponding to the files that have been created by the copy

#### Defined in

[config.d.ts:89](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L89)

___

### writeServer

▸ **writeServer**(`dest`): `string`[]

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `dest` | `string` | the destination folder to which files should be copied |

#### Returns

`string`[]

an array of paths corresponding to the files that have been created by the copy

#### Defined in

[config.d.ts:94](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L94)

___

### writeStatic

▸ **writeStatic**(`dest`): `string`[]

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `dest` | `string` | the destination folder to which files should be copied |

#### Returns

`string`[]

an array of paths corresponding to the files that have been created by the copy

#### Defined in

[config.d.ts:99](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L99)
