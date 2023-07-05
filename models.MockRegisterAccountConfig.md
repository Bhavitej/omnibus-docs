# Class: MockRegisterAccountConfig

[models](../wiki/models).MockRegisterAccountConfig

Describes the Mock Register Account SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockRegisterAccountParams`](../wiki/models.MockRegisterAccountParams), [`RegisterAccountErrorCode`](../wiki/models.RegisterAccountErrorCode)\>

  ↳ **`MockRegisterAccountConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockRegisterAccountConfig#constructor)

### Properties

- [err](../wiki/models.MockRegisterAccountConfig#err)
- [errorCode](../wiki/models.MockRegisterAccountConfig#errorcode)
- [params](../wiki/models.MockRegisterAccountConfig#params)

## Constructors

### constructor

• **new MockRegisterAccountConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:457](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L457)

___

### errorCode

• `Optional` **errorCode**: [`RegisterAccountErrorCode`](../wiki/models.RegisterAccountErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:458](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L458)

___

### params

• `Optional` **params**: [`MockRegisterAccountParams`](../wiki/models.MockRegisterAccountParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:459](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L459)
