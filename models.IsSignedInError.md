# Class: IsSignedInError

[models](../wiki/models).IsSignedInError

Describes the Is signed in SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`IsSignedInErrorCode`](../wiki/models.IsSignedInErrorCode)\>

  ↳ **`IsSignedInError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.IsSignedInError#constructor)

### Properties

- [data](../wiki/models.IsSignedInError#data)
- [err](../wiki/models.IsSignedInError#err)
- [errorCode](../wiki/models.IsSignedInError#errorcode)
- [errorDetail](../wiki/models.IsSignedInError#errordetail)
- [status](../wiki/models.IsSignedInError#status)

## Constructors

### constructor

• **new IsSignedInError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:280](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L280)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:278](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L278)

___

### errorCode

• **errorCode**: `undefined` \| [`IsSignedInErrorCode`](../wiki/models.IsSignedInErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:282](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L282)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:281](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L281)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:279](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L279)
