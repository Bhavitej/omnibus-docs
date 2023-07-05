# Class: MockGetDefaultProductImageConfig

[models](../wiki/models).MockGetDefaultProductImageConfig

Describes the Mock Get Default Product image SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetDefaultProductImageParams`](../wiki/models.MockGetDefaultProductImageParams), [`GetDefaultProductImageErrorCode`](../wiki/models.GetDefaultProductImageErrorCode)\>

  ↳ **`MockGetDefaultProductImageConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetDefaultProductImageConfig#constructor)

### Properties

- [err](../wiki/models.MockGetDefaultProductImageConfig#err)
- [errorCode](../wiki/models.MockGetDefaultProductImageConfig#errorcode)
- [params](../wiki/models.MockGetDefaultProductImageConfig#params)

## Constructors

### constructor

• **new MockGetDefaultProductImageConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:339](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L339)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetDefaultProductImageErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:340](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L340)

___

### params

• `Optional` **params**: [`MockGetDefaultProductImageParams`](../wiki/models.MockGetDefaultProductImageParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:341](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L341)
