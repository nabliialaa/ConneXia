# ConneXia

ConneXia est un logiciel qui permet la gestion et l'optimisation des espaces de travail. Basé sur une architecture 3 tiers.

## Architecture

![](https://www.geonov.fr/fig/client-server/client-server-3-tiers-small.png)

## Pre requis Client
- une connexion internet stable
- un navigateur à jour

### Systèmes d'exploitation compatible

- Linux (Ubuntu, CentOs, Debian... ).
- Windows 7 et plus.
- MacOs version 10.13 et plus.
- iOS
- Android

## Pre requis Serveur
- XAMPP

## Installation sur Linux

```bash
1- Télécharger le package XAMPP pour Linux depuis le site officiel d'Apache
2- Accédez au dossier Téléchargements à l'aide de la commande suivante:
$ cd / home / [nom d'utilisateur] / Téléchargements
3- Exécutez la commande suivante à cet effet:
$ chmod 755 [nom du package]
- Exemple:
$ chmod 755 xampp-linux-x64-7.2.10-0-installer.run
Le package d'installation est maintenant sous une forme exécutable.

4- Confirmer l'autorisation d'exécution :
 $ ls -l [nom du package]
 -Exemple :
 $ ls -l xampp-linux-x64-7.2.10-0-installer.run
 
5- Lancez l'assistant de configuration :
 $ sudo ./[package name]
 - Exemple :
 sudo ./xampp-linux-7.2.10-0-installer.run
 
6- Suivre les étapes d'installation 
 
7- Lancez XAMPP via le terminal :
 $ sudo / opt / lampp / lampp start
 
8- Vérifier l'installation
 Après avoir installé XAMPP sur votre système Linux, il est recommandé de vérifier l'installation. 
 Pour ce faire, entrez l'URL suivante dans votre navigateur :
 http: // localhost 
```

## Installation sur Windows
1- Télécharger le package XAMPP pour Linux depuis le site officiel d'Apache
2- Suivre les étapes d'installation
3- Lancer XAMPP 
4- Cliquer sur start pour Apache et Mysql

## Installation sur MacOS
1- Télécharger le package XAMPP pour Linux depuis le site officiel d'Apache
2- Ouvrez le fichier téléchargé (l'image DMG).
3- Faites glisser et déposez le dossier XAMPP dans votre dossier Applications 
4- Lancer XAMPP
Pour démarrer XAMPP, ouvrez simplement XAMPP Control (en accédant à /Applications/XAMPP/manager-osx.app dans le Finder ) et démarrez Apache et MySQL dans l' onglet Gérer les serveurs .

5- Si MySQL ne démarre pas :
Si votre serveur MySQL ne démarre pas, vous devrez peut-être définir les autorisations pour celui-ci à l'aide de Terminal avec cette commande:
```Bash
chmod -R 777 /Applications/XAMPP/xamppfiles/var
```
6- Test de votre installation OSX XAMPP
Dans votre navigateur Web, accédez à http: // localhost .
Vous devriez voir la page de démarrage de XAMPP
![](https://s3.amazonaws.com/webucator-how-tos/2080.png)

## Usage


- Connexia importation RH : 
![](https://i.ibb.co/X3nKHrf/Untitled-3.png)
- SSO (OPTIONAL)
![](https://i.ibb.co/fHxSz7P/sso.png)

- Utilisation du plugin autocad (GINCAD)
dans le cas d’une gestion internalisé des plans, l’installation du plugin autocad (GINCAD) est necessaire
![](https://i.ibb.co/G5tFCHz/export.png)

![](https://i.ibb.co/nz9JN5q/download.png)





## Contribution


## License
[MIT](https://choosealicense.com/licenses/mit/)
