# WHMCS Server Selector
The Server Selector allows you to create rules based on the configurations set within WHMCS to determine what server group your customers new services will be assigned to. Great for multi-location hosting services, no longer needing multiple WHMCS products for each location you offer, you just need one configuration and one rule.

## Supported Configuration Types
* [Configuration Options](https://docs.whmcs.com/8-13/products/configuration-options/configurable-options/) 

## Requirements
- WHMCS 7, 8+
- PHP Recommended 8.1+
- Ioncube PHP Encoded Support 7.4+

## Installation
Installing this addon module is very straight forward and requires no code changes. Just follow these steps to get up and running:

* Download this Github Repo and unzip it, direct download: [https://github.com/hostmedia/whmcs-serverselector-encoded/archive/refs/heads/main.zip](https://github.com/hostmedia/whmcs-serverselector-encoded/archive/refs/heads/main.zip)
* Upload the contents to your WHMCS root directory.
* Once uploaded, navigate to WHMCS admin, addons section to activate the module, when activated, select the 'Configure' option for the module and enter your license key and make sure to select the user groups you wish to have access. It is highly recommended to add your WHMCS username as this module uses local API calls.
* Now everything has been setup, you can click on Addons in the top navigation bar to see the "Server Selector" option. If you do not see this option, double check your user group configuration on the addon module.

## Upgrade
Before uploading the a new version of the Server Selector, please make sure to take a backup of your WHMCS database.

## License Key
To purchase a license key please order at: [https://portal.hostmedia.uk/store/software/whmcs-server-selector](https://portal.hostmedia.uk/store/software/whmcs-server-selector)

## Ioncube Loaders
The WHMCS Banner Manager is encoded using the latest Ioncube loader, this does support backward compatibility but recommend always using the lastest Ioncube loader

Download Loader: [https://www.ioncube.com/loaders.php](https://www.ioncube.com/loaders.php)

## Support
If you have any issues please open a ticket to our development team at: [https://portal.hostmedia.uk/submitticket.php?step=2&deptid=21](https://portal.hostmedia.uk/submitticket.php?step=2&deptid=21)
