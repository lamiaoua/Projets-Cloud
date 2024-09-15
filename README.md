# Projets-Cloud



# Projet1 : Mise en place d'un Cloud PaaS Privé avec OpenShift
**Description du projet**

Ce projet consiste à déployer et à exploiter une solution Cloud PaaS (Platform as a Service) privée en utilisant OpenShift, une plateforme open source conçue pour héberger et gérer des applications dans des conteneurs. L'objectif est de créer un environnement privé de cloud computing qui permet aux développeurs de déployer, tester et gérer facilement leurs applications tout en automatisant une grande partie des processus de gestion d'infrastructure.

Le projet se déroule en plusieurs étapes, depuis la configuration initiale du système jusqu'au déploiement d'applications sur OpenShift. Voici un aperçu des principales étapes :

1. **Mise à jour du système** : Cette première étape garantit que le système est à jour et prêt pour l'installation des composants nécessaires, notamment Docker, qui est essentiel pour la gestion des conteneurs sur OpenShift.

2. **Installation de Docker CE** : Docker est installé pour créer, gérer et exécuter des conteneurs, une composante clé de l'architecture OpenShift.

3. **Téléchargement d'OpenShift Origin** : OpenShift Origin (maintenant appelé OKD) est la distribution open source de Red Hat OpenShift. L'installation de cette version permet de démarrer un cluster OpenShift localement.

4. **Démarrage du Cluster OpenShift** : Une fois OpenShift installé, le cluster est démarré. Cela met en place l'infrastructure nécessaire pour héberger des applications, gérer les conteneurs et orchestrer les services.

5. **Création d’un projet sur OpenShift** : Un projet est une manière d'organiser les ressources dans OpenShift. Ici, les utilisateurs créent un environnement dédié où ils peuvent déployer leurs applications et gérer les services associés.

6. **Accès à la console Web d'OpenShift** : OpenShift offre une interface graphique via une console web, permettant de surveiller et de gérer les projets et applications de manière intuitive.

7. **Déploiement d'applications sur OpenShift** : Dans cette étape, l'utilisateur déploie une application sur le cluster OpenShift. Ce processus est automatisé grâce à des templates et des configurations prédéfinies.

8. **Vérification de l'accès externe** : Enfin, l'application déployée est testée pour vérifier qu'elle est accessible de l'extérieur, assurant ainsi que le déploiement est fonctionnel et que l'application est prête à être utilisée.

**Objectif du projet** : Fournir un environnement de développement cloud privé basé sur OpenShift pour héberger et gérer des applications conteneurisées, offrant ainsi un contrôle et une flexibilité accrus par rapport aux solutions PaaS publiques.

# Projet2 : Mise en place d'un Cloud IaaS Privé avec OpenStack

**Description du projet : Mise en place d'un Cloud IaaS Privé avec OpenStack**

Ce projet consiste à déployer et exploiter une solution de Cloud IaaS (Infrastructure as a Service) privée en utilisant OpenStack, une plateforme open source permettant de créer et de gérer des infrastructures cloud privées et publiques. OpenStack offre la possibilité de gérer des ressources virtuelles telles que des machines virtuelles, des réseaux, des volumes de stockage et des images de manière dynamique et automatisée.

### Objectifs du projet :
L’objectif principal est de créer un cloud privé en configurant et en administrant une infrastructure OpenStack. Cela permettra aux utilisateurs de provisionner des ressources informatiques à la demande, comme dans un cloud public, tout en conservant un contrôle total sur l'infrastructure sous-jacente.

### Déroulement du projet :
Le projet se déroule en deux parties principales :

#### 1. **Mise en place d’un Cloud IaaS privé avec OpenStack** :
Dans cette première étape, l’objectif est de déployer l’infrastructure OpenStack qui servira de base à la création et à la gestion de machines virtuelles, de réseaux et de stockage. Cela comprend :

- **Installation d’OpenStack** : Installation et configuration d'OpenStack sur des serveurs physiques ou virtuels pour créer l’infrastructure de base.
- **Configuration des composants de base** : Cela inclut la mise en place des services nécessaires comme Nova (pour la gestion des machines virtuelles), Neutron (pour le réseau), Keystone (pour l’authentification et la gestion des utilisateurs), Glance (pour les images des machines), et Cinder (pour le stockage).

#### 2. **Exploitation de la solution Cloud créée avec OpenStack** :
Cette partie est axée sur l’utilisation et l’administration du cloud créé, avec une série d’objectifs pratiques :

- **Création d’un projet** : Un projet dans OpenStack est une unité organisationnelle permettant de regrouper des utilisateurs, des machines virtuelles et des réseaux.
- **Manipulation des quotas** : Limitation des ressources (CPU, RAM, stockage, etc.) attribuées à chaque projet ou utilisateur.
- **Création d’un utilisateur et affectation à un projet** : Gestion des accès utilisateurs en leur attribuant des rôles spécifiques au sein d’un projet.
- **Création d’un réseau** : Configuration de réseaux internes pour les instances (machines virtuelles) à l’intérieur du cloud.
- **Ajout d’un routeur Internet** : Permettre aux instances de se connecter à l’Internet public via un routeur configuré dans OpenStack.
- **Création d’une image** : Gestion des images de machines virtuelles (systèmes d’exploitation préconfigurés) pour le déploiement rapide des instances.
- **Création d’un groupe de sécurité et configuration des règles** : Gestion des règles de sécurité réseau (firewall) pour contrôler les accès entrants et sortants vers les instances.
- **Création d’une paire de clés** : Génération de clés SSH pour permettre des connexions sécurisées aux instances sans mot de passe.
- **Création des instances** : Déploiement des machines virtuelles (instances) qui utiliseront les ressources du cloud.

### Objectif final :
À l’issue de ce projet, une infrastructure cloud privée complète sera opérationnelle, capable d’héberger et de gérer des machines virtuelles, des réseaux et des volumes de stockage, tout en permettant une gestion fine des utilisateurs et des ressources.

## Authors

- [Lamia Oualili](https://github.com/lamiaoua)
