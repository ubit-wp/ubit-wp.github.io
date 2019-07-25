[Home](/) | [Demo](/demo/) | [Download](/download) | [Docs](/docs) | [Changelog](/changelog) | [Support](/support)

# Documentation

## Getting started

If you are new to WordPress or Elementor page builder, follow these links to learn more:

- [First Steps with WordPress](https://wordpress.org/support/article/first-steps-with-wordpress-b/)
- [FAQ New To WordPress](https://codex.wordpress.org/FAQ_New_To_WordPress)
- [Elementor Support](https://elementor.com/support/)

## System requirements

To use Ubit theme you need to have:

- PHP version 5.6.20 (or higher)
- MySQL version 5.0.15 (or higher)
- WordPress version 4.7 (or higher)

## How to install Ubit theme

To install the theme on your WordPress website, follow these steps:

1. Extract the zipped package which you have downloaded from ThemeForest website. In the extracted package you will find `ubit.zip` file which is WordPress theme.
2. Go to `Appearance > Themes > Add New > Upload Theme`.
3. Upload `ubit.zip` file.
4. Once the theme is uploaded click `Activate` button. If you do not see the button, then go to `Appearance > Themes` and click `Activate` button on Ubit theme.

Alternatively, you can extract `ubit.zip` file and upload the extracted folder to `/wp-content/themes/` folder on your server using FTP. Then go to `Appearance > Themes` and click `Activate` button on Ubit theme.

### Required plugins

> Skip to [How to import Ubit theme demo content](#how-to-import-ubit-theme-demo-content) section, if you prefer to use the setup wizard.

After installing the theme you must install the required plugins for a correct work of the theme.

If you prefer not to import the demo content, then you can use any plugin in the theme (see the plugins list below) as is or almost without any additional configuration (see [After importing Ubit theme demo content](#after-importing-ubit-theme-demo-content) section).

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
- [Envato Market](https://github.com/envato/wp-envato-market)

## How to import Ubit theme demo content

The theme provides a set of pre-built pages. Instead of starting a website design from scratch you can import the demo content with a few clicks and customize it in your own way.

By default, the theme uses Elementor page builder for the demo content. If you prefer you can use other page builders too, but in this case some of the demo content may not show correctly.

To import the demo content, follow these steps:

1. Go to `Appearance > Ubit Options`.
2. Click `Run the Setup Wizard` button.
3. Follow the setup wizard instructions.

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

## How to (FAQs)

### How to change Ubit theme appearance, customize options, etc.

A basic theme options are in `Appearance > Ubit Options`.

A general theme appearance options are in `Appearance > Customize`. There you will find many customization options of layout, top bar, 404 page, colors, buttons, typography (fonts), WooCommerce, etc.

- To set a favicon go to `Appearance > Customize > Site Identity`.
- To apply a custom CSS code go to `Appearance > Customize > Additional CSS`.

You can change home and other pages appearance in detail using Elementor page builder itself.

- To change a header and a footer go to `Appearance > Header Footer Builder` and edit them using Elementor page builder.

Shop and blog sidebars can be changed by going to `Appearance > Widgets`.

### How to get Ubit child theme

If you want to make advanced code changes to the theme, the best way to do it is using a child theme.

If you used the theme setup wizard, then you should already have a child theme installed and activated automatically.

### How to update Ubit theme

As suggested in [After importing Ubit theme demo content](#after-importing-ubit-theme-demo-content) section, you should already have a correctly setup Envato Market plugin which provides an automatic theme updates.

Once an automatic theme update is available, go to `Appearance > Themes` and click `Update Now` button on Ubit theme.

If you prefer not to use Envato Market plugin, then you should check for available updates manually on [ThemeForest website](https://themeforest.net/search/ubit).

To check which theme version you are using, go to `Appearance > Themes` and click on Ubit theme block.
