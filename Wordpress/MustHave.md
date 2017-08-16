# Wordpress Must Have

## Setup

1. _Pages_ > _Add New_ > Create basic pages: home, contact...
2. _Appearance_ > Themes > Choose theme.
3. _Settings_ > Setup all SubMenus.
4. _Settings_ > _Writing_ > _Update Services_ > Copy & Paste the Ping Services from [WordpressPingList.md](WordpressPingList.md).


## Plugins


### General Purpose

* [**Favicon by RealFaviconGenerator**](http://realfavicongenerator.net/extensions/wordpress/)


### SEO

* [**Yoast SEO**](https://wordpress.org/plugins/wordpress-seo/):
This plugin is written from the ground up by Joost de Valk and his team at [Yoast](https://yoast.com/) to improve your site's SEO on *all* needed aspects. While this [Yoast SEO plugin](https://yoast.com/wordpress/plugins/seo/) goes the extra mile to take care of all the technical optimization/.[How to Install and Setup WordPress SEO Plugin by Yoast](http://www.wpbeginner.com/plugins/how-to-install-and-setup-wordpress-seo-plugin-by-yoast/)
Alternative:[_All in One SEO_](https://wordpress.org/plugins/all-in-one-seo-pack/).

* [**WPSSO**](https://wpsso.com):
**WPSSO uses your *existing* content to generate meta tags and Schema markup** --- there's no need to manually enter / configure any additional settings or values, *but if you want to* , you can customize just about anything and everything. ;-)
    * Free: [WPSSO (Core Plugin)](https://wordpress.org/plugins/wpsso/)
    * Pro: [WPSSO (Core Plugin)](http://wpsso.com/extend/plugins/wpsso/)
    * [Performance Tuning](https://wpsso.com/docs/plugins/wpsso/installation/performance-tuning/)


### Performance

* [**Disable XML-RPC**](https://wordpress.org/plugins/disable-xml-rpc/)
The XMLRPC allows remote connection to WordPress. For the most part, XMLRPC is only truly useful if you’re planning to use mobile apps or remote connections to publish content on your website.
By disabling this feature, you eliminate the risk of external attacks gaining access.


* [**Heartbeat Control**](https://wordpress.org/plugins/heartbeat-control/)
WordPress 3.6 introduced the WordPress Heartbeat API - it allows your browser to communicate with the server when you're logged into the WordPress admin panel. However, even though this is great functionality it may cause issues in certain cases.
Usually, you can completely disable it if you're the only person working at any given time in your site and you know that you don't have any important functionality that heavily relies on it to work properly.
Override heartbeat frequency: _6o seconds_.
Control heartbeat locations: _Disable everywhere_.


