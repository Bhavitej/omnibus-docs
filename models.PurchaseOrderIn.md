# Class: PurchaseOrderIn

[models](../wiki/models).PurchaseOrderIn

Describes the details of purchase order placed by the customer

## Table of contents

### Constructors

- [constructor](../wiki/models.PurchaseOrderIn#constructor)

### Properties

- [billingaddress](../wiki/models.PurchaseOrderIn#billingaddress)
- [billingaddresscode](../wiki/models.PurchaseOrderIn#billingaddresscode)
- [couponcode](../wiki/models.PurchaseOrderIn#couponcode)
- [creditsToAdd](../wiki/models.PurchaseOrderIn#creditstoadd)
- [creditsToReduce](../wiki/models.PurchaseOrderIn#creditstoreduce)
- [currency](../wiki/models.PurchaseOrderIn#currency)
- [giftwrap](../wiki/models.PurchaseOrderIn#giftwrap)
- [giftwrapmsg](../wiki/models.PurchaseOrderIn#giftwrapmsg)
- [note](../wiki/models.PurchaseOrderIn#note)
- [paymentmethodnote](../wiki/models.PurchaseOrderIn#paymentmethodnote)
- [premiumshipping](../wiki/models.PurchaseOrderIn#premiumshipping)
- [sameaddress](../wiki/models.PurchaseOrderIn#sameaddress)
- [shippingaddress](../wiki/models.PurchaseOrderIn#shippingaddress)
- [shippingaddresscode](../wiki/models.PurchaseOrderIn#shippingaddresscode)

## Constructors

### constructor

• **new PurchaseOrderIn**()

## Properties

### billingaddress

• `Optional` **billingaddress**: [`Address`](../wiki/models.Address)

#### Defined in

[models/checkout.ts:238](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L238)

___

### billingaddresscode

• `Optional` **billingaddresscode**: `string`

#### Defined in

[models/checkout.ts:240](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L240)

___

### couponcode

• `Optional` **couponcode**: `string`

#### Defined in

[models/checkout.ts:247](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L247)

___

### creditsToAdd

• `Optional` **creditsToAdd**: [`CreditsToAddIn`](../wiki/models.CreditsToAddIn)[]

#### Defined in

[models/checkout.ts:249](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L249)

___

### creditsToReduce

• `Optional` **creditsToReduce**: [`CreditsToReduceIn`](../wiki/models.CreditsToReduceIn)

#### Defined in

[models/checkout.ts:248](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L248)

___

### currency

• **currency**: `string` = `'INR'`

#### Defined in

[models/checkout.ts:250](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L250)

___

### giftwrap

• **giftwrap**: `boolean` = `false`

#### Defined in

[models/checkout.ts:243](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L243)

___

### giftwrapmsg

• `Optional` **giftwrapmsg**: `string`

#### Defined in

[models/checkout.ts:244](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L244)

___

### note

• `Optional` **note**: `string`

#### Defined in

[models/checkout.ts:245](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L245)

___

### paymentmethodnote

• **paymentmethodnote**: [`PaymentMethodNote`](../wiki/models.PaymentMethodNote) = `PaymentMethodNote.COD`

#### Defined in

[models/checkout.ts:246](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L246)

___

### premiumshipping

• **premiumshipping**: `boolean` = `false`

#### Defined in

[models/checkout.ts:242](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L242)

___

### sameaddress

• **sameaddress**: `boolean` = `true`

#### Defined in

[models/checkout.ts:239](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L239)

___

### shippingaddress

• `Optional` **shippingaddress**: [`Address`](../wiki/models.Address)

#### Defined in

[models/checkout.ts:237](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L237)

___

### shippingaddresscode

• `Optional` **shippingaddresscode**: `string`

#### Defined in

[models/checkout.ts:241](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L241)
