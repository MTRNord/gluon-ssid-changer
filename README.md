ssid-changer
============

Script to change the SSID when there is no suffic sufficient connection to the selected Gateway.

It is quite basic, it just checks the Quality of the Connection and decides if a change of the SSID is necessary.

Create a file "modules" with the following content in your <a href="https://github.com/ffac/site/tree/offline-ssid"> site directory:</a>

GLUON_SITE_FEEDS="ssidchanger"<br>
PACKAGES_SSIDCHANGER_REPO=https://github.com/MTRNord/gluon-ssid-changer.git<br>
PACKAGES_SSIDCHANGER_COMMIT=a8d29705db169df45e9885256971c85e7dae8ced<br>

With this done you can add the package gluon-ssid-changer to your site.mk

This skript is tested with Gluon 2015.2.1
