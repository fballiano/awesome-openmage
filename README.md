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
- [Mirror of the legacy Magento 1 devdocs](https://devdocs-openmage.org/guides/m1x)
- [Magento Extension Developer’s Guide](https://info2.magento.com/rs/magentosoftware/images/magento-extension-developers-guide-v1.0.pdf)
- [Alan Storm blog](https://alanstorm.com/category/magento): one of the most influential and complete blog about Magento development
- [PacktPub ebooks about Magento](https://subscription.packtpub.com/search?query=magento)

## Tools
- [Magerun](https://files.magerun.net): provides a huge set of well tested command line commands which save hours of work time.
- [PHPStorm](https://www.jetbrains.com/phpstorm): the best IDE for OpenMage
- [Magicento](https://magicento.com): a plugin for PHPStorm than enables great features targeted to OpenMage development

## Modules

This list is organized in alphabetical order.

### Backend
- [Flagbit_ChangeAttributeSet](https://github.com/flagbit/Magento-ChangeAttributeSet): change the attribute set of existing product

### Cache
- [Lesti_Fpc](https://github.com/fballiano/openmage-lesti-fpc): PHP based full page cache (fork maintained by [fballiano](https://github.com/fballiano))
- [Nexcessnet_Turpentine](https://github.com/luigifab/openmage-turpentine-varnish): Varnish based full page cache (fork maintained by [luigifab](https://github.com/luigifab))

### Frontend
- [CustomGento_ProductBadges](https://github.com/customgento/CustomGento_ProductBadges): product badges and labels

### Image processing
- [Fballiano_ImageCleaner](https://github.com/fballiano/openmage-image-cleaner): orphaned image cleaner
- [FireGento_PerfectWatermarks](https://github.com/colinmollenhour/Perfect_Watermarks): replaces GD2 adapter with imagemagick (fork maintained by [colinmollenhour](https://github.com/colinmollenhour))
- [Yireo_Webp](https://github.com/yireo-magento1/Yireo_Webp): webp generation

### Payment methods
- [Bitcoin](https://github.com/rvelhote/opennode-magento)
- [Braintree](https://github.com/justinbeaty/module-gene-braintree) (fork maintained by [justinbeaty](https://github.com/justinbeaty))
- [HiPay](https://github.com/hipay/hipay-fullservice-sdk-magento1)

### Utilities
- [Aoe_Scheduler](https://github.com/AOEpeople/Aoe_Scheduler): better cron scheduling
- [Aschroder_SMTPPro](https://github.com/aschroder/Magento-SMTP-Pro-Email-Extension): SMTP support
- [FireGento_AdminMonitoring](https://github.com/firegento/firegento-adminmonitoring): log almost every activity in the backend
- [FireGento_Logger](https://github.com/firegento/firegento-logger): advanced logging adapters
- [Maven_Html5uploader](https://github.com/anhuy1989/html5upload): multiple images uploader using HTML5
