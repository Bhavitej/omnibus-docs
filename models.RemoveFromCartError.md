# Class: RemoveFromCartError

[models](../wiki/models).RemoveFromCartError

Describes the Remove from cart SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`RemoveFromCartErrorCode`](../wiki/models.RemoveFromCartErrorCode)\>

  ↳ **`RemoveFromCartError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.RemoveFromCartError#constructor)

### Properties

- [data](../wiki/models.RemoveFromCartError#data)
- [err](../wiki/models.RemoveFromCartError#err)
- [errorCode](../wiki/models.RemoveFromCartError#errorcode)
- [errorDetail](../wiki/models.RemoveFromCartError#errordetail)
- [status](../wiki/models.RemoveFromCartError#status)

## Constructors

### constructor

• **new RemoveFromCartError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/cart.ts:151](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L151)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/cart.ts:149](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L149)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.RemoveFromCartErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/cart.ts:153](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L153)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/cart.ts:152](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L152)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/cart.ts:150](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L150)
