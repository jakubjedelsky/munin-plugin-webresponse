munin plugin: webresponse
=====================

USAGE
-----
`webresponse [config] [autoconfig]`

DESCRIPTION
-----------
A simple Munin plugin to graph a webpage response in seconds.

You need to set url in plugin-conf.d. For `yahoo.com` it can be:

```
[webresponse]
env.url yahoo.com
```

If there is not any variable, `google.com` is used.

LICENSE
-------
This script is in the public domain, free from copyrights or restrictions.

COMMENT
-------
I should send a pull request to [official munin repoitory](https://github.com/munin-monitoring/contrib) and I'll do it. Later. Maybe.
