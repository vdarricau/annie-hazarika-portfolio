# Annie Hazarika Portfolio

## Info

This project uses [Grav](https://learn.getgrav.org/17), a Symfony based CMS.

## Install

### Requirements

PHP > 7.1
Sass installed.

### Commands

To start the local server:
```bash
bin/grav server
```

To compile css files from `custom` there:
```bash
cd user/themes/custom
sass --source-map --watch scss:css-compiled
```