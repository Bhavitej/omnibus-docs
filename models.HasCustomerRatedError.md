# Class: HasCustomerRatedError

[models](../wiki/models).HasCustomerRatedError

Describes the Has Customer Rated Error API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`HasCustomerRatedErrorCode`](../wiki/models.HasCustomerRatedErrorCode)\>

  ↳ **`HasCustomerRatedError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.HasCustomerRatedError#constructor)

### Properties

- [data](../wiki/models.HasCustomerRatedError#data)
- [err](../wiki/models.HasCustomerRatedError#err)
- [errorCode](../wiki/models.HasCustomerRatedError#errorcode)
- [errorDetail](../wiki/models.HasCustomerRatedError#errordetail)
- [status](../wiki/models.HasCustomerRatedError#status)

## Constructors

### constructor

• **new HasCustomerRatedError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/detail.ts:298](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L298)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/detail.ts:296](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L296)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.HasCustomerRatedErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/detail.ts:300](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L300)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/detail.ts:299](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L299)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/detail.ts:297](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/detail.ts#L297)
