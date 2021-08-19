# ArchiveBox pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/example.svg)](https://dash.yunohost.org/appci/app/example) ![](https://ci-apps.yunohost.org/ci/badges/example.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/example.maintain.svg)  
[![Installer ArchiveBox avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=example)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer ArchiveBox rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble



**Version incluse :** 1.0~ynh1

**Démo :** https://archivebox.io/

## Captures d'écran

![](./doc/screenshots/screenshot_archivebox1.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * required to be run at the base path / , subpaths not yet supported
    * currently only tested on amd64
    * haven't yet implemented single-sign or LDAP integration 

* Other infos that people should be aware of, such as:
    * nothing comes to mind 

## Documentations et ressources

* Site officiel de l'app : https://archivebox.io/
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : https://yunohost.org/packaging_apps
* Dépôt de code officiel de l'app : https://github.com/ArchiveBox/ArchiveBox
* Documentation YunoHost pour cette app : https://yunohost.org/app_example
* Signaler un bug : https://github.com/YunoHost-Apps/example_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/example_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
ou
sudo yunohost app upgrade example -u https://github.com/YunoHost-Apps/example_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps