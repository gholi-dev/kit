[Chart.js - v1.0.0-next.278](../README.md) / SSRManifest

# Interface: SSRManifest

## Table of contents

### Properties

- [\_](SSRManifest.md#_)
- [appDir](SSRManifest.md#appdir)
- [assets](SSRManifest.md#assets)

## Properties

### \_

• **\_**: `Object`

private fields

#### Type declaration

| Name | Type |
| :------ | :------ |
| `entry` | { `css`: `string`[] ; `file`: `string` ; `js`: `string`[]  } |
| `entry.css` | `string`[] |
| `entry.file` | `string` |
| `entry.js` | `string`[] |
| `mime` | `Record`<`string`, `string`\> |
| `nodes` | `SSRNodeLoader`[] |
| `routes` | `SSRRoute`[] |

#### Defined in

[app.d.ts:25](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/app.d.ts#L25)

___

### appDir

• **appDir**: `string`

#### Defined in

[app.d.ts:22](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/app.d.ts#L22)

___

### assets

• **assets**: `Set`<`string`\>

#### Defined in

[app.d.ts:23](https://github.com/sveltejs/kit/blob/f766a54d/packages/kit/types/app.d.ts#L23)
