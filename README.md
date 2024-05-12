# Bird Language Support

Cette extension pour Visual Studio Code ajoute une prise en charge de la coloration syntaxique pour le langage Bird, permettant une meilleure lisibilité et une expérience de développement améliorée pour les utilisateurs de ce langage spécifique.

## Caractéristiques

- Coloration syntaxique pour les fichiers `.bird`.
- Prise en charge des principaux éléments syntaxiques de Bird.

## Installation

Pour installer cette extension, suivez ces étapes :

1. Ouvrez Visual Studio Code.
2. Naviguez vers l'onglet Extensions en cliquant sur l'icône carrée sur la barre latérale gauche ou en utilisant le raccourci `Ctrl+Shift+X`.
3. Tapez `Bird Language Support` dans la barre de recherche.
4. Cliquez sur le bouton "Installer" à côté de l'extension.

Alternativement, vous pouvez installer l'extension manuellement en téléchargeant le fichier `.vsix` et en suivant ces étapes :

```bash
code --install-extension bird-language-0.0.1.vsix

```
## developper

```bash
vsce login BirdLanguageSupport
vsce publish
```