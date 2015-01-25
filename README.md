# ACIScripts

# Description
This is a holding place for scrips created around ACI, the plan is to merge them with the main Cisco ACI repo [http://datacenter.github.io/acitoolkit/](http://datacenter.github.io/acitoolkit/).

# Installation

## Environment

Required

* Python 2.7+
* [setuptools package](https://pypi.python.org/pypi/setuptools)
* [requests library](http://docs.python-requests.org/en/latest/user/install/#install)
* [websocket-client library](https://github.com/liris/websocket-client)
* [acitoolkit](http://datacenter.github.io/acitoolkit/

## Downloading

Clone the repository

    git clone https://github.com/datacenter/acitoolkit.git

# Scripts
| Name          | Description             |
| ------------- |:-------------:| -----:|
| credentials.py  | Contains the login details and some other variables used by the other scripts |
| clone_tenant.py | Script for managing tenants, this will allow users to clone Tenant config on APIC, pushing to github etc. |
| push_or_pull_github.py | Pushing and Pulling APIC config to GutHub |
