# Class: MockProductSearchQueryConfig

[models](../wiki/models).MockProductSearchQueryConfig

Describes the Mock Product search Query SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockProductSearchQueryParams`](../wiki/models.MockProductSearchQueryParams), [`ProductSearchQueryErrorCode`](../wiki/models.ProductSearchQueryErrorCode)\>

  ↳ **`MockProductSearchQueryConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockProductSearchQueryConfig#constructor)

### Properties

- [err](../wiki/models.MockProductSearchQueryConfig#err)
- [errorCode](../wiki/models.MockProductSearchQueryConfig#errorcode)
- [params](../wiki/models.MockProductSearchQueryConfig#params)

## Constructors

### constructor

• **new MockProductSearchQueryConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/search.ts:107](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L107)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.ProductSearchQueryErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/search.ts:108](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L108)

___

### params

• `Optional` **params**: [`MockProductSearchQueryParams`](../wiki/models.MockProductSearchQueryParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/search.ts:109](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L109)
