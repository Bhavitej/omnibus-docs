# Class: GetCustomerProfileError

[models](../wiki/models).GetCustomerProfileError

Describes the Get Customer Profile SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetCustomerProfileErrorCode`](../wiki/models.GetCustomerProfileErrorCode)\>

  ↳ **`GetCustomerProfileError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetCustomerProfileError#constructor)

### Properties

- [data](../wiki/models.GetCustomerProfileError#data)
- [err](../wiki/models.GetCustomerProfileError#err)
- [errorCode](../wiki/models.GetCustomerProfileError#errorcode)
- [errorDetail](../wiki/models.GetCustomerProfileError#errordetail)
- [status](../wiki/models.GetCustomerProfileError#status)

## Constructors

### constructor

• **new GetCustomerProfileError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:268](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L268)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:266](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L266)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetCustomerProfileErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:270](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L270)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:269](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L269)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:267](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L267)
