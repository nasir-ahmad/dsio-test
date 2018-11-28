# DirectSalesIO Test for Magento 2

## How to install Mageplaza_Core


### Install via composer

Run the following command in Magento 2 root folder

#### Install

```
composer require directsalesio/module-test
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

#### Update

```
composer update directsalesio/module-test
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run compile if your store in Product mode:

```
php bin/magento setup:di:compile
```
