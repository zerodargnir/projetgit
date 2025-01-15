# Journal des Commandes Git

## Initialisation du dépôt
1. Clonage du dépôt :
   ```bash
   git clone https://github.com/zerodargnir/projetgit.git
   ```
2. Initialisation du dossier local comme un dépôt Git :
   ```bash
   git init
   ```
3. Vérification des fichiers cachés :
   ```bash
   ls -a
   ```
   > Confirmation que le dossier .git est présent.

## Configuration de Git
4. Configuration de l'email utilisateur :
   ```bash
   git config user.email darpsn94@gmail.com
   ```
5. Configuration du nom utilisateur :
   ```bash
   git config user.name zerodargnir
   ```

## Création des fichiers et premier commit
6. Création des fichiers `README.md` et `LICENCE`.
7. Ajout de tous les fichiers au suivi Git :
   ```bash
   git add .
   ```
8. Premier commit :
   ```bash
   git commit -m "premier commit avec juste le readme.md et la licence"
   ```
9. Push de la branche `main` sur le dépôt distant :
   ```bash
   git push origin main
   ```
   > Utilisation du token Git pour l'authentification.

## Gestion des branches
10. Création de la branche `dario` :
    ```bash
    git branch dario
    ```
11. Basculer sur la branche `dario` :
    ```bash
    git checkout dario
    ```
12. Vérification de la branche active :
    ```bash
    git status
    ```

## Travail dans la branche `dario`
13. Ajout du fichier `listecommandeespositodario.txt` :
    ```bash
    git add listecommandeespositodario.txt
    ```
14. Commit des modifications :
    ```bash
    git commit -m "commit de ma branche avec le rapport de commande"
    ```
15. Push de la branche `dario` :
    ```bash
    git push origin dario
    ```

## Résolution de conflit et synchronisation
16. Désactivation du rebase pour les pulls :
    ```bash
    git config pull.rebase false
    ```
    > Le pull de la branche `youssef` ne fonctionnait pas correctement.
17. Pull des modifications de la branche `youssef` :
    ```bash
    git pull origin youssef
    ```
18. Ajout et modification des fichiers `html` et `css` :
    ```bash
    git add .
    git commit -m "commit avec le html corrigé et le css créé et codé"
    git push origin dario
    ```
19. Synchronisation avec la branche `youssef` :
    ```bash
    git pull origin youssef
    ```

## Dernières modifications
20. Modification du fichier CSS mobile :
    ```bash
    git add .
    git commit -m "commit avec modification du fichier css mobile"
    ```
21. Push des modifications :
    ```bash
    git push origin dario
    
