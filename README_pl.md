<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# FacePrivacy dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/faceprivacy)](https://ci-apps.yunohost.org/ci/apps/faceprivacy/)
![Status działania](https://apps.yunohost.org/badge/state/faceprivacy)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/faceprivacy)

[![Zainstaluj FacePrivacy z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faceprivacy)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację FacePrivacy na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

Face Privacy is a web application that makes it easy to blur faces and specific areas on photos, all entirely within the browser. It guarantees data confidentiality by processing all operations locally on the user's device, without downloading photos to external servers.

### Features

- Face blur
- Blurring of customised areas
- Completely local processing
- Export in different resolutions 
- Intuitive interface


**Dostarczona wersja:** 1.0~ynh1

**Demo:** <https://faceprivacy.forge.apps.education.fr/app/>

## Zrzuty ekranu

![Zrzut ekranu z FacePrivacy](./doc/screenshots/screenshot.png)

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://faceprivacy.forge.apps.education.fr/app/>
- Repozytorium z kodem źródłowym: <https://forge.apps.education.fr/faceprivacy/app>
- Sklep YunoHost: <https://apps.yunohost.org/app/faceprivacy>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/faceprivacy_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
lub
sudo yunohost app upgrade faceprivacy -u https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
