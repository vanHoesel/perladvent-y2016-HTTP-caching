# Perl Advent - 2016 - HTTP-caching
Client Server demo for REST api's with HTTP Caching (RFC 7234 compliant)

This repo will contain (workinmg) demo's for a REST end-point written in Dancer2 and a LWP::UserAgent based client.

These demo's are specifically written around HTTP Caching as described in RFC 7234.
It will demonstrate how a Dancer2 application can utilise some plugins to help setting the right response headers that play a role.

- eTag
- Last-Modified
- Vary
- Cache-Control

It also will highlight the problems in existing modules that try to help by creating some kind off bad caching implementation.
Finally it will show a proper LWP::UserAgent demo that does not suffer from the before mentioned problems and does what the RFC expets us to do.

