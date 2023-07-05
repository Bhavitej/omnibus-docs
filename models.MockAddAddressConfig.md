# Class: MockAddAddressConfig

[models](../wiki/models).MockAddAddressConfig

Describes the Mock Add address SDK config.

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockAddAddressParams`](../wiki/models.MockAddAddressParams), [`AddAddressErrorCode`](../wiki/models.AddAddressErrorCode)\>

  ↳ **`MockAddAddressConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockAddAddressConfig#constructor)

### Properties

- [err](../wiki/models.MockAddAddressConfig#err)
- [errorCode](../wiki/models.MockAddAddressConfig#errorcode)
- [params](../wiki/models.MockAddAddressConfig#params)

## Constructors

### constructor

• **new MockAddAddressConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:665](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L665)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.AddAddressErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:666](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L666)

___

### params

• `Optional` **params**: [`MockAddAddressParams`](../wiki/models.MockAddAddressParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:667](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L667)
