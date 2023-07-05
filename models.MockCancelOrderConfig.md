# Class: MockCancelOrderConfig

[models](../wiki/models).MockCancelOrderConfig

Describes the Mock Cancel Order SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockCancelOrderParams`](../wiki/models.MockCancelOrderParams), [`CancelOrderErrorCode`](../wiki/models.CancelOrderErrorCode)\>

  ↳ **`MockCancelOrderConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockCancelOrderConfig#constructor)

### Properties

- [err](../wiki/models.MockCancelOrderConfig#err)
- [errorCode](../wiki/models.MockCancelOrderConfig#errorcode)
- [params](../wiki/models.MockCancelOrderConfig#params)

## Constructors

### constructor

• **new MockCancelOrderConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/orders.ts:257](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L257)

___

### errorCode

• `Optional` **errorCode**: [`CancelOrderErrorCode`](../wiki/models.CancelOrderErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/orders.ts:258](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L258)

___

### params

• `Optional` **params**: [`MockCancelOrderParams`](../wiki/models.MockCancelOrderParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/orders.ts:259](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L259)
