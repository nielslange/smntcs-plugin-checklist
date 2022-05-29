# SMNTCS plugin checklist

This document contains the general checklist for my SMNTCS plugins.

## Main plugin file

The main plugin file must contain the following header:

```php
/**
 * Plugin Name: { PLUGIN NAME }
 * Plugin URI: { PLUGIN DESCRIPTION }
 * Description: { PLUGIN DESCRIPTION }
 * Author: Niels Lange
 * Author URI: https://nielslange.de
 * Text Domain: { PLUGIN SLUG }
 * Version: { PLUGIN VERSION }
 * Requires PHP: { SUPPORTED PHP VERSION }
 * Requires at least: { SUPPORTED WP VERSION }
 * License: GPL v2 or later
 * License URI: https://www.gnu.org/licenses/gpl-2.0.html
 *
 * WC requires at least: { REQUIRED WC VERSION, IF APPLICABLE }
 * WC tested up to: { SUPPORTED WC VERSION, IF APPLICABLE }
 *
 * @category   Plugin
 * @package    WordPress
 * @subpackage { PLUGIN NAME }
 * @author     Niels Lange <info@nielslange.de>
 * @license    http://opensource.org/licenses/gpl-license.php GNU Public License
 */
```


## README.txt

The README.txt contains the following header:

```txt
Contributors: nielslange
Tags: { PLUGIN TAGS }
Stable tag: { STABLE VERSION }
Tested up to: { TESTED WP VERSION }
Requires PHP: { SUPPORTED PHP VERSION }
Requires at least: { SUPPORTED WP VERSION }
License: GPL v2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
```
