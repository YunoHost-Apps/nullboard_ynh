# Nullboard for YunoHost

[![Integration level](https://dash.yunohost.org/integration/nullboard.svg)](https://dash.yunohost.org/appci/app/nullboard) ![](https://ci-apps.yunohost.org/ci/badges/nullboard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/nullboard.maintain.svg)  
[![Install Nullboard with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nullboard)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Nullboard quickly and simply on a YunoHost server.  
If you don’t have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Nullboard is a minimalist take on a kanban board / a task list manager, designed to be compact, readable and quick in use.

## Screenshots

![](https://camo.githubusercontent.com/700edd0af42b2fe7ca91961691d856e05bd1d9aeb7966b1da2478d7ccce863a5/68747470733a2f2f6e756c6c626f6172642e696f2f696d616765732f6e756c6c626f6172642d6578616d706c652d616c742e706e673f7a)

## Demo

* [Official demo](https://nullboard.io/preview)

## Documentation

 * Official documentation: https://nullboard.io/preview
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported? **No**
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/nullboard%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/nullboard/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/nullboard%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/nullboard/)

## Limitations

* :warning: Uses localStorage for storing boards/lists/notes, so be careful around clearing your cache.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/nullboard_ynh/issues
 * App website: https://nullboard.io/preview
 * Upstream app repository: https://github.com/apankrat/nullboard
 * YunoHost website: https://yunohost.org/

---

## Developers info

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/nullboard_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/nullboard_ynh/tree/testing --debug
or
sudo yunohost app upgrade nullboard -u https://github.com/YunoHost-Apps/nullboard_ynh/tree/testing --debug
```
