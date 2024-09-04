---
icon: rocket
---

# 🚀 Utiliser Expo avec Papillon

{% hint style="warning" %}
⚠️ Cette documentation concerne l'utilisation de Papillon dans un environnement Expo, qui n'est pas une application native. Certaines fonctionnalités natives peuvent ne pas être disponibles ou fonctionner différemment.
{% endhint %}

## 📋 Prérequis

- 💻 [Node.js](https://nodejs.org/) installé sur votre machine
- 🛠️ Expo CLI installé globalement : 
  ```bash
  npm install -g expo-cli
  ```

##  Installation et démarrage

1. 📥 Clonez le dépôt Papillon :
   ```bash
   git clone https://github.com/PapillonApp/Papillon
   cd Papillon
   ```

2. 📦 Installez les dépendances du projet :
   ```bash
   npm install
   ```

3. 🚀 Lancez le projet :
   ```bash
   npx expo start
   ```

## 🖥️ Commande `npx expo start`

Cette commande :
- 🌐 Lance le serveur de développement Expo
- 📱 Affiche un QR code pour l'ouverture sur appareil physique
- 🔧 Propose des options de lancement sur émulateur/simulateur ou directement sur un appareil connecté en USB
- 🔄 Active le rechargement à chaud (hot reload) pour une mise à jour instantanée de l'application lors des modifications du code

Options principales :
| Option | Description                   |
|--------|-------------------------------|
| `-i`   | 🍎 Lance sur iOS Simulator    |
| `-a`   | 🤖 Lance sur Android Emulator |

## 📱 Test sur appareil mobile

1. 📲 Installez Expo Go ([Android](https://play.google.com/store/apps/details?id=host.exp.exponent) / [iOS](https://apps.apple.com/fr/app/expo-go/id982107779))
2. 📷 Scannez le QR code du terminal avec Expo Go ou l'appareil photo
3. 🎉 L'app Papillon s'ouvrira dans Expo Go

{% hint style="info" %}
💡 Grâce au rechargement à chaud, toute modification que vous apportez au code sera immédiatement reflétée dans l'application sans avoir besoin de la redémarrer !
{% endhint %}

## 🔒 Utilisation avec ports non exposés

Pour les serveurs ou réseaux avec ports non exposés, utilisez l'option `--tunnel` :

```bash
npx expo start --tunnel
```

## 🖥️ Utilisation de port personnalisé

Pour utiliser un port personnalisé, utilisez l'option `-p` suivi du numéro de port :

```bash
npx expo start -p 3000
```

## ❔ Aide

Pour connaître toutes les options disponibles, utilisez la commande `npx expo start --help`.

{% hint style="info" %}
📚 Pour plus d'informations sur Expo CLI, consultez la [documentation officielle](https://docs.expo.dev/workflow/expo-cli/).
{% endhint %}
