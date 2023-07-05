# Class: GetRecentlyAddedProductsError

[models](../wiki/models).GetRecentlyAddedProductsError

Describes the Get Recently added products SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetRecentlyAddedProductsErrorCode`](../wiki/models.GetRecentlyAddedProductsErrorCode)\>

  ↳ **`GetRecentlyAddedProductsError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetRecentlyAddedProductsError#constructor)

### Properties

- [data](../wiki/models.GetRecentlyAddedProductsError#data)
- [err](../wiki/models.GetRecentlyAddedProductsError#err)
- [errorCode](../wiki/models.GetRecentlyAddedProductsError#errorcode)
- [errorDetail](../wiki/models.GetRecentlyAddedProductsError#errordetail)
- [status](../wiki/models.GetRecentlyAddedProductsError#status)

## Constructors

### constructor

• **new GetRecentlyAddedProductsError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:184](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L184)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:182](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L182)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetRecentlyAddedProductsErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:186](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L186)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:185](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L185)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:183](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L183)
