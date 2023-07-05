# Class: MockEvaluatesRulesParams

[models](../wiki/models).MockEvaluatesRulesParams

Describes the Mock evaluate rules SDK params

## Table of contents

### Properties

- [cartItems](../wiki/models.MockEvaluatesRulesParams#cartitems)
- [couponcode](../wiki/models.MockEvaluatesRulesParams#couponcode)
- [couponvalue](../wiki/models.MockEvaluatesRulesParams#couponvalue)
- [shippingcost](../wiki/models.MockEvaluatesRulesParams#shippingcost)
- [totalNumOfProducts](../wiki/models.MockEvaluatesRulesParams#totalnumofproducts)

## Properties

### cartItems

• `Optional` **cartItems**: [`MockCartItemParams`](../wiki/models.MockCartItemParams)[]

The detailed list of products and their respective quantities, that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are specified, this parameter takes precedence over totalNumOfProducts.

#### Defined in

[models/checkout.ts:594](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L594)

___

### couponcode

• `Optional` **couponcode**: `string`

The coupon code applied on the order

#### Defined in

[models/checkout.ts:602](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L602)

___

### couponvalue

• `Optional` **couponvalue**: `number`

The value of the coupon code applied

#### Defined in

[models/checkout.ts:606](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L606)

___

### shippingcost

• **shippingcost**: `number` = `0`

The shipping cost of the order

#### Defined in

[models/checkout.ts:598](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L598)

___

### totalNumOfProducts

• `Optional` **totalNumOfProducts**: `number`

The total number of products that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are not specified, all products in the file are returned.

#### Defined in

[models/checkout.ts:590](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/checkout.ts#L590)
