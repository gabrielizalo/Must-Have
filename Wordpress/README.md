# Wordpress Must Have

Inspired by:
1. [**Launching a New Wordpress Site - Part 1**](http://www.hongkiat.com/blog/launching-new-wordpress-site-part-1/)
2. [**Launching a New Wordpress Site - Part 2**](http://www.hongkiat.com/blog/launching-new-wordpress-site-part-2/)


## Setup - Off-site Tasks

1. [Register a domain](http://bit.ly/AX-Dominios)
2. [Buy a hosting plan](http://bit.ly/AX-SuperHosting)
3. Install WordPress.
4. Configure an SSL certificate by Default in CPanel.
5. Create email accounts (1 from gmail + N from own domain).
6. Register your site with [Google Search Console](https://search.google.com/search-console/about)
   and remember add *Sitemap* after **Yoast SEO** configuration.
7. Set up a [Google Analytics](https://analytics.google.com/) account
8. Plan a reliable backup workflow (via CPanel or Plugin).
9. Set latest _PHP_ version in CPanel.


## Setup - Preparation

1. Domain Name
2. Slogan
3. Description of the company
4. Address
5. Whatsapp number
6. Company services categories (main and others)
7. Company Logo Horizontal
8. Company LogoSymbol 600 x 600 (for FavIcon)
9. Banner 600x60 (for WPSSO Google)
10. Banner 1200x630 (for WPSSO Facebook)


## Setup - On-site Tasks

1. Configure an SSL Url by Default in Wordpress > Admin > Settings >
   General >  WordPress Address (URL) & Site Address (URL)
2. [Install a security plugin](#security)
3. Create your content: _Pages_ > _Add New_ > Create basic pages: home,
   contact...
4. Configure your settings, setup main menu and update: _Settings_ >
   _Writing_ > _Update Services_ > Copy & Paste the Ping Services from
   [WordpressPingList.md](PingList.md).
5. Configure your settings, permalinks: _Settings_ >
   _Permalinks_:
   - Common Settings > Custom Structure: `/blog/%year%/%monthnum%/%postname%/`
   - Optional:
     - Category Base: `/shop/categories`
     - Tag Base: `/shop/tags`
   - Product permalinks `/shop/`
6. Create users
7. [Install a SEO plugin](#seo)
8. [Add social buttons](#social-media) (share and follow buttons).
9. Activate & customize [a theme](https://themeforest.net/category/wordpress)
   although [Elementor](https://elementor.com/) or
   [Beaver Builder](https://www.wpbeaverbuilder.com/) page Builders are
   my recommended.
10. [Connect your site to Google Analytics](#analytics).
11. [Install a caching plugin](#performance)
12. Setup the other below plugins. **Only install and enable truly
    necessary plugins**.
13. Test the site: Check all posts and pages, if you have a contact form
    test if it properly works, try out the social buttons & all the other
    features you have on your site.
14. Setup a [Uptime Monitoring Service](https://www.freshworks.com/website-monitoring/).
15. Do you want to get info about conversions, ads...? Then:
    - [Add Goals and Track Events with Google Analytics](https://www.wpbeginner.com/wp-tutorials/how-to-add-google-analytics-event-tracking-in-wordpress/).
    - [Add Facebook Pixel](https://www.facebook.com/business/learn/facebook-ads-pixel).
    - [WordPress Conversion Tracking Made Simple: A Step-by-Step Guide](https://www.wpbeginner.com/beginners-guide/wordpress-conversion-tracking-made-simple-a-step-by-step-guide/).




## Plugins


### General Purpose

* [**Coming Soon Page & Maintenance Mode by SeedProd**](https://wordpress.org/plugins/coming-soon/)
  (_Enable only when you need to use it_): Create a simple Coming Soon
  Page or Maintenance Mode Page. Work on your site in private while
  visitors see a “Coming Soon” or “Maintenance Mode” page.


* [**Contact Form by WPForms**](https://wordpress.org/plugins/wpforms-lite/):
  Drag & drop WordPress form builder that’s EASY and POWERFUL. WPForms
  allow you to create beautiful contact forms, subscription forms,
  payment forms, and other type of forms for your site in minutes, not
  hours!


* [**Favicon by RealFaviconGenerator**](http://realfavicongenerator.net/extensions/wordpress/):
  Favicon by RealFaviconGenerator is a WordPress plugin to create and
  install your favicon in a few seconds.


* [**Imagify Image Optimizer**](https://wordpress.org/plugins/imagify/):
  Dramatically reduce image file sizes without losing quality, make your
  website load faster, boost your SEO and save money on your bandwidth
  (From Us 5 per Month).

  Alternative: [_Smush Image Compression and Optimization_](https://wordpress.org/plugins/wp-smushit/).


* [**Loco Translate**](https://wordpress.org/plugins/loco-translate/):
  Loco Translate provides in-browser editing of WordPress translation
  files.


* [**Polilang**](https://wordpress.org/plugins/polylang/): Polylang
  allows you to create a bilingual or multilingual WordPress site.


* [**Virtual Robots.txt**](https://wordpress.org/plugins/pc-robotstxt/):
  Virtual Robots.txt is an easy (i.e. automated) solution to creating
  and managing a robots.txt file for your site. Instead of mucking about
  with FTP, files, permissions.. etc, just upload and activate the plugin
  and you’re done. Use this robots.txt for best results:
  [robots.txt](robots.txt) **and remember update Sitemaps at the final
  of the file**.



### Analytics

#### For ecommerce

* [**Enhanced Ecommerce Google Analytics Plugin for WooCommerce**](https://www.tatvic.com/tatvic-labs/woocommerce-extension/):
  Google Analytics WooCommerce plugin allows you to use the newly
  launched feature of Universal Analytics – Enhanced Ecommerce.

    * [Google Analytics Plugin for WooCommerce](https://wordpress.org/plugins/enhanced-e-commerce-for-woocommerce-store/) (Free)
    * [Google Analytics Plugin for WooCommerce Pro](https://codecanyon.net/item/actionable-google-analytics-for-woocommerce/9899552) (Us 135)


#### For blogs and ecommerce sites

* [**Monster Insights**](https://www.monsterinsights.com/): Number 1
  Google Analytics Plugin for WordPress that’s Easy and Powerful.

    * [Monster Insights](https://wordpress.org/plugins/google-analytics-for-wordpress/) (Free but not useful for ecommerce)
    * [Monster Insights Pro](https://www.monsterinsights.com/pricing/) (Us 200/Year)


### Social Media

* [**Easy Social Share Buttons for WordPress**](https://socialsharingplugin.com):
  Easy Social Share Buttons for WordPress is the best social sharing
  plugin on the market, and the most complete and optimized social share
  buttons package. With a single plugin, the whole world of social media
  sharing is opened up to you: increase your shares, grow your profile,
  build your following, get new subscribers and drive more traffic.



### SEO

* [**WPSSO**](https://wpsso.com):
  **WPSSO uses your *existing* content to generate meta tags and Schema
  markup** --- there's no need to manually enter / configure any
  additional settings or values, *but if you want to* , you can
  customize just about anything and everything.
    * [WPSSO Core Plugin](https://wordpress.org/plugins/wpsso/) (Free)
    * [WPSSO Core Plugin Pro](http://wpsso.com/extend/plugins/wpsso/) (Us 49)
    * [WPSSO Schema JSON-LD Markup ](https://wordpress.org/plugins/wpsso-schema-json-ld/) (Free Addon)
    * [WPSSO Schema JSON-LD Markup Pro](https://wpsso.com/extend/plugins/wpsso-schema-json-ld/) (Us 29)
    * [Performance Tuning](https://wpsso.com/docs/plugins/wpsso/installation/performance-tuning/)


* [**Yoast SEO**](https://wordpress.org/plugins/wordpress-seo/):
  This plugin is written from the ground up by Joost de Valk and his
  team at [Yoast](https://yoast.com/) to improve your site's SEO on
  *all* needed aspects. While this
  [Yoast SEO plugin](https://yoast.com/wordpress/plugins/seo/) goes the
  extra mile to take care of all the technical optimization.
  [How to Install and Setup WordPress SEO Plugin by
  Yoast](http://www.wpbeginner.com/plugins/how-to-install-and-setup-wordpress-seo-plugin-by-yoast/).



### Security

* [**SecuPress**](https://secupress.me):
  Protect your WordPress with malware scans; block bots & suspicious IPs.
  Get a complete WordPress security toolkit for free or as a pro plugin.
    * [SecuPress Free](https://wordpress.org/plugins/secupress/) (Free)
    * [SecuPress Pro](https://secupress.me/) (Us 59 per Year)

   Other alternatives can be found in: [8 Best WordPress Security Plugins to Lock Down Your Site](https://elementor.com/blog/wordpress-security-plugins/).


### Performance

* [**instant.page**](https://instant.page/):
  Make your site’s pages instant in 1 minute and improve your conversion rate by 1%.
  Add this `Snippet` to wordpress using [Code Snippets](https://wordpress.org/plugins/code-snippets/) plugin.
  ```
  add_action( 'wp_footer', function () { ?>
  	HERE INSTA.PAGE CODE
  <?php } );
  ```

* [**SG Optimizer/SuperCacher SiteGround**](https://wordpress.org/plugins/sg-cachepress/):
  This plugin is designed to link WordPress with the [**SiteGround**](http://bit.ly/AX-SuperHosting )
  Performance services. **It WILL NOT WORK on another hosting provider**.

  _Important:_ Verify that it is working via CPanel and if you use _WP  
  Rocket_, disable _Home Optimization_ (HTML, JS & CSS).


* [**WP Rocket**](https://wp-rocket.me/):
  Make WordPress Load Fast in a Few Clicks. Recognized as the most
  powerful caching plugin by WordPress experts (Us 39 per Year).
  [The Ideal WP Rocket Settings With Cloudflare + MaxCDN Instructions](https://onlinemediamasters.com/wp-rocket-settings/).

    Alternatives:
    [_WP Super Cache_](https://wordpress.org/plugins/wp-super-cache/)
    (easier to set up)
    or
    [_W3 Total Cache_](hhttps://wordpress.org/plugins/w3-total-cache/)
    (more options but it’s harder to configure).


## CDN


* [**Use KeyCDN**](http://bit.ly/AX-CDN) or [**RocketCDN**](https://go.wp-rocket.me/rocket-cdn)

    * Enable [HTTP/2](https://www.keycdn.com/support/http2/).
    * Enable [Prefetching](https://www.keycdn.com/support/prefetching/).
