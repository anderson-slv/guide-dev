# Workflow Git

## 1. Branch
Créer une branche pour isoler chaque nouvelle fonctionnalité.
`git checkout -b feature/nom-de-la-branche`

## 2. Commit
Enregistrer les modifications avec un message clair.
`git add .`
`git commit -m "Description du changement"`

## 3. Push
Envoyer la branche sur le dépôt distant.
`git push origin feature/nom-de-la-branche`

## 4. Pull Request
Ouvrir une PR sur GitHub pour demander la fusion dans main.
- Aller sur GitHub → Compare & pull request
- Ajouter une description
- Demander une review si nécessaire

## 5. Merge
Fusionner la branche dans main après validation.
`git checkout main`
`git merge feature/nom-de-la-branche`
