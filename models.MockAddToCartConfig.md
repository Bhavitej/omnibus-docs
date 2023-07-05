# Class: MockAddToCartConfig

[models](../wiki/models).MockAddToCartConfig

Describes the Mock Add to cart SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockAddToCartParams`](../wiki/models.MockAddToCartParams), [`AddToCartErrorCode`](../wiki/models.AddToCartErrorCode)\>

  ↳ **`MockAddToCartConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockAddToCartConfig#constructor)

### Properties

- [err](../wiki/models.MockAddToCartConfig#err)
- [errorCode](../wiki/models.MockAddToCartConfig#errorcode)
- [params](../wiki/models.MockAddToCartConfig#params)

## Constructors

### constructor

• **new MockAddToCartConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/cart.ts:307](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L307)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.AddToCartErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/cart.ts:308](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L308)

___

### params

• `Optional` **params**: [`MockAddToCartParams`](../wiki/models.MockAddToCartParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/cart.ts:309](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L309)
