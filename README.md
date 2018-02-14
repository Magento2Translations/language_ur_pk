# Urdu (اردو) Magento2 Language Pack (ur_PK)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Urdu (اردو) translations used can be found [here](https://crowdin.com/project/magento-2/ur).
This translation is usefull for people living in the Pakistan (پاکستان).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/ur#/Head) at Crowdin and based on the Magento 2.2.0 sourcefiles.
There have been  48 strings translated of the 8763 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/1)

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_ur_pk:dev-Head
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_ur_pk/archive/Head.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_ur_pk`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/ur_PK/ur_PK.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Urdu (Pakistan)*'

# Contribute
To help push the '*Urdu (اردو) Magento2 Language Pack (ur_PK)*' forward please goto [this](https://crowdin.com/project/magento-2/ur) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).