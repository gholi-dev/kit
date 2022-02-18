[Chart.js - v1.0.0-next.278](../README.md) / Config

# Interface: Config

## Table of contents

### Properties

- [compilerOptions](Config.md#compileroptions)
- [extensions](Config.md#extensions)
- [kit](Config.md#kit)
- [preprocess](Config.md#preprocess)

## Properties

### compilerOptions

• `Optional` **compilerOptions**: `CompileOptions`

#### Defined in

[config.d.ts:140](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L140)

___

### extensions

• `Optional` **extensions**: `string`[]

#### Defined in

[config.d.ts:141](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L141)

___

### kit

• `Optional` **kit**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `adapter?` | [`Adapter`](Adapter.md) |
| `amp?` | `boolean` |
| `appDir?` | `string` |
| `browser?` | { `hydrate?`: `boolean` ; `router?`: `boolean`  } |
| `browser.hydrate?` | `boolean` |
| `browser.router?` | `boolean` |
| `csp?` | { `directives?`: `CspDirectives` ; `mode?`: ``"hash"`` \| ``"nonce"`` \| ``"auto"``  } |
| `csp.directives?` | `CspDirectives` |
| `csp.mode?` | ``"hash"`` \| ``"nonce"`` \| ``"auto"`` |
| `files?` | { `assets?`: `string` ; `hooks?`: `string` ; `lib?`: `string` ; `routes?`: `string` ; `serviceWorker?`: `string` ; `template?`: `string`  } |
| `files.assets?` | `string` |
| `files.hooks?` | `string` |
| `files.lib?` | `string` |
| `files.routes?` | `string` |
| `files.serviceWorker?` | `string` |
| `files.template?` | `string` |
| `floc?` | `boolean` |
| `inlineStyleThreshold?` | `number` |
| `methodOverride?` | { `allowed?`: `string`[] ; `parameter?`: `string`  } |
| `methodOverride.allowed?` | `string`[] |
| `methodOverride.parameter?` | `string` |
| `package?` | { `dir?`: `string` ; `emitTypes?`: `boolean` ; `exports?`: (`filepath`: `string`) => `boolean` ; `files?`: (`filepath`: `string`) => `boolean`  } |
| `package.dir?` | `string` |
| `package.emitTypes?` | `boolean` |
| `package.exports?` | [object Object] |
| `package.files?` | [object Object] |
| `paths?` | { `assets?`: `string` ; `base?`: `string`  } |
| `paths.assets?` | `string` |
| `paths.base?` | `string` |
| `prerender?` | { `concurrency?`: `number` ; `crawl?`: `boolean` ; `enabled?`: `boolean` ; `entries?`: `string`[] ; `onError?`: `PrerenderOnErrorValue`  } |
| `prerender.concurrency?` | `number` |
| `prerender.crawl?` | `boolean` |
| `prerender.enabled?` | `boolean` |
| `prerender.entries?` | `string`[] |
| `prerender.onError?` | `PrerenderOnErrorValue` |
| `serviceWorker?` | { `register?`: `boolean` ; `files?`: (`filepath`: `string`) => `boolean`  } |
| `serviceWorker.register?` | `boolean` |
| `serviceWorker.files?` | [object Object] |
| `trailingSlash?` | `TrailingSlash` |
| `version?` | { `name?`: `string` ; `pollInterval?`: `number`  } |
| `version.name?` | `string` |
| `version.pollInterval?` | `number` |
| `vite?` | `UserConfig` \| () => `MaybePromise`<`UserConfig`\> |
| `routes?` | (`filepath`: `string`) => `boolean` |

#### Defined in

[config.d.ts:142](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L142)

___

### preprocess

• `Optional` **preprocess**: `any`

#### Defined in

[config.d.ts:197](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/config.d.ts#L197)
