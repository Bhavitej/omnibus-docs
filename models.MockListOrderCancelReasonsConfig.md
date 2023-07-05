# Class: MockListOrderCancelReasonsConfig

[models](../wiki/models).MockListOrderCancelReasonsConfig

Describes the Mock List Order Cancel Reasons SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockListOrderCancelReasonsParams`](../wiki/models.MockListOrderCancelReasonsParams), [`ListOrderCancelReasonsErrorCode`](../wiki/models.ListOrderCancelReasonsErrorCode)\>

  ↳ **`MockListOrderCancelReasonsConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockListOrderCancelReasonsConfig#constructor)

### Properties

- [err](../wiki/models.MockListOrderCancelReasonsConfig#err)
- [errorCode](../wiki/models.MockListOrderCancelReasonsConfig#errorcode)
- [params](../wiki/models.MockListOrderCancelReasonsConfig#params)

## Constructors

### constructor

• **new MockListOrderCancelReasonsConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/orders.ts:290](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L290)

___

### errorCode

• `Optional` **errorCode**: [`ListOrderCancelReasonsErrorCode`](../wiki/models.ListOrderCancelReasonsErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/orders.ts:291](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L291)

___

### params

• `Optional` **params**: [`MockListOrderCancelReasonsParams`](../wiki/models.MockListOrderCancelReasonsParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/orders.ts:292](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L292)
