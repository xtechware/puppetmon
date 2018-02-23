# Puppetmon Project

<a name="table-of-contents"></a>
## Table of Contents
=================

* [Overview](#overview)
* [General Setup Requirements](#general-setup-requirements)
* [Release Notes](#release-notes)

<a name="overview"></a>
## Overview

This project contains various tools to interact with the Puppetmaster server for troubleshooting and reporting purposes.

[Table of Contents](#table-of-contents)

<a name="general-setup-requirements"></a>
## General Setup Requirements

In order to use these tools you will need a RHEL 7 host with connectivity to the target Puppetmaster.

Some tools may have more stringent requirements, i.e. a working Puppet agent connected to the target Puppetmaster, access to the Puppetmaster access keys etc..
These additional requirements will be noted in the individual tool's respective documentation.

To configure the RHEL 7 host to run this tool:

* Login to the RHEL 7 host
* If not already installed, install git by running 'yum install git', enter 'y' to confirm installation
* Make whatever provisions are necessary for the host to access Github, e.g. set proxy environment variables http_proxy, https_proxy and no_proxy.
* Disable GIT SSL certificate verification by running 'export GIT_SSL_NO_VERIFY=false'
* Change to an appropriate directory to install the tool, it is suggested to use your own home directory and not root's
* Clone tooling repo locally by running 'git clone https://github.com/xtechware/puppetmon.git', if prompted enter a valid GIT user ID with access and password
* Change to tool directory by running 'cd puppetmon'

[Table of Contents](#table-of-contents)

<a name="release-notes"></a>
## Release Notes

Version: N/A  
Date: 2/22/2018+  
Author: Jerome Gudknecht  
Updates:
* Framing  out project

[Table of Contents](#table-of-contents)
