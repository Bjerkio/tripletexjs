[tripletexjs](../README.md) › [PaymentTypeOut](paymenttypeout.md)

# Interface: PaymentTypeOut

## Hierarchy

* **PaymentTypeOut**

## Index

### Properties

* [changes](paymenttypeout.md#optional-readonly-changes)
* [creditAccount](paymenttypeout.md#creditaccount)
* [description](paymenttypeout.md#description)
* [id](paymenttypeout.md#optional-id)
* [isBruttoWageDeduction](paymenttypeout.md#optional-isbruttowagededuction)
* [isInactive](paymenttypeout.md#optional-isinactive)
* [requiresSeparateVoucher](paymenttypeout.md#optional-requiresseparatevoucher)
* [sequence](paymenttypeout.md#optional-sequence)
* [showIncomingInvoice](paymenttypeout.md#optional-showincominginvoice)
* [showVatReturns](paymenttypeout.md#optional-showvatreturns)
* [showWagePayment](paymenttypeout.md#optional-showwagepayment)
* [showWagePeriodTransaction](paymenttypeout.md#optional-showwageperiodtransaction)
* [url](paymenttypeout.md#optional-readonly-url)
* [version](paymenttypeout.md#optional-version)

## Properties

### `Optional` `Readonly` changes

• **changes**? : *Array‹[Change](../modules/change.md)›*

___

###  creditAccount

• **creditAccount**: *[Account](../modules/account.md)*

___

###  description

• **description**: *string*

___

### `Optional` id

• **id**? : *undefined | number*

___

### `Optional` isBruttoWageDeduction

• **isBruttoWageDeduction**? : *undefined | false | true*

true if it should be a deduction from the wage. The module PROVISIONSALARY is required to both view and change this setting

___

### `Optional` isInactive

• **isInactive**? : *undefined | false | true*

true if the payment type should be hidden from available payment types

___

### `Optional` requiresSeparateVoucher

• **requiresSeparateVoucher**? : *undefined | false | true*

true if a separate voucher is required

___

### `Optional` sequence

• **sequence**? : *undefined | number*

determines in which order the types should be listed. No 1 is listed first

___

### `Optional` showIncomingInvoice

• **showIncomingInvoice**? : *undefined | false | true*

true if the payment type should be available in supplier invoices

___

### `Optional` showVatReturns

• **showVatReturns**? : *undefined | false | true*

true if the payment type should be available in vat returns

___

### `Optional` showWagePayment

• **showWagePayment**? : *undefined | false | true*

true if the payment type should be available in wage payments. The wage module is required to both view and change this setting

___

### `Optional` showWagePeriodTransaction

• **showWagePeriodTransaction**? : *undefined | false | true*

true if the payment type should be available in period transactionsThe wage module is required to both view and change this setting

___

### `Optional` `Readonly` url

• **url**? : *undefined | string*

___

### `Optional` version

• **version**? : *undefined | number*
