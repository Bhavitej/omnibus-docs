# Class: WishlistPage

[resources](../wiki/resources).[WishlistV1](../wiki/resources.WishlistV1).WishlistPage

## Hierarchy

- `BaseClassV1`

  ↳ **`WishlistPage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.WishlistV1.WishlistPage#constructor)

### Methods

- [removeFromWishlist](../wiki/resources.WishlistV1.WishlistPage#removefromwishlist)

## Constructors

### constructor

• **new WishlistPage**()

Initialises the WislistPage SDK

**`Example`**

Use this below JS snippet to create an instance of WislistPage SDK 
```js
const wishlistPageSDK = new OMNIBUS.WishlistV1.WislistPage();
```

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/wishlist-v1.ts:23](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/wishlist-v1.ts#L23)

## Methods

### removeFromWishlist

▸ **removeFromWishlist**(`wishlistId`, `callback`, `mockConfig?`): `undefined` \| ``false``

Removes an item from the wishlist based on the Wishlist ID

**`Example`**

For live SDK in production use the below snippet for reference
```js
const wishlistPageSDK = new OMNIBUS.WishlistV1.WishlistPage();
wishlistPageSDK.removeFromWishlist(wishlistId, (error, responseObj) => {
    if (error) {
         // Appropriate actions on removeFromWishlist failure depending on error.errorCode 
    }

    // Appropriate actions on removeFromWishlist success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const wishlistPageSDK = new OMNIBUS.WishlistV1.WishlistPage();
wishlistPageSDK.removeFromWishlist(wishlistId, (error, responseObj) => {
    if (error) {
         // Appropriate actions on removeFromWishlist failure depending on error.errorCode 
    }

    // Appropriate actions on removeFromWishlist success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `wishlistId` | `string` | The Id of the wishlist item |
| `callback` | (`errorObj`: ``null`` \| [`RemoveFromWishlistRequestError`](../wiki/models.RemoveFromWishlistRequestError), `wishlist`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockRemoveFromWishlistRequestConfig`](../wiki/models.MockRemoveFromWishlistRequestConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/wishlist-v1.ts:57](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/wishlist-v1.ts#L57)
