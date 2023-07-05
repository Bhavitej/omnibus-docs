# Class: MockHasCustomerRatedConfig

[models](../wiki/models).MockHasCustomerRatedConfig

Describes the Mock Has customer rated SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockHasCustomerRatedParams`](../wiki/models.MockHasCustomerRatedParams), [`HasCustomerRatedErrorCode`](../wiki/models.HasCustomerRatedErrorCode)\>

  ↳ **`MockHasCustomerRatedConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockHasCustomerRatedConfig#constructor)

### Properties

- [err](../wiki/models.MockHasCustomerRatedConfig#err)
- [errorCode](../wiki/models.MockHasCustomerRatedConfig#errorcode)
- [params](../wiki/models.MockHasCustomerRatedConfig#params)

## Constructors

### constructor

• **new MockHasCustomerRatedConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/detail.ts:529](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L529)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.HasCustomerRatedErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/detail.ts:530](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L530)

___

### params

• `Optional` **params**: [`MockHasCustomerRatedParams`](../wiki/models.MockHasCustomerRatedParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/detail.ts:531](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L531)
