# Mage2 Module Europarts Europarts

    ``europarts/module-europarts``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## Main Functionalities


## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Europarts`
 - Enable the module by running `php bin/magento module:enable Europarts_Europarts`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require europarts/module-europarts`
 - enable the module by running `php bin/magento module:enable Europarts_Europarts`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`


## Configuration




## Specifications




## Attributes

 - Product - New (is_new)

 - Product - Model (model)

 - Product - EET condition code (eet_condition_code)

 - Product - EET model (eet_model)

 - Product - EET id (eet_id)

 - Product - EET ean (eet_ean)

 - Product - EET mpn (eet_mpn)

 - Product - EET oem (eet_oem)

 - Product - EET pph (eet_pph)

