# Initialiser le dépôt
git init

# Vérifier l’état
git status

# Ajouter des fichiers
git add <fichier>     # un seul fichier
git add .             # tous les fichiers modifiés

# Créer un commit
git commit -m "Message clair"

# Créer une nouvelle branche
git checkout -b feature/ma-tache

# Changer de branche
git checkout main

# Pousser une branche sur GitHub
git push origin feature/ma-tache

# Fusionner une branche dans main
git checkout main
git merge feature/ma-tache
