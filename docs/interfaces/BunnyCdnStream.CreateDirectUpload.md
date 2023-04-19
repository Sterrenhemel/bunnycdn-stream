[bunnycdn-stream-s](../README.md) / [Exports](../modules.md) / [BunnyCdnStream](../modules/BunnyCdnStream.md) / CreateDirectUpload

# Interface: CreateDirectUpload

[BunnyCdnStream](../modules/BunnyCdnStream.md).CreateDirectUpload

## Table of contents

### Properties

- [endpoint](BunnyCdnStream.CreateDirectUpload.md#endpoint)
- [headers](BunnyCdnStream.CreateDirectUpload.md#headers)
- [metadata](BunnyCdnStream.CreateDirectUpload.md#metadata)
- [video](BunnyCdnStream.CreateDirectUpload.md#video)

## Properties

### endpoint

• **endpoint**: `string`

#### Defined in

[src/index.ts:782](https://github.com/Sterrenhemel/bunnycdn-stream/blob/2954655/src/index.ts#L782)

___

### headers

• **headers**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `AuthorizationExpire` | `number` |
| `AuthorizationSignature` | `string` |
| `LibraryId` | `string` |
| `VideoId` | `string` |

#### Defined in

[src/index.ts:783](https://github.com/Sterrenhemel/bunnycdn-stream/blob/2954655/src/index.ts#L783)

___

### metadata

• **metadata**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `collection` | `undefined` \| `string` |
| `filetype` | `string` |
| `title` | `string` |

#### Defined in

[src/index.ts:789](https://github.com/Sterrenhemel/bunnycdn-stream/blob/2954655/src/index.ts#L789)

___

### video

• **video**: [`BunnyCdnStreamVideo`](../classes/BunnyCdnStreamVideo.md)

#### Defined in

[src/index.ts:781](https://github.com/Sterrenhemel/bunnycdn-stream/blob/2954655/src/index.ts#L781)
