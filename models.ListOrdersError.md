# Class: ListOrdersError

[models](../wiki/models).ListOrdersError

Describes the List orders SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`ListOrdersErrorCode`](../wiki/models.ListOrdersErrorCode)\>

  ↳ **`ListOrdersError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.ListOrdersError#constructor)

### Properties

- [data](../wiki/models.ListOrdersError#data)
- [err](../wiki/models.ListOrdersError#err)
- [errorCode](../wiki/models.ListOrdersError#errorcode)
- [errorDetail](../wiki/models.ListOrdersError#errordetail)
- [status](../wiki/models.ListOrdersError#status)

## Constructors

### constructor

• **new ListOrdersError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/orders.ts:12](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L12)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/orders.ts:10](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L10)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.ListOrdersErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/orders.ts:14](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L14)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/orders.ts:13](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L13)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/orders.ts:11](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L11)
