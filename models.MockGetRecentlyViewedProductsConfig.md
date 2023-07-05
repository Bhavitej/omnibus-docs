# Class: MockGetRecentlyViewedProductsConfig

[models](../wiki/models).MockGetRecentlyViewedProductsConfig

Describes the Mock Get Recently viewed products SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetRecentlyViewedProductsParams`](../wiki/models.MockGetRecentlyViewedProductsParams), [`GetRecentlyViewedProductsErrorCode`](../wiki/models.GetRecentlyViewedProductsErrorCode)\>

  ↳ **`MockGetRecentlyViewedProductsConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetRecentlyViewedProductsConfig#constructor)

### Properties

- [err](../wiki/models.MockGetRecentlyViewedProductsConfig#err)
- [errorCode](../wiki/models.MockGetRecentlyViewedProductsConfig#errorcode)
- [params](../wiki/models.MockGetRecentlyViewedProductsConfig#params)

## Constructors

### constructor

• **new MockGetRecentlyViewedProductsConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:361](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L361)

___

### errorCode

• `Optional` **errorCode**: [`GetRecentlyViewedProductsErrorCode`](../wiki/models.GetRecentlyViewedProductsErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:362](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L362)

___

### params

• `Optional` **params**: [`MockGetRecentlyViewedProductsParams`](../wiki/models.MockGetRecentlyViewedProductsParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:363](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L363)
