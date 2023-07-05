# Class: GetOrderError

[models](../wiki/models).GetOrderError

Describes the Get order SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetOrderErrorCode`](../wiki/models.GetOrderErrorCode)\>

  ↳ **`GetOrderError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetOrderError#constructor)

### Properties

- [data](../wiki/models.GetOrderError#data)
- [err](../wiki/models.GetOrderError#err)
- [errorCode](../wiki/models.GetOrderError#errorcode)
- [errorDetail](../wiki/models.GetOrderError#errordetail)
- [status](../wiki/models.GetOrderError#status)

## Constructors

### constructor

• **new GetOrderError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/orders.ts:24](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L24)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/orders.ts:22](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L22)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetOrderErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/orders.ts:26](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L26)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/orders.ts:25](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L25)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/orders.ts:23](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L23)
