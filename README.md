# WP Options Editor Reloaded

* Requires at least: 3.4
* Tested up to: 5.3
* Stable tag: 1.2
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

Easily view, edit, add, and delete all of your WP Options from the dashboard.

## Description

WP Options Editor allows you to easily view, edit, delete, and add options in your WP options table. The easy interface allows you to search for a particular option, edit it or delete it all within the same WP admin page.

Please be careful when using this plugin! Wordpress core options are excluded from displaying in this plugin.
Serialized data is presented in JSON format. PHP Objects are not editable.
### White label
Just call $WP_Options_Editor->white_label('Your name','Your description');
Or if you want hide plugin in plugin list for anyone who don't have special permission:
$WP_Options_Editor->hide_plugin('manage_options'); 

### Custom access list
Developers can set allowed prefixes by filter apply_filters('wp_options_allowed_prefix',$prefix_array). Defualt array contains * .Plugin supports fnmatch pattern for simplified use see: https://www.php.net/manual/en/function.fnmatch.php.


## Installation

1. Upload `WP Options Editor` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the `Plugins` menu in WordPress
3. Go to Tools->Manage wp_options to see and edit your options
