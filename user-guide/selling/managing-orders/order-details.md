---
description: >-
  Fully redesigned for PrestaShop 1.7.7, the order details page helps you save
  time when processing your orders. On this page, you will learn how to manage
  order details.
---

# Order details management

## **Understanding the page organization**

Divided into **6 sections**, the page provides you all the details about an order. 

At the **top of the page** is a **quick summary** of the order containing the: 

* order reference 
* customer’s name
* total price 
* date and hour of validation

![](../../../.gitbook/assets/image%20%282%29.png)

In the **top left-hand corner**, the **“Customer” section** gives you information about the customer and the private note, if any. You can even access the customer's personal file to see more details.

![](../../../.gitbook/assets/image%20%285%29.png)

In the **top right-hand corner**, the **“Products” section** gives you access to various details on the ordered products.

![](../../../.gitbook/assets/image%20%286%29.png)

  
Just under the “Products” section, there is an **administrative section** that contains **four tabs** that give you access to the: 

* status and status history of the order
* documents related to the order \(e.g. invoice, delivery slip, etc.\)
* shipping information 
* merchandise returns

In **the bottom right-hand corner**, the **“Payment” section** gives you information about the payment details \(date of the transaction, method used, total amount, etc.\) You can also add a new payment. 

![](../../../.gitbook/assets/image%20%284%29.png)

Finally, the **“Messages” section** allows you to send a message to the customer about their order.

![](../../../.gitbook/assets/image%20%283%29.png)

## **Adding a product**

At the bottom of the "Products" list:

* Click on the "Add a product" button
* Enter the product’s name
* Select the product you want to add 
* Set the quantity and click on the “Add” button

![](https://lh4.googleusercontent.com/pN61QdHvvYXsyffV5na9GBQpZ7Ak6mXf0U7wnr-UJopwjxxYLUAb9mKju2VgCfBbHutyW0AV8zpDC9J-sT-2A5-lBphPcKbmjol3jX49E6pIP5WXmzZx-xT-0vYM0NrzKR7rSk2f)

Note that you cannot add more products than available in stock. When you select a product, the number of items in stock appears in the “Available” column.

To add a product that is already in the order, click on the “Edit” button and modify the "Quantity" field.

{% hint style="warning" %}
If the invoice has already been sent to the customer, you should not add new products to it. Instead, you should create another invoice: when adding a new product, choose "create a new invoice" in the drop-down list. 
{% endhint %}

## **‌Removing a product**

**‌**To cancel a product, go to the product list and delete the product by clicking on the "Delete" button. 

If you only want to remove a certain quantity, click on the “Edit” button and modify the "Quantity" field.

You can also cancel or edit the quantity of several products at the same time. To do so, click on the “Cancel products” button, at the top of the page and select the products, or the quantity you want to delete. This button is only available if merchandise returns are enabled in the Customer Service menu and if the order is not already paid for.

## **Editing the order status**

There are two places on the order page where you can update its status:

* In the top left-hand corner of the page, next to the action buttons.
* In the “Status” tab

Select the status you want in the drop-down list and click on the “Update status” button. 

You can choose between the following statuses:

![](https://lh6.googleusercontent.com/6UrdsTFPXoizMX_PyjnMDRvnZ7yuqcdqRrboLt3v0W2XXalPe3lTD0Iuv4fbb-mVLzK0alGYtWtMQWmo7W5rlDsl03a42CyJjQgieEvfiV1c9ga1MXtFfiQGgkCLPXd-D9d1-tDa)

{% hint style="info" %}
Any module impacting the order monitoring might extend this status list.
{% endhint %}

In order to get a better view of the order's activity, every status change is recorded in the “Status” tab, as well as its author and the date/time of the update.

![](../../../.gitbook/assets/image%20%281%29.png)

It is very important to **update a status only when it has been clearly confirmed**. For example, do not mark an order as “Delivered” when you have only sent the package, use “Shipped” instead. 

For some status updates, an email is sent to the customer. You can resend this email by clicking on the button next to the order status, in the “Status” tab. If you have edited the order at some point, the customer will receive an updated email.

## Accessing the order documents

You can get many PDF documents out of the order page. When available, they are listed in the "Documents" section of the page.‌

* **Print/Download the order**

You can print or download the order as a PDF by clicking on the "Print order" button at the top of the order page. 

* **Download the invoice**

You can download the invoice by clicking on the “View invoice” button at the top of the page. You can also access or generate the invoice in the “Documents” tab. ‌

In the “Documents” section, you can add a note to the invoice that will appear just below the tax table on the invoice. 

{% hint style="info" %}
Here is some advice for tech-savvy merchants: You can customize the invoice layout: the PDF template files are located in the /pdf folder. These .tpl files are actually HTML files with Smarty tags for dynamic data. You can change the invoice's layout by editing the file named invoice.tpl
{% endhint %}

* **Download the delivery slip**

If the order status is "Processing in progress", a delivery slip PDF is generated. You can download it from the "Documents" tab or click on the “View deliver slip” button at the top of the page. 

## **Editing shipping details**

In the administrative section, click on the “Carriers” tab. Then, click on the “Edit” button to modify the tracking number and the carrier. Note that the carrier can only be modified if the order has not been shipped yet. 

## **Editing the shipping address or the invoice address**

The shipping address is the address where the package will be sent, whereas the invoice address is the address of the buyer. They might be different \(in case of a customer ordering a gift for a friend, for example\). 

If a customer asks you to modify one of these addresses, go to the “Customer” section and click on the 3 vertical dots button, next to the “Shipping Address” or the “Invoice address” label. 

You can edit the existing address or select another address, from the list of addresses that were provided by the customer.

If the address you want to link to the order is not already registered in PrestaShop, you must create it first. To do this:

* In the “Customer section”, access the customer’s personal file, by clicking on “View full details”
* At the bottom of the page, click on the “+” in the “Addresses” section.
* Fill in the form and save
* Go back to the order details page and select the address in the drop-down list.

{% hint style="info" %}
You can also add a new address directly from the Customer &gt; Addresses page. If you choose this option, make sure to enter the correct email address for your customer, as PrestaShop will rely on this information to associate that new address with the existing customer.
{% endhint %}

## **Adding a discount**

‌In the "Products" section, at the bottom of the product listing, click on the "Add a new discount" button, and fill in the form:

![](https://lh4.googleusercontent.com/1WozYkYNQW2M0NuruC-5SGI5zbVsYheWGOC8elIvG6X6V1Qmw2G2iP25y1rZsLqeJgfMPzWQ8sqUti1B6WNYOSwLSXU473WpLn4YAKWiCdnBpl5uiM_0SFEY1_6lfXRXNDZ6jhWy)

* **Name:** Give the discount a short name. This will be visible to the customer.
* **Type:** Choose the discount type: "percent", "amount" or "free shipping".
* **Value:** For the "percent" or "amount" types, set the value of the discount. 
* **Invoice:** Select to which invoice of this order this discount should apply. When there is more than one invoice, you can check the box to apply the discount to all the invoices.

The discount is not applied to the shipping costs unless you check free shipping.

## **‌Attaching a message to the order**

In the "New Messages" section, in the bottom right-hand corner of the page, you can attach a comment to the order for your team. Write your comment in the message field and send it. The customer will not be able to see it. This can be particularly helpful if several employees take care of the same order and want to exchange information about it.

To make a message available for the customer, do not forget to check the “Display to customer” box before clicking on the “Send message” button. You might need to send the customer a message to keep them informed of their order’s progress or let them know about an unforeseen event. Communication is key for a good customer experience!

### **Send predefined messages**

You can select a predefined order message from the drop-down list. You can then add further details to the pre-written message if needed.

If you want to write custom predefined messages, click on the “Configure predefined messages” button. You will be redirected to the "Order messages" page, under the "Customer service" menu. From there, click on “Add new order message”. 

The message will be stored in the client's profile in your Customer Service database, which you can access either by going to the client's page, or the Customer Service page. **‌**

## Creating returns and refunds

### **Proceeding to a standard refund**

It is possible to proceed to refunds when the order is paid, or when at least one payment is linked to the order. Standard refunds are accessible only when merchandise returns are enabled on the Customer service &gt; Merchandise returns page. Once the order is shipped, you cannot proceed to a standard refund anymore.

* Click on the “Standard refund” button

A new column appears in the Products table, entitled “Standard refund”.

* Set the amount and quantity for each of the products you want to refund
* Choose one of the refund methods See “Choosing a refund option” below for more details.
* Check the “Shipping” box to refund the shipping costs too
* Click on the “Standard refund” button to validate

### **Proceeding to a partial refund** 

Partial refunds are only available when the order is paid, or when at least one payment is linked to the order. A partial refund is also possible after the order has left the warehouse. 

You should proceed to a partial refund if you only want to refund part of the order, either because the customer returned the ordered product, or simply as a sign of goodwill for a damaged product that the customer chose to keep anyway.

* Click on the “Partial refund” button

A new column appears in the Products table, entitled “Partial refund”.

* Set the amount and quantity for each of the products you want to refund
* Choose one of the refund methods See “Choosing a refund option” below for more details.
* Click on the “Partial refund” button to validate 

### **Registering a product return**

Registering a product return is possible only once the order is shipped and if requested by the customer. Merchandise returns should also be enabled on the Customer service &gt; Merchandise returns page.

Merchandise return requests from customers are available in the “Merchandise returns” tab.

Make sure that you have received the returned products. If everything is ok, you can mark it as “returned” directly from the order page. 

* Click on the “Return products” button

A new column appears in the Products table, entitled “Return products”

* Select the products and quantity returned 
* Click on the “Return products” button to validate ****

### **‌Choosing a refund option**

When you set a product as returned or to be refunded, four options are available, depending on the order status: 

#### **Re-stock products** 

When registering a product return, you may choose to re-stock the products in question.

If you select this option, PrestaShop will consider that the returned product is available for sale again, and will therefore increase the stock for this product. You should make sure not to check the “Re-stock products” box if the returned product has a manufacturing defect or is broken.

#### **Generate a credit slip** 

When proceeding to a refund, you may choose to generate a credit slip. 

A credit slip is an acknowledgment from the store that the merchandise refund has been issued. This will be used for accounting purposes.

Depending on your refund policy, you might pay the customer back or generate a voucher for their next purchase.

#### **Generate a voucher**

When proceeding to a refund, you may choose to generate a voucher.

A voucher takes the form of a discount code that the customer can enter during the checkout process.   
  
In PrestaShop, vouchers are part of a special kind of discount feature: "cart rules". They can be created and edited from the Cart Rules page, under the Discounts menu. You can also edit customers' existing vouchers directly from the Customer page, in the vouchers section.

#### **Repay shipping costs**

You can choose to refund the shipping costs of the returned products. It is always an appreciated gesture!

{% hint style="info" %}
If the order was paid by check or bank transfer, you will have to issue the refund yourself and update the order status to “Refunded” when it is done.
{% endhint %}

