# Class: ClearCartError

[models](../wiki/models).ClearCartError

Describes the Clear Cart SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`ClearCartErrorCode`](../wiki/models.ClearCartErrorCode)\>

  ↳ **`ClearCartError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.ClearCartError#constructor)

### Properties

- [data](../wiki/models.ClearCartError#data)
- [err](../wiki/models.ClearCartError#err)
- [errorCode](../wiki/models.ClearCartError#errorcode)
- [errorDetail](../wiki/models.ClearCartError#errordetail)
- [status](../wiki/models.ClearCartError#status)

## Constructors

### constructor

• **new ClearCartError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/cart.ts:163](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L163)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/cart.ts:161](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L161)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.ClearCartErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/cart.ts:165](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L165)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/cart.ts:164](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L164)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/cart.ts:162](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L162)
