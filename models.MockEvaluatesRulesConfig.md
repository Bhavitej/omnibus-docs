# Class: MockEvaluatesRulesConfig

[models](../wiki/models).MockEvaluatesRulesConfig

Describes the Mock evaluate rules SDK config

## Hierarchy

- [`BaseMockConfig`](../wiki/models.BaseMockConfig)<[`MockEvaluatesRulesParams`](../wiki/models.MockEvaluatesRulesParams), [`EvaluatesRulesErrorCode`](../wiki/models.EvaluatesRulesErrorCode)\>

  ↳ **`MockEvaluatesRulesConfig`**

## Table of contents

### Constructors

- [constructor](../wiki/models.MockEvaluatesRulesConfig#constructor)

### Properties

- [err](../wiki/models.MockEvaluatesRulesConfig#err)
- [errorCode](../wiki/models.MockEvaluatesRulesConfig#errorcode)
- [params](../wiki/models.MockEvaluatesRulesConfig#params)

## Constructors

### constructor

• **new MockEvaluatesRulesConfig**()

#### Inherited from

[BaseMockConfig](../wiki/models.BaseMockConfig).[constructor](../wiki/models.BaseMockConfig#constructor)

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[err](../wiki/models.BaseMockConfig#err)

#### Defined in

[models/checkout.ts:620](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L620)

___

### errorCode

• `Optional` **errorCode**: [`EvaluatesRulesErrorCode`](../wiki/models.EvaluatesRulesErrorCode)

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[errorCode](../wiki/models.BaseMockConfig#errorcode)

#### Defined in

[models/checkout.ts:621](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L621)

___

### params

• `Optional` **params**: [`MockEvaluatesRulesParams`](../wiki/models.MockEvaluatesRulesParams)

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Overrides

[BaseMockConfig](../wiki/models.BaseMockConfig).[params](../wiki/models.BaseMockConfig#params)

#### Defined in

[models/checkout.ts:622](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L622)
