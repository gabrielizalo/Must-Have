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
7. [Install a SEO plugin and Connect your site to Google Analytics and Search Console](#seo)
8. [Add social buttons](#social-media) (share and follow buttons).
9. Activate & customize [the CHILD theme of a FAST theme](https://kinsta.com/blog/fastest-wordpress-theme/) with
   [Elementor](https://elementor.com/) or [Beaver Builder](https://www.wpbeaverbuilder.com/) page Builders.
10. [Install a caching plugin](#performance)
11. Setup the other below plugins. **Only install and enable truly
    necessary plugins**.
12. Test the site: Check all posts and pages, if you have a contact form
    test if it properly works, try out the social buttons & all the other
    features you have on your site.
13. Setup a [Uptime Monitoring Service](https://www.freshworks.com/website-monitoring/).
14. Do you want to get info about conversions, ads...? Then:
    - [Add Goals and Track Events with Google Analytics](https://www.wpbeginner.com/wp-tutorials/how-to-add-google-analytics-event-tracking-in-wordpress/).
    - [Add Facebook Pixel](https://www.facebook.com/business/learn/facebook-ads-pixel).
    - [WordPress Conversion Tracking Made Simple: A Step-by-Step Guide](https://www.wpbeginner.com/beginners-guide/wordpress-conversion-tracking-made-simple-a-step-by-step-guide/).
15. Does company need a CRM? Then:
    - [14 WordPress CRM Plugins to Supercharge Your Business in 2020](https://kinsta.com/blog/wordpress-crm/).
16. Do you want the latest Wordpress/Google feature? Then:
    - [Get Ready to Tell Stories on WordPress](https://google.github.io/web-stories-wp/beta/).




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


* [**ManageWP Worker**](https://wordpress.org/plugins/worker/):
  If you have several Wordpress sites, use ManageWP, a dashboard that
  helps you save time and nerves by automating your workflow.


* [**Polilang**](https://wordpress.org/plugins/polylang/): Polylang
  allows you to create a bilingual or multilingual WordPress site.


* [**Virtual Robots.txt**](https://wordpress.org/plugins/pc-robotstxt/):
  Virtual Robots.txt is an easy (i.e. automated) solution to creating
  and managing a robots.txt file for your site. Instead of mucking about
  with FTP, files, permissions.. etc, just upload and activate the plugin
  and you’re done. Use this robots.txt for best results:
  [robots.txt](robots.txt) **and remember update Sitemaps at the final
  of the file**.


* [**Yoast Duplicate Post**](https://wordpress.org/plugins/duplicate-post/):
  This plugin allows users to clone posts of any type, or copy them to
  new drafts for further editing.



### Social Media

* [**Easy Social Share Buttons for WordPress**](https://socialsharingplugin.com):
  Easy Social Share Buttons for WordPress is the best social sharing
  plugin on the market, and the most complete and optimized social share
  buttons package. With a single plugin, the whole world of social media
  sharing is opened up to you: increase your shares, grow your profile,
  build your following, get new subscribers and drive more traffic.



### SEO

* [**Rank Math**](https://rankmath.com/):
  The new kid of the block. Use it or the Alternative **Yoast SEO**.
  [How To Migrate To Rank Math](https://www.matthewwoodward.co.uk/seo/reviews/rank-math/).
  - Config:
    1. Create and config **Google Analytics** account.
    2. Create and config **Search Console** account.
    3. Setup all Rank Math Settings.
    4. General Settings > Analytics:
       - Search Console
       - Analytics > Install analytics code
       - Email Reports > Activate
    5. In Google Analytics create monthly emails reports too:
       Info: [How to Set Up Recurring Google Analytics Email Reports](https://www.cdgi.com/2019/05/google-analytics-email-reports/)



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
  - [The Ideal WP Rocket Settings With Cloudflare + MaxCDN Instructions](https://onlinemediamasters.com/wp-rocket-settings/).
  - [How to Properly Install and Setup WP Rocket in WordPress](https://www.wpbeginner.com/plugins/how-to-properly-install-and-setup-wp-rocket-in-wordpress/).

  Alternatives:
  [_WP Super Cache_](https://wordpress.org/plugins/wp-super-cache/) (easier to set up)
  or
  [_W3 Total Cache_](https://wordpress.org/plugins/w3-total-cache/) (more options but it’s harder to configure).


## CDN


* [**Use KeyCDN**](http://bit.ly/AX-CDN) or [**RocketCDN**](https://go.wp-rocket.me/rocket-cdn)

    * Enable [HTTP/2](https://www.keycdn.com/support/http2/).
    * Enable [Prefetching](https://www.keycdn.com/support/prefetching/).
