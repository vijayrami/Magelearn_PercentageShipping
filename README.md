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
This module adds new shipping method to the Store >> Configuration >> Sales >> Shipping Method of your stores configuration.

### How to Configure

## Compatibility
This module has been tested and validated to work on Magento versions 2.3 to 2.4.2.

## Bugs & Issues
If you find a bug or issue please create a new issue [here](https://github.com/vijayrami/Magelearn_PercentageShipping/issues) and include as much detail and context as possible including screenshots.

## License
This module is licensed under the Open Software License V3.0 which you can refer to [here](LICENSE.txt).
