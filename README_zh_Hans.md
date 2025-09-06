<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Readarr

[![集成程度](https://apps.yunohost.org/badge/integration/readarr)](https://ci-apps.yunohost.org/ci/apps/readarr/)
![工作状态](https://apps.yunohost.org/badge/state/readarr)
![维护状态](https://apps.yunohost.org/badge/maintained/readarr)

[![使用 YunoHost 安装 Readarr](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=readarr)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Readarr。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Readarr is an eBook and audiobook collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new books and will interface with clients and indexers to grab, sort, and rename them. It can also be configured to automatically upgrade the quality of existing files in the library when a better quality format becomes available. It does not manage comics or magazines.

**分发版本：** 0.3.19.2437~ynh2

## 截图

![Readarr 的截图](./doc/screenshots/calendar.png)

## 文档与资源

- 官方应用网站： <https://readarr.com/>
- 官方管理文档： <https://wiki.servarr.com/readarr/installation/linux>
- 上游应用代码库： <https://github.com/Readarr/Readarr>
- YunoHost 商店： <https://apps.yunohost.org/app/readarr>
- 报告 bug： <https://github.com/YunoHost-Apps/readarr_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/readarr_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
或
sudo yunohost app upgrade readarr -u https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
