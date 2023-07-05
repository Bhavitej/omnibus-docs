# Class: MockUpdateProfileConfig

[models](../wiki/models).MockUpdateProfileConfig

Describes the Mock Update profile SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockUpdateProfileParams`](../wiki/models.MockUpdateProfileParams), [`UpdateProfileErrorCode`](../wiki/models.UpdateProfileErrorCode)\>

  ↳ **`MockUpdateProfileConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockUpdateProfileConfig#constructor)

### Properties

- [err](../wiki/models.MockUpdateProfileConfig#err)
- [errorCode](../wiki/models.MockUpdateProfileConfig#errorcode)
- [params](../wiki/models.MockUpdateProfileConfig#params)

## Constructors

### constructor

• **new MockUpdateProfileConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:572](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L572)

___

### errorCode

• `Optional` **errorCode**: [`UpdateProfileErrorCode`](../wiki/models.UpdateProfileErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:573](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L573)

___

### params

• `Optional` **params**: [`MockUpdateProfileParams`](../wiki/models.MockUpdateProfileParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:574](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L574)
