# Contributions de Scripts Linux Communautaires

Bienvenue dans le dépôt des scripts Linux pour le portfolio de Mahery !

Ce dépôt est dédié à la collecte et au partage de scripts Bash, Python, etc., utiles pour l'administration système, l'automatisation, le réseau, et bien plus encore.

## Comment Contribuer :

1.  **Forkez** ce dépôt sur votre compte GitHub.
2.  **Clonez** votre fork localement : `git clone https://github.com/votre-utilisateur/LinuxScriptsCommunity.git`
3.  **Créez une nouvelle branche** pour votre contribution : `git checkout -b ma-super-contribution`
4.  **Ajoutez votre script :**
    * Placez votre script dans un sous-dossier approprié (ex: `scripts/system/mon-script.sh`).
    * Si aucune catégorie ne convient, vous pouvez en proposer une ou utiliser `scripts/misc`.
    * Assurez-vous que votre script est bien commenté et que son objectif est clair.
    * **IMPORTANT :** Créez un fichier Markdown descriptif pour votre script à côté du script lui-même (ex: `scripts/system/mon-script.md`). Ce fichier doit contenir :
        ```markdown
        ---
        title: "Mon Super Script pour Gérer les Logs"
        description: "Ce script automatise la rotation et l'analyse des fichiers de logs."
        category: "system"
        tags: ["bash", "logs", "automation"]
        author: "Votre Nom / Pseudo GitHub"
        ---

        ## Description Détaillée

        Expliquez ici plus en détail ce que fait votre script, pourquoi il est utile, et ses fonctionnalités principales.

        ## Prérequis

        - `outil_necessaire` (ex: `jq` si vous parsez du JSON)

        ## Utilisation

        ```bash
        # Exemple d'exécution
        ./mon-script.sh --option valeur
        ```

        ## Code du Script

        [Lien vers le fichier du script dans ce même dépôt : `mon-script.sh`](./mon-script.sh)
        ```
5.  **Testez** votre script pour vous assurer qu'il fonctionne comme prévu.
6.  **Commitez vos changements** et **pushez** vers votre fork.
7.  Créez une **Pull Request** de votre fork vers la branche `main` de ce dépôt original.
8.  Votre Pull Request sera examinée par les mainteneurs. Soyez patient et prêt à apporter des modifications si nécessaire.

## Conventions :

* Nommez vos scripts de manière descriptive.
* Ajoutez des commentaires clairs dans le code.
* Assurez-vous que les scripts sont sécurisés et ne contiennent pas de données sensibles.
* Chaque script doit avoir un fichier `.md` descriptif.

Merci pour votre contribution !
