# Class: MockListOrdersParams

[models](../wiki/models).MockListOrdersParams

Describes the Mock List Orders SDK params

## Table of contents

### Properties

- [numOfOrders](../wiki/models.MockListOrdersParams#numoforders)
- [orderids](../wiki/models.MockListOrdersParams#orderids)

## Properties

### numOfOrders

• `Optional` **numOfOrders**: `number` = `0`

Fetch the orders list of this size from orders in sample-orders data file of Forge. Max size is the max number of orders in the data file. In case both these parameters are not passed, this parameter defaults to all orders present in the data file.

#### Defined in

[models/orders.ts:191](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L191)

___

### orderids

• `Optional` **orderids**: `string`[] = `[]`

Fetch the orders list for the orders corresponding to these orderids in sample-orders data file of Forge. This parameter takes precedence over numOfOrders, in case both are mentioned.

#### Defined in

[models/orders.ts:187](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L187)
