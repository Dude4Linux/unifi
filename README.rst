UniFi - Controller for Ubiquiti UniFi Access Points
===================================================

`UniFi`_ is a propritary application used by permission.

Description or Purpose
----------------------
.. Briefly describe what the appliance does 

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

Additional Features
-------------------
.. Add or remove additional features from the list below

- SSL support out of the box.
- `PHPMyAdmin`_ administration frontend for MySQL (listening on port
  12322 - uses SSL).
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Webmin modules for configuring Apache2, PHP, MySQL and Postfix.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**

.. Edit above to remove references to MySQL, phpMyAdmin, etc if not used in your appliance.  Add a line for additional application credentials, if any, set at first boot.

.. _UniFi: https://community.ubnt.com/t5/UniFi-Wireless/bd-p/UniFi
.. _TurnKey Core: http://www.turnkeylinux.org/core
