# Class: GetDefaultProductImageError

[models](../wiki/models).GetDefaultProductImageError

Describes the Get Default Product Image SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetDefaultProductImageErrorCode`](../wiki/models.GetDefaultProductImageErrorCode)\>

  ↳ **`GetDefaultProductImageError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetDefaultProductImageError#constructor)

### Properties

- [data](../wiki/models.GetDefaultProductImageError#data)
- [err](../wiki/models.GetDefaultProductImageError#err)
- [errorCode](../wiki/models.GetDefaultProductImageError#errorcode)
- [errorDetail](../wiki/models.GetDefaultProductImageError#errordetail)
- [status](../wiki/models.GetDefaultProductImageError#status)

## Constructors

### constructor

• **new GetDefaultProductImageError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:245](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L245)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:243](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L243)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetDefaultProductImageErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:247](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L247)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:246](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L246)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:244](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L244)
