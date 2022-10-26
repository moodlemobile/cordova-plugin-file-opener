# cordova-plugin-file-opener (fork)

This is a fork of `cordova-plugin-file-opener2` by [Moodle HQ](https://moodle.com/). If you are looking for the documentation, you can read the original at [pwlin/cordova-plugin-file-opener2](https://github.com/pwlin/cordova-plugin-file-opener2).

## Modifications from the original

We created this fork because we needed to include the following modifications in [our mobile application](https://github.com/moodlehq/moodleapp):

| PR | Description |
| -- | ----------- |
| [#330](https://github.com/pwlin/cordova-plugin-file-opener2/pull/330) | fix(#329): removed 'REQUEST_INSTALL_PACKAGES' android permission |

You can see all the changes here: [f22bbef...moodlemobile:v3.0.5-moodle.1](https://github.com/pwlin/cordova-plugin-file-opener2/compare/f22bbef0023a9db8d04a397b444cf61667db67f7...moodlemobile:v3.0.5-moodle.1)

## Installation

You can install this package using the [original installation instructions](https://github.com/pwlin/cordova-plugin-file-opener2#installation), but installing this package instead:

```sh
cordova plugin add @moodlehq/cordova-plugin-file-opener@3.0.5-moodle.1
```
