<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Readarr untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/readarr)](https://ci-apps.yunohost.org/ci/apps/readarr/)
![Status kerja](https://apps.yunohost.org/badge/state/readarr)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/readarr)

[![Pasang Readarr dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=readarr)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Readarr secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Readarr is an eBook and audiobook collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new books and will interface with clients and indexers to grab, sort, and rename them. It can also be configured to automatically upgrade the quality of existing files in the library when a better quality format becomes available. It does not manage comics or magazines.

**Versi terkirim:** 0.3.19.2437~ynh2

## Tangkapan Layar

![Tangkapan Layar pada Readarr](./doc/screenshots/calendar.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://readarr.com/>
- Dokumentasi admin resmi: <https://wiki.servarr.com/readarr/installation/linux>
- Depot kode aplikasi hulu: <https://github.com/Readarr/Readarr>
- Gudang YunoHost: <https://apps.yunohost.org/app/readarr>
- Laporkan bug: <https://github.com/YunoHost-Apps/readarr_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/readarr_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
atau
sudo yunohost app upgrade readarr -u https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
