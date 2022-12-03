# SMNTCS plugin checklist

This document contains the general checklist for my SMNTCS plugins.

## Main plugin file

The main plugin file must contain the following header:

```php
/**
 * Plugin Name:           { PLUGIN NAME }
 * Plugin URI:            { PLUGIN URI }
 * Description:           { PLUGIN DESCRIPTION }
 * Author:                Niels Lange
 * Author URI:            https://nielslange.de
 * Text Domain:           { PLUGIN SLUG }
 * Version:               { PLUGIN VERSION }
 * Requires PHP:          { SUPPORTED PHP VERSION }
 * Requires at least:     { SUPPORTED WP VERSION }
 * WC requires at least:  { REQUIRED WC VERSION, IF APPLICABLE }
 * WC tested up to:       { SUPPORTED WC VERSION, IF APPLICABLE }
 * License:               GPL v2 or later
 * License URI:           https://www.gnu.org/licenses/gpl-2.0.html
 *
 * @package { PLUGIN NAME }
 */
```


## README.txt

The README.txt contains the following header:

```txt
Contributors:       nielslange
Tags:               { PLUGIN TAGS }
Stable tag:         { STABLE VERSION }
Tested up to:       { TESTED WP VERSION }
Requires PHP:       { SUPPORTED PHP VERSION }
Requires at least:  { SUPPORTED WP VERSION }
License:            GPL v2 or later
License URI:        https://www.gnu.org/licenses/gpl-2.0.html
```
