---
icon: apple
---

# Pour iOS

{% hint style="danger" %}
Pour compiler Papillon pour iOS, vous devez posséder un Mac.
{% endhint %}

{% stepper %}
{% step %}
### Prébuild du projet

Dans la racine du projet, éxecutez l'une de ces commandes :

{% tabs %}
{% tab title="npm" %}
```sh
npm prebuild
```
{% endtab %}

{% tab title="pnpm" %}
```sh
pnpm prebuild
```
{% endtab %}

{% tab title="yarn" %}
```sh
yarn prebuild
```
{% endtab %}

{% tab title="bun" %}
```sh
bun prebuild
```
{% endtab %}
{% endtabs %}
{% endstep %}

{% step %}
### Ouverture d'xCode

Ouvrir `Papillon.xcworkspace` avec xCode (**TRÈS IMPORTANT**)
{% endstep %}

{% step %}
### Configuration de Signing

Si vous n'avez pas de compte payant Apple Developer: changer les teams pour le signing et enlever les "Assiocated Domains"
{% endstep %}

{% step %}
### Selection du schemes et de la target

Sélectionner `Papillon (release)`au niveau des schemes et votre target (physique ou simulateur)
{% endstep %}

{% step %}
### C'est terminé !

Attendre un peu et c'est tout bon!
{% endstep %}
{% endstepper %}

![](https://github.com/user-attachments/assets/97efe4bc-526e-45b4-b44c-eb281c25a4cc) ![](https://github.com/user-attachments/assets/7642b6d0-f296-4e49-89ee-a2f7e81ef728) ![](https://github.com/user-attachments/assets/04a8df53-b33f-4909-8738-da2fb131e87c)
