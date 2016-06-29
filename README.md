# BluePay_ECheck_M2
BluePay E-Check payment module for Magento 2

# Installation
1. First, navigate to your Magento 2 root directory
2. Enter the following commands:

```cmd
composer config repositories.bluepay_echeck git https://github.com/jslingerland/BluePay_ECheck_M2.git
composer require bluepay/echeck:dev-master
```

Once the dependencies have finished installing, enter the next commands:

```cmd
php bin/magento module:enable BluePay_ECheck --clear-static-content
php bin/magento setup:upgrade
```

At this point, the module should be fully installed. Finally, log into your Magento admin section and navigate to Stores -> Configuration -> Payment Methods -> BluePay ECheck to finish the setup.
