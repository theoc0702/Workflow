# Bonnes Pratiques d'Utilisation de Git

## 1. Utiliser des messages de commit clairs
- Décrire brièvement et précisément les changements apportés.
- Utiliser l'impératif : "Ajoute la documentation", "Corrige le bug".

## 2. Commits atomiques
- Ne pas mélanger plusieurs fonctionnalités ou corrections dans un même commit.
- Un commit = une modification logique.

## 3. Branches pour chaque fonctionnalité
- Créer une branche dédiée pour chaque nouvelle fonctionnalité ou correction.
- Nommer les branches de façon descriptive : `feature/login`, `fix/typo-readme`.

## 4. Pull régulièrement
- Synchroniser fréquemment avec la branche principale pour éviter les conflits.

## 5. Utiliser `.gitignore`
- Exclure les fichiers temporaires, binaires ou sensibles du suivi Git.

## 6. Revue de code
- Utiliser les Pull Requests pour faciliter la relecture et la validation du code.

## 7. Documentation
- Documenter les étapes importantes dans le README ou dans les messages de commit.

## 8. Tags et versions
- Utiliser les tags pour marquer les versions stables ou les releases.

## 9. Nettoyer l’historique
- Utiliser `git rebase` ou `git squash` pour garder un historique propre si besoin.

## 10. Sécurité
- Ne jamais committer de mots de passe ou de clés privées.
- Vérifier le contenu avant chaque push.
