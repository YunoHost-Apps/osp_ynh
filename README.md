<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Open Streaming Platform for YunoHost

[![Integration level](https://dash.yunohost.org/integration/osp.svg)](https://dash.yunohost.org/appci/app/osp) ![Working status](https://ci-apps.yunohost.org/ci/badges/osp.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/osp.maintain.svg)  
[![Install Open Streaming Platform with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=osp)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Open Streaming Platform quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Explain in *a few (10~15) words* the purpose of the app or what it actually does (it is meant to give a rough idea to users browsing a catalog of 100+ apps)

**Shipped version:** 0.9.6~ynh1

**Demo:** https://demo.openstreamingplatform.com/

## Screenshots

![Screenshot of Open Streaming Platform](./doc/screenshots/screenshot.png)

## Disclaimers / important information

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentation and resources

* Official app website: <https://openstreamingplatform.com/>
* Official user documentation: <https://yunohost.org/apps>
* Official admin documentation: <https://wiki.openstreamingplatform.com>
* Upstream app code repository: <https://gitlab.com/Deamos/flask-nginx-rtmp-manager>
* YunoHost documentation for this app: <https://yunohost.org/app_osp>
* Report a bug: <https://github.com/YunoHost-Apps/osp_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/osp_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/osp_ynh/tree/testing --debug
or
sudo yunohost app upgrade osp -u https://github.com/YunoHost-Apps/osp_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
