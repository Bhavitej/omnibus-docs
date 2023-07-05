# Class: MockGetSiteInfoConfig

[models](../wiki/models).MockGetSiteInfoConfig

Describes the Mock Site Info SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetSiteInfoParams`](../wiki/models.MockGetSiteInfoParams), [`GetSiteInfoErrorCode`](../wiki/models.GetSiteInfoErrorCode)\>

  ↳ **`MockGetSiteInfoConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetSiteInfoConfig#constructor)

### Properties

- [err](../wiki/models.MockGetSiteInfoConfig#err)
- [errorCode](../wiki/models.MockGetSiteInfoConfig#errorcode)
- [params](../wiki/models.MockGetSiteInfoConfig#params)

## Constructors

### constructor

• **new MockGetSiteInfoConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:405](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L405)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetSiteInfoErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:406](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L406)

___

### params

• `Optional` **params**: [`MockGetSiteInfoParams`](../wiki/models.MockGetSiteInfoParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:407](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L407)
