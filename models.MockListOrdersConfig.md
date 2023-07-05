# Class: MockListOrdersConfig

[models](../wiki/models).MockListOrdersConfig

Describes the Mock List Orders SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockListOrdersParams`](../wiki/models.MockListOrdersParams), [`ListOrdersErrorCode`](../wiki/models.ListOrdersErrorCode)\>

  ↳ **`MockListOrdersConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockListOrdersConfig#constructor)

### Properties

- [err](../wiki/models.MockListOrdersConfig#err)
- [errorCode](../wiki/models.MockListOrdersConfig#errorcode)
- [params](../wiki/models.MockListOrdersConfig#params)

## Constructors

### constructor

• **new MockListOrdersConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/orders.ts:205](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L205)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.ListOrdersErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/orders.ts:206](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L206)

___

### params

• `Optional` **params**: [`MockListOrdersParams`](../wiki/models.MockListOrdersParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/orders.ts:207](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L207)
