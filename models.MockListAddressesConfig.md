# Class: MockListAddressesConfig

[models](../wiki/models).MockListAddressesConfig

Describes the Mock List Addresses SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockListAddressesParams`](../wiki/models.MockListAddressesParams), [`ListAddressesErrorCode`](../wiki/models.ListAddressesErrorCode)\>

  ↳ **`MockListAddressesConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockListAddressesConfig#constructor)

### Properties

- [err](../wiki/models.MockListAddressesConfig#err)
- [errorCode](../wiki/models.MockListAddressesConfig#errorcode)
- [params](../wiki/models.MockListAddressesConfig#params)

## Constructors

### constructor

• **new MockListAddressesConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/checkout.ts:460](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L460)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.ListAddressesErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/checkout.ts:461](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L461)

___

### params

• `Optional` **params**: [`MockListAddressesParams`](../wiki/models.MockListAddressesParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/checkout.ts:462](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L462)
