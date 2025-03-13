<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# FacePrivacy for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/faceprivacy)](https://ci-apps.yunohost.org/ci/apps/faceprivacy/)
![Working status](https://apps.yunohost.org/badge/state/faceprivacy)
![Maintenance status](https://apps.yunohost.org/badge/maintained/faceprivacy)

[![Install FacePrivacy with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faceprivacy)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install FacePrivacy quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Face Privacy is a web application that makes it easy to blur faces and specific areas on photos, all entirely within the browser. It guarantees data confidentiality by processing all operations locally on the user's device, without downloading photos to external servers.

### Features

- Face blur
- Blurring of customised areas
- Completely local processing
- Export in different resolutions 
- Intuitive interface


**Shipped version:** 2025.03.13~ynh1

**Demo:** <https://faceprivacy.forge.apps.education.fr/app/>

## Screenshots

![Screenshot of FacePrivacy](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official app website: <https://faceprivacy.forge.apps.education.fr/app/>
- Upstream app code repository: <https://forge.apps.education.fr/faceprivacy/app>
- YunoHost Store: <https://apps.yunohost.org/app/faceprivacy>
- Report a bug: <https://github.com/YunoHost-Apps/faceprivacy_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
or
sudo yunohost app upgrade faceprivacy -u https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
