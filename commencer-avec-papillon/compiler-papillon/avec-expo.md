---
icon: laptop
---

# Avec Expo Go

{% hint style="info" %}
Expo Go permet de tester le bon fonctionnement de l’app avec vos modifications avant de le compiler. De plus, les fonctionnalités natives ne sont pas supportées sur Expo Go et vous devez être sur les deux réseaux sur votre PC et votre mobile.
{% endhint %}

Expo Go peut s’exécuter sur Windows, Mac ou Linux, et s’exécute avec l’app « Expo Go » (disponible sur [Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent) ou sur [l’App Store](https://apps.apple.com/fr/app/expo-go/id982107779)).

Pour pouvoir utiliser Expo Go avec Papillon, vous devez d’abord si cela n’est pas déjà fait :

- 1 : Cloner Papillon
`git clone PapillonApp/Papillon`
- 2 : Dans un terminal et dans le dossier Papillon, exécuter la commande : (Node.JS doit être installé et cette commande peut prendre un certain temps
`npm install`

Ensuite, pour lancer Expo Go, faites :
`npx expo start`
Après quelques secondes, un QR Code s’affichera et vous devrez le scanner sur votre appareil ou Expo Go est installé. (Vous devriez sans doute aussi autoriser le terminal à accéder au réseau si c’est la première fois que vous le faites)

Lorsque Expo Go se lance et charge l’app, vous aurez un écran de chargement ou il faudra attendre que l’app soit correctement chargée. 

Et voilà, vous voilà sur Papillon avec Expo Go ! Les informations et erreurs sur l’app se trouvent en bas de l’app comme sur l’image présente ci dessous.
![image](https://i.ibb.co/nztvy40/IMG-1201.jpg)
