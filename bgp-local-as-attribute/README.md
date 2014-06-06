Configuring a Local AS for EBGP Sessions
===========

This example is described in detail in the following document:
http://www.juniper.net/techpubs/en_US/release-independent/nce/information-products/topic-collections/nce/bgp-local-as/bgp-local-as-configuring.pdf

It specifically applies to the section "Configuring a Local AS for EBGP Sessions on page 5 of the pdf.


Notes
-----

This Template differs from the documentation in that all interfaces configurations are based on unit 0.  This is because unless you turn on vlan-tagging (on SRX/M/J) or vlan-tagging/flexible-ethernet-services on MX units other than 0 are not supported in Junos on ethernet interfaces.

Usage
-----

sh
python bgp-local-as-attrib.py

