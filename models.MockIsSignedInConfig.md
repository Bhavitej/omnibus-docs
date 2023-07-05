# Class: MockIsSignedInConfig

[models](../wiki/models).MockIsSignedInConfig

Describes the Mock Is signed in SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockIsSignedInParams`](../wiki/models.MockIsSignedInParams), [`IsSignedInErrorCode`](../wiki/models.IsSignedInErrorCode)\>

  ↳ **`MockIsSignedInConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockIsSignedInConfig#constructor)

### Properties

- [err](../wiki/models.MockIsSignedInConfig#err)
- [errorCode](../wiki/models.MockIsSignedInConfig#errorcode)
- [params](../wiki/models.MockIsSignedInConfig#params)

## Constructors

### constructor

• **new MockIsSignedInConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:621](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L621)

___

### errorCode

• `Optional` **errorCode**: [`IsSignedInErrorCode`](../wiki/models.IsSignedInErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:622](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L622)

___

### params

• `Optional` **params**: [`MockIsSignedInParams`](../wiki/models.MockIsSignedInParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:623](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L623)
