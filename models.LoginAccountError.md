# Class: LoginAccountError

[models](../wiki/models).LoginAccountError

Describes the Login Account SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`LoginAccountErrorCode`](../wiki/models.LoginAccountErrorCode)\>

  ↳ **`LoginAccountError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.LoginAccountError#constructor)

### Properties

- [data](../wiki/models.LoginAccountError#data)
- [err](../wiki/models.LoginAccountError#err)
- [errorCode](../wiki/models.LoginAccountError#errorcode)
- [errorDetail](../wiki/models.LoginAccountError#errordetail)
- [status](../wiki/models.LoginAccountError#status)

## Constructors

### constructor

• **new LoginAccountError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:208](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L208)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:206](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L206)

___

### errorCode

• **errorCode**: `undefined` \| [`LoginAccountErrorCode`](../wiki/models.LoginAccountErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:210](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L210)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:209](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L209)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:207](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L207)
