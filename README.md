# Recommend-related-products
Recommend related products
To add the required code to your theme:

 
 
From your Shopify admin, go to Online Store > Themes.
Find the theme you want to edit, and then click Actions > Edit code.

In the Templates directory, click product.liquid.

Look for this line of Liquid code:

{% section 'product-template' %}
Create a new line below it, and then paste in the following code:

{% section 'related-products' %}
Click Save.

In the Sections directory, click Add a new section:

Create the section: a. Name your new section related-products. b. Click Create section. Your new file will open in the code editor. c. Delete all of the default code in the new section file so that the file is empty.

In this step, you will paste some code into your new related-products.liquid file. The code that you paste will depend on your theme:
