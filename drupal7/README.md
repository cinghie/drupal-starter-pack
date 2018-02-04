# Drupal 7 Starter Pack
Drupal 7 Starter Pack is a ready-to-use bootstrap site with:

- Bootstrap Business Theme
- Mandatory modules
- Mandatory libraries

# Installation

## 1 Download and install Drupal 7 last version:

https://www.drupal.org/project/drupal

## 2a) Copy drupal7 folder to your project root

## 2b) Clone git drupal7 from terminal

```
git clone -b drupal7 --single-branch https://github.com/cinghie/drupal-demo.git .
```

## 3 Uncompress and load database from drupal7.sql.rar

## 4 Run Security Review

```
admin/reports/security-review
```

## 5 Set Logging

```
node#overlay=admin/config/development/logging
```

 - On Development set "All Errors"
 - On Production set "Nobody"
 
