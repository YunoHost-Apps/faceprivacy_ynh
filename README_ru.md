<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# FacePrivacy для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/faceprivacy)](https://ci-apps.yunohost.org/ci/apps/faceprivacy/)
![Состояние работы](https://apps.yunohost.org/badge/state/faceprivacy)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/faceprivacy)

[![Установите FacePrivacy с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faceprivacy)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить FacePrivacy быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Face Privacy is a web application that makes it easy to blur faces and specific areas on photos, all entirely within the browser. It guarantees data confidentiality by processing all operations locally on the user's device, without downloading photos to external servers.

### Features

- Face blur
- Blurring of customised areas
- Completely local processing
- Export in different resolutions 
- Intuitive interface


**Поставляемая версия:** 1.0~ynh1

**Демо-версия:** <https://faceprivacy.forge.apps.education.fr/app/>

## Снимки экрана

![Снимок экрана FacePrivacy](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://faceprivacy.forge.apps.education.fr/app/>
- Репозиторий кода главной ветки приложения: <https://forge.apps.education.fr/faceprivacy/app>
- Магазин YunoHost: <https://apps.yunohost.org/app/faceprivacy>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/faceprivacy_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
или
sudo yunohost app upgrade faceprivacy -u https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
