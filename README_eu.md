<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# FacePrivacy YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/faceprivacy)](https://ci-apps.yunohost.org/ci/apps/faceprivacy/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/faceprivacy)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/faceprivacy)

[![Instalatu FacePrivacy YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faceprivacy)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek FacePrivacy YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Face Privacy is a web application that makes it easy to blur faces and specific areas on photos, all entirely within the browser. It guarantees data confidentiality by processing all operations locally on the user's device, without downloading photos to external servers.

### Features

- Face blur
- Blurring of customised areas
- Completely local processing
- Export in different resolutions 
- Intuitive interface


**Paketatutako bertsioa:** 2025.03.13~ynh1

**Demoa:** <https://faceprivacy.forge.apps.education.fr/app/>

## Pantaila-argazkiak

![FacePrivacy(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://faceprivacy.forge.apps.education.fr/app/>
- Jatorrizko aplikazioaren kode-gordailua: <https://forge.apps.education.fr/faceprivacy/app>
- YunoHost Denda: <https://apps.yunohost.org/app/faceprivacy>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/faceprivacy_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
edo
sudo yunohost app upgrade faceprivacy -u https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
