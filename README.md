# ATT&CK Python Client

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OTRF/ATTACK-Python-Client/master)
[![Open_Threat_Research Community](https://img.shields.io/badge/Open_Threat_Research-Community-brightgreen.svg)](https://twitter.com/OTR_Community)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

A Python module to access up to date ATT&CK content available in STIX via public TAXII server. This project leverages the python classes and functions of the [cti-python-stix2](https://github.com/oasis-open/cti-python-stix2) and [cti-taxii-client](https://github.com/oasis-open/cti-taxii-client) libraries developed by MITRE.

## Goals

* Provide an easy way to access and interact with up to date ATT&CK content available in STIX via public TAXII server
* Allow security analysts to quickly explore ATT&CK content and apply it in their daily operations
* Allow the integration of ATT&Ck content with other platforms to host up to date information from the framework
* Help security analysts during the transition from the ATT&CK MediaWiki API to the STIX/TAXII 2.0 API
* Learn STIX2 and TAXII Client Python libraries

## Documentation

## [https://attackcti.com](https://attackcti.com)

## Current Status: Production/Stable

The project is currently in a Production/Stable stage, which means that the current main functions are more stable. I would love to get your feedback to make it a better project.

## Resources

* [MITRE CTI](https://github.com/mitre/cti)
* [OASIS CTI TAXII Client](https://github.com/oasis-open/cti-taxii-client)
* [OASIS CTI Python STIX2](https://github.com/oasis-open/cti-python-stix2)
* [MITRE ATT&CK Framework](https://attack.mitre.org/wiki/Main_Page)
* [ATT&CK MediaWiki API](https://attack.mitre.org/wiki/Using_the_API)
* [Invoke-ATTACKAPI](https://github.com/Cyb3rWard0g/Invoke-ATTACKAPI)
* [Mitre-Attack-API](https://github.com/annamcabee/Mitre-Attack-API)

### Requirements

Python 3+

### Installation

You can install it via PIP:

```
pip install attackcti
```

Or you can also do the following:

```
git clone https://github.com/OTRF/ATTACK-Python-Client
cd ATTACK-Python-Client
pip install .
```

## Author

* Roberto Rodriguez [@Cyb3rWard0g](https://twitter.com/Cyb3rWard0g)

## Official Committers

* Jose Luis Rodriguez [@Cyb3rPandaH](https://twitter.com/Cyb3rPandaH)
