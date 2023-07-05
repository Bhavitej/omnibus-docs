# Class: CartPage

[resources](../wiki/resources).[CartV1](../wiki/resources.CartV1).CartPage

## Hierarchy

- `BaseClassV1`

  ↳ **`CartPage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.CartV1.CartPage#constructor)

### Methods

- [addToCart](../wiki/resources.CartV1.CartPage#addtocart)
- [clearCart](../wiki/resources.CartV1.CartPage#clearcart)
- [getCart](../wiki/resources.CartV1.CartPage#getcart)
- [removeFromCart](../wiki/resources.CartV1.CartPage#removefromcart)
- [updateCart](../wiki/resources.CartV1.CartPage#updatecart)

## Constructors

### constructor

• **new CartPage**()

Initialises the CartPage SDK

**`Example`**

Use this below JS snippet to create an instance of CartPage SDK 
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
```

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/cart-v1.ts:24](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/cart-v1.ts#L24)

## Methods

### addToCart

▸ **addToCart**(`cartItem`, `callback`, `mockConfig?`): `undefined` \| ``false``

Adds the product(item) to cart

**`Example`**

For live SDK in production use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.addToCart(cartItem, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on addToCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on addToCart success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.addToCart(cartItem, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on addToCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on addToCart success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cartItem` | [`CartItemIn`](../wiki/models.CartItemIn) | The cart item information |
| `callback` | (`errorObj`: ``null`` \| [`AddToCartError`](../wiki/models.AddToCartError), `responseObj`: ``null`` \| [`Cart`](../wiki/models.Cart)) => `void` | The Callback function |
| `mockConfig?` | [`MockAddToCartConfig`](../wiki/models.MockAddToCartConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/cart-v1.ts:59](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/cart-v1.ts#L59)

___

### clearCart

▸ **clearCart**(`callback`, `mockConfig?`): `undefined` \| ``false``

Clear all items from the cart

**`Example`**

For live SDK in production use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.clearCart((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on clearCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on clearCart success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.clearCart((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on clearCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on clearCart success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`errorObj`: ``null`` \| [`ClearCartError`](../wiki/models.ClearCartError), `responseObj`: ``null`` \| [`Cart`](../wiki/models.Cart)) => `void` | The Callback function |
| `mockConfig?` | [`MockClearCartConfig`](../wiki/models.MockClearCartConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/cart-v1.ts:176](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/cart-v1.ts#L176)

___

### getCart

▸ **getCart**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieve the cart

**`Example`**

For live SDK in production use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.getCart((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getCart success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.getCart((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getCart success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`errorObj`: ``null`` \| [`GetCartError`](../wiki/models.GetCartError), `responseObj`: ``null`` \| [`Cart`](../wiki/models.Cart)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetCartConfig`](../wiki/models.MockGetCartConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/cart-v1.ts:230](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/cart-v1.ts#L230)

___

### removeFromCart

▸ **removeFromCart**(`cartItem`, `callback`, `mockConfig?`): `undefined` \| ``false``

Remove the product(item) from cart

**`Example`**

For live SDK in production use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.removeFromCart(cartItem, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on removeFromCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on removeFromCart success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.removeFromCart(cartItem, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on removeFromCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on removeFromCart success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cartItem` | [`CartItemIn`](../wiki/models.CartItemIn) | The cart item information |
| `callback` | (`errorObj`: ``null`` \| [`RemoveFromCartError`](../wiki/models.RemoveFromCartError), `responseObj`: ``null`` \| [`Cart`](../wiki/models.Cart)) => `void` | The Callback function |
| `mockConfig?` | [`MockRemoveFromCartConfig`](../wiki/models.MockRemoveFromCartConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/cart-v1.ts:118](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/cart-v1.ts#L118)

___

### updateCart

▸ **updateCart**(`cartItem`, `callback`, `mockConfig?`): `undefined` \| ``false``

Update the cart

**`Example`**

For live SDK in production use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.updateCart(cartItem, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on updateCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on updateCart success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const cartPageSDK = new OMNIBUS.CartV1.CartPage();
cartPageSDK.updateCart(cartItem, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on updateCart failure depending on errorObj.errorCode 
    }

    // Appropriate actions on updateCart success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cartItem` | [`CartItemIn`](../wiki/models.CartItemIn) | The cart item information to be updated |
| `callback` | (`errorObj`: ``null`` \| [`UpdateCartError`](../wiki/models.UpdateCartError), `responseObj`: ``null`` \| [`Cart`](../wiki/models.Cart)) => `void` | The Callback function |
| `mockConfig?` | [`MockUpdateCartConfig`](../wiki/models.MockUpdateCartConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/cart-v1.ts:284](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/cart-v1.ts#L284)
