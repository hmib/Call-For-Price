# CallForPrice-Magento2

# Overview

Call For Price extension for Magento 2 has been developed by the product team at RLTSquare. This extension supports store owners to manage product’s price visibility. So buyers contact the store owners to ask for price.

The products are sold by a large number of distributors, so shop owners keep the price non-public to avoid the competitiveness. Also the price changes with time, so showing the fixed price is not good. Customers should contact directly to get the actual price of the product.  

Let’s imagine that you own an online store selling high-tech gadgets and a visitor comes across. He feels curious about some kind of product but  the price is showed and he finds that he can not afford it, then he will leave your store without buying that product. But hiding the price will make the customer to invest more time to deeply understand the product value before considering its price. Hiding prices will increase the communication between store owners and buyers. Customer will be able to negotiate about the product price privately. It will increase the store’s sale rate. 

Here are some of the salient features for the extension:

```
1. Hide Price & Add to Cart of Specific Products
2. eplace with a button to open a quote form
3. Hide by Products & Store Views
4. Visible on Product Page 
5. Email Notifications for Both Merchants & Customers
```

## Installation

### Magento® Marketplace

This extension will also be available on the Magento® Marketplace when approved.

### Manually

1. Go to Magento® 2 root folder

2. Require/Download this extension:

   Enter following commands to install extension.

   ```
   composer require rltsquare/call-for-price
   ```

   Wait while composer is updated.
   
   #### OR
   
   You can also download code from this repo under Magento® 2 following directory:
    
    ```
    app/code/RLTSquare/CallForPrice
    ```    

3. Enter following commands to enable the module:

   ```
   php bin/magento module:enable RLTSquare_CallForPrice
   php bin/magento setup:upgrade
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```

4. If Magento® is running in production mode, deploy static content: 

   ```
   php bin/magento setup:static-content:deploy
   ```


## Requirements

1. This Magento® extension works on Magento 2.2 and 2.3 versions. Tested on versions 2.3.0 and above.

2. Tested on different themes specifically Ultimo, Porto and certain custom themes

For details, read our blog:
https://www.rltsquare.com/blog/call-for-price-magento-2-extension/
