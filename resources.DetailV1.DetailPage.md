# Class: DetailPage

[resources](../wiki/resources).[DetailV1](../wiki/resources.DetailV1).DetailPage

## Hierarchy

- `BaseClassV1`

  ↳ **`DetailPage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.DetailV1.DetailPage#constructor)

### Properties

- [IMAGE\_SIZES](../wiki/resources.DetailV1.DetailPage#image_sizes)

### Methods

- [addProductRating](../wiki/resources.DetailV1.DetailPage#addproductrating)
- [addToWishlist](../wiki/resources.DetailV1.DetailPage#addtowishlist)
- [extractSKUs](../wiki/resources.DetailV1.DetailPage#extractskus)
- [getActiveSKUId](../wiki/resources.DetailV1.DetailPage#getactiveskuid)
- [getAvgProductRating](../wiki/resources.DetailV1.DetailPage#getavgproductrating)
- [getImageURLs](../wiki/resources.DetailV1.DetailPage#getimageurls)
- [getPriceOfSKU](../wiki/resources.DetailV1.DetailPage#getpriceofsku)
- [getPrimaryThumbImgUrl](../wiki/resources.DetailV1.DetailPage#getprimarythumbimgurl)
- [getSizeForSKU](../wiki/resources.DetailV1.DetailPage#getsizeforsku)
- [getThisProductInfo](../wiki/resources.DetailV1.DetailPage#getthisproductinfo)
- [groupAttributesByCategory](../wiki/resources.DetailV1.DetailPage#groupattributesbycategory)
- [hasCustomerRated](../wiki/resources.DetailV1.DetailPage#hascustomerrated)
- [saveOutOfStockRequest](../wiki/resources.DetailV1.DetailPage#saveoutofstockrequest)
- [setActiveSKUId](../wiki/resources.DetailV1.DetailPage#setactiveskuid)
- [getProductIdFromDetailPageURL](../wiki/resources.DetailV1.DetailPage#getproductidfromdetailpageurl)

## Constructors

### constructor

• **new DetailPage**(`productId`, `callback`, `mockConfig?`)

Initialises the DetailPage SDK

**`Example`**

For live SDK in production use the below snippet for reference
```js
const detailPageSDK = new OMNIBUS.DetailV1.DetailPage(productId, (error, productInfo) => {
    if (error) {
         // Appropriate actions on SDK initialisation failure depending on error.errorCode 
    }

    // Use productInfo object to retrieve desired information of the product detail page
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const detailPageSDK = new OMNIBUS.DetailV1.DetailPage(productId, (error, productInfo) => {
    if (error) {
         // Appropriate actions on SDK initialisation failure depending on error.errorCode 
    }

    // Use productInfo object to retrieve desired information of the product detail page
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `productId` | `string` | The unique identifier which represents the product |
| `callback` | (`error`: ``null`` \| [`GetProductInfoError`](../wiki/models.GetProductInfoError), `productInfo`: ``null`` \| [`Product`](../wiki/models.Product)) => `void` | The Callback function |
| `mockConfig?` | [`MockInitDetailPageConfig`](../wiki/models.MockInitDetailPageConfig) | The Mock configuration that can be passed to mock this operation |

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/detail-v1.ts:63](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L63)

## Properties

### IMAGE\_SIZES

▪ `Static` `Readonly` **IMAGE\_SIZES**: `any`

#### Defined in

[resources/detail-v1.ts:27](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L27)

## Methods

### addProductRating

▸ **addProductRating**(`productRating`, `callback`, `mockConfig?`): `undefined` \| ``false``

Saves a product rating

**`Example`**

For live SDK in production use the below snippet for reference
```js
detailPageSDK.addProductRating(productRating, (errorObj, rating) => {
    if (errorObj) {
         // Appropriate actions on addProductRating failure depending on errorObj.errorCode 
    }

    // Appropriate actions on addProductRating success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
detailPageSDK.addProductRating(productRating, (errorObj, rating) => {
    if (errorObj) {
         // Appropriate actions on addProductRating failure depending on errorObj.errorCode 
    }

    // Appropriate actions on addProductRating success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `productRating` | [`ProductRating`](../wiki/models.ProductRating) | The product rating provided by the customer |
| `callback` | (`errorObj`: ``null`` \| [`AddProductRatingError`](../wiki/models.AddProductRatingError), `rating`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockAddProductRatingConfig`](../wiki/models.MockAddProductRatingConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/detail-v1.ts:222](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L222)

___

### addToWishlist

▸ **addToWishlist**(`wishlistItemIn`, `callback`, `mockConfig?`): `undefined` \| ``false``

Adds a product SKU to the wish list

**`Example`**

For live SDK in production use the below snippet for reference
```js
detailPageSDK.addToWishlist(wishlistItemIn, (errorObj, wishlist) => {
    if (errorObj) {
         // Appropriate actions on addToWishlist failure depending on errorObj.errorCode 
    }

    // Appropriate actions on addToWishlist success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
detailPageSDK.addToWishlist(wishlistItemIn, (errorObj, wishlist) => {
    if (errorObj) {
         // Appropriate actions on addToWishlist failure depending on errorObj.errorCode 
    }

    // Appropriate actions on addToWishlist success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `wishlistItemIn` | [`WishlistItemIn`](../wiki/models.WishlistItemIn) | The wish list item to be added to the wish list |
| `callback` | (`errorObj`: ``null`` \| [`AddToWishListError`](../wiki/models.AddToWishListError), `wishlist`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockAddToWishlistConfig`](../wiki/models.MockAddToWishlistConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/detail-v1.ts:171](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L171)

___

### extractSKUs

▸ **extractSKUs**(`productInfo`): `string`[]

Retrieves SKU Ids of the product

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `productInfo` | [`Product`](../wiki/models.Product) | The product Information |

#### Returns

`string`[]

SKU Ids of the product

#### Defined in

[resources/detail-v1.ts:464](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L464)

___

### getActiveSKUId

▸ **getActiveSKUId**(): `string`

Gets the active SKU Id of the product

**`Example`**

Use the below snippet for reference
```js
// Remember that this statement should be invoked inside callback of constructor of OMNIBUS.DetailV1.DetailPage. 
// For more clarity - Refer documentation of getActiveSKUId SDK method
const activeSKUId = detailPageSDK.getActiveSKUId();
```

#### Returns

`string`

The active SKU Id

#### Defined in

[resources/detail-v1.ts:586](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L586)

___

### getAvgProductRating

▸ **getAvgProductRating**(`productId`, `callback`, `mockConfig?`): `undefined` \| ``false``

Fetches the average rating for a product

**`Example`**

For live SDK in production use the below snippet for reference
```js
detailPageSDK.getAvgProductRating(productId, (error, avgProductRating) => {
    if (errorObj) {
         // Appropriate actions on getAvgProductRating failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getAvgProductRating success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
detailPageSDK.getAvgProductRating(productId, (error, avgProductRating) => {
    if (errorObj) {
         // Appropriate actions on getAvgProductRating failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getAvgProductRating success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `productId` | `string` | The product ID for which the rating has to be fetched |
| `callback` | (`error`: ``null`` \| [`GetAvgProductRatingError`](../wiki/models.GetAvgProductRatingError), `avgProductRating`: ``null`` \| [`AvgProductRating`](../wiki/models.AvgProductRating)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetProductAvgRatingConfig`](../wiki/models.MockGetProductAvgRatingConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/detail-v1.ts:273](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L273)

___

### getImageURLs

▸ **getImageURLs**(`imageType`): `string`[]

Fetches a list of image URLs for a size

**`Example`**

Use the below snippet for reference
```js
// Remember that this statement should be invoked inside callback of constructor of OMNIBUS.DetailV1.DetailPage. 
// For more clarity - Refer documentation of getThisProductInfo SDK method
const imageURLs = detailPageSDK.getImageURLs(imageType);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `imageType` | [`ProductImageType`](../wiki/models.ProductImageType) | The type of the product image |

#### Returns

`string`[]

The size of the product SKU

#### Defined in

[resources/detail-v1.ts:488](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L488)

___

### getPriceOfSKU

▸ **getPriceOfSKU**(`skuId`): `undefined` \| [`Price`](../wiki/models.Price)

Fetches the price of the given SKU Id

**`Example`**

Use the below snippet for reference
```js
// Remember that this statement should be invoked inside callback of constructor of OMNIBUS.DetailV1.DetailPage. 
// For more clarity - Refer documentation of getThisProductInfo SDK method
const price = detailPageSDK.getPriceOfSKU(skuId);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `skuId` | `string` | The unique identifier which represents a product SKU |

#### Returns

`undefined` \| [`Price`](../wiki/models.Price)

The price of the product SKU

#### Defined in

[resources/detail-v1.ts:538](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L538)

___

### getPrimaryThumbImgUrl

▸ **getPrimaryThumbImgUrl**(): `string`

Fetches the primary thumb image URL

**`Example`**

Use the below snippet for reference
```js
// Remember that this statement should be invoked inside callback of constructor of OMNIBUS.DetailV1.DetailPage. 
// For more clarity - Refer documentation of getThisProductInfo SDK method
const primaryThumbImgUrl = detailPageSDK.getPrimaryThumbImgUrl();
```

#### Returns

`string`

The url of primary thumb image

#### Defined in

[resources/detail-v1.ts:508](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L508)

___

### getSizeForSKU

▸ **getSizeForSKU**(`skuId`): `string`

Fetches the size of the given SKU Id

**`Example`**

Use the below snippet for reference
```js
// Remember that this statement should be invoked inside callback of constructor of OMNIBUS.DetailV1.DetailPage. 
// For more clarity - Refer documentation of getThisProductInfo SDK method
const size = detailPageSDK.getSizeForSKU(skuId);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `skuId` | `string` | The unique identifier which represents a product SKU |

#### Returns

`string`

The size of the product SKU

#### Defined in

[resources/detail-v1.ts:524](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L524)

___

### getThisProductInfo

▸ **getThisProductInfo**(): [`Product`](../wiki/models.Product)

Retrieves the product information

**`Example`**

Use the below snippet for reference
```js
const detailPageSDK = new OMNIBUS.DetailV1.DetailPage(productId, (error, productInfo) => {
    if (error) {
         // Appropriate actions on SDK initialisation failure depending on error.errorCode 
    }

    // Remember that the method which includes the detailPageSDK.getThisProductInfo() call should be invoked inside callback of constructor.
    const productDescription = extractProductDescription();
});

const extractProductDescription = () => {
    const productInfo = detailPageSDK.getThisProductInfo();
    // Logic to extract productDescription from productInfo;
    return productDescription;
}
```

#### Returns

[`Product`](../wiki/models.Product)

The detailed information of the product

#### Defined in

[resources/detail-v1.ts:138](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L138)

___

### groupAttributesByCategory

▸ **groupAttributesByCategory**(): `Object`

Groups attributes by category and returns attribute map

**`Example`**

Use the below snippet for reference
```js
// Remember that this statement should be invoked inside callback of constructor of OMNIBUS.DetailV1.DetailPage. 
// For more clarity - Refer documentation of getThisProductInfo SDK method
const attributeMap = detailPageSDK.groupAttributesByCategory();
```

#### Returns

`Object`

The attribute map

#### Defined in

[resources/detail-v1.ts:557](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L557)

___

### hasCustomerRated

▸ **hasCustomerRated**(`productId`, `callback`, `mockConfig?`): `undefined` \| ``false``

Checks whether the customer has already provided a rating for a product

**`Example`**

For live SDK in production use the below snippet for reference
```js
detailPageSDK.hasCustomerRated(productId, (error, responseObj) => {
    if (errorObj) {
         // Appropriate actions on hasCustomerRated failure depending on errorObj.errorCode 
    }

    // Appropriate actions on hasCustomerRated success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
detailPageSDK.hasCustomerRated(productId, (error, responseObj) => {
    if (errorObj) {
         // Appropriate actions on hasCustomerRated failure depending on errorObj.errorCode 
    }

    // Appropriate actions on hasCustomerRated success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `productId` | `string` | The product ID |
| `callback` | (`error`: ``null`` \| [`HasCustomerRatedError`](../wiki/models.HasCustomerRatedError), `responseObj`: ``null`` \| [`HasCustomerRatedResponse`](../wiki/models.HasCustomerRatedResponse)) => `void` | The Callback function |
| `mockConfig?` | [`MockHasCustomerRatedConfig`](../wiki/models.MockHasCustomerRatedConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/detail-v1.ts:326](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L326)

___

### saveOutOfStockRequest

▸ **saveOutOfStockRequest**(`outOfStockRequest`, `callback`, `mockConfig?`): `undefined` \| ``false``

Saves request to be notified for restock of an out of stock product SKU

**`Example`**

For live SDK in production use the below snippet for reference
```js
detailPageSDK.saveOutOfStockRequest(outOfStockRequest, (errorObj, hasAlreadyOptedIn) => {
    if (errorObj) {
         // Appropriate actions on saveOutOfStockRequest failure depending on errorObj.errorCode 
    }

    // Appropriate actions on saveOutOfStockRequest success
}, mockConfig);
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
detailPageSDK.saveOutOfStockRequest(outOfStockRequest, (errorObj, hasAlreadyOptedIn) => {
    if (errorObj) {
         // Appropriate actions on saveOutOfStockRequest failure depending on errorObj.errorCode 
    }

    // Appropriate actions on saveOutOfStockRequest success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `outOfStockRequest` | [`OutOfStockRequestItem`](../wiki/models.OutOfStockRequestItem) | The request object to be saved |
| `callback` | (`errorObj`: ``null`` \| [`SaveOutOfStockRequestError`](../wiki/models.SaveOutOfStockRequestError), `hasAlreadyOptedIn`: ``null`` \| `boolean`) => `void` | The Callback function |
| `mockConfig?` | [`MockSaveOutOfStockRequestConfig`](../wiki/models.MockSaveOutOfStockRequestConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/detail-v1.ts:378](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L378)

___

### setActiveSKUId

▸ **setActiveSKUId**(`skuId`): `string`

Sets the active SKU Id of the product

**`Example`**

Use the below snippet for reference
```js
// Remember that this statement should be invoked inside callback of constructor of OMNIBUS.DetailV1.DetailPage. 
// For more clarity - Refer documentation of getThisProductInfo SDK method
detailPageSDK.setActiveSKUId(skuId);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `skuId` | `string` | The unique identifier which represents the product SKU |

#### Returns

`string`

#### Defined in

[resources/detail-v1.ts:573](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L573)

___

### getProductIdFromDetailPageURL

▸ `Static` **getProductIdFromDetailPageURL**(): `undefined` \| `string`

Get the product Id from Detail page

**`Example`**

Use the below snippet for reference
```js
const productId = OMNIBUS.DetailV1.DetailPage.getProductIdFromDetailPageURL();
```

#### Returns

`undefined` \| `string`

The product Id of the Detail page

#### Defined in

[resources/detail-v1.ts:102](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/detail-v1.ts#L102)
