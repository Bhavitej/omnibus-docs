# Class: OrdersPage

[resources](../wiki/resources).[OrdersV1](../wiki/resources.OrdersV1).OrdersPage

## Hierarchy

- `BaseClassV1`

  ↳ **`OrdersPage`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.OrdersV1.OrdersPage#constructor)

### Methods

- [cancelOrder](../wiki/resources.OrdersV1.OrdersPage#cancelorder)
- [getOrder](../wiki/resources.OrdersV1.OrdersPage#getorder)
- [listOrderCancelReasons](../wiki/resources.OrdersV1.OrdersPage#listordercancelreasons)
- [listOrders](../wiki/resources.OrdersV1.OrdersPage#listorders)
- [showPaymentPageForOrder](../wiki/resources.OrdersV1.OrdersPage#showpaymentpagefororder)

## Constructors

### constructor

• **new OrdersPage**()

Initialises the OrdersPage SDK

**`Example`**

Use this below JS snippet to create an instance of OrdersPage SDK 
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
```

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/orders-v1.ts:23](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/orders-v1.ts#L23)

## Methods

### cancelOrder

▸ **cancelOrder**(`cancelOrderRequestIn`, `callback`, `mockConfig?`): `undefined` \| ``false``

Attempts to cancel the confirmed order on customer's request

**`Example`**

For live SDK in production use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.cancelOrder(cancelOrderRequestIn, (error, responseObj) => {
    if (error) {
         // Appropriate actions on cancelOrder failure depending on error.errorCode 
    }

    // Appropriate actions on cancelOrder success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.cancelOrder(cancelOrderRequestIn, (error, responseObj) => {
    if (error) {
         // Appropriate actions on cancelOrder failure depending on error.errorCode 
    }

    // Appropriate actions on cancelOrder success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `cancelOrderRequestIn` | [`CancelOrderRequestIn`](../wiki/models.CancelOrderRequestIn) | The cancel order customer request |
| `callback` | (`error`: `any`, `response`: `any`) => `void` | The Callback function |
| `mockConfig?` | [`MockCancelOrderConfig`](../wiki/models.MockCancelOrderConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/orders-v1.ts:217](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/orders-v1.ts#L217)

___

### getOrder

▸ **getOrder**(`orderId`, `callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the order information for the given Id

**`Example`**

For live SDK in production use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.getOrder(orderId, (error, responseObj) => {
    if (error) {
         // Appropriate actions on getOrder failure depending on error.errorCode 
    }

    // Appropriate actions on getOrder success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.getOrder(orderId, (error, responseObj) => {
    if (error) {
         // Appropriate actions on getOrder failure depending on error.errorCode 
    }

    // Appropriate actions on getOrder success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `orderId` | `string` | The unique identifier for the customer order |
| `callback` | (`error`: ``null`` \| [`GetOrderError`](../wiki/models.GetOrderError), `responseObj`: ``null`` \| [`CustomerOrder`](../wiki/models.CustomerOrder)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetOrderConfig`](../wiki/models.MockGetOrderConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/orders-v1.ts:109](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/orders-v1.ts#L109)

___

### listOrderCancelReasons

▸ **listOrderCancelReasons**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the order cancellation reasons

**`Example`**

For live SDK in production use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.listOrderCancelReasons((error, responseObj) => {
    if (error) {
         // Appropriate actions on listOrderCancelReasons failure depending on error.errorCode 
    }

    // Appropriate actions on listOrderCancelReasons success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.listOrderCancelReasons((error, responseObj) => {
    if (error) {
         // Appropriate actions on listOrderCancelReasons failure depending on error.errorCode 
    }

    // Appropriate actions on listOrderCancelReasons success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: `any`, `response`: `any`) => `void` | The Callback function |
| `mockConfig?` | [`MockListOrderCancelReasonsConfig`](../wiki/models.MockListOrderCancelReasonsConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/orders-v1.ts:165](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/orders-v1.ts#L165)

___

### listOrders

▸ **listOrders**(`page`, `size`, `callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the list of orders for the given query

**`Example`**

For live SDK in production use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.listOrders(page, size, (error, responseObj) => {
    if (error) {
         // Appropriate actions on listOrders failure depending on error.errorCode 
    }

    // Appropriate actions on listOrders success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const ordersPageSDK = new OMNIBUS.OrdersV1.OrdersPage();
ordersPageSDK.listOrders(page, size, (error, responseObj) => {
    if (error) {
         // Appropriate actions on listOrders failure depending on error.errorCode 
    }

    // Appropriate actions on listOrders success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `page` | `number` | The page number of the orders list |
| `size` | `number` | The size of the page of the orders list |
| `callback` | (`error`: ``null`` \| [`ListOrdersError`](../wiki/models.ListOrdersError), `responseObj`: ``null`` \| [`OrdersListResult`](../wiki/models.OrdersListResult)[]) => `void` | The Callback function |
| `mockConfig?` | [`MockListOrdersConfig`](../wiki/models.MockListOrdersConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/orders-v1.ts:58](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/orders-v1.ts#L58)

___

### showPaymentPageForOrder

▸ **showPaymentPageForOrder**(`orderId`, `callback`, `mockConfig?`): `undefined` \| ``false``

#### Parameters

| Name | Type |
| :------ | :------ |
| `orderId` | `string` |
| `callback` | (`error`: ``null`` \| [`GetOrderError`](../wiki/models.GetOrderError), `responseObj`: ``null`` \| [`CustomerOrder`](../wiki/models.CustomerOrder)) => `void` |
| `mockConfig?` | [`MockGetOrderConfig`](../wiki/models.MockGetOrderConfig) |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/orders-v1.ts:130](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/orders-v1.ts#L130)
