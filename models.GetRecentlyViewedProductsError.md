# Class: GetRecentlyViewedProductsError

[models](../wiki/models).GetRecentlyViewedProductsError

Describes the Get Recently viewed products SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetRecentlyViewedProductsErrorCode`](../wiki/models.GetRecentlyViewedProductsErrorCode)\>

  ↳ **`GetRecentlyViewedProductsError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetRecentlyViewedProductsError#constructor)

### Properties

- [data](../wiki/models.GetRecentlyViewedProductsError#data)
- [err](../wiki/models.GetRecentlyViewedProductsError#err)
- [errorCode](../wiki/models.GetRecentlyViewedProductsError#errorcode)
- [errorDetail](../wiki/models.GetRecentlyViewedProductsError#errordetail)
- [status](../wiki/models.GetRecentlyViewedProductsError#status)

## Constructors

### constructor

• **new GetRecentlyViewedProductsError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:204](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L204)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:202](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L202)

___

### errorCode

• **errorCode**: `undefined` \| [`GetRecentlyViewedProductsErrorCode`](../wiki/models.GetRecentlyViewedProductsErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:206](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L206)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:205](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L205)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:203](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L203)
