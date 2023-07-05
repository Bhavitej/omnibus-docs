# Class: ListAddressesError

[models](../wiki/models).ListAddressesError

Describes the List addresses SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`ListAddressesErrorCode`](../wiki/models.ListAddressesErrorCode)\>

  ↳ **`ListAddressesError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.ListAddressesError#constructor)

### Properties

- [data](../wiki/models.ListAddressesError#data)
- [err](../wiki/models.ListAddressesError#err)
- [errorCode](../wiki/models.ListAddressesError#errorcode)
- [errorDetail](../wiki/models.ListAddressesError#errordetail)
- [status](../wiki/models.ListAddressesError#status)

## Constructors

### constructor

• **new ListAddressesError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/checkout.ts:341](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L341)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/checkout.ts:339](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L339)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.ListAddressesErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/checkout.ts:343](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L343)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/checkout.ts:342](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L342)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/checkout.ts:340](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L340)
