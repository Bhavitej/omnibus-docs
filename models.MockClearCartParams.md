# Class: MockClearCartParams

[models](../wiki/models).MockClearCartParams

Describes the Clear cart SDK params

## Table of contents

### Properties

- [cartItems](../wiki/models.MockClearCartParams#cartitems)
- [totalNumOfProducts](../wiki/models.MockClearCartParams#totalnumofproducts)

## Properties

### cartItems

• `Optional` **cartItems**: [`MockCartItemParams`](../wiki/models.MockCartItemParams)[]

The detailed list of products and their respective quantities, that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are specified, this parameter takes precedence over totalNumOfProducts.

#### Defined in

[models/cart.ts:344](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L344)

___

### totalNumOfProducts

• `Optional` **totalNumOfProducts**: `number`

The total number of products that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are not specified, all products in the file are returned.

#### Defined in

[models/cart.ts:340](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L340)
