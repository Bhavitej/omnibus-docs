# Class: DeleteAddressError

[models](../wiki/models).DeleteAddressError

Describes the Delete address SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`DeleteAddressErrorCode`](../wiki/models.DeleteAddressErrorCode)\>

  ↳ **`DeleteAddressError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.DeleteAddressError#constructor)

### Properties

- [data](../wiki/models.DeleteAddressError#data)
- [err](../wiki/models.DeleteAddressError#err)
- [errorCode](../wiki/models.DeleteAddressError#errorcode)
- [errorDetail](../wiki/models.DeleteAddressError#errordetail)
- [status](../wiki/models.DeleteAddressError#status)

## Constructors

### constructor

• **new DeleteAddressError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:316](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L316)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:314](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L314)

___

### errorCode

• **errorCode**: `undefined` \| [`UNAUTHORISED_REQUEST`](../wiki/models.DeleteAddressErrorCode#unauthorised_request)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:318](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L318)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:317](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L317)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:315](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L315)
