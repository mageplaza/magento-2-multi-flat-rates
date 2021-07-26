# Magento 2 Multiple Flat Rates Shipping extension

Native Magento 2 only supports **one flat rate shipping** which can lead to difficulty for stores in defining the best price for delivering products to customers in different countries.  

[Magento 2 Multiple flat rate shipping](https://www.mageplaza.com/magento-2-multi-flat-rates/) is a must have for many online stores, especially international brands which deliver their products worldwide. Offering buyers different flat rates to select makes shopping easier and convenient for customers. Besides, this also helps stores manage shipping methods better.

[![Latest Stable Version](https://poser.pugx.org/mageplaza/module-multi-flat-rates/v/stable)](https://packagist.org/packages/mageplaza/module-multi-flat-rates)
[![Total Downloads](https://poser.pugx.org/mageplaza/module-multi-flat-rates/downloads)](https://packagist.org/packages/mageplaza/module-multi-flat-rates)


## 1. Flat Rates Shipping Documentation

- [Installation guide](https://www.mageplaza.com/install-magento-2-extension/)
- [User guide](https://docs.mageplaza.com/multi-flat-rates/index.html)
- [Contribute on Github](https://github.com/mageplaza/magento-2-multi-flat-rates/)
- [Get Support](https://github.com/mageplaza/magento-2-multi-flat-rates/issues)

## 2. FAQs

- **Q: I got an error: Mageplaza_Core has been already defined**

- A: Read solution: https://github.com/mageplaza/module-core/issues/3

## 3. How to install Magento 2 Multi Flat Rates Shipping extension

### Install via composer (recommend)

Run the following command in Magento 2 root folder:

With Marketing Automation (recommend):
```
composer require mageplaza/module-multi-flat-rates mageplaza/module-smtp
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Without Marketing Automation:
```
composer require mageplaza/module-multi-flat-rates
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
## 4. Multiple Flat Rates Shipping features

### 5 multiple flat rate shipping

**Magento 2 Multi flat rate shipping extension** allows store admins to add up to 5 other shipping rates. Admins are free to give a shipping flat rate a name and/or a title to help buyers distinguish it with others on Cart page and Checkout page. 

Each flat rate can be turned on/off easily on the backend. A set of configuration options for price, sort order, applicable countries, and error message are also ready to be selected.

### Sort multi flat rates neatly

As a store may want to have more than only one flat rate shipping, **Multiple Flat Rates Shipping** should be in a certain order. Admins can choose this order by sorting every shipping rate on the backend. 

### Multi flat rate visibility

**Each flat rate shipping** can be applied on a restricted number of countries or all allowed countries depending on the settings on backend. 

Admins can multiple select countries to allow buyers in those countries to choose a specific shipping flat rate.

### Error message

Buyers who are not in applicable countries will not be allowed to select that shipping flat rate. In this case, admins can set an error message to inform buyers. This message can be enabled/disabled and changed easily on the backend.

### Compatible with One Step Checkout

**Magento 2 Multi Flat Rates Shipping extension** is amazingly compatible with [Mageplaza One Step Checkout](https://www.mageplaza.com/magento-2-one-step-checkout-extension/) which delivers the best shopping experience for your customers. 


## 5. How to configure multiple flat rate shipping on Magento 2

From your Magento admin panel, follow this route: `Stores > Settings > Configuration > Sales > Shipping methods`. Then, click on `Flat rate #1 - Flat rate #5` to configure these 5 shipping rates.

![Magento 2 Multiple Flat Rates Shipping](https://i.imgur.com/yiEzfE6.png)

### Configure flat rate shipping #1

![Magento 2 Multiple Flat Rates Shipping module](https://i.imgur.com/s3kpRye.png)

- **Enable**: Select Yes to run Flat Rate #1
- **Method Name**: This is the name the flat rate #1 that is displayed on the View cart page and the Checkout page. If you leave this field blank, the rate will have no name on these two pages.
- **Price**: This is the shipping fee of Flat Rate #1 which is displayed on the frontend. If you leave this field blank, the price will be automatically set $0.00 as default.
- **Sort Order**: This is the order of Flat Rate #1 on the flat rates list displayed on the frontend. For example: If Sort Order = 1 is set for Flat Rate #1 while Sort Order = 2 is set for Flat Rate #2, Flat Rate #1 will stand above Flat Rate #2 on the frontend.

![Magento 2 Multiple Flat Rates Shipping extension](https://i.imgur.com/sgrBrOz.png)


- **Title**: This is the title of the flat rate which is displayed on the Cart page and Checkout page. If you leave this field blank, no title is displayed.

![Configure Multiple Flat Rates Shipping for Magento 2](https://i.imgur.com/bIfptAy.png)


- `Ship to Applicable Countries`: 
  - Select All Allowed Countries to apply the rate on all available countries.
  - Select Specific Countries to apply the rate on the countries which are selected on the field Ship to Specific Countries.

![Configure Magento 2 Multiple Flat Rates Shipping](https://i.imgur.com/GWOQSeW.png)

- `Ship to Specific Countries`: Select one or several countries which the rate is applied for.
- `Display Error Message`: Enter an error message which is displayed to buyers when the rate is not available. If you leave this box blank, the default message will be displayed: `Sorry, but we can’t deliver to the destination country with this shipping module`. This error message is displayed only when `Show Method if Not Applicable` = Yes
- `Show Method if Not Applicable`: Select Yes to display all shipping methods even when they do not belong to any applicable countries.

Similarly, admins can add up to 5 shipping methods and configure them for their online store.

![Mageplaza Multiple Flat Rates Shipping](https://i.imgur.com/JvvkKHF.png)

![Magento 2 Multi Flat Rates Shipping](https://i.imgur.com/bniI7zg.png)


**People alse search:**
- magento 2 multiple flat rate shipping
- magento 2 flat rate shipping
- flat rate magento 2
- magento 2 multiple shipping methods
- magento 2 multiple flat rate shipping free
- magento 2 shipping rates per product extension
- magento 2 shipping per product per country extension
- magento 2 product shipping rates per country extension


**Other free extension on Github**
- [Magento 2 Same Order Number](https://github.com/mageplaza/magento-2-same-order-number)
- [Magento 2 Google Maps](https://github.com/mageplaza/magento-2-google-maps)
- [Magento 2 popup extension](https://github.com/mageplaza/magento-2-better-popup)
- [Magento 2 Reports extension](https://github.com/mageplaza/magento-2-reports)
- [Magento 2 seo extension](https://github.com/mageplaza/magento-2-seo)
- [Magento 2 blog](https://github.com/mageplaza/magento-2-blog)
- [Magento 2 Layered Navigation](https://github.com/mageplaza/magento-2-ajax-layered-navigation)
- [Magento 2 security extension](https://github.com/mageplaza/magento-2-security)


**Get more [Magento 2 extension on Marketplace](https://marketplace.magento.com/partner/Mageplaza):**
- [Magento 2 Layered Navigation](https://marketplace.magento.com/mageplaza-layered-navigation-m2.html)
- [Magento 2 Payment Restriction](https://marketplace.magento.com/mageplaza-module-payment-restriction.html)
- [Magento 2 Auto Related Products](https://marketplace.magento.com/mageplaza-module-automatic-related-products.html)
- [Magento 2 SEO](https://marketplace.magento.com/mageplaza-magento-2-seo-extension.html)
- [Magento 2 Abandoned Cart Email](https://marketplace.magento.com/mageplaza-module-abandoned-cart-email.html)
- [Magento 2 SMTP](https://marketplace.magento.com/mageplaza-module-smtp.html)
- [Magento 2 Shipping Restrictions](https://marketplace.magento.com/mageplaza-module-shipping-restriction.html)
- [Magento 2 Multiple Coupons](https://marketplace.magento.com/mageplaza-module-multiple-coupons.html)
- [Magento 2 Order Attributes](https://marketplace.magento.com/mageplaza-module-order-attributes.html)
- [Magento 2 Gift Card](https://marketplace.magento.com/mageplaza-module-gift-card.html)
- [Magento 2 Affiliate Program](https://marketplace.magento.com/mageplaza-module-affiliate.html)


