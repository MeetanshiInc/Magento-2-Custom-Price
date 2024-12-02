# **Magento 2 Custom Price Extension**

The **Magento 2 Custom Price Extension** by Meetanshi offers an efficient way to personalize pricing for products on your Magento 2 store. Whether you’re running promotions, offering discounts or handling custom quotations, this extension provides seamless functionality to meet your needs. With the ability to set custom prices dynamically, you can cater to specific customer requirements and boost sales effectively.

## **How It Works**

The **Magento 2 Custom Price Extension** integrates seamlessly into your Magento 2 backend. It allows store admins to override the default product prices with custom pricing during the order process. Admins can set unique prices for specific products directly from the cart, ensuring flexibility in meeting customer demands or offering personalized deals.

## **Key Features**

* Set a minimum payment amount.  
* Edit prices in the product page or cart page.  
* Customers can edit prices on the product page or in the shopping cart page.

## **Override Product Prices**

The extension enables admins to override default product prices directly from the shopping cart, making it ideal for businesses offering discounts, negotiated prices or exclusive deals. Admins can set custom prices for individual products in the cart without altering the original prices in the catalog.

## **Dynamic Price Updates**

The extension allows for dynamic price adjustments based on specific conditions or customer requirements, enabling custom prices to be applied per customer, cart or order, with updated prices reflected instantly in the shopping cart and checkout process.

## **Enhance Customer Experience**

The extension offers personalized pricing for a tailored shopping experience, helping build customer loyalty through exclusive deals and enhancing satisfaction with flexible pricing solutions.

## **Extension Installation**

Installing the Magento 2 Custom Price Extension is straightforward. Follow these steps:

### **Step 1: Download the Extension Files**

Extract the ZIP folder and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2: Upload the Extension to Your Magento Installation**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 Custom Price Extension**

### **Step 1: Configure Settings**

To configure the extension, log in to Magento 2 and navigate to **Stores \> Configuration \> Custom Price**, where you can adjust various settings for the extension.

![configuration](https://github.com/user-attachments/assets/7c6025c3-5d5b-466a-827d-0ca867f3720b)

* **Custom Price**: Enable or disable the Custom Price extension here.  
* **Alert Message**: Enter a message to display when users add a price lower than the minimum custom price.

### **Step 2: Setting Custom Price for Products**

After enabling the extension, you can activate custom pricing for specific products. To do this, go to **Catalog \> Products**, select the product you want to enable custom pricing for, and edit it. Under the **Custom Price** tab, you can configure the following settings:

![Setting Custom Price for Products](https://github.com/user-attachments/assets/f57b3d9c-5771-473e-8409-11984bdac61f)

* **Enable Custom Price**: Set to "YES" to enable custom pricing for the selected product.  
* **Minimum Custom Price**: Define the minimum price for the product to allow checkout with the custom price on the frontend.

### **Step 3: Custom Price in the Frontend**

![Custom Price in the Frontend1](https://github.com/user-attachments/assets/2b6749a8-137a-407e-aaa6-34b696eddb99)

After successfully configuring the extension, when users add products with a custom price to their shopping cart, the system checks the minimum price set and allows checkout only if the custom price meets the required minimum.

* **Alert Message :** If customers enter a custom price lower than the set minimum, an alert message configured in the backend will be displayed.

![Alert Message](https://github.com/user-attachments/assets/5068cce7-1857-4eef-819c-608998322d4f)

## Download our [Magento 2 Custom Price](https://meetanshi.com/magento-2-custom-price.html) Extension
