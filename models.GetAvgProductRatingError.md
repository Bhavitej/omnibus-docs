# Class: GetAvgProductRatingError

[models](../wiki/models).GetAvgProductRatingError

Describes the Get Product Rating API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetAvgProductRatingErrorCode`](../wiki/models.GetAvgProductRatingErrorCode)\>

  ↳ **`GetAvgProductRatingError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetAvgProductRatingError#constructor)

### Properties

- [data](../wiki/models.GetAvgProductRatingError#data)
- [err](../wiki/models.GetAvgProductRatingError#err)
- [errorCode](../wiki/models.GetAvgProductRatingError#errorcode)
- [errorDetail](../wiki/models.GetAvgProductRatingError#errordetail)
- [status](../wiki/models.GetAvgProductRatingError#status)

## Constructors

### constructor

• **new GetAvgProductRatingError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/detail.ts:246](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L246)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/detail.ts:244](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L244)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetAvgProductRatingErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/detail.ts:248](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L248)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/detail.ts:247](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L247)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/detail.ts:245](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L245)
