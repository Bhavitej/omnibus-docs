# Class: MockUpdateCartParams

[models](../wiki/models).MockUpdateCartParams

Describes the Mock update cart SDK params

## Table of contents

### Properties

- [cartItems](../wiki/models.MockUpdateCartParams#cartitems)
- [totalNumOfProducts](../wiki/models.MockUpdateCartParams#totalnumofproducts)

## Properties

### cartItems

• `Optional` **cartItems**: [`MockCartItemParams`](../wiki/models.MockCartItemParams)[]

The detailed list of products and their respective quantities, that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are specified, this parameter takes precedence over totalNumOfProducts.

#### Defined in

[models/cart.ts:384](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L384)

___

### totalNumOfProducts

• `Optional` **totalNumOfProducts**: `number`

The total number of products that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are not specified, all products in the file are returned.

#### Defined in

[models/cart.ts:380](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L380)
