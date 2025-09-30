## 🚀 Le GitHub Flow en 6 étapes

1. **Créer une branche**
   - Depuis `main`, chaque membre crée une branche pour sa tâche :
     ```bash
     git checkout -b feature/ma-tache
     ```

2. **Développer sa fonctionnalité**
   - Modifier le code, ajouter des fichiers, corriger des bugs…
   - Ajouter les changements :
     ```bash
     git add .
     git commit -m "Ajout de la fonctionnalité X"
     ```

3. **Pousser la branche sur GitHub**
   ```bash
   git push origin feature/ma-tache
Créer une Pull Request (PR)

Sur GitHub, ouvrir une PR de feature/ma-tache vers main.

L’équipe relit le code et propose des améliorations.

Revue de code et corrections

Les autres membres commentent la PR.

Le développeur applique les corrections si nécessaire :

bash
Copier le code
git add .
git commit -m "Corrections après revue"
git push origin feature/ma-tache
Merge dans main

Une fois validée, la branche est fusionnée dans main.

La branche peut être supprimée :

bash
Copier le code
git branch -d feature/ma-tache
git push origin --delete feature/ma-tache