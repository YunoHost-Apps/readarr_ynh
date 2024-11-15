<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Readarr voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/readarr.svg)](https://ci-apps.yunohost.org/ci/apps/readarr/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/readarr.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/readarr.maintain.svg)

[![Readarr met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=readarr)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Readarr snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Readarr is an eBook and audiobook collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new books and will interface with clients and indexers to grab, sort, and rename them. It can also be configured to automatically upgrade the quality of existing files in the library when a better quality format becomes available. It does not manage comics or magazines.

**Geleverde versie:** 0.3.19.2437~ynh2

## Schermafdrukken

![Schermafdrukken van Readarr](./doc/screenshots/calendar.png)

## Documentatie en bronnen

- Officiele website van de app: <https://readarr.com/>
- Officiele beheerdersdocumentatie: <https://wiki.servarr.com/readarr/installation/linux>
- Upstream app codedepot: <https://github.com/Readarr/Readarr>
- YunoHost-store: <https://apps.yunohost.org/app/readarr>
- Meld een bug: <https://github.com/YunoHost-Apps/readarr_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/readarr_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
of
sudo yunohost app upgrade readarr -u https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
