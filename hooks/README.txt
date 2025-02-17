# Installation du Hook pre-commit

Ce dépôt contient un hook `pre-commit` qui permet d'ajouter automatiquement un fichier `suivi/commitInfo.txt` 
contenant la date et l'heure du commit si l'utilisateur confirme.

## Installation

1. Copiez le fichier `pre-commit` dans le dossier des hooks Git local :
   cp hooks/pre-commit .git/hooks/pre-commit
