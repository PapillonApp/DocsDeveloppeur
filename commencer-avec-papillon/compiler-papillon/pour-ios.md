---
icon: apple
---

# Pour iOS

{% hint style="danger" %}Pour compiler Papillon pour iOS, vous devez posséder un Mac.{% endhint %} 

1. Dans la racine du projet, exécuter `pnpm prebuild`
2. ouvrir `Papillon.xcworkspace` avec xCode (**TRÈS IMPORTANT**),
3. Changer les teams pour le signing et enlever les app links si vous n'avez pas de compte payant Apple Developer,
4. Sélectionner `Papillon (release)` au niveau des schemes et votre target (physique ou simulateur),
5. Attendre un peu et c'est tout bon!

![CleanShot 2024-10-03 at 21 41 06](https://github.com/user-attachments/assets/97efe4bc-526e-45b4-b44c-eb281c25a4cc)
![CleanShot 2024-10-03 at 21 42 24](https://github.com/user-attachments/assets/7642b6d0-f296-4e49-89ee-a2f7e81ef728)
![CleanShot 2024-10-03 at 21 44 13](https://github.com/user-attachments/assets/04a8df53-b33f-4909-8738-da2fb131e87c)
