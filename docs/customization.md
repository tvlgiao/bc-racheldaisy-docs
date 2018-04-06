# Customization

This page will explain all configuration available and how to edit each section appear on theme. Let's view the first homepage.

![Homepage of Default Style](img/home1.jpg)







## Top Banner

![Top Banner](img/home1-top-banner.png)

The top banner can be showed / edited in admin page > __Marketing__ > __Banners__. When you add / edit remember to choose __Location__ is __Top of Page__.

### Colors Customization

To customize colors of this section, go to admin page > __Storefront Design__ > __My Themes__, click button __Customize__ of the current theme to open the Theme Editor. 

![Click customize theme](img/click-customize-theme.png)

Look into the options showing below:

![Theme editor top banner](img/theme-editor-top-banner.png)


## HotLine in Top Banner
![HotLine](img/hotline.png)

You can change the hotline text in this html file 

`..\templates\components\common\header.html`


![Edit hotline lang](img/hotline-lang.png)


## Links in Top Banner

![Links in top banner](img/top-link.png)

You can change the text links in this html file:

`..\templates\components\common\header-toplinks-right.html`

![Edit top links lang](img/top-link-lang.png)



## Header

### Header Styles
This theme support 3 different header styles:
- Logo at left
- Logo at right
- Logo at center

![Header Logo at left](img/home1-header-left.png)

![Header Logo at right](img/home1-header-right.png)

![Header Logo at center](img/home1-header-center.png)

To configure, open the __Theme Editor__, scroll down to section __Logo__, click to expand the logo options. Choose a certain option of __Logo position__, then click __Refresh__ button appear after.

![Change logo position](img/change-logo-position.png)


### Colors Customization

To customize colors of the header section, look into the options showing below in the Theme Editor:

![Theme editor header](img/theme-editor-header.png)



## Mega Menu

![Mega Menu](img/home1-megamenu.png)

Images or labels appear on the mega menu can be edited in the language file `en.json`:

![Edit language for mega menu](img/edit-language-megamenu.png)

For example if the current menu __Shop By__ has category ID = `23`.

- `"show_cat_image_23": "yes"`: specify an image will show on this menu.
- `cat_image_23`: is the image URL.

If you want to show a label beside a menu items like above image, for example the menu item __Season__ has category ID = `28`:

- `"show_item_label_28": "yes"`: specify a label will show beside this menu item.
- `"item_label_28"`: is the label text.

You can add more for other items as you want.

### Dropdown Mega Menu 1

![Dropdown mega menu 1](img/home1-megamenu1.jpg)

To display this mega menu when hover a category menu item, edit the language file `lang/en.json`, in section `emthemesmodez` > `megamenu`, you will see `"menu_cat_0": "2"`.

- `menu_cat_0` mean the first category item (start from 0).
- `2` is the identifier number of this dropdown menu.

For example if you want the third category item show this dropdown menu style, input `"menu_cat_2": "2"`.

To edit content inside this dropdown menu, you can edit template file `/templates/components/common/navigation-list-mega2.html`

Edit banner images on this dropdown menu here:

![Edit banner images of mega menu 2](img/edit-template-file-mega2-banners.png)



### Dropdown Mega Menu 2

![Dropdown mega menu 2](img/home1-megamenu2.jpg)

To display this mega menu when hover a category menu item, edit the language file `lang/en.json`, in section `emthemesmodez` > `megamenu`, you will see `"menu_cat_1": "3"`.

- `menu_cat_1` mean the second category item (start from 0).
- `3` is the identifier number of this dropdown menu.
- `mega_page_X`: mean the Xth page item (start from 0).

For example if you want the third category item show this dropdown menu style, input `"menu_cat_2": "3"`.

To edit content inside this dropdown menu, you can edit template file `/templates/components/common/navigation-list-mega3.html`

Edit banner images on this dropdown menu here:

![Edit banner images of mega menu 3](img/edit-template-file-mega3-banners.png)



### Dropdown Mega Menu 3

![Dropdown mega menu 3](img/home1-megamenu3.jpg)

To display this mega menu when hover a category menu item, edit the language file `lang/en.json`, in section `emthemesmodez` > `megamenu`, you will see `"menu_cat_2": "4"`.

- `menu_cat_2` mean the third category item (start from 0).
- `4` is the identifier number of this dropdown menu.
- `mega_page_X`: mean the Xth page item (start from 0).

For example if you want the third category item show this dropdown menu style, input `"menu_cat_2": "4"`.

To edit content inside this dropdown menu, you can edit template file `/templates/components/common/navigation-list-mega4.html`

Edit banner images and static text on this dropdown menu here:

![Edit banner images of mega menu 4](img/edit-template-file-mega4-banners.png)



### Dropdown Mega Menu 4

![Dropdown mega menu 4](img/home1-megamenu4.jpg)

To display this mega menu when hover a category menu item, edit the language file `lang/en.json`, in section `emthemesmodez` > `megamenu`, you will see `"menu_cat_3": "5"`.

- `menu_cat_3` mean the fourth category item (start from 0).
- `5` is the identifier number of this dropdown menu.
- `mega_page_X`: mean the Xth page item (start from 0).

For example if you want the third category item show this dropdown menu style, input `"menu_cat_2": "5"`.

To edit content inside this dropdown menu, you can edit template file `/templates/components/common/navigation-list-mega5.html`

Edit banner images on this dropdown menu here:

![Edit banner images of mega menu 5](img/edit-template-file-mega5-banners.png)

Replace the image URL `https://tvlgiao.github.io/bigcommerce-themes/parallaxbag/demo/images/banner-menu-jewelry{{@index}}.jpg` by your own but keep `{{@index}}` to be replaced by index numbers (start from `0`).



### Default Dropdown Mega Menu

![Dropdown mega menu](img/home1-megamenu-default.jpg)

To display the default style mega menu when hover a category menu item, edit the language file `lang/en.json`, in section `emthemesmodez` > `megamenu`, you will see `"menu_cat_4": " "`.

- `menu_cat_4` mean the fifth category item (start from 0). Leave a space character between the double quote to set default style dropdown menu.
- `mega_page_X`: mean the Xth page item (start from 0).

For example if you want the third category item show default style dropdown menu, input `"menu_cat_2": " "`.









## Main Slideshow / Carousel

### Edit the slideshow

Edit the slideshow in admin page > __Storefront Design__ > __Home Page Carousel__:

![Edit homepage carousel](img/edit-homepage-carousel.png)

### Change position of text content

The theme supports showing slideshow content like heading, text, button on __left__, __right__ or __center__ of the image. To configure this option, open Theme Editor, Look into section Carousel, click to expand:

![Edit position of each carousel slide](img/theme-editor-carousel-desc-position.png)

Choose position of each slide you want to change.

### Colors Customization

To customize color of the slideshow's elements, look into section __Carousel__ in the Theme Editor:

![Theme editor carousel](img/theme-editor-carousel.png)

### Hide the slideshow

To hide the slideshow on homepage, uncheck on the checkbox __Show Carousel__ in section __Carousel__ of the Theme Editor.








## Home - New Product Block

![Home New Product](img/home1-new-product.png)

You can configure number of products and product display type in __Theme Editor__ > __Homepage__:

![Theme editor configure products on homepage](img/theme-editor-products-on-homepage.png)





## Home - Text Block Slideshow

![Home Text Block Slideshow](img/home-policy.png)

To change the text of the block, you edit in this html file :

`..\templates\components\emthemes-modez\sections\section-policy.html`


To change the banners:

Step 1: You upload the banners in __Storefront__ > __Image Manager__  and copy its url.

![Upload Image Manager](img/home-upload-image.png)


Step 2: Paste the image's url in this html file:

`..\templates\components\emthemes-modez\sections\section-policy.html`

![Image Url](img/image-url.png)




## Home - Product Background Parallax

![Home Product Parallax](img/home-new-parallax.png)

__To change the background image:__

Step 1: You upload the background image in __Storefront__ > __Image Manager__ 
and copy its url.

![Upload Image Manager](img/home-upload-image.png)

Step 2: Paste the image's url in the language file `lang/en.json`, find key `newParallax` > `bg_img`:

![Edit language for new parallax](img/home-new-parallax-bg.png)



__To remove diamond effects:__

Step 1 : You find key `illustration` in this html file:

`..\templates\components\products\new.html`

Step 2 : Remove this below html and save the file to update.

![Home Diamond Effect](img/diamond-effect.png)



## Home - Featured Product Categories List

![Home Product Categories List](img/home-categories.png)

You can change title of categories list in the language file `lang/en.json`, find key `newCategories` > `heading`:

![Edit language for product categories list](img/home-new-categories.png)

You can configure number of products and product display type in __Theme Editor__ > __Homepage__:

![Theme editor configure products on homepage](img/theme-editor-products-on-homepage.png)



## Home - Fifth Banners Block

![Home Fifth Banners Block](img/home-fifth-banner.png)

To change the banners, 

Step 1: You upload the images in __Storefront__ > __Image Manager__ and copy its url

![Upload Image Manager](img/home-upload-image.png)

Step 2 : Paste the image's url in this html file:

`..\templates\components\emthemes-modez\sections\section-fifth-banners.html`

![Image url](img/home-fith-banner-url.png)



## Image Brands Carousel

![Image carousel](img/brand-slider.png)

Step 1: You upload the images in __Storefront__ > __Image Manager__ and copy its url

![Upload Image Manager](img/home-upload-image.png)

Step 2 : Paste the image's url in this html file:

`..\templates\components\emthemes-modez\brand\carousel.html`

![Image url](img/brand-url.png)




## Instagram Block

![Instagram](img/instagram.png)

Edit language file `lang/en.json` find key `instagram`:

![Edit language instagram](img/instagram-lang.png)





## Footer - Links

![footer links](img/footer-links.png)

Edit language file `lang/en.json` find key `footer` > `links`:

![edit language footer links](img/footer-links-lang.png)




## Footer - Social Icons

![Footer connect with us](img/footer-social.png)

In your admin page > __Storefront Design__ > __Design Options__ > __Social Media__, enter your social links:

![Edit social media icons](img/edit-social-media.png)




## Footer - Payment Icons

![Theme editor payment icons](img/footer-payment.png)

To show/hide payment icons, go to Theme __Editor__ > __Payment Icons__ secitons, check or uncheck any icons you want to show or hide.



## Credit Links

![Theme editor credit links](img/credit-link.png)

To show/hide the credit links, go to Theme Editor > __Footer__ section, tick or untick the checkboxes as showing above.



## Assign different product layout to a specific product page

Theme has 2 product layouts: __default__ and __Fullwith with Lightbox__.

Product layout fullwidth:

![Product layout fullwidth](img/product-layout-fullwidth.jpg)

To assign a product layout, edit your product in the admin panel. In tab __Order Details__, choose __Template Layout File__ with the layout out want:

![Assign product layout](img/assign-product-layout.png)





## Assign different category layout to a specific category page

Theme has 2 category layout: __default__ and __Fullwidth__.

Category layout fullwidth:

![Category layout fullwidth](img/category-layout-fullwidth.jpg)

To assign a category layout, edit your category in the admin panel. Choose __Template Layout File__ with the layout out want:

![Assign category layout](img/assign-category-layout.png)



## Show custom product labels

![Product labels](img/product-labels.jpg)

Turn on displaying product labels in the __Theme Editor__ > __Products__ section, tick on the checkbox __Show custom label using custom field 'card_label'__ and choose __Display Product Sale Badges__ as __Top Left__.

![Theme editor products options](img/theme-editor-products-show-options.png)

![Theme editor product sale badges](img/theme-editor-product-sale-badges.png)

Edit your product in the admin panel to add custom label:

![Edit product custom fields](img/edit-product-custom-fields.png)

Add a custom label named `card_label` and enter label text in the value input box.





## Show color swatches on product card:

![Color swatches on product card](img/product-card-color-swatches.png)

To display color watches on product card, open __Theme Editor__ > __Products__ section, tick on the checkbox __Show color swatches using custom field 'card_color'__.

![Theme editor products options](img/theme-editor-products-show-options.png)

Edit your product in the admin panel to add custom label:

![Edit product custom fields](img/edit-product-custom-fields.png)

Add a custom label named `card_color` and enter color hex code in the value input box seperator by commas.


## Show Size guide / Color guide on product attributes

![Size guide](img/size-guide.png)

To display size guide, color guide for any similar link beside product attribute, edit product and add custom fields like below:

![add custom fields for size guide](img/custom-fields-for-size-guide.png)

Create a web page for guide:

![size guide web page](img/size-guide-web-page.png)


## Show Fullscreen popup banner

![Fullscreen popup banner](img/home1-fullscreen-banner.jpg)

To show this fullscreen popup banner on homepage, Go to Marketing > Banners > Create a banner.

In Banner Content, click on button HTML button (Edit HTML source) and input content below:

```html
<div id="emthemesModezBannersBlockFullscreenBanner" class="emthemesModez-bannersContainer emthemesModez-bannersContainer--fullscreen tada animatecss" data-emthemesmodez-fullscreen-modal="" data-emthemesmodez-fullscreen-modal-delay="5000">
<div class="emthemesModez-banner">
<div class="emthemesModez-banner-figure"><a href="https://store-fcn1lgnyqp.mybigcommerce.com/shoes/"><img class="emthemesModez-banner-image" title="Fullscreen Banner" src="https://tvlgiao.github.io/bigcommerce-themes/parallaxbag/demo/images/banner19.jpg" alt="Fullscreen Banner" /></a>
<div class="emthemesModez-banner-figcaption">
<div class="emthemesModez-banner-figcaption-body">
<h4 class="emthemesModez-banner-figcaption-title">Bag Store</h4>
<div class="emthemesModez-banner-figcaption-text">UP TO <span class="alt" style="color: red;">50%</span> OFF</div>
<a class="button button--primary emthemesModez-banner-figcaption-button" href="https://store-fcn1lgnyqp.mybigcommerce.com/shoes/">Shop Now</a></div>
</div>
</div>
</div>
</div>
```

![Edit fullscreen popup banner](img/edit-fullscreen-popup-banner.jpg)

- Choose **Show on Page** = `Home Page`.
- Choose **Location** = `Bottom of Page`.
- Tick on **Visible** = `Yes`.


## Banner Sizes

### Homepage 1

![home1 banner sizes](img/home1-banner-sizes.png)

### Homepage 2

![home2 banner sizes](img/home2-banner-sizes.png)

### Homepage 3

![home3 banner sizes](img/home3-banner-sizes.png)




## Mix contents from other theme styles

For example, if you want to use theme __default__ style as the main theme, but also want to display other content blocks from __LaParis II__ style. You can edit the template files, rearrange, add more content blocks or delete unused content blocks.

Let open folder `templates` > `components` > `emthemes-modez` > `home` in the template files editor:

![Edit template file home default](img/edit-file-home-default.png)

There is 2 files in this folder:

- `default.html`: is used for __default__ style.
- `laparis2.html`: is used for __LaParis II__ style.

Let's take a look at contents of 2 files:

__default.html__

```plain
{{> components/emthemes-modez/sections/section section="banner_laparis1_1"}}
{{> components/emthemes-modez/sections/section section="new_products"}}
{{> components/emthemes-modez/sections/section section="categories_featured"}}
{{> components/emthemes-modez/sections/section section="popular_products"}}
{{> components/emthemes-modez/sections/section section="blog_recent"}}
{{> components/emthemes-modez/sections/section section="brands_carousel"}}
{{> components/emthemes-modez/sections/section section="instagram_grid"}}
```

__laparis2.html__

```plain
{{> components/emthemes-modez/sections/section section="products_by_category_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_2"}}
{{> components/emthemes-modez/sections/section section="carousel_laparis2_1"}}
{{> components/emthemes-modez/sections/section section="special_products_columns"}}
{{> components/emthemes-modez/sections/section section="brands_carousel"}}
{{> components/emthemes-modez/sections/section section="instagram_grid"}}
```

The files are showing very clearly how content blocks are displayed. See values in parameter `section="..."`:

- `banner_laparis1_1`: Is the first block content 3 banners in the homepage of default style.
- `new_products`: Is a block contains new products.
- `categories_featured`: Is a block contains featured products with categories list as appeared on the homepage of default style.
- `popular_products`: Is a block contains popular (or bestselling) products.
- `blog_recent`: Is a block contains recent blog posts.
- `brands_carousel`: Is a brand images carousel.
- `instagram_grid`: Is a block displaying instagram photos.
- `products_by_category_1` & `products_by_category_2`: Is a block contains product in a certain category as showing on homepage of LaParis II style.
- `carousel_laparis2_1`: Is the image carousel as showing on homepage of LaParis II style.
- `special_products_columns`: Is a block contains 3 columns showing new products, featured products and bestselling products as displayed on homepage of LaParis II style.

So just copy a line from the other file to the other. Arrange position of these sections as you wish.

Example of a mixed __default.html__:

```plain
{{> components/emthemes-modez/sections/section section="new_products"}}
{{> components/emthemes-modez/sections/section section="popular_products"}}
{{> components/emthemes-modez/sections/section section="banner_laparis1_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_1"}}
{{> components/emthemes-modez/sections/section section="products_by_category_2"}}
{{> components/emthemes-modez/sections/section section="instagram_grid"}}
{{> components/emthemes-modez/sections/section section="blog_recent"}}
{{> components/emthemes-modez/sections/section section="brands_carousel"}}
```

## Add our own CSS (Sass) code

To add your own custom CSS code you can edit the file `assets/scss/_theme-custom.scss_` in __Edit Theme Files__ editor:

![Edit file _theme-custom.scss](img/edit-file-theme-custom-css.png)

__Note: __

- Copy / backup this file for future theme upgrade.
- Add custom CSS code required CSS (or Sass) programming skill. It's not recommended for new users.
