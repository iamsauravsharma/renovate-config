# renovate-config
Common Renovate config to be used for all iamsauravsharma hosted repo which are supported by renovatebot.

**Status:**

| Travis Build Status |
|:---:|
| [![Travis Build Status][build_badge]][build_link] |

**Project Info:**

| License | npm version |
| :---: | :---: |
| [![License: MIT][license_badge]][license_link] | [![Crate][npm_badge]][npm_link] |


### Supported Preset
| Preset List |
|:---:|
| [Default](#default) |
| [Bledding edge](#github) |


### Installation
No need for installation for using this configuration

### Usage
To configure configuration in resporitory use
The list of preset example configuration are: 

#### default
To use configuration published over npm registry
```json
{
  "extends": ["@iamsauravsharma"]
}
```
__OR__
```json
{
    "extends": ["@iamsauravsharma:default"]
}
```
Use of @iamsauravsharma symbolize for renovate as use of @iamsauravsharma/renovate-config as a configuration


#### github
To use configuration as latest github branch config and using bleeding edge
```json
{
  "extends": ["github>iamsauravsharma/renovate-config"]
}
```
__OR__
```json
{
    "extends": ["github>iamsauravsharma/renovate-config:default"]
}
```
Use of above config symbolize for renovate as use of https://github.com/iamsauravsharma/renovate-config as a configuration

[build_badge]: https://img.shields.io/travis/com/iamsauravsharma/renovate-config.svg?logo=travis
[build_link]: https://travis-ci.com/iamsauravsharma/renovate-config

[license_badge]: https://img.shields.io/github/license/iamsauravsharma/renovate-config.svg
[license_link]: LICENSE

[npm_badge]: https://img.shields.io/npm/v/@iamsauravsharma/renovate-config.svg?logo=npm
[npm_link]: https://www.npmjs.com/package/@iamsauravsharma/renovate-config
