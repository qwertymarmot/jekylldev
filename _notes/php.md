---
title: PHP
category: now
layout: now
navigation: True
date: 2022-04-17 10:18:00
cover: 'assets/images/cover8.jpg'
tags: now
subclass: 'post tag-test tag-content'
logo: 'assets/images/logo_white.png'
author: brandon
imagecredit_id: '@markusspiske'
imagecredit_name: 'Markus Spiske'
---
<br>
## General Management
- <a href="{{ site.baseurl }}notes/PHP-Basics">PHP Basics</a>
- <a href="{{ site.baseurl }}notes/PHP-Data-types">PHP Data types</a>
- <a href="{{ site.baseurl }}notes/PHP-File-Types">PHP File Types</a>
- <a href="{{ site.baseurl }}notes/PHP-Permissions">PHP Permissions</a>

## Coding
- <a href="{{ site.baseurl }}notes/PHP-Variables">PHP Variables</a>
- <a href="{{ site.baseurl }}notes/PHP-Operators">PHP Operators</a>
- <a href="{{ site.baseurl }}notes/PHP-Comments">PHP Comments</a>
- <a href="{{ site.baseurl }}notes/PHP-Functions">PHP Functions</a>
- <a href="{{ site.baseurl }}notes/PHP-Strings">PHP Strings</a>
- <a href="{{ site.baseurl }}notes/PHP-User-Input">PHP User Input</a>
- <a href="{{ site.baseurl }}notes/PHP-Sending-Email">PHP Sending Email</a>
- <a href="{{ site.baseurl }}notes/PHP-MySQL">PHP MySQL</a>

## Tips
- phpinfo will allow you to see what features you have enabled
```php
<?php
phpinfo();
?>
```
- To turn on error reporting you can add the following to your script
 ```php
<?php
error\_reporting(E\_ALL);
// The rest of your script goes here.
?>
```