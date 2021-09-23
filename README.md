# ShipStation Magento Extension
The ShipStation (`Auctane_Api`) module ported to GitHub from Magento Connect.

## Changelog

2.0.0 : Shipstation has moved on to m2 connection, but clients that use OpenMage will see authentication breaking. An update here to use teh new m2 TOKEN onto the M1 (openmage) code.

1.3.28: If a configurable child selection was sent to shipstation (not the main parent), teh SHIP callback did not mark that line item / row as shipped.
      : This has been fixed and the paent is now marked shipped allowing order to complete.

From original forked repo:

I have extended it only to provide a `modman` and `composer.json` file for convenient
loading as a project dependency.

## Disclaimer
This module was developed by ShipStation. I am publishing this work publicly on GitHub
as an alternative method to installation by Magento Connect. Please do not submit pull
requests for this module. If you wish to make customizations, use your own forks
indefinitely.
