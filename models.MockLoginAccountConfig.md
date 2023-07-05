# Class: MockLoginAccountConfig

[models](../wiki/models).MockLoginAccountConfig

Describes the Mock Login Account SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockLoginAccountParams`](../wiki/models.MockLoginAccountParams), [`LoginAccountErrorCode`](../wiki/models.LoginAccountErrorCode)\>

  ↳ **`MockLoginAccountConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockLoginAccountConfig#constructor)

### Properties

- [err](../wiki/models.MockLoginAccountConfig#err)
- [errorCode](../wiki/models.MockLoginAccountConfig#errorcode)
- [params](../wiki/models.MockLoginAccountConfig#params)

## Constructors

### constructor

• **new MockLoginAccountConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:479](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L479)

___

### errorCode

• `Optional` **errorCode**: [`LoginAccountErrorCode`](../wiki/models.LoginAccountErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:480](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L480)

___

### params

• `Optional` **params**: [`MockLoginAccountParams`](../wiki/models.MockLoginAccountParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:481](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L481)
