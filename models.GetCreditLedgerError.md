# Class: GetCreditLedgerError

[models](../wiki/models).GetCreditLedgerError

Describes the Get credit ledger API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetCreditLedgerErrorCode`](../wiki/models.GetCreditLedgerErrorCode)\>

  ↳ **`GetCreditLedgerError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetCreditLedgerError#constructor)

### Properties

- [data](../wiki/models.GetCreditLedgerError#data)
- [err](../wiki/models.GetCreditLedgerError#err)
- [errorCode](../wiki/models.GetCreditLedgerError#errorcode)
- [errorDetail](../wiki/models.GetCreditLedgerError#errordetail)
- [status](../wiki/models.GetCreditLedgerError#status)

## Constructors

### constructor

• **new GetCreditLedgerError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/checkout.ts:365](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L365)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/checkout.ts:363](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L363)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetCreditLedgerErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/checkout.ts:367](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L367)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/checkout.ts:366](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L366)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/checkout.ts:364](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L364)
