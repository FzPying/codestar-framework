---
title: Usage as Theme
type: h2
weight: 101
filename: installation/usage_as_theme.md
---

```
.
├── wp-content
|   ├── themes
|   |   ├── themename
|   |   ├── functions.php
|   |   ├── ...
|   |   ├── ...
```

```php?start_inline=1
/**
 *
 * Codestar Framework
 * A Lightweight and easy-to-use WordPress Options Framework
 *
 */
define( 'CS_FRAMEWORK_DIRECTORY', get_template_directory_uri() . '/cs-framework/' );
require_once dirname( __FILE__ ) .'/cs-framework/cs-framework.php';

// -( or )-
// define( 'CS_FRAMEWORK_DIRECTORY', get_template_directory_uri() . '/subfolder/' );
// require_once dirname( __FILE__ ) .'/subfolder/cs-framework.php';

```

> This is **not meant** replace your main **functions.php**, only put this code below your codes

* Download zip file from github repository
* Extract download zip on `themename/cs-framework` folder under your theme directory
* Add framework include code on your theme `themename/functions.php` file
* Yay! Right now you are ready to configure framework, metaboxes, taxonomies, wp customize, shortcoder
* Take a look for config files from `themename/cs-framework/config` folder
* Read for about [configuration](#configuration)
