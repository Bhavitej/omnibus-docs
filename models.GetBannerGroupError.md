# Class: GetBannerGroupError

[models](../wiki/models).GetBannerGroupError

Describes the Get Banner Group SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetBannerGroupErrorCode`](../wiki/models.GetBannerGroupErrorCode)\>

  ↳ **`GetBannerGroupError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetBannerGroupError#constructor)

### Properties

- [data](../wiki/models.GetBannerGroupError#data)
- [err](../wiki/models.GetBannerGroupError#err)
- [errorCode](../wiki/models.GetBannerGroupError#errorcode)
- [errorDetail](../wiki/models.GetBannerGroupError#errordetail)
- [status](../wiki/models.GetBannerGroupError#status)

## Constructors

### constructor

• **new GetBannerGroupError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:225](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L225)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:223](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L223)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetBannerGroupErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:227](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L227)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:226](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L226)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:224](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L224)
