# Class: GetCatalogueInfoError

[models](../wiki/models).GetCatalogueInfoError

Describes the Get Catalogue Info SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`GetCatalogueInfoErrorCode`](../wiki/models.GetCatalogueInfoErrorCode)\>

  ↳ **`GetCatalogueInfoError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.GetCatalogueInfoError#constructor)

### Properties

- [data](../wiki/models.GetCatalogueInfoError#data)
- [err](../wiki/models.GetCatalogueInfoError#err)
- [errorCode](../wiki/models.GetCatalogueInfoError#errorcode)
- [errorDetail](../wiki/models.GetCatalogueInfoError#errordetail)
- [status](../wiki/models.GetCatalogueInfoError#status)

## Constructors

### constructor

• **new GetCatalogueInfoError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/catalogue.ts:59](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L59)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/catalogue.ts:57](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L57)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.GetCatalogueInfoErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/catalogue.ts:61](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L61)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/catalogue.ts:60](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L60)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/catalogue.ts:58](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/catalogue.ts#L58)
