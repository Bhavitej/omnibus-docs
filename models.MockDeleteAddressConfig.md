# Class: MockDeleteAddressConfig

[models](../wiki/models).MockDeleteAddressConfig

Describes the Mock Delete address SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockDeleteAddressParams`](../wiki/models.MockDeleteAddressParams), [`DeleteAddressErrorCode`](../wiki/models.DeleteAddressErrorCode)\>

  ↳ **`MockDeleteAddressConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockDeleteAddressConfig#constructor)

### Properties

- [err](../wiki/models.MockDeleteAddressConfig#err)
- [errorCode](../wiki/models.MockDeleteAddressConfig#errorcode)
- [params](../wiki/models.MockDeleteAddressConfig#params)

## Constructors

### constructor

• **new MockDeleteAddressConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:687](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L687)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.DeleteAddressErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:688](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L688)

___

### params

• `Optional` **params**: [`MockDeleteAddressParams`](../wiki/models.MockDeleteAddressParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:689](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L689)
