# Class: AutoSuggestProductSearchQueryError

[models](../wiki/models).AutoSuggestProductSearchQueryError

Describes the Auto suggest Product search Query SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`AutoSuggestProductSearchQueryErrorCode`](../wiki/models.AutoSuggestProductSearchQueryErrorCode)\>

  ↳ **`AutoSuggestProductSearchQueryError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.AutoSuggestProductSearchQueryError#constructor)

### Properties

- [data](../wiki/models.AutoSuggestProductSearchQueryError#data)
- [err](../wiki/models.AutoSuggestProductSearchQueryError#err)
- [errorCode](../wiki/models.AutoSuggestProductSearchQueryError#errorcode)
- [errorDetail](../wiki/models.AutoSuggestProductSearchQueryError#errordetail)
- [status](../wiki/models.AutoSuggestProductSearchQueryError#status)

## Constructors

### constructor

• **new AutoSuggestProductSearchQueryError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/search.ts:66](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L66)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/search.ts:64](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L64)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.AutoSuggestProductSearchQueryErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/search.ts:68](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L68)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/search.ts:67](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L67)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/search.ts:65](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L65)
