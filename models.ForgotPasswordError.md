# Class: ForgotPasswordError

[models](../wiki/models).ForgotPasswordError

Describes the Forgot Password SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`ForgotPasswordErrorCode`](../wiki/models.ForgotPasswordErrorCode)\>

  ↳ **`ForgotPasswordError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.ForgotPasswordError#constructor)

### Properties

- [data](../wiki/models.ForgotPasswordError#data)
- [err](../wiki/models.ForgotPasswordError#err)
- [errorCode](../wiki/models.ForgotPasswordError#errorcode)
- [errorDetail](../wiki/models.ForgotPasswordError#errordetail)
- [status](../wiki/models.ForgotPasswordError#status)

## Constructors

### constructor

• **new ForgotPasswordError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:220](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L220)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:218](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L218)

___

### errorCode

• **errorCode**: `undefined` \| [`INVALID_LOGIN_EMAILADDRESS`](../wiki/models.ForgotPasswordErrorCode#invalid_login_emailaddress)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:222](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L222)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:221](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L221)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:219](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L219)
