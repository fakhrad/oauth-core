# oauth-core

[![npm Version][npm-image]][npm-url]
[![npm Downloads][downloads-image]][downloads-url]
[![Test Status][travis-image]][travis-url]
[![MIT Licensed][license-image]][license-url]
[![oauthjs Slack][slack-image]][slack-url]

Complete, compliant and well tested module for implementing an OAuth2 server in [Node.js](https://nodejs.org).


## Installation

```bash
npm install oauth-core
```

The *oauth-core* module is framework-agnostic but there are several officially supported wrappers available for popular HTTP server frameworks such as [Express](https://npmjs.org/package/express-oauth-server) and [Koa](https://npmjs.org/package/koa-oauth-server). If you're using one of those frameworks it is strongly recommended to use the respective wrapper module instead of rolling your own.


## Features

- Supports `authorization_code`, `client_credentials`, `refresh_token` and `password` grant, as well as *extension grants*, with scopes.
- Can be used with *promises*, *Node-style callbacks*, *ES6 generators* and *async*/*await* (using [Babel](https://babeljs.io)).
- Fully [RFC 6749](https://tools.ietf.org/html/rfc6749.html) and [RFC 6750](https://tools.ietf.org/html/rfc6749.html) compliant.
- Implicitly supports any form of storage, e.g. *PostgreSQL*, *MySQL*, *MongoDB*, *Redis*, etc.
- Complete [test suite](https://github.com/oauthjs/node-oauth-core/tree/master/test).


## Documentation

[Documentation](https://oauth-core.readthedocs.io) is hosted on Read the Docs.


## Examples

Most users should refer to our [Express](https://github.com/oauthjs/express-oauth-server/tree/master/examples) or [Koa](https://github.com/oauthjs/koa-oauth-server/tree/master/examples) examples.

Examples for v3 are yet to be made. 

## Upgrading from 2.x

This module has been rewritten using a promise-based approach, introducing changes to the API and model specification. v2.x is no longer supported.

Please refer to our [3.0 migration guide](https://oauth-core.readthedocs.io/en/latest/misc/migrating-v2-to-v3.html) for more information.


## Tests

To run the test suite, install dependencies, then run `npm test`:

```bash
npm install
npm test
```


[npm-image]: https://img.shields.io/npm/v/oauth-core.svg
[npm-url]: https://npmjs.org/package/oauth-core
[downloads-image]: https://img.shields.io/npm/dm/oauth-core.svg
[downloads-url]: https://npmjs.org/package/oauth-core
[travis-image]: https://img.shields.io/travis/oauthjs/node-oauth-core/master.svg
[travis-url]: https://travis-ci.org/oauthjs/node-oauth-core
[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
[license-url]: https://raw.githubusercontent.com/oauthjs/node-oauth-core/master/LICENSE
[slack-image]: https://img.shields.io/badge/slack-join-E01563.svg
[slack-url]: https://oauthjs.slack.com

