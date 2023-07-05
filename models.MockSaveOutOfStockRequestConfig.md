# Class: MockSaveOutOfStockRequestConfig

[models](../wiki/models).MockSaveOutOfStockRequestConfig

Describes the Mock Save out of stock request SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockSaveOutOfStockRequestParams`](../wiki/models.MockSaveOutOfStockRequestParams), [`SaveOutOfStockRequestErrorErrorCode`](../wiki/models.SaveOutOfStockRequestErrorErrorCode)\>

  ↳ **`MockSaveOutOfStockRequestConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockSaveOutOfStockRequestConfig#constructor)

### Properties

- [err](../wiki/models.MockSaveOutOfStockRequestConfig#err)
- [errorCode](../wiki/models.MockSaveOutOfStockRequestConfig#errorcode)
- [params](../wiki/models.MockSaveOutOfStockRequestConfig#params)

## Constructors

### constructor

• **new MockSaveOutOfStockRequestConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/detail.ts:451](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L451)

___

### errorCode

• `Optional` **errorCode**: [`SaveOutOfStockRequestErrorErrorCode`](../wiki/models.SaveOutOfStockRequestErrorErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/detail.ts:452](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L452)

___

### params

• `Optional` **params**: [`MockSaveOutOfStockRequestParams`](../wiki/models.MockSaveOutOfStockRequestParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/detail.ts:453](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L453)
