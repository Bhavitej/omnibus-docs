# Class: AddToCartError

[models](../wiki/models).AddToCartError

Describes the Add to cart SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`AddToCartErrorCode`](../wiki/models.AddToCartErrorCode)\>

  ↳ **`AddToCartError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.AddToCartError#constructor)

### Properties

- [data](../wiki/models.AddToCartError#data)
- [err](../wiki/models.AddToCartError#err)
- [errorCode](../wiki/models.AddToCartError#errorcode)
- [errorDetail](../wiki/models.AddToCartError#errordetail)
- [status](../wiki/models.AddToCartError#status)

## Constructors

### constructor

• **new AddToCartError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/cart.ts:139](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L139)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/cart.ts:137](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L137)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.AddToCartErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/cart.ts:141](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L141)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/cart.ts:140](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L140)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/cart.ts:138](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L138)
