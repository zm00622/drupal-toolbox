## drupal-toolbox
This toolbox is going to provide me with the notes and resources I acquire as I learn Drupal!

_________________________


This morning I had an ensure where I encountered a "composer command not found error."

This StackOverflow comment was the fix:

Well I tried a lot of things but none seemed to be working. But the following process did it right, I can now use composer command in terminal. I'm in mac OS 10.12.1

$ curl -sS https://getcomposer.org/installer | php
$ chmod +x composer.phar
$ mv composer.phar /usr/local/bin/composer
$ composer

_________________________

Encountered problem installing admin toolbar module. Ran this command to find out why composer would not install the admin toolbar:

composer prohibits drupal/admin_toolbar

Received the following error: 

  [Symfony\Component\Console\Exception\RuntimeException]  
  Not enough arguments (missing: "version").              

_________________________

## drush commands for migration

First, delete uid in new config file

drush cim (config import)

drush cex (config export)

drush migrate import

________________________

## How to configure the Forgerock DS and AM Servers for CTS:

https://backstage.forgerock.com/docs/ds/7.1/config-guide/proxy.html

*See "Try the CTS example" at the bottom of the page*

## DS 7.1 Getting Started

https://backstage.forgerock.com/docs/ds/7.1/getting-started/preface.html

## Platform Setup Guide (Sent from Chase in Slack)

https://backstage.forgerock.com/docs/platform/7.1/platform-setup-guide/
