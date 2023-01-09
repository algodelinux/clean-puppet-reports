clean-puppet-reports
====================

Overview
--------

This program cleans old puppet reports.


Installing
----------

You can install it simply running these commands on your puppetmaster:

```
   wget --no-check-certificate -O /usr/local/sbin/clean-puppet-reports https://raw.githubusercontent.com/algodelinux/clean-puppet-reports/main/clean-puppet-reports
   chmod 755 /usr/local/sbin/clean-puppet-reports
```

Using
----------

You can use it without parameters an clean nodes older than predefined days:

```
   clean-puppet-reports
```

Or specify maximun number days:

```
   clean-puppet-reports 60
```

## Authors

- Esteban M. Navas Martín (algodelinux@gmail.com)
