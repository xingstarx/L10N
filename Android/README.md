Shou Android L10N
=================

All Android related l10n resources are put here.


How to Translate
----------------

You may find detailed instructions at [Android developers site](http://developer.android.com/training/basics/supporting-devices/languages.html).

### TL;DR ###

1. Read the [general contribution rules](https://github.com/shoutv/L10N/blob/master/README.md) at first
2. Launch your favorite XML editor
3. Find the ISO code for the language to translate, e.g. `es` for Spanish
4. Copy `res/values` to your locale directory like `res/values-es`
5. Repeat the previous step for `res/values-v17` and `res/values-v18`
6. Edit your own `strings.xml`, translate from `<string...>EN</string>` to `<string>LOCALE</string>`
3. Edit your own `arrays.xml`, translate from `<item>EN</item>` to `<item>LOCALE</item>`

DO NOT TOUCH ANY OTHER LETTERS!
