# TP Git - Ynov DevOps B3

Si vous avez des problèmes sur une command utilisez `git [command] --help`.

**Rendu :** Un fichier pdf : DEVOPS_GIT_[NOM]\_[PRENOM].md

Pour chaque étape, documenter vos actions :   
        - Screenshot commande + output
        - Explication d'une ou 2 ligne sur ce que fait la commande
        
:star: **Astuce :** Pour uploader des images dans votre Readme : https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github

## Authentification

- Générer une paire de clef SSH
- Pousser votre clef publique dans votre profile Github
- Configurer votre git local en rajoutant
  - username
  - email  

## Exercice 1 : Création d'un Repo Github

- Initialiser votre dépôt local
- Faire pointer le dépôt local sur un dépôt distant (Remote)
- Vérifier le dépôt distant
- Cloner le repository

## Exercice 2 : Modification du Projet CLI

- Modifier un fichier déjà existant
  - Ajouter le port 2222 pour l'host **Tyrell**
  - Set le niveau de log à `INFO` pour tout les hosts finissant en **ell**
- Commiter vos modifications
- Consulter le statut et les différences
- Ajouter un fichier `diff.txt` et commencer à le tracker
  - Expliquer rapidement la différence entre `git pull` et `git fetch`
- Pousser vos modifications

## Exercice 3 : Modification du projet GUI

- Modifier le fichier `config` en se connectant sur l'interface Github
  - Rajouter :
```sh
Host stark
    HostName 127.0.0.1
    User john
    Port 6666
    IdentityFile ~/.ssh/stark.key
```

## Exervice 4 : Branching et Merging

- Assurer vous d'avoir un repo à jour
- Créer une nouvelle branche et basculer dessus
  - Branch name : change_throne 
- Modifier la configuration SSH 
  -  Modifier le user `daenerys` pour `john`dans l'host `targaryen`
  -  Supprimer le user `john`dans l'host `stark`
-  Commiter et pousser la modification dans la nouvelle branche
-  Créer une Pull Request sur Github
-  Merger les 2 branches
  
