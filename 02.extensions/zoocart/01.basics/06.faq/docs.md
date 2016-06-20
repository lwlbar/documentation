---
title: F.A.Q.
taxonomy:
    category: docs
---

* **Does ZOOcart generate Invoices?** <br /> No, that's not store scope but 3rd party integrations will be developed in the future. Alternatively, and in some countries, the **Order** print version is a valid document which the user can access under the **Print** button in the **Orders** view.

* **Where can I find ZOOcart Admin Panel?** <br /> In ZOOlanders component Nav Menu, make sure ZOOcart plugin is enabled.

* **Is it possible to specify the gross price instead of the net price, so that ZOOcart calculates net prices automatically?** <br /> Currently you can specify only the net price. The option "Show price and fees with tax" allows to display the item price with tax (gross price) or price without tax (net price).  The feature "Save price with included taxes" is planned for a future ZOOcart release (no planned date). 

* **How to change some text on ZOOcart layouts?** <br /> All ZOOcart text constants are available in the plugin translation file. The default file is in `/administrator/language/en-GB/en-GB.plg_system_zoocart.ini` where you can find any text and constant to be translated. To translate the language constant use Joomla! Language Manager, Overrides section to avoid overwriting text during extension updates.    

* **How to add a new payment plugin?** <br /> You can take as an example the existing payment plugin in the `/plugins/zoocart_payment` folder. The main plugin file should be inherited from the `JPaymentDriver` abstract class. There are several main functions to be overridden in the new plugin: `getPaymentFee()` - calculating the fee for using the payment system, `getRenderData()` - set the variables for template, `callback()` - method to make a payment. To make a payment you should review the payment system API. The payment views should be in the `tmpl` folder inside the plugin: `default.php` layout is used to render the form, `message.php` is shown after making a successful payment.

* **Why are shipping rates not assigning automatically?** <br /> Ensure that all conditions of your configured shipping rates are true for the current order.

* **How can a Subscribtion be renewed from the frontend?** <br /> On the [Subscriptions page](/extensions/zoocart/basics/integration#menu-assignment), the **Renew** button is available, after a Subscription ends (if this product still exists). After clicking on the Renew button the product will be added to the Cart and the user redirected to the Checkout.

* **Is ZOOcart compatible with Widgetkit widgets** <br /> Variation element is not compatible with Widgetkit2 widgets while the other elements are, depending on the Widget and its position.  
