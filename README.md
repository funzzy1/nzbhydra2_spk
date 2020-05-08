It's the project to create the spk package to install nzbhydra2 (https://github.com/theotherp/nzbhydra2/) on Synology.

You need to download the spk file, and install it manually on your Synology package center.

This package is based on nzbhydra package by `adchevrier` from synocommunity.

FAQ
===

Project Dependencies:

- git
- python-2.7
- Java8


Could nzbhydra and nzbhydra2 be installed at the same time ?

Yes, nzbhydra use sc-nzbhydra user and nzbhydra group while nzbhydra2 use sc-nzbydra2 zn nzbhydra2.
Port number is 5075 for nzbhydra and 5076 for nzbhydra2


I have just installed the package or started the application, but I can't connect to my synology port 5076 ?

Please be patient, the web interface take some time to be reachable


Tests
=====

Tested on DSM 6.2 with Synology DS415play.

