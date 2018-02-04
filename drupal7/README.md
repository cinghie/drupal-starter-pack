# Drupal Demo
Drupal Demo site with Bootstrap Business Template and mandatory modules adn libraries just installed

# Installation

## 1 Set on your server the Github Token Access

```
composer config -g github-oauth.github.com <oauthtoken>
```

to create a token access: 

https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/


## 2 Copy git From terminal

Install in the some folder

```
git clone https://github.com/cinghie/drupal-demo.git .
```

Install in a specific folder
```
git clone https://github.com/cinghie/drupal-demo.git path/to/folder/
```

# Configuration

## 1 Download and install Drupal last version:

https://www.drupal.org/project/drupal

## 2 Adding this project files to root folder

## 3 Install this project database

## 5 Run Security Review

```
admin/reports/security-review
```

## 5 Set Logging

```
node#overlay=admin/config/development/logging
```

 - On Development set Tutti gli errori
 - On Production set Nessuno
 
