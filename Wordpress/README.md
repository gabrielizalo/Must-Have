# Wordpress Must Have

## Setup - Off-site Tasks

Taken from:
[**Launching a New Wordpress Site - Part 1**](http://www.hongkiat.com/blog/launching-new-wordpress-site-part-1/)

1. [Register a domain](http://bit.ly/AX-Dominios)
2. [Buy a hosting plan](http://bit.ly/AX-SuperHosting)
3. Install WordPress.
4. Install an SSL certificate.
5. Create email accounts (1 from gmail + N from own domain).
6. Set up an FTP connection
7. Register your site with search engines including the 4 versions: http://www.yoursite.com, http://yoursite.com, https://www.yoursite.com, https://yoursite.com. Add all of them as separate properties, finally set your preferred version according [to these instructions](https://support.google.com/webmasters/answer/44231?hl=en). If you use an SSL certificate select one of the HTTPS URLs.
   a. [Google Webmaster Tools](https://www.google.com/webmasters/)
   b. [Bing Webmaster Tools](https://www.bing.com/toolbox/webmaster)
8. Set up a Google Analytics account
9. Plan a reliable backup workflow (via CPanel or Plugin).
10. Set _PHP 7_ in CPanel.



## Setup - On-site Tasks

Taken from:
[**Launching a New Wordpress Site - Part 2**](http://www.hongkiat.com/blog/launching-new-wordpress-site-part-2/)

1. [Install a security plugin](#security)
2. Create your content: _Pages_ > _Add New_ > Create basic pages: home, contact...
3. Configure your settings, setup main menu and update: _Settings_ > _Writing_ > _Update Services_ > Copy & Paste the Ping Services from [WordpressPingList.md](PingList.md).
4. Create users
5. [Install a SEO plugin](#seo)
6. [Add social buttons](#social-media) (share and follow buttons).
7. Activate & customize [a theme](http://bit.ly/AX-Envato) that uses the _WPBakery Page Builder_.
8. [Connect your site to Google Analytics](#general-purpose).
9. [Install a caching plugin](#performance)
10. Setup the other below plugins. **Only install and enable truly necessary plugins**.
11. Test the site: Check all posts and pages, if you have a contact form test if it properly works, try out the social buttons & all the other features you have on your site.
12. Setup a [Uptime Monitoring Service](https://www.statuscake.com).




## Plugins


### General Purpose

* [**Coming Soon Page & Maintenance Mode by SeedProd**](https://wordpress.org/plugins/coming-soon/)
  (_Enable only when you need to use it_): Create a simple Coming Soon Page or Maintenance Mode Page. Work on your site in private while visitors see a “Coming Soon” or “Maintenance Mode” page.


* [**Contact Form by WPForms**](https://wordpress.org/plugins/wpforms-lite/):
  Drag & drop WordPress form builder that’s EASY and POWERFUL. WPForms allow you to create beautiful contact forms, subscription forms, payment forms, and other type of forms for your site in minutes, not hours!


* [**Favicon by RealFaviconGenerator**](http://realfavicongenerator.net/extensions/wordpress/):
  Favicon by RealFaviconGenerator is a WordPress plugin to create and install your favicon in a few seconds.


* [**GA Google Analytics**](https://wordpress.org/plugins/ga-google-analytics/):
  This plugin enables Google Analytics for your entire WordPress site. Lightweight and fast with plenty of great features.


* [**Smush Image Compression and Optimization**](https://wordpress.org/plugins/wp-smushit/):
  Compress and optimize (or optimise) image files, improve performance and boost your SEO rank using Smush WordPress image compression and optimization..

    Alternative:
    [_Imagify Image Optimizer_](https://wordpress.org/plugins/imagify/) (Commercial: From Us 5 per Month).


* [**Loco Translate**](https://wordpress.org/plugins/loco-translate/):
  Loco Translate provides in-browser editing of WordPress translation files.


* [**Polilang**](https://wordpress.org/plugins/polylang/): Polylang
  allows you to create a bilingual or multilingual WordPress site.


* [**Virtual Robots.txt**](https://wordpress.org/plugins/pc-robotstxt/): Virtual Robots.txt is an easy (i.e. automated) solution to creating and managing a robots.txt file for your site. Instead of mucking about with FTP, files, permissions ..etc, just upload and activate the plugin and you’re done. Use this robots.txt for best results: [robots.txt](robots.txt).


* [**WP Bakery Page Builder**](https://wpbakery.com/) formerly _Visual Composer_:
  Choose a theme that use it. It's the # 1 WordPress Page Builder Plugin. Build any layout you can imagine with intuitive drag and drop builder – no programming knowledge required.



### Social Media

* [**Easy Social Share Buttons for WordPress**](https://socialsharingplugin.com):
  Easy Social Share Buttons for WordPress is the best social sharing plugin on the market, and the most complete and optimized social share buttons package. With a single plugin, the whole world of social media sharing is opened up to you: increase your shares, grow your profile, build your following, get new subscribers and drive more traffic.



### SEO

* [**WPSSO**](https://wpsso.com):
  **WPSSO uses your *existing* content to generate meta tags and Schema markup** --- there's no need to manually enter / configure any additional settings or values, *but if you want to* , you can customize just about anything and everything.
    * [WPSSO Core Plugin](https://wordpress.org/plugins/wpsso/) (Free)
    * [WPSSO Core Plugin Pro](http://wpsso.com/extend/plugins/wpsso/) (Us 49)
    * [WPSSO Schema JSON-LD Markup ](https://wordpress.org/plugins/wpsso-schema-json-ld/) (Free Addon)
    * [WPSSO Schema JSON-LD Markup Pro](https://wpsso.com/extend/plugins/wpsso-schema-json-ld/) (Us 29)
    * [Performance Tuning](https://wpsso.com/docs/plugins/wpsso/installation/performance-tuning/)


* [**Yoast SEO**](https://wordpress.org/plugins/wordpress-seo/):
  This plugin is written from the ground up by Joost de Valk and his team at [Yoast](https://yoast.com/) to improve your site's SEO on *all* needed aspects. While this [Yoast SEO plugin](https://yoast.com/wordpress/plugins/seo/) goes the extra mile to take care of all the technical optimization.
  [How to Install and Setup WordPress SEO Plugin by Yoast](http://www.wpbeginner.com/plugins/how-to-install-and-setup-wordpress-seo-plugin-by-yoast/).



### Security

* [**SecuPress**](https://secupress.me):
  Protect your WordPress with malware scans; block bots & suspicious IPs. Get a complete WordPress security toolkit for free or as a pro plugin.
    * [SecuPress Free](https://wordpress.org/plugins/secupress/) (Free)
    * [SecuPress Pro](https://secupress.me/) (Us 59 per Year)



### Performance

* [**SG Optimizer/SuperCacher SiteGround**](https://wordpress.org/plugins/sg-cachepress/):
  This plugin is designed to link WordPress with the [**SiteGround**](http://bit.ly/AX-SuperHosting ) Performance services. **It WILL NOT WORK on another hosting provider**. _Important:_ Verify that is working via CPanel and plugin config.


* [**WP Disable**](https://wordpress.org/plugins/wp-disable/):
  Reduce HTTP requests – Disable Emojis, Disable Gravatars, Disable Embeds and Remove Querystrings. SpeedUp WooCommerce, Added support to disable pingbacks, disable trackbacks, close comments after 28 days, Added the ability to force pagingation after 20 posts, Disable WooCommerce scripts and CSS on non WooCommerce Pages, Disable RSS, Disable XML-RPC, Disable Autosave, Remove Windows Live Writer tag, Remove Shortlink Tag, Remove WP API from header and many more features to help speed and SEO gains. Now includes Disable Comments, Heartbeat Control, Selective Disable.


* [**WP Rocket**](https://wp-rocket.me/):
  Make WordPress Load Fast in a Few Clicks. Recognized as the most powerful caching plugin by WordPress experts (Us 39 per Year). [The Ideal WP Rocket Settings With Cloudflare + MaxCDN Instructions](http://www.onlinemediamasters.com/wp-rocket-settings-with-cloudflare-maxcdn/).

    Alternatives:
    [_WP Super Cache_](https://wordpress.org/plugins/wp-super-cache/) (easier to set up)
    or
    [_W3 Total Cache_](hhttps://wordpress.org/plugins/w3-total-cache/) (more options but it’s harder to configure).


## Other


* [**Use KeyCDN**](http://bit.ly/AX-CDN)

    * Enable [HTTP/2](https://www.keycdn.com/support/http2/).
    * Enable [Prefetching](https://www.keycdn.com/support/prefetching/).
