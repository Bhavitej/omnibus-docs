# Class: MockGetLoginTypeConfig

[models](../wiki/models).MockGetLoginTypeConfig

Describes the Mock Get Login type SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetLoginTypeParams`](../wiki/models.MockGetLoginTypeParams), [`GetLoginTypeErrorCode`](../wiki/models.GetLoginTypeErrorCode)\>

  ↳ **`MockGetLoginTypeConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetLoginTypeConfig#constructor)

### Properties

- [err](../wiki/models.MockGetLoginTypeConfig#err)
- [errorCode](../wiki/models.MockGetLoginTypeConfig#errorcode)
- [params](../wiki/models.MockGetLoginTypeConfig#params)

## Constructors

### constructor

• **new MockGetLoginTypeConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:528](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L528)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetLoginTypeErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:529](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L529)

___

### params

• `Optional` **params**: [`MockGetLoginTypeParams`](../wiki/models.MockGetLoginTypeParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:530](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L530)
