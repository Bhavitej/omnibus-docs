# Class: MockRemoveFromWishlistRequestConfig

[models](../wiki/models).MockRemoveFromWishlistRequestConfig

Describes the Mock remove from wishlist request SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockRemoveFromWishlistRequestParams`](../wiki/models.MockRemoveFromWishlistRequestParams), [`RemoveFromWishlistRequestErrorCode`](../wiki/models.RemoveFromWishlistRequestErrorCode)\>

  ↳ **`MockRemoveFromWishlistRequestConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockRemoveFromWishlistRequestConfig#constructor)

### Properties

- [err](../wiki/models.MockRemoveFromWishlistRequestConfig#err)
- [errorCode](../wiki/models.MockRemoveFromWishlistRequestConfig#errorcode)
- [params](../wiki/models.MockRemoveFromWishlistRequestConfig#params)

## Constructors

### constructor

• **new MockRemoveFromWishlistRequestConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/wishlist.ts:35](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L35)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.RemoveFromWishlistRequestErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/wishlist.ts:36](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L36)

___

### params

• `Optional` **params**: [`MockRemoveFromWishlistRequestParams`](../wiki/models.MockRemoveFromWishlistRequestParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/wishlist.ts:37](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/wishlist.ts#L37)
