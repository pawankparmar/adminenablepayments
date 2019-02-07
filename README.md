# Installation and User Guide

## Installation

### 1. Using Composer:
```
composer require pawankparmar/adminenablepayments
php bin/magento module:enable PawanKParmar_AdminEnablePayments
php bin/magento setup:upgrade
```
### 2. Manual Installation

First extract package ZIP file on your computer.

By using SSH/FTP upload file at Magento2Root/app/code/PawanKParmar/AdminEnablePayments

After that you need to run following command:

```
1. php bin/magento setup:upgrade
2. php bin/magento cache:flush
3. php bin/magento setup:static-content:deploy

	If required compilation, run 
	php bin/magento setup:di:compile
```

# How to check extension successfully installed.

If extension successfully installed, You will see a new Menu at  **System->Configuration->Pawankparmar->Admin Enable Payment Methods** 

![Configuration](https://raw.githubusercontent.com/pawankparmar/assets/master/Config_PawanKParmar.png)

# **How to Use Extension:**

> There will two configuration Settings available

**Enable:** Admin can enable and disable module.

**Disable Payment Method for front-end:** Here admin will see all active payment method.
Admin can choose which payment method need only for admin.


**Example:** In the above image, **Purchase Order** Payment method is selected, So this payment method will not available for front end customer. But at the same time, Admin can accept Payment by **Purchase Order** Payment Method from Admin.

**Front End**

![FrontEnd](https://raw.githubusercontent.com/pawankparmar/assets/master/FrontEnd_PawanKParmar.png)

**Admin Create Order**

![Admin](https://raw.githubusercontent.com/pawankparmar/assets/master/Admin_PawnKParmar.png)

# Support

If you encounter any problems or bugs, please [open an issue](https://github.com/pawankparmar/adminenablepayments/issues) on GitHub.