# Class: GetMenuError

[models](../wiki/models).GetMenuError

Describes the Get Menu SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetMenuErrorCode`](../wiki/models.GetMenuErrorCode)\>

  ↳ **`GetMenuError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetMenuError#constructor)

### Properties

- [data](../wiki/models.GetMenuError#data)
- [err](../wiki/models.GetMenuError#err)
- [errorCode](../wiki/models.GetMenuError#errorcode)
- [errorDetail](../wiki/models.GetMenuError#errordetail)
- [status](../wiki/models.GetMenuError#status)

## Constructors

### constructor

• **new GetMenuError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/home.ts:265](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L265)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/home.ts:263](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L263)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetMenuErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/home.ts:267](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L267)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/home.ts:266](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L266)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/home.ts:264](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/home.ts#L264)
