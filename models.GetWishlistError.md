# Class: GetWishlistError

[models](../wiki/models).GetWishlistError

Describes the Get Wishlist SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetWishlistErrorCode`](../wiki/models.GetWishlistErrorCode)\>

  ↳ **`GetWishlistError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetWishlistError#constructor)

### Properties

- [data](../wiki/models.GetWishlistError#data)
- [err](../wiki/models.GetWishlistError#err)
- [errorCode](../wiki/models.GetWishlistError#errorcode)
- [errorDetail](../wiki/models.GetWishlistError#errordetail)
- [status](../wiki/models.GetWishlistError#status)

## Constructors

### constructor

• **new GetWishlistError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:297](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L297)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:295](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L295)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetWishlistErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:299](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L299)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:298](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L298)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:296](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L296)
