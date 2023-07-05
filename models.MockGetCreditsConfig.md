# Class: MockGetCreditsConfig

[models](../wiki/models).MockGetCreditsConfig

Describes the Mock Get Credits SDK Config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetCreditsParams`](../wiki/models.MockGetCreditsParams), [`GetCreditsErrorCode`](../wiki/models.GetCreditsErrorCode)\>

  ↳ **`MockGetCreditsConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetCreditsConfig#constructor)

### Properties

- [err](../wiki/models.MockGetCreditsConfig#err)
- [errorCode](../wiki/models.MockGetCreditsConfig#errorcode)
- [params](../wiki/models.MockGetCreditsConfig#params)

## Constructors

### constructor

• **new MockGetCreditsConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/checkout.ts:565](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L565)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetCreditsErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/checkout.ts:566](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L566)

___

### params

• `Optional` **params**: [`MockGetCreditsParams`](../wiki/models.MockGetCreditsParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/checkout.ts:567](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L567)
