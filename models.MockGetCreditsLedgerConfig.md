# Class: MockGetCreditsLedgerConfig

[models](../wiki/models).MockGetCreditsLedgerConfig

Describes the Mock Get Credits Ledger SDK Config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetCreditsLedgerParams`](../wiki/models.MockGetCreditsLedgerParams), [`GetCreditLedgerErrorCode`](../wiki/models.GetCreditLedgerErrorCode)\>

  ↳ **`MockGetCreditsLedgerConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetCreditsLedgerConfig#constructor)

### Properties

- [err](../wiki/models.MockGetCreditsLedgerConfig#err)
- [errorCode](../wiki/models.MockGetCreditsLedgerConfig#errorcode)
- [params](../wiki/models.MockGetCreditsLedgerConfig#params)

## Constructors

### constructor

• **new MockGetCreditsLedgerConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/checkout.ts:576](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L576)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetCreditLedgerErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/checkout.ts:577](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L577)

___

### params

• `Optional` **params**: [`MockGetCreditsLedgerParams`](../wiki/models.MockGetCreditsLedgerParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/checkout.ts:578](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L578)
