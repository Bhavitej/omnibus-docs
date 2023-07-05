# Class: MockPlaceOrderParams

[models](../wiki/models).MockPlaceOrderParams

Describes the Mock Place order SDK params

## Table of contents

### Properties

- [amount](../wiki/models.MockPlaceOrderParams#amount)
- [orderid](../wiki/models.MockPlaceOrderParams#orderid)
- [paymentMethodNote](../wiki/models.MockPlaceOrderParams#paymentmethodnote)

## Properties

### amount

• **amount**: `number` = `0`

The total order amount payable

#### Defined in

[models/checkout.ts:474](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L474)

___

### orderid

• **orderid**: `string` = `''`

The id of order

#### Defined in

[models/checkout.ts:478](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L478)

___

### paymentMethodNote

• **paymentMethodNote**: [`PaymentMethodNote`](../wiki/models.PaymentMethodNote) = `PaymentMethodNote.COD`

The method of payment chosen by customer

#### Defined in

[models/checkout.ts:482](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L482)
