# Unbxd Site Search Module For Magento 2

The Magento 2 module, which provides the ability to search the site using the Unbxd service

Support Magento 2.2.\* || 2.3.\*

# Installation Guide

### Install by composer
Currently is not available.

### Manual installation

1. Download module Unbxd_ProductFeed [Link](https://github.com/unbxd/Magento-2-Extension/archive/master.zip)
1. Download module Unbxd_Analytics [Link](https://github.com/unbxd/Magento-2-Analytics/archive/master.zip)
2. Download this module [Link](https://github.com/unbxd/Magento-Search-Module/archive/master.zip)
3. Unzip modules in the folder:

    app\code\Unbxd\ProductFeed  
    app\code\Unbxd\Analytics  
    app\code\Unbxd\Search

4. Access the root of you Magento 2 instance from command line and run the following commands:

```
php bin/magento module:enable Unbxd_ProductFeed
php bin/magento module:enable Unbxd_Analytics
php bin/magento module:enable Unbxd_Search
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento cache:flush
```

5. Configure module in backend


 

