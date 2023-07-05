# Class: UpdateProfileError

[models](../wiki/models).UpdateProfileError

Describes the Update Profile SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`UpdateProfileErrorCode`](../wiki/models.UpdateProfileErrorCode)\>

  ↳ **`UpdateProfileError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.UpdateProfileError#constructor)

### Properties

- [data](../wiki/models.UpdateProfileError#data)
- [err](../wiki/models.UpdateProfileError#err)
- [errorCode](../wiki/models.UpdateProfileError#errorcode)
- [errorDetail](../wiki/models.UpdateProfileError#errordetail)
- [status](../wiki/models.UpdateProfileError#status)

## Constructors

### constructor

• **new UpdateProfileError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/account.ts:256](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L256)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/account.ts:254](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L254)

___

### errorCode

• **errorCode**: `undefined` \| [`UpdateProfileErrorCode`](../wiki/models.UpdateProfileErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/account.ts:258](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L258)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/account.ts:257](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L257)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/account.ts:255](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L255)
