[![Build Status](https://travis-ci.org/battlemidget/sosreport.png?branch=master)](https://travis-ci.org/battlemidget/sosreport)

This set of tools is designed to provide information to support organizations
in an extensible manner, allowing third parties, package maintainers, and
anyone else to provide plugins that will collect and report information that
is useful for supporting software packages.

This project is hosted at http://github.com/sosreport/sosreport For the latest
version, to contribute, and for more information, please visit there.

To access to the public source code repository for this project run:

```
git clone git://github.com/sosreport/sosreport.git
```

### Manual Installation  ###

```
to install locally (as root) ==> make install
to build an rpm ==> make rpm
to build a deb ==> make deb-unsign
to build a zipfile for use with jython ==> make zip
```

### Pre-built Packaging ###

Fedora/RHEL users install via yum:

```
yum install sos
```

Debian/Ubuntu users can install via PPA:

```
sudo add-apt-repository ppa:debugmonkeys/sosreport
sudo apt-get update
sudo apt-get install sosreport
```
