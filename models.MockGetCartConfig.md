# Class: MockGetCartConfig

[models](../wiki/models).MockGetCartConfig

Describes the Mock Get cart SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetCartParams`](../wiki/models.MockGetCartParams), [`GetCartErrorCode`](../wiki/models.GetCartErrorCode)\>

  ↳ **`MockGetCartConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetCartConfig#constructor)

### Properties

- [err](../wiki/models.MockGetCartConfig#err)
- [errorCode](../wiki/models.MockGetCartConfig#errorcode)
- [params](../wiki/models.MockGetCartConfig#params)

## Constructors

### constructor

• **new MockGetCartConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/cart.ts:257](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L257)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetCartErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/cart.ts:258](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L258)

___

### params

• `Optional` **params**: [`MockGetCartParams`](../wiki/models.MockGetCartParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/cart.ts:259](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L259)
