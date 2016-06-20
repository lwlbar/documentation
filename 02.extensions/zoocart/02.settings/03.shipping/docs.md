---
title: Shipping
taxonomy:
    category: docs
---

These options apply if your store ships physical products.

| Field       | Description |
| :---------- | :---------- |
| **Enabled Shipping Rates** | The Shipping status. When enabled the shipping information will be required and processed during checkout. This option requires at least one shipping plugin to be installed and enabled. |
| **Assign shipping automatically** | When enabled and only one shipping rate is available, it will be auto selected during checkout. |
| **Filter considering with taxes** | When enabled the shipping filter will consider the rates with item taxes included. Recommended when Show Prices with tax is enabled. |

## Shipping Rates Manager

![Shipping Rates Manager](shipping.png)

In the Settings Shipping tab upper right corner is the **Shipping Rates Manager** button, leading to the view where you can create new shipping rates or manage existing ones with the following options:

| Field       | Description | Element value |
| :---------- | :---------- | :---------- |
| **Name** | Shipping rate name that will be displayed during checkout. ||
| **Status** | The shipping rate status. ||
| **Price** | The rate price. ||
| **Type** | The rate type, based on ordered items or entire order. ||
| **Price From** | The lower price margin. | PricePro |
| **Price To** | The upper price margin. | PricePro |
| **Quantity From** | The lower quantity margin. | Quantity |
| **Quantity To** | The upper quantity margin. | Quantity |
| **Weight From** | The lower weight margin. | MeasurePro |
| **Weight To** | The upper weight margin. | MeasurePro |
| **Countries** | The countries the shipping rates are applied to. | Address field marked as 'Country' |
| **States** | The countries states the shipping rates are to be applied to. | Address field marked as 'State' |
| **Cities** | The countries cities the shipping rates are to be applied to. | Address field marked as 'City' |
| **ZIP Codes** | The ZIP codes (comma separated) the shipping rate is to be applied to. | Address field marked as 'ZIP code' |
| **User Groups** | The User Groups the shipping rates is to be applied to. ||

>>> _Countries_, _States_, _Cities_, _ZIP Codes_ and _User Groups_ fields will limit the shipping rates availability. If you don't want to apply any limit leave these options empty.
