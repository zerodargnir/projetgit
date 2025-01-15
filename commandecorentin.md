# Commande du projet git

## Création des fichier qui serve de base pour faire les modification pour la version mobile

git add mobile.html
git commit -m "fichier html du site mobile"
git push origin Corentin "pour l'envoyé sur le dépôt distant"

git add mobile.css
git commit -m "fichier css du site mobile"
git push origin Corentin "pour l'envoyé sur le dépot distant"

## Récupération de la partie de Dario pour y appliquer mes modification

git pull origin dario "pour récupérer le travail de dario afin d'appliquer 
mes modification sur sont travail"

## Ajout des modification

git add css
git commit -m "ajout du fichier mobile.css dans le dossier css"
git push origin Corentin

## Ajout du lien mobile.css sur index.html
git add html
git commit -m "ajout du lien vers mobile.css"
git push origin Corentin

## Création du .gitignor

git add .gitignor
git commit -m "ajout du fichier .gitignor"
git push origin Corentin

## Création de la license

git add LICENSE
git commit -m "ajout de la license"
git push origin Corentin

## Merge de ma branch avec le main

git checkout main
git merge Corentin
