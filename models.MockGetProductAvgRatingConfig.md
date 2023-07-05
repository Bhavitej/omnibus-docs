# Class: MockGetProductAvgRatingConfig

[models](../wiki/models).MockGetProductAvgRatingConfig

Describes the Mock Get Avg Product Rating SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetAvgProductRatingParams`](../wiki/models.MockGetAvgProductRatingParams), [`GetAvgProductRatingErrorCode`](../wiki/models.GetAvgProductRatingErrorCode)\>

  ↳ **`MockGetProductAvgRatingConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetProductAvgRatingConfig#constructor)

### Properties

- [err](../wiki/models.MockGetProductAvgRatingConfig#err)
- [errorCode](../wiki/models.MockGetProductAvgRatingConfig#errorcode)
- [params](../wiki/models.MockGetProductAvgRatingConfig#params)

## Constructors

### constructor

• **new MockGetProductAvgRatingConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/detail.ts:508](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L508)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetAvgProductRatingErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/detail.ts:509](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L509)

___

### params

• `Optional` **params**: [`MockGetAvgProductRatingParams`](../wiki/models.MockGetAvgProductRatingParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/detail.ts:510](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L510)
