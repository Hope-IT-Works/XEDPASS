<p align="center">
  <img src="https://user-images.githubusercontent.com/52013820/184260670-06b30eaa-3a91-4022-b7a8-172dd5b4139e.png" alt="budibase-php_logo" style="width: 50%"/>
</p>

<hr>

<h1 align="center">XEDPASS</h1>
<h3 align="center">selfhosted authorization kit for web developement</h3>

<hr>

## About

XEDPASS is a selfhosted authorization kit for web developement projects. You want to create a web project with account functionality? Maybe this kit is for you!

## Status

![status](https://img.shields.io/badge/status-not%20ready-red)

XEDPASS is currently in developement state, there is no release available *(yet)*.

## About hosting

This package was hosted with [WCMP](https://github.com/Hope-IT-Works/WCMP)[^wcmp-description] during development.

[^wcmp-description]: WCMP is a tool for setting up a Caddy server with PHP and MariaDB support

## Dependencies

### Hosting[^replace-notice]

[^replace-notice]: items in this list could be replaced, however, doing so may result in unknown issues

| Name | Description | Tested version | Default Port |
|------|-------------|----------------|--------------|
| [Caddy](https://github.com/caddyserver/caddy) | Fast, multi-platform web server with automatic HTTPS | *irrelevant* | 443 ([HTTPS](https://caddyserver.com/docs/quick-starts/https)) |
| [Composer](https://github.com/composer/composer) | dependency management system for PHP projects | *irrelevant* | / |
| [MariaDB](https://github.com/MariaDB/server) | open source relational database management system server | >=10 | 3306 ([SQL](https://mariadb.com/kb/en/connecting-to-mariadb/)) |
| [PHP](https://github.com/php/php-src) | scripting language interpreter suited for web developement | >=8 | 9000 ([FastCGI](https://www.php.net/manual/en/install.fpm.php)) |
| [winsw/winsw](https://github.com/winsw/winsw) | windows service wrapper | >=2 | / |

### Source[^source-replace]

[^source-replace]: items in this list may not be replaced, as they are partially hard coded into this kit

| Name | Description | Tested version |
|------|-------------|----------------|
| [animate-css/animate.css](https://github.com/animate-css/animate.css) | cross-browser CSS library for animations | 4.1.1 |
| [twbs/bootstrap](https://github.com/twbs/bootstrap) | HTML, CSS and JavaScript front-end framework | 5.2.0 |
| [delight-im/PHP-Auth](https://github.com/delight-im/PHP-Auth) | authorization framework for PHP | 8.3.0 |
| [guzzle/guzzle](https://github.com/guzzle/guzzle) | extensible PHP HTTP client | 7.4.5 |
| [PHPMailer/PHPMailer](https://github.com/PHPMailer/PHPMailer) | email sending library for PHP | 6.6.3 |
| [ActiveCampaign/postmark-templates](https://github.com/ActiveCampaign/postmark-templates) | transactional email templates | *irrelevant* |
| [mevdschee/php-crud-api](https://github.com/mevdschee/php-crud-api) | single-file PHP REST-API for databases | 2.14.8 |
| [vrana/adminer](https://github.com/vrana/adminer) | database management system GUI | 4.8.1 |
