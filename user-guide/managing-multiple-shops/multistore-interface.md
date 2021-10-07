# The multistore interface

## Managing your stores <a id="Themultistoreinterface-Managingyourstores"></a>

The "Multistore" page comprises three mains sections:

* **Multistore tree**. Gives you a bird's eye view of your shop groups, their shops, and even the various URLs tied to a single shop. By default, there is only one shop, in the default group: the main shop.
* **Shop groups** table. Lists the available shop groups. You can edit them by click on the 'Edit' icon on the right.
* **Multistore options**. Lists the available options for the existing shops.
  * **Default shop**. The default shop is the one which will serve a central hub for all the other ones, shares its details with other shops \(products, carriers, etc.\), and is the one that appears when you log in the administration.

![](../../.gitbook/assets/57081978%20%284%29%20%284%29%20%283%29.png)

## One back office to rule them all <a id="Themultistoreinterface-Onebackofficetorulethemall"></a>

When the multistore feature is enabled for your PrestaShop installation, many aspects of PrestaShop become customizable on a per-shop or per-shop-group basis.

To help you understand which shop your changes are applied to, PrestaShop adds a drop-down selector at the top of each screen, where you can choose the scope of application of your changes:

* Apply to all of your shops on this installation of PrestaShop.
* Apply to only the shops of the selected shop group.
* Apply to only the selected shop.

![](../../.gitbook/assets/57081980%20%284%29%20%284%29%20%282%29.png)

This shop selector helps you know on which shop\(s\) you are currently working.

That being said, once the multistore mode is in place, many of the regular settings can only be changed on a global \(all shops\) scale \(international, shop and advanced parameters, administration\) and will, therefore, present the options as disabled in any other selection. Still, you can choose to edit those settings on a more local \(per group shop or even per shop\) scale if it is needed.

Indeed, settings pages will look regular when the shop selector is on "All shops", while in any other selection \(shop group or single shop\) they get additional options:

* A "Yes/No" option at the top of each section of the settings page.
* A check box next to each option.

![](../../.gitbook/assets/57082007%20%284%29%20%284%29.png)

They both serve the same purpose: letting you enable the options that would otherwise be disabled in the current shop context. You can pick the options that you want to enable, or you can enable all the options of the section by switching the Yes/No option. Once enabled, it is up to you to change the value of each option: clicking the checkbox or switching the Yes/No option does not change any settings, it just allows you to change it in that context.

Nevertheless, some options cannot be edited in a local context: they will display "You can't change the value of this configuration field in the context of this shop".

**Categories**: A product can only appear in a given category of a shop if it has been associated with this category in that shop's context. In other words: if shop A and shop B have the C category in common, you can associate the P product to the C category for the A shop's context, and P will not appear in category C on shop B.

**Carriers**: You can manage the carriers' association on a per-shop basis, a per-shop-group basis or for all shops; but you cannot customize a carrier on a per-shop basis. You must duplicate the carrier if you want to use the same carrier with different price ranges on two shops.

**Products:** For each shop, you can set specific prices for every product, share part of the catalog or the whole of it, change product images, etc.

**Customers:** You can choose to share the customer accounts between your shops, enabling your customers to use the credentials between all shops, and even be transparently signed-in to each.

