<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# FacePrivacy pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/faceprivacy)](https://ci-apps.yunohost.org/ci/apps/faceprivacy/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/faceprivacy)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/faceprivacy)

[![Installer FacePrivacy avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=faceprivacy)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer FacePrivacy rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Face Privacy est une application web qui permet de flouter facilement les visages et les zones spécifiques sur les photos, le tout entièrement dans le navigateur. Elle garantit la confidentialité des données en traitant toutes les opérations localement sur l'appareil de l'utilisateur, sans téléchargement de photos sur des serveurs externes.

### Fonctionnalités

- Floutage des visages
- Floutage de zones personnalisées
- Traitement entièrement local
- Exportation en différentes résolutions 
- Interface intuitive


**Version incluse :** 1.0~ynh1

**Démo :** <https://faceprivacy.forge.apps.education.fr/app/>

## Captures d’écran

![Capture d’écran de FacePrivacy](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://faceprivacy.forge.apps.education.fr/app/>
- Dépôt de code officiel de l’app : <https://forge.apps.education.fr/faceprivacy/app>
- YunoHost Store : <https://apps.yunohost.org/app/faceprivacy>
- Signaler un bug : <https://github.com/YunoHost-Apps/faceprivacy_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
ou
sudo yunohost app upgrade faceprivacy -u https://github.com/YunoHost-Apps/faceprivacy_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
