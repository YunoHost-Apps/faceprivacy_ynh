<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# FacePrivacy untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/faceprivacy)](https://ci-apps.yunohost.org/ci/apps/faceprivacy/)
![Status kerja](https://apps.yunohost.org/badge/state/faceprivacy)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/faceprivacy)

[![Pasang FacePrivacy dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faceprivacy)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang FacePrivacy secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Face Privacy is a web application that makes it easy to blur faces and specific areas on photos, all entirely within the browser. It guarantees data confidentiality by processing all operations locally on the user's device, without downloading photos to external servers.

### Features

- Face blur
- Blurring of customised areas
- Completely local processing
- Export in different resolutions 
- Intuitive interface


**Versi terkirim:** 2025.03.13~ynh1

**Demo:** <https://faceprivacy.forge.apps.education.fr/app/>

## Tangkapan Layar

![Tangkapan Layar pada FacePrivacy](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://faceprivacy.forge.apps.education.fr/app/>
- Depot kode aplikasi hulu: <https://forge.apps.education.fr/faceprivacy/app>
- Gudang YunoHost: <https://apps.yunohost.org/app/faceprivacy>
- Laporkan bug: <https://github.com/YunoHost-Apps/faceprivacy_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
atau
sudo yunohost app upgrade faceprivacy -u https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
