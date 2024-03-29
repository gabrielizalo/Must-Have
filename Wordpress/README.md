# WordPress Must Have

Inspired by:
1. [**Launching a New WordPress Site — Part 1**](http://www.hongkiat.com/blog/launching-new-wordpress-site-part-1/)
2. [**Launching a New WordPress Site — Part 2**](http://www.hongkiat.com/blog/launching-new-wordpress-site-part-2/)


## Setup — Preparation

1. Domain Name
2. Slogan
3. Description of the company
4. Address
5. Whatsapp number
6. Company services categories (main and others)
7. Company Logo Horizontal
8. Company LogoSymbol 600px × 600px (for FavIcon and RankMath SEO)
9. Banner 1200px × 630px (for RankMath OpenGraph Thumbnail)
10. Brand colors (4): **Primary**, **Secondary**, for **Text** and **Accent** to highlight


## Setup — Off-site Tasks

1. [Register a domain](http://bit.ly/AX-Dominios)
2. [Buy a hosting plan](http://bit.ly/AX-SuperHosting)
3. Install WordPress.
4. Configure an SSL certificate by Default in CPanel.
5. Create email accounts (1 from gmail + N from own domain).
6. Register your site with [Google Search Console](https://search.google.com/search-console/about) and remember add
   **Sitemap** _(If using Rank Math it will config automatically)_.
7. Set up a [Google Analytics](https://analytics.google.com/) account _(If using RankMath it will config automatically)_.
8. Plan a reliable backup workflow (via CPanel or Plugin).
9. Set latest _PHP_ version in CPanel. With SiteGround use [Ultafast PHP](https://www.siteground.com/kb/ultrafast-php-enable/).
10. Update PHP variables to:
      ```
      upload_max_filesize = 128M
      post_max_size = 128M
      max_execution_time = 300
      memory_limit = 256M
      max_input_vars = 2000  
      ```


## Setup - On-site Tasks

1. Configure SSL by Default in WordPress > Admin > Settings > General > WordPress Address (URL) & Site Address (URL)
2. [Install a security plugin](#security)
3. Create your content: _Pages_ > _Add New_ > Create basic pages: home, contact…
4. Configure your settings:
   - Setup main menu.
   - Update: _Settings_ > _Writing_ > _Update Services_ > Copy & Paste the Ping Services from [WordpressPingList.md](PingList.md).
5. Configure permalinks: _Settings_ > _Permalinks_:
   - Common Settings > Custom Structure: `/blog/%year%/%monthnum%/%postname%/`
   - Optional:
     - Category Base: `/shop/categories`
     - Tag Base: `/shop/tags`
   - Product permalinks `/shop/`
6. Create WordPress users
7. [Install SEO plugin and Connect your site to Google Analytics and Search Console](#seo)
8. [Add social buttons](#social-media) (share and follow buttons).
9. Activate & customize [the CHILD theme of a FAST theme](https://kinsta.com/blog/fastest-wordpress-theme/) with
   [Elementor](https://elementor.com/) page Builder.
10. [Install a caching plugin](#performance)
11. Setup General Purpose plugins _(Only install and enable truly necessary plugins)_.
12. Test the site: Check all posts and pages, if you have a contact form test if it properly works, try the social
    buttons & all the other features you have on your site.
13. Setup a Uptime Monitoring Service: Use the Free [Freshping by Freshworks](https://www.freshworks.com/website-monitoring/).
14. Does the business have an office? Then:
    - [Add it to Google Maps](https://maps.google.com/).
    - [Add it to Google Business](https://business.google.com/).
15. Do you want to get info about conversions, ads…? Then:
    - [Add Goals and Track Events with Google Analytics](https://www.wpbeginner.com/wp-tutorials/how-to-add-google-analytics-event-tracking-in-wordpress/).
    - [Add Facebook Pixel](https://www.facebook.com/business/learn/facebook-ads-pixel).
    - [WordPress Conversion Tracking Made Simple: A Step-by-Step Guide](https://www.wpbeginner.com/beginners-guide/wordpress-conversion-tracking-made-simple-a-step-by-step-guide/).
16. Does company need a CRM? Then:
    - [14 WordPress CRM Plugins to Supercharge Your Business in 2020](https://kinsta.com/blog/wordpress-crm/).
17. Do you want the latest WordPress/Google feature? Then:
    - [Get Ready to Tell Stories on WordPress](https://google.github.io/web-stories-wp/beta/).
18. Do you use WooCommerce and Instagram? Then:
    - [The definitive guide on how to set up WooCommerce + Facebook + Instagram shop](https://saucal.com/the-definitive-guide-on-how-to-setup-woocommerce-facebook-instagram-shop/).




## Plugins


### General Purpose

* [**Coming Soon Page & Maintenance Mode by SeedProd**](https://wordpress.org/plugins/coming-soon/):
  _(Enable only when you need to use it and not necessary if using Elementor)_ Create a simple Coming Soon Page or
  Maintenance Mode Page. Work on your site in private while visitors see a “Coming Soon” or “Maintenance Mode” page.


* [**Contact Form by WPForms**](https://wordpress.org/plugins/wpforms-lite/):
  _(Not necessary if using Elementor)_ Drag & drop WordPress form builder that’s EASY and POWERFUL. WPForms allow you
  to create beautiful contact forms, subscription forms, payment forms, and other type of forms for your site in
  minutes, not hours!


* [**Favicon by RealFaviconGenerator**](https://wordpress.org/plugins/favicon-by-realfavicongenerator/):
  Favicon by RealFaviconGenerator is a WordPress plugin to create and install your favicon in a few seconds.


* [**Smush — Lazy Load Images, Optimize & Compress Images**](https://wordpress.org/plugins/wp-smushit/):
  _(Not necessary if using SiteGround Optimizer)_ Optimize images, turn on lazy load, resize, compress & improve your
  Google Page Speed with the incredibly powerful and 100% free WordPress image smasher.

  Alternative: [_Imagify Image Optimizer_](https://wordpress.org/plugins/imagify/) by **WP Rocket**.


* [**Loco Translate**](https://wordpress.org/plugins/loco-translate/):
  Loco Translate provides in-browser editing of WordPress translation files.


* [**ManageWP Worker**](https://wordpress.org/plugins/worker/):
  If you have several WordPress sites, use [ManageWP](https://managewp.com/), a dashboard that helps you save time and
  nerves by automating your workflow.


* [**Polilang**](https://wordpress.org/plugins/polylang/):
  Polylang allows you to create a bilingual or multilingual WordPress site.


* [**Virtual Robots.txt**](https://wordpress.org/plugins/pc-robotstxt/):
  Virtual Robots.txt is an easy (i.e. automated) solution to creating and managing a robots.txt file for your site.
  Instead of mucking about with an FTP, files, permissions…, just upload and activate the plugin, and you're done.
  Use this [robots.txt](robots.txt) for best results **and remember updating Sitemaps at the final of the file**.


* [**Yoast Duplicate Post**](https://wordpress.org/plugins/duplicate-post/):
  This plugin allows users to clone posts of any type, or copy them to new drafts for further editing.



### Social Media

* [**Easy Social Share Buttons for WordPress**](https://socialsharingplugin.com) (Us 22):
  Easy Social Share Buttons for WordPress is the best social sharing plugin on the market, and the most complete and
  optimized social share buttons package. With a single plugin, the world of social media sharing is opened to
  you: increase your shares, grow your profile, build your following, get new subscribers and drive more traffic.

  Alternatives: _[20+ Best WordPress Social Media Share Plugins](https://blog.hubspot.com/website/best-social-media-plugins-for-wordpress)_.



### SEO

* [**Rank Math**](https://bit.ly/AX-Seo):
  WordPress SEO Made Easy. Rank Math is the most powerful way to get the BEST WordPress SEO tools added to your website.
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
  - How to Migrate to Rank Math: _[Rank Math Review – Why I Ditched Yoast For RankMath](https://www.matthewwoodward.co.uk/seo/reviews/rank-math/)_

  Alternative: _[Yoast SEO](https://yoast.com/wordpress/plugins/seo/)_.



### Security

* [**SecuPress**](https://secupress.me):
  Protect your WordPress with malware scans; block bots & suspicious IPs. Get a complete WordPress security toolkit for
  free or as a pro plugin.
    * [SecuPress Free](https://wordpress.org/plugins/secupress/) (Free)
    * [SecuPress Pro](https://secupress.me/) (Us 70 per Year)

   Alternatives: _[8 Best WordPress Security Plugins to Lock Down Your Site](https://elementor.com/blog/wordpress-security-plugins/)_.



### Performance

* [**instant.page**](https://instant.page/):
  _(Not necessary if using WP Rocket)_ Make your site’s pages instant in 1 minute and improve your conversion rate by
  1%. Add this `Snippet` to WordPress using [Code Snippets](https://wordpress.org/plugins/code-snippets/) plugin.

  ```
  add_action( 'wp_footer', function () { ?>
      HERE INSTA.PAGE CODE
  <?php } );
  ```

* [**SiteGround Optimizer**](https://wordpress.org/plugins/sg-cachepress/):
  _(Use only with Siteground hosting)_ This plugin is designed to link WordPress with the
  [**SiteGround**](http://bit.ly/AX-SuperHosting ) Performance services.
  - [Best SiteGround Optimizer Settings for 2021 (To Pass Core Web Vitals)](https://startblogging101.com/sg-optimizer-settings/).
  
  _Important:_ Verify that it is working via CPanel and if you use _WP Rocket_, disable _Home Optimization_ (HTML, JS & CSS).


* [**WP Rocket**](https://wp-rocket.me/?ref=04c2ff82) (Us 39 per Year):
  Make WordPress Load Fast in a Few Clicks. Recognized as the most powerful caching plugin by WordPress experts.
  - [The Ideal WP Rocket Settings (2021)](https://onlinemediamasters.com/wp-rocket-settings/).
  - [Page Speed Optimization for WordPress: 19 Performance Tips](https://wp-rocket.me/blog/guide-to-page-speed-optimization-for-wordpress/).
  - [How to Speed Up Your WordPress Site (Ultimate 2021 Guide)](https://kinsta.com/learn/speed-up-wordpress/).

  Alternatives:
  [_7 Best WordPress Caching Plugins to Lower Page Load Time and Time to First Byte_](https://kinsta.com/blog/wordpress-caching-plugins/)].



## CDN

* [**Bunny.net**](https://bit.ly/AX-SuperCDN) (Europe & North America $0.01 /GB):
  Go faster than the fastest with the next-generation CDN, edge storage, and optimization service. We make lightning
  fast performance at any scale easier than ever before.
  - [How to Set up BunnyCDN in WordPress](https://wpspeedmatters.com/bunnycdn-wordpress/#how-to-setup-bunnycdn-in-wordpress).

  Alternative: [_RocketCDN_](https://wp-rocket.me/rocketcdn/) by **WP Rocket**.
