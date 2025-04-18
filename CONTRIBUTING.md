# Guide de contribution au projet NEURON

Merci de votre intérêt pour contribuer au projet NEURON ! Ce document vous guidera à travers les processus et conventions que nous utilisons pour maintenir la qualité et l'intégrité du projet.

## 🌟 Code de conduite

En participant à ce projet, vous vous engagez à respecter notre [Code de conduite](CODE_OF_CONDUCT.md). Veuillez le lire avant de contribuer.

## 🔍 Comment contribuer

### Signaler des bugs

Si vous trouvez un bug, veuillez créer une issue en utilisant le modèle de rapport de bug. Assurez-vous d'inclure :

- Un titre clair et descriptif
- Les étapes précises pour reproduire le problème
- Comportement attendu et comportement observé
- Captures d'écran si applicable
- Contexte supplémentaire (environnement, OS, etc.)

### Proposer des améliorations

Les suggestions d'amélioration sont toujours les bienvenues. Pour en proposer une :

1. Créez une issue en utilisant le modèle de demande de fonctionnalité
2. Décrivez clairement la fonctionnalité souhaitée
3. Expliquez pourquoi cette fonctionnalité serait utile au projet
4. Suggérez une implémentation si possible

### Première contribution

Vous cherchez à faire votre première contribution ? Consultez les issues marquées "good first issue" qui sont spécialement sélectionnées pour les nouveaux contributeurs.

### Pull Requests

1. Forkez le dépôt et créez votre branche à partir de `main`
2. Si vous ajoutez du code, ajoutez des tests qui couvrent vos changements
3. Si vous modifiez les APIs, mettez à jour la documentation
4. Assurez-vous que tous les tests passent
5. Assurez-vous que votre code est conforme aux directives de style
6. Soumettez votre pull request !

## 📋 Standards de codage

### Style de code

- Suivez les conventions de nommage camelCase pour les variables et fonctions
- Utilisez PascalCase pour les noms de classes
- Commentez votre code de manière complète et précise
- Écrivez des messages de commit descriptifs

### Tests

- Tous les nouveaux modules doivent être accompagnés de tests unitaires
- Maintenez une couverture de tests d'au moins 80%
- Les tests doivent être indépendants les uns des autres

### Documentation

- Tout nouveau code doit être documenté avec des commentaires appropriés
- Les APIs publiques doivent avoir une documentation complète
- Mettez à jour le README et autres documents lorsque nécessaire

## 🏗️ Architecture

Avant de contribuer du code, familiarisez-vous avec l'architecture du projet décrite dans [docs/architecture.md](docs/architecture.md).

## 🔄 Processus de développement

### Branches

- `main` - Branche stable, protégée
- `develop` - Branche de développement principal
- `feature/*` - Pour les nouvelles fonctionnalités
- `bugfix/*` - Pour les corrections de bugs
- `release/*` - Pour la préparation des versions

### Versionnement

Nous suivons [Semantic Versioning](https://semver.org/).

### Révisions de code

Toutes les soumissions nécessitent une révision de code. Nous utilisons les Pull Requests de GitHub pour cela.

## 💬 Communication

- Utilisez les issues GitHub pour les discussions liées au développement
- Pour les questions plus générales, utilisez [notre forum de discussion](https://github.com/servais1983/NEURON-cybersecurite/discussions)

## 🙏 Remerciements

Votre contribution est inestimable pour ce projet. Tous les contributeurs seront reconnus dans notre fichier [CONTRIBUTORS.md](CONTRIBUTORS.md).

---

Merci d'aider à faire de NEURON un projet qui révolutionne la cybersécurité adaptative !
