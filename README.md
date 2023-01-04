# Awesome OpenMage [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/fballiano/awesome-openmage/issues)
Curated list of awesome OpenMage extensions, resources and other highlights.

## Most important resources for new projects
- [OpenMage official GitHub repository](https://github.com/OpenMage/magento-lts)
- [Download OpenMage official releases](https://github.com/OpenMage/magento-lts/releases)
- Use OpenMage v20 to have the more cutting edge version of OpenMage

## Install OpenMage
- Method 1: unzip the release archive in the document root of your web server
- Method 2: `composer require "openmage/magento-lts":"^20"` (it will automatically download the latest v20 release), it will ask for the OpenMage root directory, my suggestion is to use `.` (the current directory)

## Tools
- [Magerun](https://files.magerun.net): provides a huge set of well tested command line commands which save hours of work time. 
- [PHPStorm](https://www.jetbrains.com/phpstorm): the best IDE for OpenMage
- [Magicento](https://magicento.com): a plugin for PHPStorm than enables great features targeted to OpenMage development

## Modules

This list is organized in alphabetical order.

### Backend
- [Flagbit_ChangeAttributeSet](https://github.com/flagbit/Magento-ChangeAttributeSet): change the attribute set of existing product

### Frontend
- [CustomGento_ProductBadges](https://github.com/customgento/CustomGento_ProductBadges): product badges and labels

### Image processing
- [Fballiano_ImageCleaner](https://github.com/fballiano/openmage-image-cleaner): orphaned image cleaner
- [FireGento_PerfectWatermarks](https://github.com/colinmollenhour/Perfect_Watermarks): replaces GD2 adapter with imagemagick
- [Yireo_Webp](https://github.com/yireo-magento1/Yireo_Webp): webp generation

### Payment methods
- [Bitcoin](https://github.com/rvelhote/opennode-magento)
- [Braintree](https://github.com/justinbeaty/module-gene-braintree)
- [HiPay](https://github.com/hipay/hipay-fullservice-sdk-magento1)

### Utilities
- [Aoe_Scheduler](https://github.com/AOEpeople/Aoe_Scheduler): better cron scheduling
- [Aschroder_SMTPPro](https://github.com/aschroder/Magento-SMTP-Pro-Email-Extension): SMTP support
- [FireGento_AdminMonitoring](https://github.com/firegento/firegento-adminmonitoring): log almost every activity in the backend
- [FireGento_Logger](https://github.com/firegento/firegento-logger): advanced logging adapters
- [Maven_Html5uploader](https://github.com/anhuy1989/html5upload): multiple images uploader using HTML5
