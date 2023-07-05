# Class: MockUpdateCartConfig

[models](../wiki/models).MockUpdateCartConfig

Describes the Mock update cart SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockUpdateCartParams`](../wiki/models.MockUpdateCartParams), [`UpdateCartErrorCode`](../wiki/models.UpdateCartErrorCode)\>

  ↳ **`MockUpdateCartConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockUpdateCartConfig#constructor)

### Properties

- [err](../wiki/models.MockUpdateCartConfig#err)
- [errorCode](../wiki/models.MockUpdateCartConfig#errorcode)
- [params](../wiki/models.MockUpdateCartConfig#params)

## Constructors

### constructor

• **new MockUpdateCartConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/cart.ts:397](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L397)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.UpdateCartErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/cart.ts:398](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L398)

___

### params

• `Optional` **params**: [`MockUpdateCartParams`](../wiki/models.MockUpdateCartParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/cart.ts:399](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L399)
