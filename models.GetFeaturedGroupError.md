# Class: GetFeaturedGroupError

[models](../wiki/models).GetFeaturedGroupError

Describes the Get Featured products SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetFeaturedGroupErrorCode`](../wiki/models.GetFeaturedGroupErrorCode)\>

  ↳ **`GetFeaturedGroupError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetFeaturedGroupError#constructor)

### Properties

- [data](../wiki/models.GetFeaturedGroupError#data)
- [err](../wiki/models.GetFeaturedGroupError#err)
- [errorCode](../wiki/models.GetFeaturedGroupError#errorcode)
- [errorDetail](../wiki/models.GetFeaturedGroupError#errordetail)
- [status](../wiki/models.GetFeaturedGroupError#status)

## Constructors

### constructor

• **new GetFeaturedGroupError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:163](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L163)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:161](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L161)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetFeaturedGroupErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:165](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L165)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:164](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L164)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:162](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L162)
