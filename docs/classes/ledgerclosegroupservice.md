[tripletexjs](../README.md) › [LedgerCloseGroupService](ledgerclosegroupservice.md)

# Class: LedgerCloseGroupService

## Hierarchy

* **LedgerCloseGroupService**

## Index

### Methods

* [ledgerCloseGroupGet](ledgerclosegroupservice.md#static-ledgerclosegroupget)
* [ledgerCloseGroupSearch](ledgerclosegroupservice.md#static-ledgerclosegroupsearch)

## Methods

### `Static` ledgerCloseGroupGet

▸ **ledgerCloseGroupGet**(`__namedParameters`: object): *Promise‹[ResponseWrapperCloseGroup](../interfaces/responsewrapperclosegroup.md)›*

Get close group by ID.

**`result`** ResponseWrapperCloseGroup successful operation

**`throws`** ApiError

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type | Description |
------ | ------ | ------ |
`fields` | string | Fields filter pattern |
`id` | number | Element ID |

**Returns:** *Promise‹[ResponseWrapperCloseGroup](../interfaces/responsewrapperclosegroup.md)›*

___

### `Static` ledgerCloseGroupSearch

▸ **ledgerCloseGroupSearch**(`__namedParameters`: object): *Promise‹[ListResponseCloseGroup](../interfaces/listresponseclosegroup.md)›*

Find close groups corresponding with sent data.

**`result`** ListResponseCloseGroup successful operation

**`throws`** ApiError

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`count` | number | 1000 | Number of elements to return |
`dateFrom` | string | - | From and including |
`dateTo` | string | - | To and excluding |
`fields` | string | - | Fields filter pattern |
`from` | number | - | From index |
`id` | string | - | List of IDs |
`sorting` | string | - | Sorting pattern |

**Returns:** *Promise‹[ListResponseCloseGroup](../interfaces/listresponseclosegroup.md)›*