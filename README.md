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


<h3>Product Catalog</h3>
<p>Say I found a vendor, perhaps a niche manufacturer, that says that it will (a) hold inventory of its products on my behalf, (b) let me sell those products virtually through my ecommerce site, and (c) fulfill the products directly to my end customer. Now all I need is the vendor’s virtual product catalog to plug into my ecommerce storefront and I’ll be off and running.</p>
<p>But what, exactly, is a “product catalog”? Here’s a list of the basic data of a product catalog that a vendor-supplier could provide to its resellers.</p>

<ul>
<li><em><strong>sku.</strong></em> Stock keeping unit.</li>
</ul>
<ul>
<li><em><strong>title.</strong></em> The title of the SKU. A common practice is to combine this data with other fields (such as manufacturer and brand) to end up with a more complete title (e.g., “Lenovo ThinkPad T410 Notebook”).</li>
</ul>
<ul>
<li><em><strong>quantity available.</strong></em> The quantity available for order. The amount in the supplier&#8217;s warehouse, ready for shipment.</li>
</ul>
<ul>
<li><em><strong>cost.</strong></em> The wholesale price of the SKU.</li>
</ul>
<ul>
<li><em><strong>product.</strong></em> A group identifier that supports item options-variants. For example, a t-shirt in 3 colors and 5 sizes could be structured as 15 SKUs grouped together as one product. Data such as cost, quantity, and title is always associated with an SKU and not the product. Product is just a grouping of closely related SKUs.</li>
</ul>
<ul>
<li><em><strong>category.</strong></em> The category the SKU is assigned to in human-readable format. If categories are hierarchal, the relationship between top-level categories and subsequent leaf (detail) categories needs to be represented.</li>
</ul>
<ul>
<li><em><strong>description.</strong></em> Full description that describes the SKU. HTML is generally used.</li>
</ul>
<ul>
<li><strong><em>brand.</em></strong> The brand or manufacturer of the SKU.</li>
</ul>
<ul>
<li><em><strong>map.</strong></em> Minimum advertised price.</li>
</ul>
<ul>
<li><em><strong>msrp.</strong></em> Manufacturer&#8217;s suggested retail price.</li>
</ul>
<ul>
<li><em><strong>mpn.</strong></em> Manufacturer part number.</li>
</ul>
<ul>
<li><em><strong>upc.</strong></em> Universal product code.</li>
</ul>
<ul>
<li><em><strong>length.</strong></em> The length of the SKU-item.</li>
</ul>
<ul>
<li><em><strong>width.</strong></em> The width of the SKU-item.</li>
</ul>
<ul>
<li><em><strong>height.</strong></em> The height of the SKU-item.</li>
</ul>
<ul>
<li><em><strong>weight.</strong></em> The weight of the SKU-item.</li>
</ul>
<ul>
<li><em><strong>handling cost.</strong></em> The handling cost or fees that will be added to the order when this SKU is fulfilled.</li>
</ul>
<ul>
<li><em><strong>product attributes.</strong></em> Possible attributes could include &#8220;color,&#8221; &#8220;size,&#8221; &#8220;rating,&#8221; &#8220;genre,&#8221; or &#8220;publisher.&#8221; Attributes can be used in place of, or in addition to, product variant groupings, as explained above.</li>
</ul>
<ul>
<li><em><strong>product images.</strong></em> The SKU&#8217;s product image(s).</li>
</ul>
<p>Not all vendors will be able to provide all of this data. The list above represents the most critical components, those that a retailer needs to sell the product to a consumer.</p>
