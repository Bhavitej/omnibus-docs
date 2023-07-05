# Class: RegisterAccountError

[models](../wiki/models).RegisterAccountError

Describes the Register Account SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`RegisterAccountErrorCode`](../wiki/models.RegisterAccountErrorCode)\>

  ↳ **`RegisterAccountError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.RegisterAccountError#constructor)

### Properties

- [data](../wiki/models.RegisterAccountError#data)
- [err](../wiki/models.RegisterAccountError#err)
- [errorCode](../wiki/models.RegisterAccountError#errorcode)
- [errorDetail](../wiki/models.RegisterAccountError#errordetail)
- [status](../wiki/models.RegisterAccountError#status)

## Constructors

### constructor

• **new RegisterAccountError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:196](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L196)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:194](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L194)

___

### errorCode

• **errorCode**: `undefined` \| [`RegisterAccountErrorCode`](../wiki/models.RegisterAccountErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:198](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L198)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:197](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L197)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:195](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L195)
