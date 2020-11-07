# Koel for YunoHost

[![Integration level](https://dash.yunohost.org/integration/koel.svg)](https://dash.yunohost.org/appci/app/koel) ![](https://ci-apps.yunohost.org/ci/badges/koel.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/koel.maintain.svg)  
[![Install koel with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=koel)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install koel quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Koel is a web-based personal audio streaming service written in Vue at the client side and Laravel
on the server side. Targeting web developers, Koel embraces some of the more modern web technologies – flexbox, audio and drag-and-drop API to name a few – to do its job.

**Shipped version:** 4.4.0

## Screenshots

![](https://docs.koel.dev/assets/img/showcase.0f8e8026.png)

## Demo

* [Official demo](https://demo.koel.dev/)

## Configuration

How to configure this app: From an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/koel%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/koel/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/koel%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/koel/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

**More info on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/YunoHost-Apps/koel_ynh/issues
 * App website: https://koel.dev/
 * Upstream app repository: https://github.com/koel/koel
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/koel_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/koel_ynh/tree/testing --debug
or
sudo yunohost app upgrade koel -u https://github.com/YunoHost-Apps/koel_ynh/tree/testing --debug
```
