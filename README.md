# Awesome OpenMage [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/fballiano/awesome-openmage/issues)
Curated list of awesome OpenMage extensions, resources and other highlights.

## Most important resources for new projects
- [OpenMage official GitHub repository](https://github.com/OpenMage/magento-lts)
- [Download OpenMage official releases](https://github.com/OpenMage/magento-lts/releases)
- Use OpenMage v20 to have the more cutting edge version of OpenMage

## Install OpenMage

1. Configure your web server (virtual host or subfolder of a domain)
2. Create the folder where you want to install OpenMage, enter it and execute  
`composer require "openmage/magento-lts":"^20"`  
it will automatically download the latest v20 release then ask for the OpenMage root directory, my suggestion is to use `.` (the current directory)
3. open your web browser and navigate to the URL you configured in point 1, the web installer will take care of the rest

## Documentation

### To read
- [Mirror of the legacy Magento 1 devdocs](https://devdocs-openmage.org/guides/m1x)
- [Magento Extension Developer’s Guide](https://info2.magento.com/rs/magentosoftware/images/magento-extension-developers-guide-v1.0.pdf)
- [Magento tutorial for beginners by MageStore](https://www.magestore.com/blog/magento-tutorial-for-beginners)
- [Alan Storm blog](https://alanstorm.com/category/magento): one of the most influential and complete blog about Magento development
- [PacktPub ebooks about Magento](https://subscription.packtpub.com/search?query=magento)

### To watch
- [Magento Community Tutorials by LevelUpTuts](https://www.youtube.com/watch?v=ktlGc6UWB9A&list=PL3B0BAAF482B16EAB)
- [Theming Magento Community by LevelUpTuts](https://www.youtube.com/watch?v=gsY51-QmxkU&list=PLLnpHn493BHHWhog4Xk36L1nyxUu16r9E)
- [Magento Training by Pierre FAY](https://www.youtube.com/playlist?list=PLcNSzkcgNPqSPyccfo8TIGZsUYtz81YpY)
- [Magento Training Course by Artur Gevorkyan](https://www.youtube.com/playlist?list=PLa6k8rC4o6VXqTvFkBVm5iEwwm3gTqg74)
- [Magento Training Course by Magento Education World](https://www.youtube.com/@magentoeducationworld8388/playlists)
- [Magento Certification Training by MagentoDiary, with Ben Marks](https://www.youtube.com/watch?v=XAjxN5bbl0E&list=PLCi45QTgjDEvbHQm7u8mDzhrVgAphGpcP)
- [Magento Fundamentals by Artur Gevorkyan](https://www.youtube.com/playlist?list=PLa6k8rC4o6VWrk4sUVGjySuBoGUVa7J3t)
- [Magento Theme Creation by Magento Godz](https://www.youtube.com/@magentogodz2892/videos)
- [Magento Tutorials by Template Monster](https://www.youtube.com/watch?v=kuvyFMYIiuM&list=PLhQIfRNfwAocfWc4zD0OPccvOuiO58-D6)
- [Mastering Magento by Shiva Modi](https://www.youtube.com/@ShivaModi/videos)
- [Magento 1.9 by Let's CMS](https://www.youtube.com/playlist?list=PLoTpPBZH6r134pilpxQJOor5L9cpkqrm3)
- Quick Start to Magento Customization (based on Magento 1.5) [part 1](https://www.youtube.com/watch?v=I0bxZ6h4w78) - [part 2](https://www.youtube.com/watch?v=FGEa0TvdwLg) - [part 3](https://www.youtube.com/watch?v=g0VHo7B0YjY)

## Tools
- [Magerun](https://files.magerun.net): provides a huge set of well tested command line commands which save hours of work time.
- [PHPStorm](https://www.jetbrains.com/phpstorm): the best IDE for OpenMage
- [Magicento](https://magicento.com): a plugin for PHPStorm than enables great features targeted to OpenMage development

## Vendors that opensourced all their modules
- [FishPig](https://fishpig.com/magento-1-extensions), also check [their github account](https://github.com/bentideswell?tab=repositories&q=magento1)
- [Manadev](https://github.com/osmianski/manadev-magento)
- [Meanbee](https://github.com/orgs/meanbee/repositories?q=magento%5C-&type=all&language=php&sort=name)

## Modules

This list is organized in alphabetical order.

### Backend
- [Flagbit_ChangeAttributeSet](https://github.com/flagbit/Magento-ChangeAttributeSet): change the attribute set of existing product
- [Monaco Editor](https://github.com/empiricompany/openmage-mm_monacoeditor): advanced code editor from Microsoft used in VSCode

### Cache
- [Cm_Diehard](https://github.com/colinmollenhour/Cm_Diehard) Advanced PHP based full page cache by the creator of the Redis module for OpenMage
- [Lesti_Fpc](https://github.com/fballiano/openmage-lesti-fpc): PHP based full page cache (fork maintained by [fballiano](https://github.com/fballiano))
- [Nexcessnet_Turpentine](https://github.com/luigifab/openmage-turpentine-varnish): Varnish based full page cache (fork maintained by [luigifab](https://github.com/luigifab))

### Captcha/Spam prevention
- [Cloudflare Turnstile](https://github.com/fballiano/openmage-cloudflare-turnstile)
- [HoneySpam](https://github.com/magento-hackathon/HoneySpam)
- [reCaptcha](https://github.com/empiricompany/reCaptcha) (fork maintained by [empiricompany](https://github.com/empiricompany))

### Frontend
- [CSS/JS versioning based on last git commit hash](https://github.com/fballiano/openmage-cssjs-versioning)
- [CustomGento_ProductBadges](https://github.com/customgento/CustomGento_ProductBadges): product badges and labels
- [Defer Javascripts](https://github.com/fballiano/openmage-defer-javascripts)
- [Matomo](https://github.com/vianetz/matomo-magento1)

### Image processing
- [Fballiano_ImageCleaner](https://github.com/fballiano/openmage-image-cleaner): orphaned image cleaner
- [FireGento_PerfectWatermarks](https://github.com/colinmollenhour/Perfect_Watermarks): replaces GD2 adapter with imagemagick (fork maintained by [colinmollenhour](https://github.com/colinmollenhour))
- [Yireo_Webp](https://github.com/yireo-magento1/Yireo_Webp): webp generation

### Payment methods
- [Amazon Pay](https://amazon-pay.readthedocs.io/en/latest)
- [Bitcoin](https://github.com/rvelhote/opennode-magento)
- [Braintree](https://github.com/justinbeaty/module-gene-braintree) (fork maintained by [justinbeaty](https://github.com/justinbeaty))
- [HiPay](https://github.com/hipay/hipay-fullservice-sdk-magento1)
- [Mollie](https://github.com/mollie/Magento)
- [PayPal Pay Later](https://github.com/empiricompany/openmage-paypal-pay-later-banner-info)
- [Stripe](https://github.com/stripe-archive/stripe-magento1-releases)

### Utilities
- [Aoe_Scheduler](https://github.com/AOEpeople/Aoe_Scheduler): better cron scheduling
- [Aschroder_SMTPPro](https://github.com/aschroder/Magento-SMTP-Pro-Email-Extension): SMTP support
- [CSS/JS Minify](https://github.com/fballiano/openmage-cssjs-minify): simple basic module that does what it says
- [FireGento_AdminMonitoring](https://github.com/firegento/firegento-adminmonitoring): log almost every activity in the backend
- [FireGento_Logger](https://github.com/firegento/firegento-logger): advanced logging adapters
- [Laravel Ignition](https://github.com/empiricompany/openmage_ignition): modern debugging solution, with support for AI problem solution
- [Orphaned config entries](https://github.com/hirale/openmage-orphaned-config): retrieve all system configurations from system.xml, compare them with the entries in the core_config_data table and list all the orphaned configurations
- [Magneto Debug](https://github.com/madalinoprea/magneto-debug): developer debug toolbar
- [Html5Upload](https://github.com/empiricompany/html5upload): multiple media file upload with drag&drop (fork maintained by [empiricompany](https://github.com/empiricompany))
