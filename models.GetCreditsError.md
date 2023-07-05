# Class: GetCreditsError

[models](../wiki/models).GetCreditsError

Describes the Get credits API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetCreditsErrorCode`](../wiki/models.GetCreditsErrorCode)\>

  ↳ **`GetCreditsError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetCreditsError#constructor)

### Properties

- [data](../wiki/models.GetCreditsError#data)
- [err](../wiki/models.GetCreditsError#err)
- [errorCode](../wiki/models.GetCreditsError#errorcode)
- [errorDetail](../wiki/models.GetCreditsError#errordetail)
- [status](../wiki/models.GetCreditsError#status)

## Constructors

### constructor

• **new GetCreditsError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/checkout.ts:353](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L353)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/checkout.ts:351](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L351)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetCreditsErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/checkout.ts:355](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L355)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/checkout.ts:354](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L354)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/checkout.ts:352](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L352)
