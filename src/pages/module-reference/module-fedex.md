---
title: Fedex
description: README.md contents of the module from the source code
---

# Magento_Fedex module

This module implements the integration with the FedEx shipping carrier.

## Installation details

For information about a module installation in Magento 2, see [Enable or disable modules](https://devdocs.magento.com/guides/v2.4/install-gde/install/cli/install-cli-subcommands-enable.html).

## Extensibility

Extension developers can interact with the Magento_Fedex module. For more information about the Magento extension mechanism, see [Magento plugins](https://developer.adobe.com/commerce/php/development/components/plugins/).

[The Magento dependency injection mechanism](https://developer.adobe.com/commerce/php/development/components/dependency-injection/) enables you to override the functionality of the Magento_Fedex module.

A lot of functionality in the module is on JavaScript, use [mixins](https://developer.adobe.com/commerce/frontend-core/javascript/mixins/) to extend it.

### Layouts

This module introduces the following layouts in the `view/frontend/layout` directory:

- `checkout_cart_index`
- `checkout_index_index`

## Additional information

You can get more information about delivery method in magento at the articles:

- [FedEx Configuration Settings](https://docs.magento.com/user-guide/shipping/fedex.html)
- [Delivery Methods Configuration](https://docs.magento.com/user-guide/configuration/sales/delivery-methods.html)
- [Add custom shipping carrier](https://developer.adobe.com/commerce/php/tutorials/frontend/custom-checkout/add-shipping-carrier/)
