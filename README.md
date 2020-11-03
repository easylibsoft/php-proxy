# Easylib PHP Proxy
ALL RIGHTS RESERVED

## Keep it up-to-date

Application itself rarely will change, vast majority of changes will be done to its requirement packages like php-proxy. Simply call this command once in a while to make sure your proxy is always using the latest versions.

```
composer update
```

#### config.php

This file will be loaded into the global Config class.

#### /templates/

This should have been named "views", but for historic purposes we keep it named as templates for now.

#### /plugins/

PHP-Proxy provides many of its own native plugins, but users are free to write their own custom plugins, which could then be automatically loaded from this very folder. See /plugins/TestPlugin.php for an example.

<hr>  

This software uses https://github.com/Athlon1600/php-proxy-app Licensed under [MIT](https://github.com/Athlon1600/php-proxy-app/blob/master/LICENSE)
