---
description: >-
  From the order page, not only can you access all of the order details, but
  also edit and update them.
---

# Editing an order

## **Updating the order status**

There are two places on the order page where you can update its status:

* In the **top left-hand corner** of the page, next to the action buttons.
* In the **Status tab**

Select the status you want in the drop-down list and click on the “Update status” button. 

![](../../../../.gitbook/assets/image%20%2816%29.png)

You can choose between the following statuses:

![](https://lh6.googleusercontent.com/6UrdsTFPXoizMX_PyjnMDRvnZ7yuqcdqRrboLt3v0W2XXalPe3lTD0Iuv4fbb-mVLzK0alGYtWtMQWmo7W5rlDsl03a42CyJjQgieEvfiV1c9ga1MXtFfiQGgkCLPXd-D9d1-tDa)

{% hint style="info" %}
Any module impacting the order monitoring might extend this status list.
{% endhint %}

In order to get a better view of the order's activity, every status change is recorded in the “Status” tab, as well as its author and the date/time of the update.

![](../../../../.gitbook/assets/image%20%281%29.png)

{% hint style="warning" %}
It is very important to **update a status only when it has been clearly confirmed**. For example, do not mark an order as “Delivered” when you have only sent the package, use “Shipped” instead. 
{% endhint %}

📨 For some status updates, an email is sent to the customer. You can resend this email by clicking on the button next to the order status, in the Status tab. If you have edited the order at some point, the customer will receive an updated email.

## Accessing the order documents

You can get many PDF documents out of the order page. When available, they are listed in the Documents tab of the administrative section.‌

* **Print/Download the order** 

You can print or download the order as a PDF by clicking on the "**Print order**" button at the top of the order page.

* **Download/Generate an invoice** 

You can download the invoice by clicking on the “**View invoice**” button at the top of the page. You can also access or generate the invoice in the Documents tab. ‌

➡ In the Documents section, you can add a note to the invoice that will appear just below the tax table on the invoice. 

{% hint style="success" %}
Here is a tip for tech-savvy merchants: You can **customize the invoice layout**: the PDF template files are located in the /pdf folder. These .tpl files are actually HTML files with Smarty tags for dynamic data. You can change the invoice's layout by editing the file named invoice.tpl
{% endhint %}

* **Download the delivery slip**

If the order status is "Processing in progress", a delivery slip PDF is automatically generated. You can download it from the Documents tab or click on the “View deliver slip” button at the top of the page. 

## Editing order items

### **Adding a product**

![](https://lh4.googleusercontent.com/pN61QdHvvYXsyffV5na9GBQpZ7Ak6mXf0U7wnr-UJopwjxxYLUAb9mKju2VgCfBbHutyW0AV8zpDC9J-sT-2A5-lBphPcKbmjol3jX49E6pIP5WXmzZx-xT-0vYM0NrzKR7rSk2f)

At the bottom of the product list:

* Click on the "Add a product" button
* Enter the product’s name
* Select the product you want to add 
* Set the quantity 
* Select the invoice on which you want this product to appear and click on the "Add" button

{% hint style="warning" %}
If the invoice has already been sent to the customer, you should not add new products to it. Instead, you should create another invoice: when adding a new product, choose "create a new invoice" in the drop-down list. 
{% endhint %}

Note that you cannot add more products than available in stock. When you select a product, the number of items in stock appears in the “Available” column.

➡ To add a product that is already present in the order, click on the “Edit” button and modify the quantity.

### **‌Removing a product**

**‌**To remove a product from the order, go to the product list and delete the product by clicking on the "Delete" button. 

➡ If you only want to remove a certain quantity, click on the “Edit” button and modify the "Quantity" field.

{% hint style="success" %}
You can also cancel or edit the quantity of **several products at the same time**.   
  
To do so, click on the “Cancel products” button, at the top of the page and select the products, or the quantity you want to delete. This button is only available if merchandise returns are enabled in the Customer Service menu and if the order is not already paid for.
{% endhint %}

## **Editing order details** 

### **Editing shipping details**

In the administrative section, click on the Carriers tab. Then, click on the “Edit” button to modify the tracking number and the carrier. 

➡ Note that the carrier can only be modified if the order has not been shipped yet. 

### **Editing the shipping address or the invoice address**

The **shipping address** is the address where the package will be sent, whereas the **invoice address** is the address of the buyer. They might be different \(in case of a customer ordering a gift for a friend, for example\). 

If a customer asks you to modify one of these addresses, go to the Customer section and click on the hamburger menu next to the “Shipping Address” or the “Invoice address” label. 

You can edit the existing address or select another address, from the list of addresses that were provided by the customer.

![](../../../../.gitbook/assets/image%20%2810%29.png)

If the address you want to link to the order is not already registered in PrestaShop, you must create it first. To do this:

* In the Customer section of the order page, access the customer’s personal file, by clicking on “View full details”
* At the bottom of the page, click on the “+” in the Addresses section.
* Fill in the form and save
* Go back to the order details page and select the address in the drop-down list.

![Adresses section of the Customer page](../../../../.gitbook/assets/image%20%2813%29.png)

## **Managing payments and discounts**

### **Registering a new payment**

To register a new payment, go to the Payments section of the order page.

* Select the date of the payment and the payment method used
* Enter the transaction ID
* Enter the amount and select the currency 
* Select the invoice on which you want this payment to appear
* Click on the "Add" button to save 

![](../../../../.gitbook/assets/image%20%2819%29.png)

### **Adding a discount**

‌In the Products section, at the bottom of the order product list, click on the "Add a new discount" button, and fill in the form:

![](https://lh4.googleusercontent.com/1WozYkYNQW2M0NuruC-5SGI5zbVsYheWGOC8elIvG6X6V1Qmw2G2iP25y1rZsLqeJgfMPzWQ8sqUti1B6WNYOSwLSXU473WpLn4YAKWiCdnBpl5uiM_0SFEY1_6lfXRXNDZ6jhWy)

* **Name:** Give the discount a short name. This will be visible to the customer.
* **Type:** Choose the discount type: "percent", "amount" or "free shipping".
* **Value:** For the "percent" or "amount" types, set the value of the discount. 
* **Invoice:** Select the invoice on which you want this discount to apply. When there is more than one invoice, you can check the box to apply the discount to all the invoices.

{% hint style="warning" %}
The discount is not applied to the shipping costs unless you check free shipping.
{% endhint %}

## **‌Managing order messages and customer private notes**

### **Adding  a private note** 🔏 

In the Customer section, you can add a private note on a customer that will only be visible by you and your team. It can very useful to let your colleagues know about important information about the customer: he or she a regular customer? should special attention be paid because of a previous incident? 

### **Attaching a message to the order**  📧 

You might need to send the customer a message to keep them informed of their order’s progress or let them know about an unforeseen event. **Communication is key for a good customer experience!** And the good news is that you can do it very easily from the order page:

Write your message in the message field and send it. 

* [x] If you want your customer to receive it, do not forget to check the "Display to customer?" box.  
* [ ] You might want to keep this message available **for you and your team only**. That is also possible: just leave the "Display to customer?" box unchecked. 

#### **Send predefined messages**

You can select a predefined order message from the drop-down list. 

You can then add further details to the pre-written message if needed.

If you want to write custom predefined messages, click on the “Configure predefined messages” button. You will be redirected to the Order Messages page, under the Customer service menu.

To know more:

{% page-ref page="../../managing-customer-service/order-messages.md" %}

