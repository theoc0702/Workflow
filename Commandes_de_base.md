# Initialiser le dépôt
```bash
git init
```

# Vérifier l’état
```bash
git status
```


# Ajouter des fichiers
```bash
git add <fichier>     # un seul fichier
git add .             # tous les fichiers modifiés
```

# Créer un commit
```bash
git commit -m "Message clair"
```

# Créer une nouvelle branche
```bash
git checkout -b feature/ma-tache
```

# Changer de branche
```bash
git checkout main
```

# Pousser une branche sur GitHub
```bash
git push origin feature/ma-tache
```

# Fusionner une branche dans main
```bash
git checkout main
git merge feature/ma-tache
```
