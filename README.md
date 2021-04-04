# Magelearn_PercentageShipping
Create Custom Shipping method based on a percentage of cart price.

### Screenshots

#### Admin Configuration
[![Configuration-Settings-Stores-Magento-Admin-1.png](https://i.postimg.cc/W3PY6T7C/Configuration-Settings-Stores-Magento-Admin-1.png)](https://postimg.cc/2q2xCpM7)

#### Frontend checkout page
[![Checkout-3.png](https://i.postimg.cc/Qxn6Ypbp/Checkout-3.png)](https://postimg.cc/w7Lc7Rnv)

## Installation

### Using Composer (Recommended)
 - Install the module composer by running `composer require magelearn/module-percentageshipping`
 - Enable the module by running `php bin/magento module:enable Magelearn_PercentageShipping`
 - apply database updates by running `php bin/magento setup:upgrade`
 - Flush the cache by running `php bin/magento cache:flush`

### Manual File Transfer
- Clone or unzip this repository to `app/code/Magelearn/PercentageShipping`
- Enable the module by running `php bin/magento module:enable Magelearn_PercentageShipping`
- Apply database updates by running `php bin/magento setup:upgrade`
- Flush the cache by running `php bin/magento cache:flush`

## Configuration
This module adds new fields to the Sales > Checkout section of your stores configuration.

### How to Configure
To access this module's configuration, navigate to `Stores > Settings > Configuration > Sales > Checkout` then expand the `Shopping Cart` group.

![Free Shipping Progress Bar Settings](https://i.postimg.cc/YCxh01N2/Annotate-a-local-image.png)

### Settings Explanation

#### Enable Free Shipping Progress Bar
If set to yes, a free shipping progress bar will be shown on the shopping cart in the cart summary. By default, the free shipping progress bar is disabled.

#### Use Free Shipping Method Configuration
If set to yes, this module will use the configuration for the core Free Shipping method. If that method is enabled then this Free Shipping Progress Bar will show based on that method's minimum order subtotal. If set to no, you will be able to set a custom order subtotal for this Free Shipping Progress Bar to show based on. This setting is primarily useful if your store is using a free shipping method other than the core Free Shipping method. By default, this setting is set to yes.

#### Free Shipping Progress Bar Minimum Order Total
When the above setting is set to no, this field is where you set the order value that the Free Shipping Progress Bar counts down to.

## Compatibility
This module has been tested and validated to work on Magento versions 2.3 to 2.4.2.

This module uses a ViewModel and should be compatible with versions 2.2 and higher.

## Bugs & Issues
If you find a bug or issue please create a new issue [here](https://github.com/vijayrami/Magelearn_FreeShippingProgressBar/issues) and include as much detail and context as possible including screenshots.

## License
This module is licensed under the Open Software License V3.0 which you can refer to [here](LICENSE.txt).
