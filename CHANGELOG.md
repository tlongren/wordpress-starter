# Changelog

This changelog is for the Docker image. There might be changes to the gulpfile that are not listed here.

## 0.9.0 - latest

- Add `DB_HOST` environment variable - Fix #46
- Various bug fixes and improvements

## 0.8.0

- Add `DB_PREFIX` optional param - Fix #37
- Only create .htaccess for non-multisite installations - Fix #32
- Various bug fixes and improvements

## 0.7.0

- Support Wordpress Multisite - Fix #33
- Fix a typo in the gulpfile

## 0.6.0

- Update wp-cli
- `gulp clean` now also clears generated templates
- Support for `WP_DEBUG_LOG` and `WP_DEBUG_DISPLAY` options

## 0.5.0

- Clear any apache pid file before starting apache

## 0.4.0

- Add a script to run wp-cli via npm
- Recreate the `wp-cli.yml` and `wp-config.php` every time to make sure they are up to date.

## 0.3.0

- Remove all the scripts
- Consolidate and improve the `run.sh`
- Update the documentation

## 0.2.0
