Setup PHP-FPM
-------------

This plugin requires PHP CLI.

- `ln -s /usr/share/munin/plugins/php-fpm /etc/munin/plugins/php-fpm-status` : Provides graph about php-fpm processes status  
- `ln -s /usr/share/munin/plugins/php-fpm /etc/munin/plugins/php-fpm-memory` : Provides graph about Memory processes usage  
- `ln -s /usr/share/munin/plugins/php-fpm /etc/munin/plugins/php-fpm-memoryPreview` : Provides graph about Memory processes pools usage (RAM max, RAM min and RAM average)  
- `ln -s /usr/share/munin/plugins/php-fpm /etc/munin/plugins/php-fpm-cpu` : Provides graph about processes CPU usage  

More information
----------------

**Please check these forks and other repositories that could further meet your expectations**

- See [sosedoff/munin-plugins](//github.com/sosedoff/munin-plugins) for installation informations and to see another php-fpm plugin.
- See MorbZ/munin-php-fpm, a fork called "Munin PHP FPM Plugin combined by Pool"
- See realhidden/munin-php-fpm, a MorbZ fork.
