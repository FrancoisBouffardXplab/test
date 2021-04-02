# Git et Github


## Git

- Ouvrir l'invité de commande : 
  - git CMD
- Vérifier la version : 
  git --version
- Vérifier la configuration : git config
- Mettre un nom et une adresse mail : 
  - git config --global user.name "Francois Bouffard"
  - git config --global user.email "francois.bouffard@univ-nantes.fr"
- Créer un nouveau dossier : mkdir xplab
- Aller dans ce dossier : cd xplab/
- Initialiser Git : git init
- Vérifier le statut : git status
- Ajouter un fichier à Git
  - git add "git_github_readMe.md"
  - git commit -m "project init"

- Modifier un fichier et le réimporter
  - modifier le fichier en local
  - re-effectuer les 2 opérations ci-dessus d'ajout de fichier
- Obtenir la timeline des modifications
  - git log

### Créer des branches

- Lister les branches

  - git branch
- Créer une branche

  - git branch project_setup
- Se déplacer vers une branche
  - git checkout project_setup

### Renvoyer les fichiers définitifs vers la branche principale

- Sélectionner la branche qui va recevoir les fichiers
  - git checkout master
- Rapatrier une branche et la fusionner avec la branche master
  - sélectionner la branche qu'on veut rapatrier
  - git merge project-setup
- Vérifier que la fusion est bien effective
  - git log
- Supprimer l'ancienne branche
  - git branch -d project-setup
- Vérifier la suppression
  - git branch

