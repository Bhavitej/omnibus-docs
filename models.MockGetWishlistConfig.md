# Class: MockGetWishlistConfig

[models](../wiki/models).MockGetWishlistConfig

Describes the Mock Get Wishlist SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetWishlistParams`](../wiki/models.MockGetWishlistParams), [`GetWishlistErrorCode`](../wiki/models.GetWishlistErrorCode)\>

  ↳ **`MockGetWishlistConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetWishlistConfig#constructor)

### Properties

- [err](../wiki/models.MockGetWishlistConfig#err)
- [errorCode](../wiki/models.MockGetWishlistConfig#errorcode)
- [params](../wiki/models.MockGetWishlistConfig#params)

## Constructors

### constructor

• **new MockGetWishlistConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:431](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L431)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetWishlistErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:432](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L432)

___

### params

• `Optional` **params**: [`MockGetWishlistParams`](../wiki/models.MockGetWishlistParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:433](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L433)
