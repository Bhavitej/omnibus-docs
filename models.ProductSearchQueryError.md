# Class: ProductSearchQueryError

[models](../wiki/models).ProductSearchQueryError

Describes the Product search Query SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`ProductSearchQueryErrorCode`](../wiki/models.ProductSearchQueryErrorCode)\>

  ↳ **`ProductSearchQueryError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.ProductSearchQueryError#constructor)

### Properties

- [data](../wiki/models.ProductSearchQueryError#data)
- [err](../wiki/models.ProductSearchQueryError#err)
- [errorCode](../wiki/models.ProductSearchQueryError#errorcode)
- [errorDetail](../wiki/models.ProductSearchQueryError#errordetail)
- [status](../wiki/models.ProductSearchQueryError#status)

## Constructors

### constructor

• **new ProductSearchQueryError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/search.ts:44](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L44)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/search.ts:42](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L42)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.ProductSearchQueryErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/search.ts:46](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L46)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/search.ts:45](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L45)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/search.ts:43](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L43)
