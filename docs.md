[Home](/) | [Demo](/demo/) | [Download](/download) | [Docs](/docs) | [Changelog](/changelog) | [Support](/support)

# Documentation

## Table of Contents

1. [Getting started](#getting-started)
	1. [Useful resources](#useful-resources)
	2. [System requirements](#system-requirements)
2. [How to install Ubit theme](#how-to-install-ubit-theme)
	1. [Download Ubit theme](#download-ubit-theme)
	2. [Install Ubit theme](#install-ubit-theme)
	3. [Required plugins](#required-plugins)
3. [How to import Ubit theme demo content](#how-to-import-ubit-theme-demo-content)
4. [After importing Ubit theme demo content](#after-importing-ubit-theme-demo-content)
5. [How to change Ubit theme appearance, customize options, etc.](#how-to-change-ubit-theme-appearance-customize-options-etc)
	1. [Customizer](#customizer)
6. [How to (FAQs)](#how-to-faqs)
	1. [How to get Ubit child theme](#how-to-get-ubit-child-theme)
	2. [How to update Ubit theme](#how-to-update-ubit-theme)
	3. [How to update bundled plugins](#how-to-update-bundled-plugins)

## Getting started

### Useful resources

If you are new to WordPress, WooCommerce or Elementor page builder, follow these links to learn more:

- [First Steps with WordPress](https://wordpress.org/support/article/first-steps-with-wordpress-b/)
- [FAQ New To WordPress](https://codex.wordpress.org/FAQ_New_To_WordPress)
- [WooCommerce Docs](https://docs.woocommerce.com/)
- [Elementor Support](https://elementor.com/support/)

### System requirements

To use Ubit theme you need to have:

- PHP version 5.6.20 (or higher)
- MySQL version 5.0.15 (or higher)
- WordPress version 4.7 (or higher)

## How to install Ubit theme

### Download Ubit theme

1. Visit [ThemeForest website](https://themeforest.net/), then go to `Downloads`
2. Download the `Installable WordPress file only` (`ubit.zip` file) as shown in the screenshot below.

![Download Ubit theme](/assets/images/docs/download-theme.jpg)

### Install Ubit theme

To install the theme on your WordPress website, follow these steps:

1. Login to your WordPress admin dashboard.
2. Go to `Appearance > Themes > Add New > Upload Theme`.
3. Upload `ubit.zip` file.
4. Once the theme is uploaded click `Activate` button. If you do not see the button, then go to `Appearance > Themes` and click `Activate` button on Ubit theme.

![Appearance - Themes](/assets/images/docs/appearance-themes.jpg)

![Appearance - Themes - Add New](/assets/images/docs/appearance-themes-add-new.jpg)

![Appearance - Themes - Add New - Upload Theme](/assets/images/docs/appearance-themes-add-new-upload-theme.jpg)

Alternatively, you can extract `ubit.zip` file and upload the extracted folder to `/wp-content/themes/` folder on your server using FTP. Then go to `Appearance > Themes` and click `Activate` button on Ubit theme.

Learn more: [How to install WordPress theme](https://envato.com/blog/install-themeforest-wordpress-theme/).

### Required plugins

> Skip to [How to import Ubit theme demo content](#how-to-import-ubit-theme-demo-content) section, if you prefer to use the setup wizard which will help you to install plugins automatically.

After installing the theme you must install the required plugins for a correct work of the theme. Recommended plugins are optional to install.

If you prefer not to import the demo content, then you can use any plugin (see the plugins list below) in the theme as is or almost without any additional configuration (see [After importing Ubit theme demo content](#after-importing-ubit-theme-demo-content) section).

The theme is using only a free and an open source plugins which are available on [WordPress.org plugins repository](https://wordpress.org/plugins/), with the only exception for [Envato Market plugin](https://envato.com/market-plugin/).

To install plugins manually go to `Plugins > Add New` and use search to find wanted plugins.

Also, do not forget to follow an official documentation of each plugin.

Required plugins:

- WooCommerce
- Elementor Page Builder

Recommended plugins (optional):

- Max Mega Menu
- Elementor - Header, Footer & Blocks
- Essential Addons for Elementor
- Variation Swatches for WooCommerce
- YITH WooCommerce Quick View
- YITH WooCommerce Wishlist
- Product Slider and Carousel with Category for WooCommerce
- WOOCS - WooCommerce Currency Switcher
- Smart Slider 3
- Mailchimp for WordPress
- Contact Form 7
- Custom Feeds for Instagram
- AddToAny Share Buttons
- Recent Posts Widget With Thumbnails
- [Envato Market](https://envato.com/market-plugin/)

## How to import Ubit theme demo content

The theme provides a set of pre-built pages. Instead of starting a website design from scratch you can import the demo content with a few clicks and customize it in your own way.

By default, the theme uses Elementor page builder for the demo content. If you prefer you can use other page builders too, but in this case some of the demo content may not show correctly.

To import the demo content, follow these steps:

1. Go to `Appearance > Ubit Options`.
2. Click `Run the Setup Wizard` button.
3. Follow the setup wizard instructions.
4. Follow [After importing Ubit theme demo content](#after-importing-ubit-theme-demo-content) section instructions.

## After importing Ubit theme demo content

A majority of a style configuration for the plugins used in the theme is already built-in, but currently the setup wizard cannot automatically setup some of functional configuration settings for them.

To fully setup the theme and finish plugins configuration, follow these steps:

1. To make sure that WordPress permalinks work correctly:
	1. Go to `Settings > Permalinks`.
	2. In `Common Settings` section select any URL structure but `Plain`.
	3. Click `Save Changes` button.
2. To setup WooCommerce:
	1. Find a notification suggesting to setup WooCommerce.
	2. Click `Run the Setup Wizard` button.
	3. Follow the setup wizard instructions.
3. To finish a setup of color variation attributes:
	1. Go to `Products > Attributes`.
	2. Move your mouse over a `color` attribute table row and click `Edit`.
	3. Change `Type` to `Color`.
	4. Click `Update` button.
4. To finish a setup of size variation attributes:
	1. Go to `Products > Attributes`.
	2. Move your mouse over a `size` attribute table row and click `Edit`.
	3. Change `Type` to `Label`.
	4. Click `Update` button.
5. To make sure that Contact Form 7 works correctly:
	1. Go to `Contact`.
	2. Check and update a configuration of each contact form (e.g. sender and receiver email addresses, etc.).
	3. Click `Save` button on each contact form if any changes were made.
6. To setup Instagram Feed:
	1. Go to `Instagram Feed`.
	2. Using your preferred connection method, connect to Instagram API.
	3. Click `Save Changes` button.
7. To finish a setup of Mailchimp for WordPress:
	1. Go to `Mailchimp for WP > Form`.
	2. Click `Save Changes` button.
8. To finish a setup of AddToAny Share Buttons:
	1. Go to `Settings > AddToAny`.
	2. Change icon style to `36` pixels.
	3. Change placement - untick checkboxes `Display at the bottom of posts on the front page` and `Display at the bottom of pages`.
	4. Click `Save Changes` button.
9. To get automatic theme updates:
	1. Go to `Envato Market`.
	2. Using your preferred connection method, Connect to Envato API.
10. To replace some URLs which are still pointing to Ubit theme demo website:
	1. Install and activate [Better Search Replace](https://wordpress.org/plugins/better-search-replace/) or [WP Migrate DB](https://wordpress.org/plugins/wp-migrate-db/) plugin.
	2. Using a preferred plugin, find and replace URLs which are still pointing to Ubit theme demo website. To find specific Ubit theme demo website URLs - use view source functionality in your browser while viewing a frontend of your website.

## How to change Ubit theme appearance, customize options, etc.

- A basic theme options are in `Appearance > Ubit Options`.
- To change a header and a footer go to `Appearance > Header Footer Builder` and edit them using Elementor page builder.
- Shop and blog sidebars can be changed by going to `Appearance > Widgets`.
- You can change home and other pages appearance in detail using Elementor page builder.

### Customizer

A general theme appearance options are in `Appearance > Customize`.

![Appearance - Customize](/assets/images/docs/appearance-customize.jpg)

There you will find many customization options of layout, top bar, 404 page, colors, buttons, typography (fonts), WooCommerce, etc.

- Site identity:
 	- Logo, site title, slogan and favicon.
- Layout:
	- Site container width and background.
	- Top bar style and left/center/right content.
	- Normal header layout options (if not using Elementor's header): style, menu visibility, various prebuilt actionable icons.
	- Page header style and breadcrumbs options.
	- Blog listing options: layout and style options, visible meta data.
	- Single blog post options: visible meta data.
	- Sidebar options: default visibility options per page/post type.
	- Footer layout options (if not using Elementor's footer): scroll-to-top, widget columns layout, colors, copyright text.
	- 404 page not found layout and style options: title, text, background image.
- Colors: brand, menu, heading, text and link colors.
- Buttons:
	- Normal and hover button colors.
	- Border radius (roundness).
- Typography:
	- Common body font style.
	- Primary menu font style (if not using Max Mega Menu).
	- Heading font style.
- WooCommerce:
	- Global store notice text.
	- Product catalog listing options.
	- Product thumbnail image options.
	- Checkout options: required fields, privacy and terms text options.
	- General product listing style: optionally shown add to cart button.
	- Show archive listing options: product columns amount, products per row, visible meta data.
	- Single product options: content color, gallery layout, optionally shown breadcrumbs, visible meta data.
- Menus:
	- Management of top, primary and footer menus.
	- Menu locations management: top, primary and footer menu locations.
	- Availability of menu locations depends on used header and footer solutions - Elementor based or basic theme layout.
- Widget areas management:
	- Blog and shop sidebars
	- Optionally shown footer column widgets.
- Homepage settings: setting of static homepage and blog posts page.
- Additional CSS: apply a custom CSS code.

## How to (FAQs)

### How to get Ubit child theme

If you want to make advanced code changes to the theme, the best way to do it is using a child theme.

If you used the theme setup wizard, then you should already have a child theme installed and activated automatically.

Learn more: [WordPress child themes](https://developer.wordpress.org/themes/advanced-topics/child-themes/).

### How to update Ubit theme

As suggested in [After importing Ubit theme demo content](#after-importing-ubit-theme-demo-content) section, you should already have a correctly setup [Envato Market plugin](https://envato.com/market-plugin/) which provides an automatic theme updates.

To check for any available updates go to `Dashboard > Updates`.

Once an automatic theme update is available go to `Appearance > Themes` and click `Update Now` button on Ubit theme.

If you prefer not to use Envato Market plugin, then you should check for available updates manually on [ThemeForest website](https://themeforest.net/search/ubit).

To check which theme version you are using go to `Appearance > Themes` and click on Ubit theme block.

### How to update bundled plugins

The theme is using only a free and an open source plugins which are available on [WordPress.org plugins repository](https://wordpress.org/plugins/), with the only exception for [Envato Market plugin](https://envato.com/market-plugin/).

To check for any available updates go to `Dashboard > Updates`.

Generally you will be informed on your WordPress admin dashboard about any available updates of bundled plugins.

For available updates of Envato Market plugin you should check them on [Envato Market plugin website](https://envato.com/market-plugin/) or [Envato Market plugin GitHub repository](https://github.com/envato/wp-envato-market/releases).
