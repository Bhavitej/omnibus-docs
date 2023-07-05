# Class: SearchPage

[resources](../wiki/resources).[SearchV1](../wiki/resources.SearchV1).SearchPage

## Hierarchy

- `BaseClassV1`

  ↳ **`SearchPage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.SearchV1.SearchPage#constructor)

### Methods

- [autoSuggestProductSearchQuery](../wiki/resources.SearchV1.SearchPage#autosuggestproductsearchquery)
- [productSearchQuery](../wiki/resources.SearchV1.SearchPage#productsearchquery)

## Constructors

### constructor

• **new SearchPage**()

Initialises the SearchPage SDK

**`Example`**

Use this below JS snippet to create an instance of SearchPage SDK 
```js
const searchPageSDK = new OMNIBUS.SearchV1.SearchPage();
```

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/search-v1.ts:23](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/search-v1.ts#L23)

## Methods

### autoSuggestProductSearchQuery

▸ **autoSuggestProductSearchQuery**(`searchText`, `callback`, `mockConfig?`): `undefined` \| ``false``

Fetches auto suggest query results for the given product search query string

**`Example`**

For live SDK in production use the below snippet for reference
```js
const searchPageSDK = new OMNIBUS.SearchV1.SearchPage();
searchPageSDK.autoSuggestProductSearchQuery(searchText, (error, responseObj) => {
    if (error) {
         // Appropriate actions on autoSuggestProductSearchQuery failure depending on error.errorCode 
    }

    // Appropriate actions on autoSuggestProductSearchQuery success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const searchPageSDK = new OMNIBUS.SearchV1.SearchPage();
searchPageSDK.autoSuggestProductSearchQuery(searchText, (error, responseObj) => {
    if (error) {
         // Appropriate actions on autoSuggestProductSearchQuery failure depending on error.errorCode 
    }

    // Appropriate actions on autoSuggestProductSearchQuery success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchText` | `string` | The search Text used to perform auto suggest query |
| `callback` | (`error`: ``null`` \| [`AutoSuggestProductSearchQueryError`](../wiki/models.AutoSuggestProductSearchQueryError), `responseObj`: ``null`` \| [`AutoSuggestProductSearchResult`](../wiki/models.AutoSuggestProductSearchResult)[]) => `void` | The Callback function |
| `mockConfig?` | [`MockAutoSuggestProductSearchQueryConfig`](../wiki/models.MockAutoSuggestProductSearchQueryConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/search-v1.ts:108](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/search-v1.ts#L108)

___

### productSearchQuery

▸ **productSearchQuery**(`searchText`, `callback`, `mockConfig?`): `undefined` \| ``false``

Fetches search results for the given product search query object

**`Example`**

For live SDK in production use the below snippet for reference
```js
const searchPageSDK = new OMNIBUS.SearchV1.SearchPage();
searchPageSDK.productSearchQuery(searchText, (error, responseObj) => {
    if (error) {
         // Appropriate actions on productSearchQuery failure depending on error.errorCode 
    }

    // Appropriate actions on productSearchQuery success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const searchPageSDK = new OMNIBUS.SearchV1.SearchPage();
searchPageSDK.productSearchQuery(searchText, (error, responseObj) => {
    if (error) {
         // Appropriate actions on productSearchQuery failure depending on error.errorCode 
    }

    // Appropriate actions on productSearchQuery success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `searchText` | `string` | The search text used to perform product search |
| `callback` | (`error`: ``null`` \| [`ProductSearchQueryError`](../wiki/models.ProductSearchQueryError), `responseObj`: ``null`` \| [`ProductSearchResult`](../wiki/models.ProductSearchResult)[]) => `void` | The Callback function |
| `mockConfig?` | [`MockProductSearchQueryConfig`](../wiki/models.MockProductSearchQueryConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/search-v1.ts:57](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/search-v1.ts#L57)
