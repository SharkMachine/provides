# Let's remove unnecessary clutter by providing it with a skeleton package

This package only provides common polyfills with the assumption that the extensions are installed. This prevents unneeded polyfills from being installed when they are not needed.

**Available versions:**

* 1.0 - PHP 8.1
* 2.0 - PHP 8.2

## Installation

```bash
composer require sharkmachine/provides
```

# Polyfills

The following packages are provided and won't be installed when this package is required:

## PHP extension specific

### Apache/FPM SAPI

* `ralouphie/getallheaders` 

### Calendar

* `fisharebest/ext-calendar` 

### Ctype

* `symfony/polyfill-ctype`

### Iconv

* `symfony/polyfill-iconv`

### Intl

* `symfony/polyfill-intl-grapheme`
* `symfony/polyfill-intl-idn`
* `symfony/polyfill-intl-normalizer`
* `symfony/polyfill-intl-messageformatter`

### Mbstring

* `symfony/polyfill-mbstring`

### Sodium

* `paragonie/sodium_compat`

## PHP version specific

* `paragonie/random_compat`
* `symfony/polyfill-php54`
* `symfony/polyfill-php55`
* `symfony/polyfill-php56`
* `symfony/polyfill-php70`
* `symfony/polyfill-php71`
* `symfony/polyfill-php72`
* `symfony/polyfill-php73`
* `symfony/polyfill-php74`
* `symfony/polyfill-php80`
* `symfony/polyfill-php81`
* `symfony/polyfill-php82`

