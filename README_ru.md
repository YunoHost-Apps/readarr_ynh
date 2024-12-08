<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Readarr для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/readarr)](https://ci-apps.yunohost.org/ci/apps/readarr/)
![Состояние работы](https://apps.yunohost.org/badge/state/readarr)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/readarr)

[![Установите Readarr с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=readarr)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Readarr быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Readarr is an eBook and audiobook collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new books and will interface with clients and indexers to grab, sort, and rename them. It can also be configured to automatically upgrade the quality of existing files in the library when a better quality format becomes available. It does not manage comics or magazines.

**Поставляемая версия:** 0.3.19.2437~ynh2

## Снимки экрана

![Снимок экрана Readarr](./doc/screenshots/calendar.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://readarr.com/>
- Официальная документация администратора: <https://wiki.servarr.com/readarr/installation/linux>
- Репозиторий кода главной ветки приложения: <https://github.com/Readarr/Readarr>
- Магазин YunoHost: <https://apps.yunohost.org/app/readarr>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/readarr_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/readarr_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
или
sudo yunohost app upgrade readarr -u https://github.com/YunoHost-Apps/readarr_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
