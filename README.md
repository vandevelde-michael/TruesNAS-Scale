# TruesNAS-Scale

## Description

TrueNas-Scale est une solution de stockage en réseau open-source conçue pour offrir une gestion avancée des données, une haute disponibilité et une évolutivité optimale. Ce projet vise à fournir une plateforme robuste et flexible pour les entreprises et les particuliers souhaitant gérer efficacement leurs données.

## Table des Matières

- [Documentation](#documentation).
- [Installation](#installation).
- [Utilisation](#utilisation).
- [Contact](#contact).

## Documentation

Pour une documentation détaillée, veuillez consulter notre [page Notion](https://drive.google.com/file/d/1MzYY7SDqee51eFPt1YgNQkfK2pvCUNlh/view?usp=sharing)

## Installation de TrueNas Scale

Nous téléchargeons la dernieère version stable sur le site officiel :  (TrueNAS SCALE 24.10.2)

https://www.truenas.com/download-truenas-scale/

Suivez ces étapes pour installer TrueNas Scale sur votre matériel.

### Prérequis

- **Matériel** : Un serveur ou une machine compatible avec TrueNas Scale. Vérifiez les exigences matérielles minimales sur le site officiel de TrueNas.
- **Média d'Installation** : Une clé USB ou un DVD pour créer le support d'installation.
- **Accès Internet** : Pour télécharger les mises à jour et les paquets nécessaires.

### Étape 1 : Télécharger TrueNas Scale

1. **Téléchargez l'image ISO** :
   - Rendez-vous sur le [site officiel de TrueNas](https://www.truenas.com/truenas-scale/).
   - Téléchargez la dernière version de TrueNas Scale en format ISO.

### Étape 2 : Créer le Support d'Installation

1. **Utilisez un outil de création de support d'installation** :
   - Pour une clé USB, utilisez un outil comme [Rufus](https://rufus.ie/) (Windows) ou [balenaEtcher](https://www.balena.io/etcher/) (Windows, macOS, Linux) pour créer une clé USB bootable avec l'image ISO téléchargée.
   - Pour un DVD, gravez l'image ISO sur un disque vierge à l'aide d'un logiciel de gravure.

### Étape 3 : Installer TrueNas Scale

1. **Démarrer à partir du support d'installation** :
   - Insérez la clé USB ou le DVD dans le serveur cible.
   - Redémarrez le serveur et accédez au menu de démarrage (souvent en appuyant sur une touche comme F2, F12, DEL ou ESC pendant le démarrage).
   - Sélectionnez le support d'installation comme périphérique de démarrage.

2. **Suivre l'assistant d'installation** :
   - Une fois le démarrage effectué, vous verrez l'écran d'installation de TrueNas Scale.
   - Suivez les instructions à l'écran pour sélectionner le disque de destination et configurer les paramètres de base (comme le nom d'hôte, le mot de passe administrateur, etc.).

3. **Finaliser l'installation** :
   - Après avoir configuré les paramètres initiaux, l'installation commencera. Cela peut prendre quelques minutes.
   - Une fois l'installation terminée, retirez le support d'installation et redémarrez le serveur.

### Étape 4 : Configuration Initiale

1. **Accéder à l'interface Web** :
   - Après le redémarrage, notez l'adresse IP affichée sur l'écran de votre serveur.
   - Ouvrez un navigateur web sur un autre ordinateur et entrez l'adresse IP dans la barre d'adresse pour accéder à l'interface Web de TrueNas Scale.

2. **Configurer le stockage et les services** :
   - Connectez-vous avec le nom d'utilisateur et le mot de passe que vous avez configurés.
   - Utilisez l'interface Web pour configurer vos pools de stockage, partager des fichiers, et activer les services nécessaires (comme SMB, NFS, etc.).

### Étape 5 : Mises à Jour et Maintenance

1. **Vérifier les mises à jour** :
   - TrueNas Scale vous informera des mises à jour disponibles via l'interface Web. Assurez-vous de les appliquer régulièrement pour bénéficier des dernières fonctionnalités et correctifs de sécurité.

---

Ces étapes devraient vous guider à travers l'installation de TrueNas Scale. Si vous avez des questions spécifiques ou des besoins particuliers, n'hésitez pas à demander !

## Utilisation

### **Cas d’usage : Serveur multimédia à domicile**  

Un utilisateur installe **TrueNAS SCALE** sur un serveur maison pour :  
✅ Stocker et gérer sa bibliothèque de films, séries et musiques  
✅ Héberger **Plex** ou **Jellyfin** pour le streaming sur TV et appareils  
✅ Accéder aux fichiers à distance via **Nextcloud**  
✅ Sécuriser ses données avec **ZFS et snapshots automatiques**  

Résultat : Un **NAS puissant et fiable**, idéal pour centraliser et diffuser du contenu multimédia chez soi.

Pour aller plus loin , nous avons choisit d'installer un emulateur 'Batocera Linux"
https://batocera.org/download
apres l'avoir telecharger sur le site officiel, (ne pas se tromper de version) nous avons procéder a differentes changfement de la configuation : 
ajout de memoire vive sur la machine vkm true nas, passsage a 10Go

attention a la virtualisation imbriqué qui peuttposer probleme dans ce cas la : 

cmd en mode administrateur : (important)
"bcdedit /set hypervisorlaunchtype off"
ensuite cmd fonction avancées decocher hyper v , virtualisation

rdmarrage imperatif


## Contact

-michael.vandevelde@laplateforme.io

-etienne.verschuere@laplateforme.io

-bastien.llorca@laplateforme.io

-frederic.perry@laplateforme.io
