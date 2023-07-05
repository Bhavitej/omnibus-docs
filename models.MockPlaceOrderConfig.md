# Class: MockPlaceOrderConfig

[models](../wiki/models).MockPlaceOrderConfig

Describes the Mock Place order SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockPlaceOrderParams`](../wiki/models.MockPlaceOrderParams), [`PlaceOrderErrorCode`](../wiki/models.PlaceOrderErrorCode)\>

  ↳ **`MockPlaceOrderConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockPlaceOrderConfig#constructor)

### Properties

- [err](../wiki/models.MockPlaceOrderConfig#err)
- [errorCode](../wiki/models.MockPlaceOrderConfig#errorcode)
- [params](../wiki/models.MockPlaceOrderConfig#params)

## Constructors

### constructor

• **new MockPlaceOrderConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/checkout.ts:496](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L496)

___

### errorCode

• `Optional` **errorCode**: [`PlaceOrderErrorCode`](../wiki/models.PlaceOrderErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/checkout.ts:497](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L497)

___

### params

• `Optional` **params**: [`MockPlaceOrderParams`](../wiki/models.MockPlaceOrderParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/checkout.ts:498](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L498)
