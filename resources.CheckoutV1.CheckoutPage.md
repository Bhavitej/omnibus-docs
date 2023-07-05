# Class: CheckoutPage

[resources](../wiki/resources).[CheckoutV1](../wiki/resources.CheckoutV1).CheckoutPage

## Hierarchy

- `BaseClassV1`

  ↳ **`CheckoutPage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.CheckoutV1.CheckoutPage#constructor)

### Methods

- [evaluateRules](../wiki/resources.CheckoutV1.CheckoutPage#evaluaterules)
- [getCredits](../wiki/resources.CheckoutV1.CheckoutPage#getcredits)
- [getCreditsLedger](../wiki/resources.CheckoutV1.CheckoutPage#getcreditsledger)
- [listAddresses](../wiki/resources.CheckoutV1.CheckoutPage#listaddresses)
- [placeOrder](../wiki/resources.CheckoutV1.CheckoutPage#placeorder)

## Constructors

### constructor

• **new CheckoutPage**()

Initialises the CheckoutPage SDK

**`Example`**

Use this below JS snippet to create an instance of CheckoutPage SDK 
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
```

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/checkout-v1.ts:25](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/checkout-v1.ts#L25)

## Methods

### evaluateRules

▸ **evaluateRules**(`purchaseOrderIn`, `callback`, `mockConfig?`): `undefined` \| ``false``

Evaluates the rules like coupons, offers, shipping cost and other charges

**`Example`**

For live SDK in production use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.evaluateRules(purchaseOrderIn, (error, response) => {
    if (error) {
         // Appropriate actions on evaluateRules failure depending on error.errorCode 
    }

    // Appropriate actions on evaluateRules success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.evaluateRules(purchaseOrderIn, (error, response) => {
    if (error) {
         // Appropriate actions on evaluateRules failure depending on error.errorCode 
    }

    // Appropriate actions on evaluateRules success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `purchaseOrderIn` | [`PurchaseOrderIn`](../wiki/models.PurchaseOrderIn) | The customer order information |
| `callback` | (`error`: ``null`` \| [`EvaluateRulesError`](../wiki/models.EvaluateRulesError), `response`: ``null`` \| [`Cart`](../wiki/models.Cart)) => `void` | The Callback function |
| `mockConfig?` | [`MockEvaluatesRulesConfig`](../wiki/models.MockEvaluatesRulesConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/checkout-v1.ts:287](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/checkout-v1.ts#L287)

___

### getCredits

▸ **getCredits**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the total credits available for a customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.getCredits((error, creditInfo) => {
    if (error) {
         // Appropriate actions on getCredits failure depending on error.errorCode 
    }

    // Appropriate actions on getCredits success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.getCredits((error, creditInfo) => {
    if (error) {
         // Appropriate actions on getCredits failure depending on error.errorCode 
    }

    // Appropriate actions on getCredits success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: ``null`` \| [`GetCreditsError`](../wiki/models.GetCreditsError), `creditInfo`: ``null`` \| [`CreditsInfo`](../wiki/models.CreditsInfo)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetCreditsConfig`](../wiki/models.MockGetCreditsConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/checkout-v1.ts:110](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/checkout-v1.ts#L110)

___

### getCreditsLedger

▸ **getCreditsLedger**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the credit ledger of a customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.getCreditsLedger((error, creditLedger) => {
    if (error) {
         // Appropriate actions on getCreditsLedger failure depending on error.errorCode 
    }

    // Appropriate actions on getCreditsLedger success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.getCreditsLedger((error, creditLedger) => {
    if (error) {
         // Appropriate actions on getCreditsLedger failure depending on error.errorCode 
    }

    // Appropriate actions on getCreditsLedger success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: ``null`` \| [`GetCreditLedgerError`](../wiki/models.GetCreditLedgerError), `creditLedger`: ``null`` \| [`CreditLedgerEntry`](../wiki/models.CreditLedgerEntry)[]) => `void` | The Callback function |
| `mockConfig?` | [`MockGetCreditsLedgerConfig`](../wiki/models.MockGetCreditsLedgerConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/checkout-v1.ts:160](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/checkout-v1.ts#L160)

___

### listAddresses

▸ **listAddresses**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the list of customer addresses

**`Example`**

For live SDK in production use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.listAddresses((error, addressInfo) => {
    if (error) {
         // Appropriate actions on listAddresses failure depending on error.errorCode 
    }

    // Appropriate actions on listAddresses success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.listAddresses((error, addressInfo) => {
    if (error) {
         // Appropriate actions on listAddresses failure depending on error.errorCode 
    }

    // Appropriate actions on listAddresses success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: ``null`` \| [`ListAddressesError`](../wiki/models.ListAddressesError), `addressInfo`: ``null`` \| [`Address`](../wiki/models.Address)[]) => `void` | The Callback function |
| `mockConfig?` | [`MockListAddressesConfig`](../wiki/models.MockListAddressesConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/checkout-v1.ts:58](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/checkout-v1.ts#L58)

___

### placeOrder

▸ **placeOrder**(`purchaseOrderIn`, `callback`, `mockConfig?`): `undefined` \| ``false``

Places the order, given the customer order information

**`Example`**

For live SDK in production use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.placeOrder(purchaseOrderIn, (error, response) => {
    if (error) {
         // Appropriate actions on placeOrder failure depending on error.errorCode 
    }

    // Appropriate actions on placeOrder success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const checkoutPageSDK = new OMNIBUS.CheckoutV1.CheckoutPage();
checkoutPageSDK.placeOrder(purchaseOrderIn, (error, response) => {
    if (error) {
         // Appropriate actions on placeOrder failure depending on error.errorCode 
    }

    // Appropriate actions on placeOrder success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `purchaseOrderIn` | [`PurchaseOrderIn`](../wiki/models.PurchaseOrderIn) | The customer order information |
| `callback` | (`error`: ``null`` \| [`PlaceOrderError`](../wiki/models.PlaceOrderError), `response`: ``null`` \| `string`) => `void` | The Callback function - response is orderId - The unique identifier for the order |
| `mockConfig?` | [`MockPlaceOrderConfig`](../wiki/models.MockPlaceOrderConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/checkout-v1.ts:210](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/checkout-v1.ts#L210)
