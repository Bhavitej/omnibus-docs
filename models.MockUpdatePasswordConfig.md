# Class: MockUpdatePasswordConfig

[models](../wiki/models).MockUpdatePasswordConfig

Describes the Mock Update password SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockUpdatePasswordParams`](../wiki/models.MockUpdatePasswordParams), [`UpdatePasswordErrorCode`](../wiki/models.UpdatePasswordErrorCode)\>

  ↳ **`MockUpdatePasswordConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockUpdatePasswordConfig#constructor)

### Properties

- [err](../wiki/models.MockUpdatePasswordConfig#err)
- [errorCode](../wiki/models.MockUpdatePasswordConfig#errorcode)
- [params](../wiki/models.MockUpdatePasswordConfig#params)

## Constructors

### constructor

• **new MockUpdatePasswordConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:550](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L550)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.UpdatePasswordErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:551](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L551)

___

### params

• `Optional` **params**: [`MockUpdatePasswordParams`](../wiki/models.MockUpdatePasswordParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:552](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L552)
