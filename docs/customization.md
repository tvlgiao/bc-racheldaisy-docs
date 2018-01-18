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

Edit the slideshow in admin page > __Storefront Design__ > __Design Options__:

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








## What's Special Banners

![What's special banners](img/home1-what-special.jpg)

You can edit heading text, sub heading, images, links, text on images in the language file `lang/en.json` in the File Editor, find section `parallaxbag` > `what_special`:

![Edit language file for what special banners](img/edit-language-what-special.png)

To remove the brush image, you can add this custom code in **Storefront** > **Footer Script**:

```html
<style>
.parallabag-whatSpecialSection {
    background: none;
}
</style>
```








## Keep In Touch (Newsletter)

![Keep in touch section](img/home1-keep-in-touch.png)

Make sure you tick on the option "__Allow Newsletter Subscription__" in admin page > __Marketing__ > __Email Marketing__:

![Enable newsletter subscription](img/enable-newsletter-subscription.png)

Edit text and description in the language file `lang/en.json`. Find key `newsletter`:

![Edit language for newsletter text](img/edit-language-newsletter.png)




## Some Features Block

![Some Features Block](img/home1-some-features.jpg)

You can edit background image, text, buttons, links in this block in the language file `lang/en.json`, find key `parallaxbag` > `some_features`:

![Edit language for some features block](img/edit-language-some-features.png)







## Special Products Tabs

![Special products tabs](img/home1-special-products-tabs.jpg)

You can configure number of products and product display type in __Theme Editor__ > __Homepage__:

![Theme editor configure products on homepage](img/theme-editor-products-on-homepage.png)

Configure colors:

![Configure special products tabs](img/theme-editor-special-products-tabs.png)





## Free Shipping & Return Block

![Free shipping and return block](img/home1-free-shipping-return.png)

You can edit text of this block in the language file `lang/en.json`, find key `parallaxbag` > `free_shipping_return`:

![Edit language for free shipping return](img/edit-language-free-shipping-return.png)

To remove the yellow background image, you can add this custom code in Storefront > Footer Script:

```html
<style>
.emthemesModez-section--parallaxbag-freeShippingReturn {
    background-image: none;
}
</style>
```

Or if you want to replace your your own image, upload your image in Image Manager and copy its URL.

Edit the background code to: `background-image: url('/path/to/your/image');`




## Popular Categories

![Popular categories block](img/home1-popular-categories.jpg)

You can edit title, category images, specify category ID to display category in the language file `lang/en.json`. Find key `parallaxbag` > `popular_categories`:

![Edit language file for popular categories section](img/edit-language-popular-categories.png)

You can find the category ID by editing the category, look at the URL on your web browser, the number is category ID:

![Find category id](img/find-category-id.png)

Note: this block only works for the root categories.





## Promotion Video Block

![Promotion video block](img/home1-promotion-video.jpg)

You can edit heading, sub-heading, background image and video in the language file `lang/en.json`. Find key `parallaxbag` > `video`:

![Edit language for promotion video](img/edit-language-promotion-video.png)





## 6 Banners Block

![6 banners block](img/home1-six-banners.jpg)

You can edit these banners in the language file `lang/en.json`. Find key `parallaxbag` > `six_banners`:

![Edit language for six banners block](img/edit-language-six-banners.png)





## Testimonials Slider

![Testimonials Slider](img/home1-testimonials.png)

You can edit testimonials in the language file `lang/en.json`. Find key `parallaxbag` > `testimonials`:

![Edit language testimonials](img/edit-language-testimonials.png)




## Image Carousel

![Image carousel](img/home1-image-carousel.png)

To edit image and links in this image carousel section, edit the language file, find key `emthemesmodez` > `image_carousel`

![Edit language image carousel](img/edit-language-brands-carousel.png)

- `image*`: is link to the image.
- `title*`: is image text description.
- `url*`: is image link. Leave a single space letter in the value if you want to hide any image.




## Footer - 3 Banners

![Footer 3 banners](img/home1-footer-3-banners.png)

You can edit content of 3 banners in the language file `lang/en.json`. Find key `parallaxbag` > `footer_three_banners`:

![Edit language for footer 3 banners](img/edit-language-footer-3-banners.png)




## Footer - Customer Services Links

![footer customer services](img/home1-footer-customer-services.png)

Edit language file `lang/en.json` find key `footer` > `links`:

![Edit language footer customer services](img/edit-language-footer-customer-services.png)





## Footer - Delivery & Returns

![footer delivery & returns](img/home1-footer-delivery-returns.png)

Edit language file `lang/en.json` find key `footer` > `links`:

![edit language footer delivery & returns](img/edit-language-footer-delivery-returns.png)





## Footer - About Us

![Footer about us](img/home1-footer-about-us.png)

Edit language file `lang/en.json` find key `footer` > `about` & `about_text`:

![Edit language footer about us](img/edit-language-footer-about-us.png)



## Footer - Contact Us

![Footer contact us](img/home1-footer-contact-us.png)

In your admin page > __Store Setup__ > __Store Profile__, edit __Store Address__ and __Phone__:

![Edit store address & phone](img/edit-store-address-phone.png)

For email, edit the language file `lang/en.json`, find key `footer` > `email`:

![Edit email in the language file](img/edit-language-footer-email.png)





## Footer - Connect With Us

![Footer connect with us](img/home1-footer-connect-with-us.png)

In your admin page > __Storefront Design__ > __Design Options__ > __Social Media__, enter your social links:

![Edit social media icons](img/edit-social-media.png)




## Payment Icons

![Theme editor payment icons](img/theme-editor-payment-icons.png)

To show/hide payment icons, go to Theme __Editor__ > __Payment Icons__ secitons, check or uncheck any icons you want to show or hide.



## Credit Links

![Theme editor credit links](img/theme-editor-credits.png)

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
