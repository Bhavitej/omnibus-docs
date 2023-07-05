# Class: MockGetCatalogueInfoConfig

[models](../wiki/models).MockGetCatalogueInfoConfig

Describes the Mock Get Catalogue Info SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetCatalogueInfoParams`](../wiki/models.MockGetCatalogueInfoParams), [`GetCatalogueInfoErrorCode`](../wiki/models.GetCatalogueInfoErrorCode)\>

  ↳ **`MockGetCatalogueInfoConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetCatalogueInfoConfig#constructor)

### Properties

- [err](../wiki/models.MockGetCatalogueInfoConfig#err)
- [errorCode](../wiki/models.MockGetCatalogueInfoConfig#errorcode)
- [params](../wiki/models.MockGetCatalogueInfoConfig#params)

## Constructors

### constructor

• **new MockGetCatalogueInfoConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/catalogue.ts:92](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L92)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetCatalogueInfoErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/catalogue.ts:93](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L93)

___

### params

• `Optional` **params**: [`MockGetCatalogueInfoParams`](../wiki/models.MockGetCatalogueInfoParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/catalogue.ts:94](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L94)
