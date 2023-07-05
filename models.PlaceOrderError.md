# Class: PlaceOrderError

[models](../wiki/models).PlaceOrderError

Describes the Place order API error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`PlaceOrderErrorCode`](../wiki/models.PlaceOrderErrorCode)\>

  ↳ **`PlaceOrderError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.PlaceOrderError#constructor)

### Properties

- [data](../wiki/models.PlaceOrderError#data)
- [err](../wiki/models.PlaceOrderError#err)
- [errorCode](../wiki/models.PlaceOrderError#errorcode)
- [errorDetail](../wiki/models.PlaceOrderError#errordetail)
- [status](../wiki/models.PlaceOrderError#status)

## Constructors

### constructor

• **new PlaceOrderError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/checkout.ts:377](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L377)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/checkout.ts:375](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L375)

___

### errorCode

• **errorCode**: `undefined` \| [`PlaceOrderErrorCode`](../wiki/models.PlaceOrderErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/checkout.ts:379](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L379)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/checkout.ts:378](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L378)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/checkout.ts:376](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L376)
