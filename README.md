cobalt-raq-lcdshowip
====================

Cobalt Raq server LCD script that allow you to show your IP address and other interesting details about your device.

=====================
How to use
=====================

- login as root

- unzip lcd-shownew.zip

- cp /etc/rc.d/init.d/lcd-showip /etc/rc.d/init.d/lcd-showip.old

- if you use CobaltOs

	cat lcd-showip chmod > /etc/rc.d/init.d/lcd-showip 

- if you use CentOs

	cat lcd-showip.centos chmod > /etc/rc.d/init.d/lcd-showip