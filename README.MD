# DoxyProxy Client Lib


![Go report card](https://goreportcard.com/badge/github.com/syrinsecurity/doxyproxy)
[![Build Status](https://travis-ci.org/syrinsecurity/doxyproxy.svg?branch=master)](https://travis-ci.org/syrinsecurity/doxyproxy)
[![GoDoc](https://godoc.org/github.com/syrinsecurity/doxyproxy?status.svg)](https://godoc.org/github.com/syrinsecurity/doxyproxy)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/syrinsecurity/doxyproxy/graphs/commit-activity)
[![License](https://img.shields.io/github/license/syrinsecurity/doxyproxy.svg)](https://github.com/syrinsecurity/doxyproxy/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/syrinsecurity/doxyproxy.svg)](https://GitHub.com/syrinsecurity/doxyproxy/releases/)
[![GitHub issues](https://img.shields.io/github/issues/syrinsecurity/doxyproxy.svg)](https://GitHub.com/syrinsecurity/doxyproxy/issues/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)


<!-- <img align="right" src="./.github/images/logo.png"> -->

This is a client lib for DoxyProxy.

DoxyProxy is a fast layer 4 **reverse proxy** supporting both; UDP and TCP.
The key features of DoxyProxy is the built in API which allows the remote origin
to **access the clients true IP address**, instead of the proxy's IP.
- Enhance security
- Hide your origin
- Protect your self origin for DDOS attacks

DoxyProxy is built for flexibility and speed, not just in raw performance but also in setup.
Use a simple json file to configure a ProxiedHost.
Features include:
- Limit connections per IP
- DualStack lookup
- Domain support
- IPv4, IPv6
- Configurable IP version switching handled by the proxy
- Force IPv6 or IPv4 (or allow all)
- Fail over IP
- Blacklist IP addresses
- Blacklist CIDRs (ip ranges)
- Whitelist IP addresses
- Whitelist CIDRs (ip ranges)

## Install

> go get github.com/syrinsecurity/doxyproxy