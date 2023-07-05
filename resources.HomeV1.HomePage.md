# Class: HomePage

[resources](../wiki/resources).[HomeV1](../wiki/resources.HomeV1).HomePage

## Hierarchy

- `BaseClassV1`

  ↳ **`HomePage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.HomeV1.HomePage#constructor)

### Methods

- [getBannerGroup](../wiki/resources.HomeV1.HomePage#getbannergroup)
- [getDefaultProductImage](../wiki/resources.HomeV1.HomePage#getdefaultproductimage)
- [getFeaturedGroup](../wiki/resources.HomeV1.HomePage#getfeaturedgroup)
- [getMenu](../wiki/resources.HomeV1.HomePage#getmenu)
- [getRecentlyAddedProducts](../wiki/resources.HomeV1.HomePage#getrecentlyaddedproducts)
- [getSiteInfo](../wiki/resources.HomeV1.HomePage#getsiteinfo)
- [getWishlist](../wiki/resources.HomeV1.HomePage#getwishlist)

## Constructors

### constructor

• **new HomePage**()

Initialises the HomePage SDK

**`Example`**

Use this below JS snippet to create an instance of HomePage SDK 
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
```

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/home-v1.ts:27](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L27)

## Methods

### getBannerGroup

▸ **getBannerGroup**(`name`, `callback`, `mockConfig?`): `undefined` \| ``false``

Get the Banner group by group name

**`Example`**

For live SDK in production use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getBannerGroup(name, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getBannerGroup failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getBannerGroup success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getBannerGroup(name, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getBannerGroup failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getBannerGroup success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The name of the Banner group |
| `callback` | (`errorObj`: ``null`` \| [`GetBannerGroupError`](../wiki/models.GetBannerGroupError), `responseObj`: ``null`` \| [`BannerGroup`](../wiki/models.BannerGroup)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetBannerGroupConfig`](../wiki/models.MockGetBannerGroupConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/home-v1.ts:211](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L211)

___

### getDefaultProductImage

▸ **getDefaultProductImage**(`callback`, `mockConfig?`): `undefined` \| ``false``

Get the default product image URL

**`Example`**

For live SDK in production use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getDefaultProductImage((errObject, responseObj) => {
    if (errObject) {
         // Appropriate actions on getDefaultProductImage failure depending on errObject.errorCode 
    }

    // Appropriate actions on getDefaultProductImage success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getDefaultProductImage((errObject, responseObj) => {
    if (errObject) {
         // Appropriate actions on getDefaultProductImage failure depending on errObject.errorCode 
    }

    // Appropriate actions on getDefaultProductImage success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`errObject`: ``null`` \| [`GetDefaultProductImageError`](../wiki/models.GetDefaultProductImageError), `responseObj`: ``null`` \| `string`) => `void` | The Callback function |
| `mockConfig?` | [`MockGetDefaultProductImageConfig`](../wiki/models.MockGetDefaultProductImageConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/home-v1.ts:260](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L260)

___

### getFeaturedGroup

▸ **getFeaturedGroup**(`name`, `callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves featured products by group name

**`Example`**

For live SDK in production use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getFeaturedGroup(name, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getFeaturedGroup failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getFeaturedGroup success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getFeaturedGroup(name, (errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getFeaturedGroup failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getFeaturedGroup success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `name` | `string` | The name of the featured group |
| `callback` | (`errorObj`: ``null`` \| [`GetFeaturedGroupError`](../wiki/models.GetFeaturedGroupError), `responseObj`: ``null`` \| [`FeaturedGroup`](../wiki/models.FeaturedGroup)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetFeaturedGroupConfig`](../wiki/models.MockGetFeaturedGroupConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/home-v1.ts:61](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L61)

___

### getMenu

▸ **getMenu**(`callback`, `mockConfig?`): `undefined` \| ``false``

Get the menu

**`Example`**

For live SDK in production use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getMenu((errObject, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getMenu failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getMenu success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getMenu((errObject, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getMenu failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getMenu success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`errObject`: ``null`` \| [`GetMenuError`](../wiki/models.GetMenuError), `responseObj`: ``null`` \| [`Menu`](../wiki/models.Menu)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetMenuConfig`](../wiki/models.MockGetMenuConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/home-v1.ts:309](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L309)

___

### getRecentlyAddedProducts

▸ **getRecentlyAddedProducts**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the recently added products

**`Example`**

For live SDK in production use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getRecentlyAddedProducts((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getRecentlyAddedProducts failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getRecentlyAddedProducts success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getRecentlyAddedProducts((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getRecentlyAddedProducts failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getRecentlyAddedProducts success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`errorObj`: ``null`` \| [`GetRecentlyAddedProductsError`](../wiki/models.GetRecentlyAddedProductsError), `responseObj`: ``null`` \| [`RecentlyAddedProduct`](../wiki/models.RecentlyAddedProduct)[]) => `void` | The Callback function |
| `mockConfig?` | [`MockGetRecentlyAddedProductsConfig`](../wiki/models.MockGetRecentlyAddedProductsConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/home-v1.ts:110](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L110)

___

### getSiteInfo

▸ **getSiteInfo**(`callback`, `mockConfig?`): `undefined` \| ``false``

Get the site information

**`Example`**

For live SDK in production use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getSiteInfo((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getSiteInfo failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getSiteInfo success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getSiteInfo((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getSiteInfo failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getSiteInfo success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`errorObj`: ``null`` \| [`GetSiteInfoError`](../wiki/models.GetSiteInfoError), `responseObj`: ``null`` \| [`SiteInfo`](../wiki/models.SiteInfo)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetSiteInfoConfig`](../wiki/models.MockGetSiteInfoConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/home-v1.ts:358](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L358)

___

### getWishlist

▸ **getWishlist**(`callback`, `mockConfig?`): `undefined` \| ``false``

Get the site information

**`Example`**

For live SDK in production use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getWishlist((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getWishlist failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getWishlist success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const homePageSDK = new OMNIBUS.HomeV1.HomePage();
homePageSDK.getWishlist((errorObj, responseObj) => {
    if (errorObj) {
         // Appropriate actions on getWishlist failure depending on errorObj.errorCode 
    }

    // Appropriate actions on getWishlist success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`errorObj`: ``null`` \| [`GetWishlistError`](../wiki/models.GetWishlistError), `responseObj`: ``null`` \| [`WishlistItem`](../wiki/models.WishlistItem)[]) => `void` | The Callback function |
| `mockConfig?` | [`MockGetWishlistConfig`](../wiki/models.MockGetWishlistConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/home-v1.ts:407](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/home-v1.ts#L407)
