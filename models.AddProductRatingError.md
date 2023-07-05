# Class: AddProductRatingError

[models](../wiki/models).AddProductRatingError

Describes the Add product rating API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`AddProductRatingErrorCode`](../wiki/models.AddProductRatingErrorCode)\>

  ↳ **`AddProductRatingError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.AddProductRatingError#constructor)

### Properties

- [data](../wiki/models.AddProductRatingError#data)
- [err](../wiki/models.AddProductRatingError#err)
- [errorCode](../wiki/models.AddProductRatingError#errorcode)
- [errorDetail](../wiki/models.AddProductRatingError#errordetail)
- [status](../wiki/models.AddProductRatingError#status)

## Constructors

### constructor

• **new AddProductRatingError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/detail.ts:286](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L286)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/detail.ts:284](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L284)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.AddProductRatingErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/detail.ts:288](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L288)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/detail.ts:287](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L287)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/detail.ts:285](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L285)
