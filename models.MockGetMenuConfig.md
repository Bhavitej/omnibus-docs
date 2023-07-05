# Class: MockGetMenuConfig

[models](../wiki/models).MockGetMenuConfig

Describes the Mock Get Menu SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetMenuParams`](../wiki/models.MockGetMenuParams), [`GetMenuErrorCode`](../wiki/models.GetMenuErrorCode)\>

  ↳ **`MockGetMenuConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetMenuConfig#constructor)

### Properties

- [err](../wiki/models.MockGetMenuConfig#err)
- [errorCode](../wiki/models.MockGetMenuConfig#errorcode)
- [params](../wiki/models.MockGetMenuConfig#params)

## Constructors

### constructor

• **new MockGetMenuConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/home.ts:383](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L383)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetMenuErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/home.ts:384](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L384)

___

### params

• `Optional` **params**: [`MockGetMenuParams`](../wiki/models.MockGetMenuParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/home.ts:385](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L385)
