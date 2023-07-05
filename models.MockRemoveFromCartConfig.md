# Class: MockRemoveFromCartConfig

[models](../wiki/models).MockRemoveFromCartConfig

Describes the Mock Remove from cart SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockRemoveFromCartParams`](../wiki/models.MockRemoveFromCartParams), [`RemoveFromCartErrorCode`](../wiki/models.RemoveFromCartErrorCode)\>

  ↳ **`MockRemoveFromCartConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockRemoveFromCartConfig#constructor)

### Properties

- [err](../wiki/models.MockRemoveFromCartConfig#err)
- [errorCode](../wiki/models.MockRemoveFromCartConfig#errorcode)
- [params](../wiki/models.MockRemoveFromCartConfig#params)

## Constructors

### constructor

• **new MockRemoveFromCartConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/cart.ts:367](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L367)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.RemoveFromCartErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/cart.ts:368](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L368)

___

### params

• `Optional` **params**: [`MockRemoveFromCartParams`](../wiki/models.MockRemoveFromCartParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/cart.ts:369](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L369)
