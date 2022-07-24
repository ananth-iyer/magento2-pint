# Magento2 - Laravel Pint support

I have recently saw this very interesting project and thought to it will help with Magento 2 developers.

- [X] It provide pint binary file to execute directly from Magento 2 root directory or move this file to central location to run from anywhere.
- [X] No need to install with composer.
- [X] It will not update the packages you have already.
- [X] It supports PHP 8.0.*

Get Started
---
- You have to create a new file pint.json at Magento 2 root and copy the content from repository to that file.
- Download the `pint.phar` file from Laravel Pint Github.

Commands to run:
---
* php pint.phar --version or -V - to check the pint version
* php pint.phar --test app/code - to test the code in `app/code` directory
* php pint.phar app/code - it applies the fixes to the files. 

Useful Links
---
- Pint Github - https://github.com/laravel/pint
- Pint Docs - https://laravel.com/docs/9.x/pint
- Pint License - https://github.com/laravel/pint/blob/main/LICENSE.md

---
Credits - Laravel Team
