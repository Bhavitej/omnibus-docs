# Class: MockGetCustomerProfileConfig

[models](../wiki/models).MockGetCustomerProfileConfig

Describes the Mock Get Customer Profile SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockGetCustomerProfileParams`](../wiki/models.MockGetCustomerProfileParams), [`GetCustomerProfileErrorCode`](../wiki/models.GetCustomerProfileErrorCode)\>

  ↳ **`MockGetCustomerProfileConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockGetCustomerProfileConfig#constructor)

### Properties

- [err](../wiki/models.MockGetCustomerProfileConfig#err)
- [errorCode](../wiki/models.MockGetCustomerProfileConfig#errorcode)
- [params](../wiki/models.MockGetCustomerProfileConfig#params)

## Constructors

### constructor

• **new MockGetCustomerProfileConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/account.ts:594](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L594)

___

### errorCode

• `Optional` **errorCode**: [`UNAUTHORISED_REQUEST`](../wiki/models.GetCustomerProfileErrorCode#unauthorised_request)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/account.ts:595](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L595)

___

### params

• `Optional` **params**: [`MockGetCustomerProfileParams`](../wiki/models.MockGetCustomerProfileParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/account.ts:596](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/account.ts#L596)
