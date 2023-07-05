# Class: GetSiteInfoError

[models](../wiki/models).GetSiteInfoError

Describes the Get Site Info SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetSiteInfoErrorCode`](../wiki/models.GetSiteInfoErrorCode)\>

  ↳ **`GetSiteInfoError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetSiteInfoError#constructor)

### Properties

- [data](../wiki/models.GetSiteInfoError#data)
- [err](../wiki/models.GetSiteInfoError#err)
- [errorCode](../wiki/models.GetSiteInfoError#errorcode)
- [errorDetail](../wiki/models.GetSiteInfoError#errordetail)
- [status](../wiki/models.GetSiteInfoError#status)

## Constructors

### constructor

• **new GetSiteInfoError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:277](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L277)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:275](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L275)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetSiteInfoErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:279](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L279)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:278](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L278)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:276](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L276)
