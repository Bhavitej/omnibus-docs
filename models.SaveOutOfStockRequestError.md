# Class: SaveOutOfStockRequestError

[models](../wiki/models).SaveOutOfStockRequestError

Describes the Save out of stock request API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`SaveOutOfStockRequestErrorErrorCode`](../wiki/models.SaveOutOfStockRequestErrorErrorCode)\>

  ↳ **`SaveOutOfStockRequestError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.SaveOutOfStockRequestError#constructor)

### Properties

- [data](../wiki/models.SaveOutOfStockRequestError#data)
- [err](../wiki/models.SaveOutOfStockRequestError#err)
- [errorCode](../wiki/models.SaveOutOfStockRequestError#errorcode)
- [errorDetail](../wiki/models.SaveOutOfStockRequestError#errordetail)
- [status](../wiki/models.SaveOutOfStockRequestError#status)

## Constructors

### constructor

• **new SaveOutOfStockRequestError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/detail.ts:310](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L310)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/detail.ts:308](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L308)

___

### errorCode

• **errorCode**: `undefined` \| [`SaveOutOfStockRequestErrorErrorCode`](../wiki/models.SaveOutOfStockRequestErrorErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/detail.ts:312](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L312)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/detail.ts:311](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L311)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/detail.ts:309](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L309)
