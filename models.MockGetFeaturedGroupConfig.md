# Class: MockGetFeaturedGroupConfig

[models](../wiki/models).MockGetFeaturedGroupConfig

Describes the Mock Get featured group SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetFeaturedGroupParams`](../wiki/models.MockGetFeaturedGroupParams), [`GetFeaturedGroupErrorCode`](../wiki/models.GetFeaturedGroupErrorCode)\>

  ↳ **`MockGetFeaturedGroupConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetFeaturedGroupConfig#constructor)

### Properties

- [err](../wiki/models.MockGetFeaturedGroupConfig#err)
- [errorCode](../wiki/models.MockGetFeaturedGroupConfig#errorcode)
- [params](../wiki/models.MockGetFeaturedGroupConfig#params)

## Constructors

### constructor

• **new MockGetFeaturedGroupConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:533](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L533)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetFeaturedGroupErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:534](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L534)

___

### params

• `Optional` **params**: [`MockGetFeaturedGroupParams`](../wiki/models.MockGetFeaturedGroupParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:535](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L535)
