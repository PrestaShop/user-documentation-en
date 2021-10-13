# Setting a store's URL

Each of your stores can have its own web address (URL), or even several ones, entirely independent from the default store.

Two stores can't share the same address. However, you can have as many stores as you want on one domain name:

* Using **subfolders**, for example: https://www.example.com**/men**, https://www.example.com**/women**, and https://www.example.com**/kids**.

{% hint style="info" %}
In the case of subfolder stores, make sure to create two URLs for each store: one with the "www.", and one without it.​

Otherwise, customers trying to access your secondary store without the "www." in the URL will be redirected to your main store.
{% endhint %}

* Using subdomains, for example: https://men.example.com, https://women.example.com, and https://kids.example.com.

Do not create any subdomain or subfolder yourself, either on your server or your computer: PrestaShop takes care of creating the path for you on your server. When the customer requests this path, PrestaShop will recognize the shop and serve the files and data for the correct store automatically.

Of course, a shop can also have its own domain name.

In case you want to use a different domain name for your supplemental shop rather than a subdomain/subfolder, you must configure your domain to point to the folder where PrestaShop is located. The URL rewriting is then done by PrestaShop itself.

Alternatively, you can create an alias for your domain name that redirects to the absolute URL where your installation of PrestaShop is located. The way to achieve this depends on the control panel and options that your hosting company provides you with: "Alias" for Plesk, "Forward" for CPanel, "Aliasdomain" for ISPConfig, etc.

To add a URL to a shop, select the shop in the "Multistore tree" selector, and then click on the "Add new URL" button. PrestaShop will load a screen with two sections and eight options:

* **URL options**.
  * **Shop**. A reminder of the shop to which you are adding a URL. You may also simply switch to another shop.
  * **Main URL**. By enabling this, you indicate that you want all the other URLs for this shop to redirect to this main URL (this will switch any other main URL to be a normal URL).
  * **Status**. You can disable and enable a URL at any time.
* **Shop URL**.
  * **Domain**. The shop's domain name itself. It does not have to be limited to the domain name: you can indicate a sub-domain if you need to. Just make sure to not add '`http://`', or any '`/`'. Example: [`www.example.com`](http://www.example.com) or [`kids.example.com`](http://kids.example.com).
  * **Domain SSL**. If your SSL domain is different from your main domain, be sure to indicate it in that field.
  * **Physical URL**. Here you must set the physical path to your actual installation on your server. If the shop is at the root of the domain or subdomain, leave this field empty. Example: `/` or `/kids/`.
  * **Virtual URL**. You can make the shop transparently available to customers using this option: through the power of URL rewriting, you can have your shop be displayed without the need to create a sub-folder. Of course, URL rewriting must be enabled in PrestaShop (meaning Friendly URLs, see the "SEO & URLs" page of the "Traffic" menu, in "Shop Parameters"). Example: `/shoes/`. Note that this only works for subfolder shops, not subdomain shops.
  * **Your final URL will be**. Gives you the impact that your URL settings above will have on the complete web address of your shop.
