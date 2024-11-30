# **Installeur de Traduction - Star Citizen par Gerby**

Cet outil est conçu pour faciliter l'installation et la mise à jour des fichiers de traduction pour Star Citizen. Il permet aux utilisateurs de télécharger automatiquement les fichiers nécessaires depuis GitHub et de les installer dans le dossier approprié.

## **Fonctionnalités**
- **Installation automatique** : Télécharge et installe les fichiers `global.ini` et `user.cfg` dans le dossier de jeu sélectionné.
- **Mise à jour facile** : Compare les versions locales et en ligne pour garantir que vous utilisez toujours les dernières traductions.
- **Suppression rapide** : Supprime les fichiers de traduction si nécessaire.
- **Icône personnalisée** : Une interface conviviale avec un logo spécifique à l'application.

---

## **Installation**
1. Téléchargez l'application :
   - Rendez-vous sur la page des [releases](https://github.com/GerbyTV/SCTMN/releases).
   - Téléchargez le fichier exécutable (`TraductionTMN.exe`) dans la dernière version disponible.

2. Placez l'exécutable dans un dossier de votre choix.

---

## **Utilisation**
1. Lancez l'application en double-cliquant sur l'exécutable.
2. Sélectionnez le dossier cible (par exemple, `Live`, `PTU`, ou `EPTU`).
3. Choisissez une action :
   - **Installer** : Télécharge les fichiers nécessaires et les installe dans le dossier sélectionné.
   - **Mettre à jour** : Vérifie et remplace le fichier `global.ini` si une nouvelle version est disponible.
   - **Supprimer la traduction** : Supprime les fichiers de traduction (dossier `data` et `user.cfg`).

4. Suivez les messages affichés pour vérifier le succès de l'action.

---

## **Structure des fichiers**
Voici les fichiers et dossiers créés ou modifiés par l'application :
- **data/Localization/french_(france)/global.ini** : Fichier principal de traduction.
- **user.cfg** : Fichier de configuration supplémentaire.

---

## **Contribuer**
Les contributions sont les bienvenues ! Pour signaler un problème ou proposer des améliorations :
1. Ouvrez une *issue* dans ce dépôt.
2. Créez une branche à partir de `main` pour vos modifications.
3. Envoyez une *pull request*.

---

## **Licence**
Ce projet est sous licence **MIT**. Voir le fichier [LICENSE](./LICENSE) pour plus d'informations.

---

## **Crédits**
Créé par **Gerby** pour simplifier l'expérience des joueurs de Star Citizen. 🌌
