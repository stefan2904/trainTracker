trainTracker
============

yet another random experiment


Ajax Proxy
----------

Add something like this to your httpd.conf:

```
ProxyPass /trainTracker/oebb http://zugradar.oebb.at/bin
ProxyPassReverse /trainTracker/oebb http://zugradar.oebb.at/bin
```

