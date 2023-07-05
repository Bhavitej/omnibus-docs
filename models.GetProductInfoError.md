# Class: GetProductInfoError

[models](../wiki/models).GetProductInfoError

Describes the Get Product Info SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetProductInfoErrorCode`](../wiki/models.GetProductInfoErrorCode)\>

  ↳ **`GetProductInfoError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetProductInfoError#constructor)

### Properties

- [data](../wiki/models.GetProductInfoError#data)
- [err](../wiki/models.GetProductInfoError#err)
- [errorCode](../wiki/models.GetProductInfoError#errorcode)
- [errorDetail](../wiki/models.GetProductInfoError#errordetail)
- [status](../wiki/models.GetProductInfoError#status)

## Constructors

### constructor

• **new GetProductInfoError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/detail.ts:234](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L234)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/detail.ts:232](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L232)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetProductInfoErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/detail.ts:236](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L236)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/detail.ts:235](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L235)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/detail.ts:233](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L233)
