# Class: MockGetBannerGroupConfig

[models](../wiki/models).MockGetBannerGroupConfig

Describes the Mock Get Banner group SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetBannerGroupParams`](../wiki/models.MockGetBannerGroupParams), [`GetBannerGroupErrorCode`](../wiki/models.GetBannerGroupErrorCode)\>

  ↳ **`MockGetBannerGroupConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetBannerGroupConfig#constructor)

### Properties

- [err](../wiki/models.MockGetBannerGroupConfig#err)
- [errorCode](../wiki/models.MockGetBannerGroupConfig#errorcode)
- [params](../wiki/models.MockGetBannerGroupConfig#params)

## Constructors

### constructor

• **new MockGetBannerGroupConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:457](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L457)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetBannerGroupErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:458](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L458)

___

### params

• `Optional` **params**: [`MockGetBannerGroupParams`](../wiki/models.MockGetBannerGroupParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:459](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L459)
