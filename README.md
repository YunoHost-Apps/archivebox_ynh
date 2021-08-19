# ArchiveBox Yunohost Package

[![Integration level](https://dash.yunohost.org/integration/archivebox.svg)](https://dash.yunohost.org/appci/app/archivebox) ![](https://ci-apps.yunohost.org/ci/badges/archivebox.status.svg)  ![](https://ci-apps.yunohost.org/ci/badges/archivebox.maintain.svg)
[![Install archivebox with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=archivebox)


> *This package allows you to install archivebox quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

[ArchiveBox](https://archivebox.io/) is a powerful, self-hosted internet archiving solution to collect, save, and view sites you want to preserve offline.

**Shipped version:** 1.0~ynh1

**Demo:** https://archivebox.commoninternet.net

# Important Points To Read Before Installing

1. ArchiveBox require a dedicated domain with no subpath to work, eg. yourdomain.tld or archivebox.yourdomain.tld

## Screenshots


   ![](./doc/screenshots/screenshot_archivebox1.png)


## Disclaimers

    * required to be run at the base path / , subpaths not yet supported
    * currently only tested on amd64
    * haven't yet implemented single-sign on or LDAP integration 
    
## Documentation and resources

* Official app website: https://archivebox.io
* Official user documentation: https://yunohost.org/apps
* Official admin documentation: https://yunohost.org/packaging_apps
* Upstream app code repository:  https://github.com/ArchiveBox/ArchiveBox
* YunoHost documentation for this app: https://yunohost.org/app_archivebox
* Report a bug: https://github.com/YunoHost-Apps/archivebox_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/archivebox_ynh/tree/testing).

To try the testing branch, please proceed like this:
```
sudo yunohost app install https://github.com/YunoHost-Apps/archivebox_ynh/tree/testing --debug
or
sudo yunohost app upgrade archivebox -u https://github.com/YunoHost-Apps/archivebox_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps
