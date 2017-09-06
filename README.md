# modular_eCommerce_component


<br/><h2>Modular/Plugable components of eCommerce Software</h2>
<br/>Modules :
<br/>-Invoice
<br/>-Catalog
<br/> ---With Search/Filter Sub Module
<br/>-Checkout
<br/>-Cart
<br/>-Payment
<br/> ---SubComponents(Per payment or transaction type)



<br/><h2>Technology Stack</h2>
<br/>-Spring Boot
<br/>-REST
<br/>-MVC
<br/>-ORM
<br/>-JDBC(Might Consider Hibernate/JPA)
<br/>-MYSQL
<br/>-Considering AWS in the future
<br/>-Others TBD



<br/><h2>Product Catalog</h2>
<p>Say I found a vendor, perhaps a niche manufacturer, that says that it will (a) hold inventory of its products on my behalf, (b) let me sell those products virtually through my ecommerce site, and (c) fulfill the products directly to my end customer. Now all I need is the vendor’s virtual product catalog to plug into my ecommerce storefront and I’ll be off and running.</p>

<p>But what, exactly, is a “product catalog”? Here’s a list of the basic data of a product catalog that a vendor-supplier could provide to its resellers.</p>

<p><h3>sku</h3>. Stock keeping unit.</p>
<p><h3>title</h3>. The title of the SKU. A common practice is to combine this data with other fields (such as manufacturer and brand) to end up with a more complete title (e.g., “Lenovo ThinkPad T410 Notebook”).</p>

<p><h3>quantity available</h3>. The quantity available for order. The amount in the supplier’s warehouse, ready for shipment.</p>

<p><h3>cost</h3>. The wholesale price of the SKU.</p>

<p><h3>product</h3>. A group identifier that supports item options-variants. For example, a t-shirt in 3 colors and 5 sizes could be structured as 15 SKUs grouped together as one product. Data such as cost, quantity, and title is always associated with an SKU and not the product. Product is just a grouping of closely related SKUs.</p>

category. The category the SKU is assigned to in human-readable format. If categories are hierarchal, the relationship between top-level categories and subsequent leaf (detail) categories needs to be represented.
description. Full description that describes the SKU. HTML is generally used.
brand. The brand or manufacturer of the SKU.
map. Minimum advertised price.
msrp. Manufacturer’s suggested retail price.
mpn. Manufacturer part number.
upc. Universal product code.
length. The length of the SKU-item.
width. The width of the SKU-item.
height. The height of the SKU-item.
weight. The weight of the SKU-item.
handling cost. The handling cost or fees that will be added to the order when this SKU is fulfilled.
product attributes. Possible attributes could include “color,” “size,” “rating,” “genre,” or “publisher.” Attributes can be used in place of, or in addition to, product variant groupings, as explained above.
product images. The SKU’s product image(s).
Not all vendors will be able to provide all of this data. The list above represents the most critical components, those that a retailer needs to sell the product to a consumer.
