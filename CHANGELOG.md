# Changelog

## Update 8, 18th of December 2017

* Rebuilt DevA — now public
* Using MySQL 5.7 instead of MariaDB on macOS
* Now possible to edit a virtual host

## Update 7, 1st of December 2017

* Added support for Ubuntu
* Reverted allow\_url\_fopen to the default value
* Now possible to input the SMTP account through a dialog
* Removed memcached

## Update 6, 23rd of November 2017

* Updated the GitHub API URLs with the new username
* Small visual improvement to the 404 page
* Fixed script not checking if DevA is installed
* Fixed script not moving itself to the correct path after installation
* Fixed issue during installation when upgrading Homebrew
* Removed Xcode Command Line Tools check, Homebrew now does that
* Brew packages update check now working properly
* Functions shell\_exec, passthru & stream\_select no longer disabled (VSCode)
* Show phpinfo() action checks if both Nginx and PHP are running

## Update 5, 13th of November 2017

* Improved and organised DevA code (more functions, less code)
* Added MD5 hash of the backup file on completion
* Changed "Press ENTER to continue" to "Press any key to continue" everywhere
* Added disable_functions setting to PHP config
* Some commands are now run simultaneously to improve speed
* Fixed MariaDB not starting after Homebrew prune command (restart services)
* Removed deva shortcut to the control panel, now it's dev only
* Backup now creates a MySQL dump instead of compressing the data dir
* Improved the user interface

## Update 4, 4th of November 2017

* Disabled allow\_url\_fopen in php.ini (Just like Plesk, use cURL instead)
* Added action to see DevA changelog

## Update 3, 2nd of November 2017

* Fixed date not showing in new vhost files
* Updated the interface colors
* Removed number after underscore in service versions

## Update 2, 31th of October 2017

* Improved DevA script code
* Backup token file contains the version of each service
* phpinfo() file now contains a random token on creation
* Adding a virtual host checks if / was added
* Adding a virtual host checks if full path was used
* Adding a virtual host checks if host name is alphanumeric
* Added action to fix file permissions
* Added action to run brew doctor
* Added a 404 page
* Updates are now performed through a single script
* Updates page now installs DevA updates
* Updated config download URLs to GitHub

## Update 1, 25th of October 2017

* Updated README.md with database accesses and update instructions
* Resolved all shellcheck notices on the deva script
* PHP-FPM processes are now started on demand to save battery/memory
* Enabled auth on MongoDB
* Added action to show phpinfo()

## Initial Release, 15th of October 2017

* Initial release
