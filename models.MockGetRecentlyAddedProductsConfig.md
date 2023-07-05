# Class: MockGetRecentlyAddedProductsConfig

[models](../wiki/models).MockGetRecentlyAddedProductsConfig

Describes the Mock Get recently added products SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetRecentlyAddedProductsParams`](../wiki/models.MockGetRecentlyAddedProductsParams), [`GetRecentlyAddedProductsErrorCode`](../wiki/models.GetRecentlyAddedProductsErrorCode)\>

  ↳ **`MockGetRecentlyAddedProductsConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetRecentlyAddedProductsConfig#constructor)

### Properties

- [err](../wiki/models.MockGetRecentlyAddedProductsConfig#err)
- [errorCode](../wiki/models.MockGetRecentlyAddedProductsConfig#errorcode)
- [params](../wiki/models.MockGetRecentlyAddedProductsConfig#params)

## Constructors

### constructor

• **new MockGetRecentlyAddedProductsConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:483](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L483)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetRecentlyAddedProductsErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:484](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L484)

___

### params

• `Optional` **params**: [`MockGetRecentlyAddedProductsParams`](../wiki/models.MockGetRecentlyAddedProductsParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:485](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L485)
