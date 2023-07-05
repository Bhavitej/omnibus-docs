# Class: CataloguePage

[resources](../wiki/resources).[CatalogueV1](../wiki/resources.CatalogueV1).CataloguePage

## Hierarchy

- `BaseClassV1`

  ↳ **`CataloguePage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.CatalogueV1.CataloguePage#constructor)

### Methods

- [getThisCatalogueInfo](../wiki/resources.CatalogueV1.CataloguePage#getthiscatalogueinfo)
- [getTagIdFromCataloguePageURL](../wiki/resources.CatalogueV1.CataloguePage#gettagidfromcataloguepageurl)

## Constructors

### constructor

• **new CataloguePage**(`tagId`, `callback`, `mockConfig?`)

Initialises the CataloguePage object

**`Example`**

For live SDK in production use the below snippet for reference
```js
const cataloguePageSDK = new OMNIBUS.CatalogueV1.CataloguePage(tagId, (error, catalogueInfo) => {
    if (error) {
         // Appropriate actions on initialisation failure depending on error.errorCode 
    }

    // Use catalogueInfo object to retrieve desired information of the catalogue page
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const cataloguePageSDK = new OMNIBUS.CatalogueV1.CataloguePage(tagId, (error, catalogueInfo) => {
    if (error) {
         // Appropriate actions on initialisation failure depending on error.errorCode 
    }

    // Use catalogueInfo object to retrieve desired information of the catalogue page
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `tagId` | `string` | The unique identifier that represents a tag (Catalogue page) |
| `callback` | (`error`: ``null`` \| [`GetCatalogueInfoError`](../wiki/models.GetCatalogueInfoError), `catalogueInfo`: ``null`` \| [`CatalogueInfo`](../wiki/models.CatalogueInfo)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetCatalogueInfoConfig`](../wiki/models.MockGetCatalogueInfoConfig) | The Mock configuration that can be passed to mock this operation |

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/catalogue-v1.ts:49](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/catalogue-v1.ts#L49)

## Methods

### getThisCatalogueInfo

▸ **getThisCatalogueInfo**(): [`CatalogueInfo`](../wiki/models.CatalogueInfo)

Retrieves the current Catalogue information

**`Example`**

Use the below snippet for reference
```js
const cataloguePageSDK = new OMNIBUS.CatalogueV1.CataloguePage(tagId, (error, catalogueInfo) => {
    if (error) {
         // Appropriate actions on initialisation failure depending on error.errorCode 
    }
    
    // Remember that the method which includes the cataloguePageSDK.getThisCatalogueInfo() call should be called inside callback of constructor.
    const tagFilters = extractTagFiltersInfo();
});

const extractTagFiltersInfo = () => {
    const catalogueInfo = cataloguePageSDK.getThisCatalogueInfo();
    // logic to extract tagFilters from catalogueInfo
    return tagFilters;
}
```

#### Returns

[`CatalogueInfo`](../wiki/models.CatalogueInfo)

The detailed information of the catalogue (tag)

#### Defined in

[resources/catalogue-v1.ts:91](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/catalogue-v1.ts#L91)

___

### getTagIdFromCataloguePageURL

▸ `Static` **getTagIdFromCataloguePageURL**(): `undefined` \| `string`

**`Example`**

Use the below snippet for reference
```js
const tagId = OMNIBUS.CatalogueV1.CataloguePage.getTagIdFromCataloguePageURL();
```

#### Returns

`undefined` \| `string`

The tag Id of the Catalogue page

#### Defined in

[resources/catalogue-v1.ts:103](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/catalogue-v1.ts#L103)
