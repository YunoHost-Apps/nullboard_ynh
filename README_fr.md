# Nullboard pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/nullboard.svg)](https://dash.yunohost.org/appci/app/nullboard) ![](https://ci-apps.yunohost.org/ci/badges/nullboard.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/nullboard.maintain.svg)  
[![Installer Nullboard avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nullboard)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d’installer Nullboard rapidement et simplement sur un serveur YunoHost.  
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Nullboard est une version minimaliste d'un tableau Kanban/gestionnaire de liste de tâches, conçu pour être compact, lisible et rapide à utiliser. 

## Captures d’écran

![](https://camo.githubusercontent.com/700edd0af42b2fe7ca91961691d856e05bd1d9aeb7966b1da2478d7ccce863a5/68747470733a2f2f6e756c6c626f6172642e696f2f696d616765732f6e756c6c626f6172642d6578616d706c652d616c742e706e673f7a)

## Démo

* [Démo officielle](https://nullboard.io/preview)

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/nullboard%40%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/nullboard/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/nullboard%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/nullboard/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/nullboard_ynh/issues
 * Site de l'application : https://nullboard.io/preview
 * Dépôt de l’application principale : https://github.com/apankrat/nullboard
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/nullboard_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/nullboard_ynh/tree/testing --debug
ou
sudo yunohost app upgrade nullboard -u https://github.com/YunoHost-Apps/nullboard_ynh/tree/testing --debug
```
