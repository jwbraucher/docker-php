# braucher/php 1.6.1

## Bugfixes
- Fixed waiting for mysql all the time

# braucher/php 1.6.0

## Features
- Added mysql-client package (needed by drush archive-dump)

# braucher/php 1.5.0

## Features
- Using new braucher/puppet puppet-apply entrypoint

## Bugfixes
- Fixed rebuild in Makefile
- Added hour to backup filename

# braucher/php 1.4.0

## Features
- Updated Makefile for backups and building with docker-compose
- Added app.install.local script for local project installs

# braucher/php 1.2.1

## Features
- Removed some of the new app scripts

# braucher/php 1.2.0

## Features
- Refactored master to use new "app" format
- Upgraded php to 5.6

# braucher/php 1.1.1

## Bugfixes
- DOCUMENT_ROOT typo in /php entrypoint

# braucher/php 1.1.0

## Features
- now serves files from $DOCUMENT_ROOT if supplied
- added sample project branch
- switched to using braucher/fcgi for http proxy

# braucher/php 1.0.0

## Features
- php installed via mayflower/php puppet module
- php5-fpm setup with /php5-fpm entrypoint
- various extensions enabled for apps like Wordpress, Drupal, Magento
- various php settings provided for apps like Wordpress, Drupal, Magento
