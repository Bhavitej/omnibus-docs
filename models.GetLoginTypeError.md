# Class: GetLoginTypeError

[models](../wiki/models).GetLoginTypeError

Describes the Get Login type SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetLoginTypeErrorCode`](../wiki/models.GetLoginTypeErrorCode)\>

  ↳ **`GetLoginTypeError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetLoginTypeError#constructor)

### Properties

- [data](../wiki/models.GetLoginTypeError#data)
- [err](../wiki/models.GetLoginTypeError#err)
- [errorCode](../wiki/models.GetLoginTypeError#errorcode)
- [errorDetail](../wiki/models.GetLoginTypeError#errordetail)
- [status](../wiki/models.GetLoginTypeError#status)

## Constructors

### constructor

• **new GetLoginTypeError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:232](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L232)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:230](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L230)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetLoginTypeErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:234](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L234)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:233](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L233)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:231](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L231)
