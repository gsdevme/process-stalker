# process-stalker
Stalks a process to make sure its still running, if its not issues a start!

## Example configuration
The configuration is very simple, just have each service name on a new line. This does assume however the process name and init.d name are the same
```
// /etc/process-stalker.conf
nginx
php-fpm
varnish
ntpd
```

