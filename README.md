# Magento 2 Extention Recentorder
**Recentorder Magento extension** (Magepow Recentorder Extension) for Magento show beautiful recent sales popups to notify visitors of recently bought items. When you have very small amount of order, you can show fake order instead to attract customers.
## 1. How to install Magento 2 Recentorder
### ✓ Install Magepow Recentorder via composer (recommend)
Run the following command in Magento 2 root folder:

`composer require magepow/recentorder`

`php bin/magento setup:upgrade`

`php bin/magento setup:static-content:deploy -f`
## 2. Magepow Recentorder user guide
### General Configuration
#### Setting Magepow Recentorder
Go to `Admin Panel > Stores > Settings > Configuration > Magepow > Recentorder`
![config-module-img](https://github.com/magepow/magento2-recentorder/blob/master/media/recent_order1.jpg)

Select `Yes` to enable module.
Select `Yes` to use fake info order
Enter the fake product ids separated by commas
Enter the fake order shipping address
Enter the number limit products
Enter the product swap time(ms)
### This Is Result In Frontend
 ![result-img](https://github.com/magepow/magento2-recentorder/blob/master/media/recent_order.jpg)
 [![Latest Stable Version](https://poser.pugx.org/magepow/recentorder/v/stable)](https://packagist.org/packages/magepow/recentorder)
[![Total Downloads](https://poser.pugx.org/magepow/recentorder/downloads)](https://packagist.org/packages/magepow/recentorder)



