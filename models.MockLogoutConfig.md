# Class: MockLogoutConfig

[models](../wiki/models).MockLogoutConfig

Describes the Mock Log out SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockLogoutParams`](../wiki/models.MockLogoutParams), [`LogoutErrorCode`](../wiki/models.LogoutErrorCode)\>

  ↳ **`MockLogoutConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockLogoutConfig#constructor)

### Properties

- [err](../wiki/models.MockLogoutConfig#err)
- [errorCode](../wiki/models.MockLogoutConfig#errorcode)
- [params](../wiki/models.MockLogoutConfig#params)

## Constructors

### constructor

• **new MockLogoutConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:643](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L643)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.LogoutErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:644](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L644)

___

### params

• `Optional` **params**: [`MockLogoutParams`](../wiki/models.MockLogoutParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:645](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L645)
