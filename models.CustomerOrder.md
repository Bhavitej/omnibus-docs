# Class: CustomerOrder

[models](../wiki/models).CustomerOrder

Describes the information of Customer order

## Table of contents

### Constructors

- [constructor](../wiki/models.CustomerOrder#constructor)

### Properties

- [amount](../wiki/models.CustomerOrder#amount)
- [billingAddress](../wiki/models.CustomerOrder#billingaddress)
- [charges](../wiki/models.CustomerOrder#charges)
- [id](../wiki/models.CustomerOrder#id)
- [orderdate](../wiki/models.CustomerOrder#orderdate)
- [orderdetails](../wiki/models.CustomerOrder#orderdetails)
- [orderedforname](../wiki/models.CustomerOrder#orderedforname)
- [orderid](../wiki/models.CustomerOrder#orderid)
- [orderstatus](../wiki/models.CustomerOrder#orderstatus)
- [shippingAddress](../wiki/models.CustomerOrder#shippingaddress)
- [shippingcost](../wiki/models.CustomerOrder#shippingcost)

## Constructors

### constructor

• **new CustomerOrder**()

## Properties

### amount

• **amount**: `number` = `0`

#### Defined in

[models/orders.ts:91](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L91)

___

### billingAddress

• `Optional` **billingAddress**: [`Address`](../wiki/models.Address)

#### Defined in

[models/orders.ts:96](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L96)

___

### charges

• **charges**: [`Charge`](../wiki/models.Charge)[] = `[]`

#### Defined in

[models/orders.ts:98](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L98)

___

### id

• **id**: `string` = `''`

#### Defined in

[models/orders.ts:88](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L88)

___

### orderdate

• **orderdate**: `string` = `''`

#### Defined in

[models/orders.ts:93](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L93)

___

### orderdetails

• **orderdetails**: [`OrderDetail`](../wiki/models.OrderDetail)[] = `[]`

#### Defined in

[models/orders.ts:95](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L95)

___

### orderedforname

• **orderedforname**: `string` = `''`

#### Defined in

[models/orders.ts:90](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L90)

___

### orderid

• **orderid**: `string` = `''`

#### Defined in

[models/orders.ts:89](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L89)

___

### orderstatus

• **orderstatus**: [`OrderStatus`](../wiki/models.OrderStatus) = `OrderStatus.PENDING_PAYMENT`

#### Defined in

[models/orders.ts:92](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L92)

___

### shippingAddress

• `Optional` **shippingAddress**: [`Address`](../wiki/models.Address)

#### Defined in

[models/orders.ts:97](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L97)

___

### shippingcost

• **shippingcost**: `number` = `0`

#### Defined in

[models/orders.ts:94](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/orders.ts#L94)
