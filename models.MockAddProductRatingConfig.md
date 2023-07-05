# Class: MockAddProductRatingConfig

[models](../wiki/models).MockAddProductRatingConfig

Describes the Mock Add Product Rating SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockAddProductRatingParams`](../wiki/models.MockAddProductRatingParams), [`AddProductRatingErrorCode`](../wiki/models.AddProductRatingErrorCode)\>

  ↳ **`MockAddProductRatingConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockAddProductRatingConfig#constructor)

### Properties

- [err](../wiki/models.MockAddProductRatingConfig#err)
- [errorCode](../wiki/models.MockAddProductRatingConfig#errorcode)
- [params](../wiki/models.MockAddProductRatingConfig#params)

## Constructors

### constructor

• **new MockAddProductRatingConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/detail.ts:487](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L487)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.AddProductRatingErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/detail.ts:488](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L488)

___

### params

• `Optional` **params**: [`MockAddProductRatingParams`](../wiki/models.MockAddProductRatingParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/detail.ts:489](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L489)
