# Class: GetCartError

[models](../wiki/models).GetCartError

Describes the Get cart SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetCartErrorCode`](../wiki/models.GetCartErrorCode)\>

  ↳ **`GetCartError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetCartError#constructor)

### Properties

- [data](../wiki/models.GetCartError#data)
- [err](../wiki/models.GetCartError#err)
- [errorCode](../wiki/models.GetCartError#errorcode)
- [errorDetail](../wiki/models.GetCartError#errordetail)
- [status](../wiki/models.GetCartError#status)

## Constructors

### constructor

• **new GetCartError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/cart.ts:175](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L175)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/cart.ts:173](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L173)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetCartErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/cart.ts:177](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L177)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/cart.ts:176](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L176)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/cart.ts:174](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L174)
