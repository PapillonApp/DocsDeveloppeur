---
icon: laptop
description: >-
  Papillon est écrit en TypeScript avec React Native et Expo. Nous utilisons
  GitHub comme hébergeur du code de l'application.
---

# Commencer à développer

### Prérequis

Pour commencer à développer Papillon vous avez besoin des outils suivants:

* Git ([https://git-scm.com](https://git-scm.com/))
* NodeJS ([https://nodejs.org/en](https://nodejs.org/en))
* xCode, si vous comptez [compiler pour iOS ](../compiler-papillon/pour-ios.md)
* Une fork de Papillon

### Installation du repo

Ce script effectue un clonage du dépôt git de Papillon auquel vous ne pouvez pas effectuer de changements, c'est pour cela qu'il vous faut remplaver l'url après `clone` par celle de votre fork que vous avez créé précédemment.

{% tabs %}
{% tab title="npm" %}
```sh
git clone git@github.com:PapillonApp/Papillon.git
cd Papillon
npm install
```
{% endtab %}

{% tab title="pnpm" %}
```sh
git clone git@github.com:PapillonApp/Papillon.git
cd Papillon
pnpm install
```
{% endtab %}
{% endtabs %}

Et voilà vous avez maintenant votre propre version de Papillon

### Vers l'infini et l'au delà...!

Voilà! Vous avez une copie locale de Papillon prête à être améliorée par vos soins, pourquoi ne pas jeter un coup d'œuil à comment[ lancer le serveur de développement](avec-expo.md) ou en apprendre un peu plus sur les [composants de l'interface utilisateur](broken-reference)?

La seule limite est votre imagination!
