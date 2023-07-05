# Class: MockAutoSuggestProductSearchQueryConfig

[models](../wiki/models).MockAutoSuggestProductSearchQueryConfig

Describes the Mock Auto suggest product search Query SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockAutoSuggestProductSearchQueryParams`](../wiki/models.MockAutoSuggestProductSearchQueryParams), [`AutoSuggestProductSearchQueryErrorCode`](../wiki/models.AutoSuggestProductSearchQueryErrorCode)\>

  ↳ **`MockAutoSuggestProductSearchQueryConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockAutoSuggestProductSearchQueryConfig#constructor)

### Properties

- [err](../wiki/models.MockAutoSuggestProductSearchQueryConfig#err)
- [errorCode](../wiki/models.MockAutoSuggestProductSearchQueryConfig#errorcode)
- [params](../wiki/models.MockAutoSuggestProductSearchQueryConfig#params)

## Constructors

### constructor

• **new MockAutoSuggestProductSearchQueryConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/search.ts:139](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L139)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.AutoSuggestProductSearchQueryErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/search.ts:140](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L140)

___

### params

• `Optional` **params**: [`MockAutoSuggestProductSearchQueryParams`](../wiki/models.MockAutoSuggestProductSearchQueryParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/search.ts:141](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L141)
