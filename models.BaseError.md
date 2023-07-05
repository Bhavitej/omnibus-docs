# Class: BaseError<DATA, ERROR_CODE\>

[models](../wiki/models).BaseError

Describes the parameters of the Base error

## Type parameters

| Name |
| :------ |
| `DATA` |
| `ERROR_CODE` |

## Hierarchy

- **`BaseError`**

  ↳ [`AddToCartError`](../wiki/models.AddToCartError)

  ↳ [`RemoveFromCartError`](../wiki/models.RemoveFromCartError)

  ↳ [`ClearCartError`](../wiki/models.ClearCartError)

  ↳ [`GetCartError`](../wiki/models.GetCartError)

  ↳ [`UpdateCartError`](../wiki/models.UpdateCartError)

  ↳ [`RegisterAccountError`](../wiki/models.RegisterAccountError)

  ↳ [`LoginAccountError`](../wiki/models.LoginAccountError)

  ↳ [`ForgotPasswordError`](../wiki/models.ForgotPasswordError)

  ↳ [`GetLoginTypeError`](../wiki/models.GetLoginTypeError)

  ↳ [`UpdatePasswordError`](../wiki/models.UpdatePasswordError)

  ↳ [`UpdateProfileError`](../wiki/models.UpdateProfileError)

  ↳ [`GetCustomerProfileError`](../wiki/models.GetCustomerProfileError)

  ↳ [`IsSignedInError`](../wiki/models.IsSignedInError)

  ↳ [`LogoutError`](../wiki/models.LogoutError)

  ↳ [`AddAddressError`](../wiki/models.AddAddressError)

  ↳ [`DeleteAddressError`](../wiki/models.DeleteAddressError)

  ↳ [`GetCatalogueInfoError`](../wiki/models.GetCatalogueInfoError)

  ↳ [`ListAddressesError`](../wiki/models.ListAddressesError)

  ↳ [`GetCreditsError`](../wiki/models.GetCreditsError)

  ↳ [`GetCreditLedgerError`](../wiki/models.GetCreditLedgerError)

  ↳ [`PlaceOrderError`](../wiki/models.PlaceOrderError)

  ↳ [`EvaluateRulesError`](../wiki/models.EvaluateRulesError)

  ↳ [`GetProductInfoError`](../wiki/models.GetProductInfoError)

  ↳ [`GetAvgProductRatingError`](../wiki/models.GetAvgProductRatingError)

  ↳ [`AddToWishListError`](../wiki/models.AddToWishListError)

  ↳ [`AddProductRatingError`](../wiki/models.AddProductRatingError)

  ↳ [`HasCustomerRatedError`](../wiki/models.HasCustomerRatedError)

  ↳ [`SaveOutOfStockRequestError`](../wiki/models.SaveOutOfStockRequestError)

  ↳ [`GetFeaturedGroupError`](../wiki/models.GetFeaturedGroupError)

  ↳ [`GetRecentlyAddedProductsError`](../wiki/models.GetRecentlyAddedProductsError)

  ↳ [`GetRecentlyViewedProductsError`](../wiki/models.GetRecentlyViewedProductsError)

  ↳ [`GetBannerGroupError`](../wiki/models.GetBannerGroupError)

  ↳ [`GetDefaultProductImageError`](../wiki/models.GetDefaultProductImageError)

  ↳ [`GetMenuError`](../wiki/models.GetMenuError)

  ↳ [`GetSiteInfoError`](../wiki/models.GetSiteInfoError)

  ↳ [`GetWishlistError`](../wiki/models.GetWishlistError)

  ↳ [`ListOrdersError`](../wiki/models.ListOrdersError)

  ↳ [`GetOrderError`](../wiki/models.GetOrderError)

  ↳ [`RemoveFromWishlistRequestError`](../wiki/models.RemoveFromWishlistRequestError)

  ↳ [`ProductSearchQueryError`](../wiki/models.ProductSearchQueryError)

  ↳ [`AutoSuggestProductSearchQueryError`](../wiki/models.AutoSuggestProductSearchQueryError)

## Table of contents

### Constructors

- [constructor](../wiki/models.BaseError#constructor)

### Properties

- [data](../wiki/models.BaseError#data)
- [err](../wiki/models.BaseError#err)
- [errorCode](../wiki/models.BaseError#errorcode)
- [errorDetail](../wiki/models.BaseError#errordetail)
- [status](../wiki/models.BaseError#status)

## Constructors

### constructor

• **new BaseError**<`DATA`, `ERROR_CODE`\>()

#### Type parameters

| Name |
| :------ |
| `DATA` |
| `ERROR_CODE` |

## Properties

### data

• `Optional` **data**: `DATA`

The data of the response

#### Defined in

[models/base.ts:25](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L25)

___

### err

• **err**: `boolean` = `true`

The boolean which specifies response is error or not

#### Defined in

[models/base.ts:17](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L17)

___

### errorCode

• **errorCode**: `undefined` \| `ERROR_CODE`

The standard error code which indicates a type of error

#### Defined in

[models/base.ts:33](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L33)

___

### errorDetail

• **errorDetail**: `string` = `''`

The error detail which mentions the reason for error

#### Defined in

[models/base.ts:29](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L29)

___

### status

• **status**: `string` = `'error'`

The status of the response

#### Defined in

[models/base.ts:21](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/base.ts#L21)
