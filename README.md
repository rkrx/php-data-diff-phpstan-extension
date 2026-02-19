# data-diff-phpstan-extension

PHPStan extension for `rkr/data-diff`.

## Installation

Install via Composer:

```sh
composer require --dev rkr/data-diff-phpstan-extension
```

The extension is auto-registered via `phpstan/extension-installer`.

## Manual include (optional)

If you do not use the extension installer, add this to your `phpstan.neon`:

```neon
includes:
	- vendor/rkr/data-diff-phpstan-extension/extension.neon
```

## Optional rule

To enable the discouraged legacy `new` usage rule, additionally include:

```neon
includes:
	- vendor/rkr/data-diff-phpstan-extension/discourage-legacy-usage-extension.neon
```
