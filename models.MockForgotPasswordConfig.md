# Class: MockForgotPasswordConfig

[models](../wiki/models).MockForgotPasswordConfig

Describes the Mock Forgot password SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockForgotPasswordParams`](../wiki/models.MockForgotPasswordParams), [`ForgotPasswordErrorCode`](../wiki/models.ForgotPasswordErrorCode)\>

  ↳ **`MockForgotPasswordConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockForgotPasswordConfig#constructor)

### Properties

- [err](../wiki/models.MockForgotPasswordConfig#err)
- [errorCode](../wiki/models.MockForgotPasswordConfig#errorcode)
- [params](../wiki/models.MockForgotPasswordConfig#params)

## Constructors

### constructor

• **new MockForgotPasswordConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:506](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L506)

___

### errorCode

• `Optional` **errorCode**: [`INVALID_LOGIN_EMAILADDRESS`](../wiki/models.ForgotPasswordErrorCode#invalid_login_emailaddress)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:507](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L507)

___

### params

• `Optional` **params**: [`MockForgotPasswordParams`](../wiki/models.MockForgotPasswordParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:508](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L508)
