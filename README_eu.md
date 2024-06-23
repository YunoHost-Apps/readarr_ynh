<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Readarr YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/readarr.svg)](https://dash.yunohost.org/appci/app/readarr) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/readarr.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/readarr.maintain.svg)

[![Instalatu Readarr YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=readarr)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Readarr YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Readarr is an eBook and audiobook collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new books and will interface with clients and indexers to grab, sort, and rename them. It can also be configured to automatically upgrade the quality of existing files in the library when a better quality format becomes available. It does not manage comics or magazines.

**Paketatutako bertsioa:** 0.3.19.2437~ynh1

## Pantaila-argazkiak

![Readarr(r)en pantaila-argazkia](./doc/screenshots/calendar.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://readarr.com/>
- Administratzaileen dokumentazio ofiziala: <https://wiki.servarr.com/readarr/installation/linux>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Readarr/Readarr>
- YunoHost Denda: <https://apps.yunohost.org/app/readarr>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/readarr_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/readarr_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
edo
sudo yunohost app upgrade readarr -u https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
