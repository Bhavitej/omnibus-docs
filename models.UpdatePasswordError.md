# Class: UpdatePasswordError

[models](../wiki/models).UpdatePasswordError

Describes the Update Password SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`UpdatePasswordErrorCode`](../wiki/models.UpdatePasswordErrorCode)\>

  ↳ **`UpdatePasswordError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.UpdatePasswordError#constructor)

### Properties

- [data](../wiki/models.UpdatePasswordError#data)
- [err](../wiki/models.UpdatePasswordError#err)
- [errorCode](../wiki/models.UpdatePasswordError#errorcode)
- [errorDetail](../wiki/models.UpdatePasswordError#errordetail)
- [status](../wiki/models.UpdatePasswordError#status)

## Constructors

### constructor

• **new UpdatePasswordError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:244](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L244)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:242](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L242)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.UpdatePasswordErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:246](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L246)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:245](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L245)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:243](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L243)
