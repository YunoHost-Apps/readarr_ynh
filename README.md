<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Readarr for YunoHost

[![Integration level](https://dash.yunohost.org/integration/readarr.svg)](https://ci-apps.yunohost.org/ci/apps/readarr/) ![Working status](https://ci-apps.yunohost.org/ci/badges/readarr.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/readarr.maintain.svg)

[![Install Readarr with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=readarr)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Readarr quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Readarr is an eBook and audiobook collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new books and will interface with clients and indexers to grab, sort, and rename them. It can also be configured to automatically upgrade the quality of existing files in the library when a better quality format becomes available. It does not manage comics or magazines.

**Shipped version:** 0.3.19.2437~ynh2

## Screenshots

![Screenshot of Readarr](./doc/screenshots/calendar.png)

## Documentation and resources

- Official app website: <https://readarr.com/>
- Official admin documentation: <https://wiki.servarr.com/readarr/installation/linux>
- Upstream app code repository: <https://github.com/Readarr/Readarr>
- YunoHost Store: <https://apps.yunohost.org/app/readarr>
- Report a bug: <https://github.com/YunoHost-Apps/readarr_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/readarr_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
or
sudo yunohost app upgrade readarr -u https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
