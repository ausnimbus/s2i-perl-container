# Perl (SCL) S2I Docker images

[![Build Status](https://travis-ci.org/ausnimbus/s2i-perl-scl.svg?branch=master)](https://travis-ci.org/ausnimbus/s2i-perl-scl)

This repository contains the source for building various versions of
the Perl application as a reproducible Docker image
[source-to-image](https://github.com/openshift/source-to-image)
to be run on [AusNimbus](https://www.ausnimbus.com.au/).

Images are built with Perl RPM packages from SCL.
The resulting image can be run using [Docker](http://docker.io).

## Versions

The versions currently supported are:

- 5.16
- 5.20
- 5.24
