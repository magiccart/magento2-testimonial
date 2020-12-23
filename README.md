# magento2-testimonial
Testimonial magento 2 extension helps you to show testimonials listing on your website.

Before you continue, ensure you meet the following requirements:

  * You have installed magento2
  * You should use a Linux or Mac OS machine. Windows is not currently supported.
  Install magento2-testimonial extension

## Step 1 : Download magento2-testimonial extension

 ### Install via composer (recommend)
Run the following commands in Magento 2 root folder:
```
composer require magiccart/testimonial
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
```
 
## Step 2: User guide

  ### 1. General configuration

  Login to magento admin, choose `stores->configuration->magiccart->testimonial`
  
  ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/testimonial_config.jpg)

  Select `yes` to enable the module.
* "General": Config general information for testimonial such as Enabled/Disable, Title for testimonial, number per page...
* "Setting Slider":Setting style for testimonial such as testimonal slider, autoplay, speed, padding,...
* "Setting Responsive": Setting testimonial responsive with different Screens.
  
  ### 2. Manage Testimonial
  
   To manage Testimonials, please log in: `Admin > Magiccart > Testimonial`. It might look like this:
   
   ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config46.png)
    
    
 You can add, edit or delete item in testimonial. After that, click `Save Testimonial` to finish.
 * Add new
    
  ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/config_backend1.png)
  ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/config_backend2.png)
  ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/config_backend3.png)
   
 * Fill information then click Save Testimonial to finish.
 * To show on website, please go to `CONTENT > Elements > Widget > Add Widget`
   
   ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config47.png)
   ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config48.png)
   
   Then Choose `Design Theme` and click `Continue`
   
    ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config49.png)
   This is the interface of widget instance after clicking continue, Type and Design Package have already filled so you just need to fill Widget Title, choose Store View and   Sort Order. After that, choose layout update
   ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config50.png)
   ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config51.png)
    After selecting kind of page, you select which page will display testimonial widget and container(Container will be the position you want to put your widget on that page) and template
     ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config53.png)
    
   Run the following command:  
   ```
   php bin/magento cache:clean
   ```
  ### 3. Result
  ![Image of magento admin config](https://github.com/magiccart/magento2-testimonial/blob/master/media/theme_config45.png)

 ## Donation

If this project help you reduce time to develop, you can give me a cup of coffee :) 


[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/paypalme/alopay)

      
**Free Extensions List**

* [Magento 2 Recent Sales Notification](https://magepow.com/magento-2-recent-sales-notification.html)

* [Magento 2 Categories Extension](https://magepow.com/magento-categories-extension.html)

* [Magento 2 Sticky Cart](https://magepow.com/magento-sticky-cart.html)

**Premium Extensions List**

* [Magento 2 Pages Speed Optimizer](https://magepow.com/magento2-speed-optimizer.html)

* [Magento 2 Mutil Translate](https://magepow.com/magento-multi-translate.html)

* [Magento 2 Instagram Integration](https://magepow.com/magento-2-instagram.html)

* [Magento 2 Lookbook Pin Products](https://magepow.com/lookbook-pin-products.html)

**Featured Magento Themes**

* [Expert Multipurpose responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/expert-premium-responsive-magento-2-and-1-support-rtl-magento-2-/21667789)

* [Gecko Premium responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/gecko-responsive-magento-2-theme-rtl-supported/24677410)

* [Milano Fashion responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/milano-fashion-responsive-magento-1-2-theme/12141971)

* [Electro responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/electro-responsive-magento-1-2-theme/17042067)

* [Pizzaro Food responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/pizzaro-food-responsive-magento-1-2-theme/19438157)

* [Biolife Organic responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/biolife-organic-food-magento-2-theme-rtl-supported/25712510)

* [Market responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/market-responsive-magento-2-theme/22997928)

* [Kuteshop responsive Magento 2 Theme](https://1.envato.market/c/1314680/275988/4415?u=https://themeforest.net/item/kuteshop-multipurpose-responsive-magento-1-2-theme/12985435)

**Featured Magento Services**

* [PSD to Magento 2 Theme Conversion](https://magepow.com/psd-to-magento-theme-conversion.html)

* [Magento Speed Optimization Service](https://magepow.com/magento-speed-optimization-service.html)

* [Magento Security Patch Installation](https://magepow.com/magento-security-patch-installation.html)

* [Magento Website Maintenance Service](https://magepow.com/website-maintenance-service.html)

* [Magento Professional Installation Service](https://magepow.com/professional-installation-service.html)

* [Magento Upgrade Service](https://magepow.com/magento-upgrade-service.html)

* [Customization Service](https://magepow.com/customization-service.html)

* [Hire Magento Developer](https://magepow.com/hire-magento-developer.html)

[![Latest Stable Version](https://poser.pugx.org/magiccart/testimonial/v/stable)](https://packagist.org/packages/magiccart/testimonial)
[![Total Downloads](https://poser.pugx.org/magiccart/testimonial/downloads)](https://packagist.org/packages/magiccart/testimonial)
