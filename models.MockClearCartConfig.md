# Class: MockClearCartConfig

[models](../wiki/models).MockClearCartConfig

Describes the Mock Clear cart SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockClearCartParams`](../wiki/models.MockClearCartParams), [`ClearCartErrorCode`](../wiki/models.ClearCartErrorCode)\>

  ↳ **`MockClearCartConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockClearCartConfig#constructor)

### Properties

- [err](../wiki/models.MockClearCartConfig#err)
- [errorCode](../wiki/models.MockClearCartConfig#errorcode)
- [params](../wiki/models.MockClearCartConfig#params)

## Constructors

### constructor

• **new MockClearCartConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/cart.ts:357](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L357)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.ClearCartErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/cart.ts:358](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L358)

___

### params

• `Optional` **params**: [`MockClearCartParams`](../wiki/models.MockClearCartParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/cart.ts:359](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L359)
