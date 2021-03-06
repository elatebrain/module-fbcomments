# Elatebrain FBComments for Magento 2



[![Latest Stable Version](https://poser.pugx.org/elatebrain/module-fbcomments/v/stable)](https://packagist.org/packages/elatebrain/module-fbcomments)
[![Total Downloads](https://poser.pugx.org/elatebrain/module-fbcomments/downloads)](https://packagist.org/packages/elatebrain/module-fbcomments)


## How to install & upgrade Elatebrain_FBComments


#### 1. Install via composer (recommended)

We recommend you to install Elatebrain_FBComments module via composer. It is easy to install, update and maintain.

Run the following command in Magento 2 root directory.

##### 1.1 Install

```
composer require elatebrain/module-fbcomments
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

##### 1.2 Upgrade

```
composer update elatebrain/module-fbcomments
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

Run setup:di:compile command if your store is in Production mode:

```
php bin/magento setup:di:compile
```

#### 2. Copy and paste

If you don't want to install this module via composer, you can use this way. 

- Download [the latest version here](https://github.com/elatebrain/module-fbcomments/archive/master.zip) 
- Extract `master.zip` file to `app/code/Elatebrain/FBComments` ; You have to create a folder path `app/code/Elatebrain/FBComments` if not exist.
- Go to Magento root folder and run upgrade command line to install `Elatebrain_FBComments`:

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```
