# Class: MockProductSearchQueryParams

[models](../wiki/models).MockProductSearchQueryParams

Describes the Mock Product search Query SDK params

## Table of contents

### Properties

- [numOfResults](../wiki/models.MockProductSearchQueryParams#numofresults)
- [productcodes](../wiki/models.MockProductSearchQueryParams#productcodes)

## Properties

### numOfResults

• `Optional` **numOfResults**: `number`

The number of search results to be fetched from sample-products data file. If both productcodes and numOfResults are not specified, then numOfResults defaults to all products in the data file

#### Defined in

[models/search.ts:93](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L93)

___

### productcodes

• `Optional` **productcodes**: `string`[]

This refers to the productcodes of the products of choice in sample-products data file of Forge. If both productcodes and numOfResults are specified, productcodes takes higher precedence than numOfResults

#### Defined in

[models/search.ts:89](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/models/search.ts#L89)
