# Drupal Demo
Drupal Demo site with Bootstrap Business Template and mandatory modules adn libraries just installed

# Installation

## 1 Download and install Drupal last version:

https://www.drupal.org/project/drupal

## 2a) Copy the content of drupal 7 folder to your project root


## 2b) Copy folder with git from Terminal

Install in the some folder

```
git clone -b drupal7 git@github.com:cinghie/drupal-demo/edit/drupal7.git
```

## 3 Install this project database

## 4 Run Security Review

```
admin/reports/security-review
```

## 5 Set Logging

```
node#overlay=admin/config/development/logging
```

 - On Development set Tutti gli errori
 - On Production set Nessuno
