---
icon: laptop
description: >-
  Expo Go permet de tester le bon fonctionnement de l’app avec vos modifications
  avant de le compiler.
---

# Tester avec Expo Go

{% hint style="warning" %}
Les fonctionnalités natives ne sont pas supportées sur Expo Go et vos appareils doivent être sur le même réseau.
{% endhint %}

### Prérequis

* L'application « Expo Go » (disponible sur [Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent) ou sur [l’App Store](https://apps.apple.com/fr/app/expo-go/id982107779)).
* Le dépot git de Papillon.

### Utilisation

1. Lancer le serveur de développement

{% tabs %}
{% tab title="npm" %}
```sh
npm run start
```
{% endtab %}

{% tab title="pnpm" %}
```sh
pnpm start
```
{% endtab %}
{% endtabs %}

2. Sanner le QR Code qui s'affiche à l'écran qui vous redigera vers l'application Expo Go qui chargera ensuite l'application.
