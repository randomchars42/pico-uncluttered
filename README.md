**This repository has been archived** because development of `picocms` seems to have been discontinued. For a simple theme for a flat file based blog consider using [randomchars42/jekyll-documentor](https://github.com/randomchars42/jekyll-documentor) with [Jekyll](https://jekyllrb.com) which is used to publish github pages and most likely won't leave us in the near future.

# pico-uncluttered

An "uncluttered" theme for Pico CMS (<https://www.picocms.org>).

Based on [Bits and Pieces Theme for Pico](https://github.com/lostkeys/Bits-and-Pieces-Theme-for-Pico) by @lostkey and ideas from [Pico Clutter](https://github.com/alan-luo/clutter) by @alan-luo.

It currently relies on the [CurrentLevel](https://github.com/randomchars42/pico-currentlevel)-Plugin to display a breadcrumb-esque directory structure.

## Installation

Simply download, unzip and move the plugin folder to your `/plugins/` folder. Now move the downloaded and unzipped (you did not exxpect that, did you? ;) ) folder to `/themes/`.

Enable both in your `/config/config.php`, by adding:

```php
/*
 * THEME
 */
$config['theme'] = 'uncluttered';

/*
 * PLUGINS
 */
$config['CurrentLevel.enabled'] = true;
```
Enjoy :) Or go ahead and improve it further :)
