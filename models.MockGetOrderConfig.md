# Class: MockGetOrderConfig

[models](../wiki/models).MockGetOrderConfig

Describes the Mock Get Order SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetOrderParams`](../wiki/models.MockGetOrderParams), [`GetOrderErrorCode`](../wiki/models.GetOrderErrorCode)\>

  ↳ **`MockGetOrderConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetOrderConfig#constructor)

### Properties

- [err](../wiki/models.MockGetOrderConfig#err)
- [errorCode](../wiki/models.MockGetOrderConfig#errorcode)
- [params](../wiki/models.MockGetOrderConfig#params)

## Constructors

### constructor

• **new MockGetOrderConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/orders.ts:173](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L173)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetOrderErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/orders.ts:174](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L174)

___

### params

• `Optional` **params**: [`MockGetOrderParams`](../wiki/models.MockGetOrderParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/orders.ts:175](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L175)
