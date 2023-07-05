# Class: RemoveFromWishlistRequestError

[models](../wiki/models).RemoveFromWishlistRequestError

Describes the Remove from wishlist request SDK error code

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`RemoveFromWishlistRequestErrorCode`](../wiki/models.RemoveFromWishlistRequestErrorCode)\>

  ↳ **`RemoveFromWishlistRequestError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.RemoveFromWishlistRequestError#constructor)

### Properties

- [data](../wiki/models.RemoveFromWishlistRequestError#data)
- [err](../wiki/models.RemoveFromWishlistRequestError#err)
- [errorCode](../wiki/models.RemoveFromWishlistRequestError#errorcode)
- [errorDetail](../wiki/models.RemoveFromWishlistRequestError#errordetail)
- [status](../wiki/models.RemoveFromWishlistRequestError#status)

## Constructors

### constructor

• **new RemoveFromWishlistRequestError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/wishlist.ts:47](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L47)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/wishlist.ts:45](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L45)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.RemoveFromWishlistRequestErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/wishlist.ts:49](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L49)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/wishlist.ts:48](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L48)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/wishlist.ts:46](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L46)
