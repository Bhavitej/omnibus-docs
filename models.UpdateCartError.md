# Class: UpdateCartError

[models](../wiki/models).UpdateCartError

Describes the Update cart SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`UpdateCartErrorCode`](../wiki/models.UpdateCartErrorCode)\>

  ↳ **`UpdateCartError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.UpdateCartError#constructor)

### Properties

- [data](../wiki/models.UpdateCartError#data)
- [err](../wiki/models.UpdateCartError#err)
- [errorCode](../wiki/models.UpdateCartError#errorcode)
- [errorDetail](../wiki/models.UpdateCartError#errordetail)
- [status](../wiki/models.UpdateCartError#status)

## Constructors

### constructor

• **new UpdateCartError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/cart.ts:187](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L187)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/cart.ts:185](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L185)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.UpdateCartErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/cart.ts:189](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L189)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/cart.ts:188](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L188)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/cart.ts:186](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L186)
