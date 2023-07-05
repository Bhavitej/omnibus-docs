# Class: MockAddToCartParams

[models](../wiki/models).MockAddToCartParams

Describes the Mock Add to cart SDK params

## Table of contents

### Properties

- [cartItems](../wiki/models.MockAddToCartParams#cartitems)
- [totalNumOfProducts](../wiki/models.MockAddToCartParams#totalnumofproducts)

## Properties

### cartItems

• `Optional` **cartItems**: [`MockCartItemParams`](../wiki/models.MockCartItemParams)[]

The detailed list of products and their respective quantities, that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are specified, this parameter takes precedence over totalNumOfProducts.

#### Defined in

[models/cart.ts:274](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L274)

___

### totalNumOfProducts

• `Optional` **totalNumOfProducts**: `number`

The total number of products that are in the cart. These products are taken from sample-products date file of Forge. If both totalNumOfProducts and cartItems are not specified, all products in the file are returned.

#### Defined in

[models/cart.ts:270](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/cart.ts#L270)
