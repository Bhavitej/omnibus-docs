# Class: AddToWishListError

[models](../wiki/models).AddToWishListError

Describes the Add to wish list API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`AddToWishListErrorErrorCode`](../wiki/models.AddToWishListErrorErrorCode)\>

  ↳ **`AddToWishListError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.AddToWishListError#constructor)

### Properties

- [data](../wiki/models.AddToWishListError#data)
- [err](../wiki/models.AddToWishListError#err)
- [errorCode](../wiki/models.AddToWishListError#errorcode)
- [errorDetail](../wiki/models.AddToWishListError#errordetail)
- [status](../wiki/models.AddToWishListError#status)

## Constructors

### constructor

• **new AddToWishListError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/detail.ts:274](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L274)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/detail.ts:272](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L272)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.AddToWishListErrorErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/detail.ts:276](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L276)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/detail.ts:275](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L275)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/detail.ts:273](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L273)
