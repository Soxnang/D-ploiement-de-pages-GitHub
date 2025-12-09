# Déploiement GitHub Pages avec GitHub Actions

Ce projet démontre comment configurer un workflow GitHub Actions pour déployer automatiquement un site web statique sur GitHub Pages.

## Fonctionnalités

- Déploiement automatique sur GitHub Pages
- Déclenchement uniquement lorsque `index.html` est modifié
- Workflow simple et efficace
- Intégration continue et déploiement continu (CI/CD)

## Comment ça marche

1. Le workflow se déclenche lorsqu'un push est effectué sur la branche `main`
2. Il vérifie si le fichier `index.html` a été modifié
3. Si oui, il déploie le site sur GitHub Pages
4. Sinon, le workflow s'arrête

## URL du site

Le site est disponible à l'adresse : https://[votre-username].github.io/gh-deployment-workflow/

## Technologies utilisées

- GitHub Actions
- GitHub Pages
- HTML
- YAML

## Configuration

Pour utiliser ce workflow dans votre propre projet :

1. Clonez ce dépôt
2. Modifiez le fichier `index.html` selon vos besoins
3. Activez GitHub Pages dans les paramètres de votre dépôt
4. Le workflow se déclenchera automatiquement lors des modifications
