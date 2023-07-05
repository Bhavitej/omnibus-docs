# Class: MockAddToWishlistConfig

[models](../wiki/models).MockAddToWishlistConfig

Describes the Mock Add to wishlist SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockAddToWishlistParams`](../wiki/models.MockAddToWishlistParams), [`AddToWishListErrorErrorCode`](../wiki/models.AddToWishListErrorErrorCode)\>

  ↳ **`MockAddToWishlistConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockAddToWishlistConfig#constructor)

### Properties

- [err](../wiki/models.MockAddToWishlistConfig#err)
- [errorCode](../wiki/models.MockAddToWishlistConfig#errorcode)
- [params](../wiki/models.MockAddToWishlistConfig#params)

## Constructors

### constructor

• **new MockAddToWishlistConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/detail.ts:440](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L440)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.AddToWishListErrorErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/detail.ts:441](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L441)

___

### params

• `Optional` **params**: [`MockAddToWishlistParams`](../wiki/models.MockAddToWishlistParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/detail.ts:442](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L442)
