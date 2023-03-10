# Annie Hazarika Portfolio

## Info

This project uses [Grav](https://learn.getgrav.org/17), a Symfony based CMS.

## Install

### Requirements

- PHP > 7.1
- Sass installed.

### Run in local

To start the local server:
```bash
bin/grav server
```

Access the website on [http://127.0.0.1:8000](http://127.0.0.1:8000) and the admin on [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

### Compile SCSS files

To compile css files from `custom` there:
```bash
cd user/themes/custom
sass --source-map --watch scss:css-compiled --style compressed
```