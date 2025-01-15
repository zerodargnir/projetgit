# Liste des commandes Git de Youssef

1. **Vérifier la version de Git** :
   ```bash
   git --version
   ```

2. **Mettre à jour les paquets sur Linux** :
   ```bash
   sudo apt update -y
   sudo apt upgrade -y
   ```

3. **Cloner le dépôt Git** :
   ```bash
   git clone https://github.com/zerodargnir/projetgit.git
   cd projetgit
   ```

4. **Créer et basculer vers la branche "youssef"** :
   ```bash
   git checkout -b youssef
   ```

5. **Créer un dossier pour le HTML et y accéder** :
   ```bash
   mkdir html
   cd html
   ```

6. **Créer le fichier index.html avec nano** :
   ```bash
   nano index.html
   cd ..
   ```

7. **Ajouter les fichiers à l'index Git** :
   ```bash
   git add .
   ```

8. **Configurer l'email et le nom de l'utilisateur pour Git** :
   ```bash
   git config user.email "scriptys1214@gmail.com"
   git config user.name "scr1ptys"
   ```

9. **Commit de la première version du fichier HTML** :
   ```bash
   git commit -m "Version 1 de la page HTML"
   ```

10. **Ajouter le token GitHub dans un fichier texte** :
    ```bash
    nano ~/token.txt
    ```

11. **Pousser la branche "youssef" sur le dépôt distant** :
    ```bash
    git push origin youssef
    ```

---

### Après ajout du CSS de Dario et du mobile de Corentin :

12. **Récupérer les modifications de la branche de Corentin** :
    ```bash
    git pull origin Corentin
    ```

13. **Ajouter le "Aside" dans le HTML** :
    ```bash
    nano html/index.html
    git add html/index.html
    git commit -m "Ajout du Aside dans le HTML"
    ```

14. **Ajouter un lien vers le CSS dans le fichier HTML** :
    ```bash
    nano html/index.html
    git add html/index.html
    git commit -m "Ajout du lien avec le css"
    ```

15. **Ajouter le CSS pour le Aside et effectuer des ajustements** :
    ```bash
    nano css/style.css
    git add css/style.css
    git commit -m "Ajout du css pour le aside et quelques ajustements"
    ```

16. **Effectuer des ajustements supplémentaires dans le CSS** :
    ```bash
    nano css/style.css
    git add css/style.css
    git commit -m "ajustements"
    ```

17. **Revert des changements indésirables** :
    ```bash
    git log
    git revert 140ee4780fed7566878d5fd5a82777eb4989e4bc
    ```

18. **Mettre à jour le fichier des commandes avec les modifications** :
    ```bash
    nano commandesyoussef.txt
    git add .
    git commit -m "derniers ajustements"
    ```

19. **Réajouter le lien CSS dans le fichier HTML** :
    ```bash
    nano css/style.css
    git add css/style.css
    git commit -m "Reajout du lien avec le css car il s'est enlevé"
    ```

20. **Pousser les modifications vers la branche "youssef"** :
    ```bash
    git push origin youssef
    ```

21. **Récupérer les dernières modifications de la branche de Corentin** :
    ```bash
    git pull origin Corentin
    ```

22. **Créer et ajouter un fichier Markdown pour les commandes** :
    ```bash
    nano CommandesYoussef.md
    git add CommandesYoussef.md
    git commit -m "Ajout des notes dans le format .md"
    ```

23. **Fusionner la branche youssef à la branche principale**

    ```bash
    git checkout main
    git pull origin main
    git merge youssef
    git push origin main
    ```
24. **Modification du Readme et ajout du 'e' à .gitignore**

    ```bash
    nano readme.md
    git add readme.md
    git commit -m "Modification du readme.md"
    nano .gitignor
    rm .gitignor
    git add .gitignore
    git commit -m "Ajout du 'e' à .gitignore"
    ```
