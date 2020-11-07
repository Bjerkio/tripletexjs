[tripletexjs](../README.md) › [ProductExternalService](productexternalservice.md)

# Class: ProductExternalService

## Hierarchy

* **ProductExternalService**

## Index

### Methods

* [productExternalGet](productexternalservice.md#static-productexternalget)
* [productExternalSearch](productexternalservice.md#static-productexternalsearch)

## Methods

### `Static` productExternalGet

▸ **productExternalGet**(`__namedParameters`: object): *Promise‹[ResponseWrapperExternalProduct](../interfaces/responsewrapperexternalproduct.md)›*

[BETA] Get external product by ID.

**`result`** ResponseWrapperExternalProduct successful operation

**`throws`** ApiError

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type | Description |
------ | ------ | ------ |
`fields` | string | Fields filter pattern |
`id` | number | Element ID |

**Returns:** *Promise‹[ResponseWrapperExternalProduct](../interfaces/responsewrapperexternalproduct.md)›*

___

### `Static` productExternalSearch

▸ **productExternalSearch**(`__namedParameters`: object): *Promise‹[ListResponseExternalProduct](../interfaces/listresponseexternalproduct.md)›*

[BETA] Find external products corresponding with sent data. The sorting-field is not in use on this endpoint.

**`result`** ListResponseExternalProduct successful operation

**`throws`** ApiError

**Parameters:**

▪ **__namedParameters**: *object*

Name | Type | Default | Description |
------ | ------ | ------ | ------ |
`count` | number | 1000 | Number of elements to return |
`elNumber` | string | - | List of valid el numbers |
`fields` | string | - | Fields filter pattern |
`from` | number | - | From index |
`isInactive` | boolean | - | Equals |
`name` | string | - | Containing |
`nrfNumber` | string | - | List of valid nrf numbers |
`organizationNumber` | string | - | Wholesaler organization number. Mandatory if Wholesaler is not selected. If Wholesaler is selected, this field is ignored. |
`sorting` | string | - | Sorting pattern |
`wholesaler` | "AHLSELL" &#124; "BROEDRENE_DAHL" &#124; "ELEKTROSKANDIA" &#124; "HEIDENREICH" &#124; "ONNINEN" &#124; "OTRA" &#124; "SOLAR" &#124; "BERGAARD_AMUNDSEN" &#124; "BERGAARD_AMUNDSEN_STAVANGER" &#124; "SORLANDET_ELEKTRO" &#124; "ETMAN_DISTRIBUSJON" &#124; "ETM_OST" &#124; "CENIKA" &#124; "EP_ENGROS" &#124; "BETEK" &#124; "DGROUP" &#124; "FAGERHULT" &#124; "GLAMOX" &#124; "SCHNEIDER" &#124; "STOKKAN" &#124; "WURTH" &#124; "ELEKTROIMPORTOEREN" &#124; "THERMOFLOOR" &#124; "LYSKOMPONENTER" &#124; "NORDESIGN" | - | Wholesaler |

**Returns:** *Promise‹[ListResponseExternalProduct](../interfaces/listresponseexternalproduct.md)›*
