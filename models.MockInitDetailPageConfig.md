# Class: MockInitDetailPageConfig

[models](../wiki/models).MockInitDetailPageConfig

Describes the Mock Init Detail Page SDK Config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockInitDetailPageParams`](../wiki/models.MockInitDetailPageParams), [`GetProductInfoErrorCode`](../wiki/models.GetProductInfoErrorCode)\>

  ↳ **`MockInitDetailPageConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockInitDetailPageConfig#constructor)

### Properties

- [err](../wiki/models.MockInitDetailPageConfig#err)
- [errorCode](../wiki/models.MockInitDetailPageConfig#errorcode)
- [params](../wiki/models.MockInitDetailPageConfig#params)

## Constructors

### constructor

• **new MockInitDetailPageConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/detail.ts:399](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L399)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetProductInfoErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/detail.ts:400](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L400)

___

### params

• `Optional` **params**: [`MockInitDetailPageParams`](../wiki/models.MockInitDetailPageParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/detail.ts:401](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L401)
