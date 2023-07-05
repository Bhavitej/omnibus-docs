# Class: BaseMockConfig<MOCK_PARAMS, ERROR_CODE\>

[models](../wiki/models).BaseMockConfig

Describes the Mock SDK config

## Type parameters

| Name |
| :------ |
| `MOCK_PARAMS` |
| `ERROR_CODE` |

## Hierarchy

- **`BaseMockConfig`**

  ↳ [`MockGetCartConfig`](../wiki/models.MockGetCartConfig)

  ↳ [`MockAddToCartConfig`](../wiki/models.MockAddToCartConfig)

  ↳ [`MockClearCartConfig`](../wiki/models.MockClearCartConfig)

  ↳ [`MockRemoveFromCartConfig`](../wiki/models.MockRemoveFromCartConfig)

  ↳ [`MockUpdateCartConfig`](../wiki/models.MockUpdateCartConfig)

  ↳ [`MockRegisterAccountConfig`](../wiki/models.MockRegisterAccountConfig)

  ↳ [`MockLoginAccountConfig`](../wiki/models.MockLoginAccountConfig)

  ↳ [`MockForgotPasswordConfig`](../wiki/models.MockForgotPasswordConfig)

  ↳ [`MockGetLoginTypeConfig`](../wiki/models.MockGetLoginTypeConfig)

  ↳ [`MockUpdatePasswordConfig`](../wiki/models.MockUpdatePasswordConfig)

  ↳ [`MockUpdateProfileConfig`](../wiki/models.MockUpdateProfileConfig)

  ↳ [`MockGetCustomerProfileConfig`](../wiki/models.MockGetCustomerProfileConfig)

  ↳ [`MockIsSignedInConfig`](../wiki/models.MockIsSignedInConfig)

  ↳ [`MockLogoutConfig`](../wiki/models.MockLogoutConfig)

  ↳ [`MockAddAddressConfig`](../wiki/models.MockAddAddressConfig)

  ↳ [`MockDeleteAddressConfig`](../wiki/models.MockDeleteAddressConfig)

  ↳ [`MockGetCatalogueInfoConfig`](../wiki/models.MockGetCatalogueInfoConfig)

  ↳ [`MockListAddressesConfig`](../wiki/models.MockListAddressesConfig)

  ↳ [`MockPlaceOrderConfig`](../wiki/models.MockPlaceOrderConfig)

  ↳ [`MockGetCreditsConfig`](../wiki/models.MockGetCreditsConfig)

  ↳ [`MockGetCreditsLedgerConfig`](../wiki/models.MockGetCreditsLedgerConfig)

  ↳ [`MockEvaluatesRulesConfig`](../wiki/models.MockEvaluatesRulesConfig)

  ↳ [`MockInitDetailPageConfig`](../wiki/models.MockInitDetailPageConfig)

  ↳ [`MockAddToWishlistConfig`](../wiki/models.MockAddToWishlistConfig)

  ↳ [`MockSaveOutOfStockRequestConfig`](../wiki/models.MockSaveOutOfStockRequestConfig)

  ↳ [`MockAddProductRatingConfig`](../wiki/models.MockAddProductRatingConfig)

  ↳ [`MockGetProductAvgRatingConfig`](../wiki/models.MockGetProductAvgRatingConfig)

  ↳ [`MockHasCustomerRatedConfig`](../wiki/models.MockHasCustomerRatedConfig)

  ↳ [`MockGetDefaultProductImageConfig`](../wiki/models.MockGetDefaultProductImageConfig)

  ↳ [`MockGetRecentlyViewedProductsConfig`](../wiki/models.MockGetRecentlyViewedProductsConfig)

  ↳ [`MockGetMenuConfig`](../wiki/models.MockGetMenuConfig)

  ↳ [`MockGetSiteInfoConfig`](../wiki/models.MockGetSiteInfoConfig)

  ↳ [`MockGetWishlistConfig`](../wiki/models.MockGetWishlistConfig)

  ↳ [`MockGetBannerGroupConfig`](../wiki/models.MockGetBannerGroupConfig)

  ↳ [`MockGetRecentlyAddedProductsConfig`](../wiki/models.MockGetRecentlyAddedProductsConfig)

  ↳ [`MockGetFeaturedGroupConfig`](../wiki/models.MockGetFeaturedGroupConfig)

  ↳ [`MockGetOrderConfig`](../wiki/models.MockGetOrderConfig)

  ↳ [`MockListOrdersConfig`](../wiki/models.MockListOrdersConfig)

  ↳ [`MockCancelOrderConfig`](../wiki/models.MockCancelOrderConfig)

  ↳ [`MockListOrderCancelReasonsConfig`](../wiki/models.MockListOrderCancelReasonsConfig)

  ↳ [`MockRemoveFromWishlistRequestConfig`](../wiki/models.MockRemoveFromWishlistRequestConfig)

  ↳ [`MockProductSearchQueryConfig`](../wiki/models.MockProductSearchQueryConfig)

  ↳ [`MockAutoSuggestProductSearchQueryConfig`](../wiki/models.MockAutoSuggestProductSearchQueryConfig)

## Table of contents

### Constructors

- [constructor](../wiki/models.BaseMockConfig#constructor)

### Properties

- [err](../wiki/models.BaseMockConfig#err)
- [errorCode](../wiki/models.BaseMockConfig#errorcode)
- [params](../wiki/models.BaseMockConfig#params)

## Constructors

### constructor

• **new BaseMockConfig**<`MOCK_PARAMS`, `ERROR_CODE`\>()

#### Type parameters

| Name |
| :------ |
| `MOCK_PARAMS` |
| `ERROR_CODE` |

## Properties

### err

• **err**: `boolean` = `false`

The boolean which specifies whether the mock response should be error or not

#### Defined in

[models/base.ts:43](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L43)

___

### errorCode

• `Optional` **errorCode**: `ERROR_CODE`

The error code which should be thrown in mock response. Works only if 'err' field is set to true.

#### Defined in

[models/base.ts:47](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L47)

___

### params

• `Optional` **params**: `MOCK_PARAMS`

The params depending on which the mock response should be generated. Works only if 'err' field is set to false.

#### Defined in

[models/base.ts:51](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L51)
