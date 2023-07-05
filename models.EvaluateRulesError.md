# Class: EvaluateRulesError

[models](../wiki/models).EvaluateRulesError

Describes the Evaluate Rules SDK error

## Hierarchy

- [`BaseError`](../wiki/models.BaseError)<`string`, [`EvaluatesRulesErrorCode`](../wiki/models.EvaluatesRulesErrorCode)\>

  ↳ **`EvaluateRulesError`**

## Table of contents

### Constructors

- [constructor](../wiki/models.EvaluateRulesError#constructor)

### Properties

- [data](../wiki/models.EvaluateRulesError#data)
- [err](../wiki/models.EvaluateRulesError#err)
- [errorCode](../wiki/models.EvaluateRulesError#errorcode)
- [errorDetail](../wiki/models.EvaluateRulesError#errordetail)
- [status](../wiki/models.EvaluateRulesError#status)

## Constructors

### constructor

• **new EvaluateRulesError**()

#### Inherited from

[BaseError](../wiki/models.BaseError).[constructor](../wiki/models.BaseError#constructor)

## Properties

### data

• `Optional` **data**: `string`

The data of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[data](../wiki/models.BaseError#data)

#### Defined in

[models/checkout.ts:390](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L390)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Overrides

[BaseError](../wiki/models.BaseError).[err](../wiki/models.BaseError#err)

#### Defined in

[models/checkout.ts:388](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L388)

___

### errorCode

• **errorCode**: `undefined` \| [`EvaluatesRulesErrorCode`](../wiki/models.EvaluatesRulesErrorCode)

The standard error code which indicates a type of error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorCode](../wiki/models.BaseError#errorcode)

#### Defined in

[models/checkout.ts:392](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L392)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Overrides

[BaseError](../wiki/models.BaseError).[errorDetail](../wiki/models.BaseError#errordetail)

#### Defined in

[models/checkout.ts:391](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L391)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Overrides

[BaseError](../wiki/models.BaseError).[status](../wiki/models.BaseError#status)

#### Defined in

[models/checkout.ts:389](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L389)
