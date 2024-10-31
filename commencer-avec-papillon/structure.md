---
icon: webhook
---

# Structure

```
├── assets (dossier des ressources)
├── ios (dossier natif ios contenant les fichiers liés à xcode et les modules natifs)
├── android
└── src
    ├── addons
    ├── background
    ├── components (différents composants utilisés dans les vues)
    ├── consts
    ├── hooks
    ├── providers
    ├── router (gestion du routage)
    ├── services (dossier pour la gestion de la récupération de données)
    ├── stores (dossier pour la gestion du stockage de données)
    ├── utils (fonctions utilitaires diverses : téléchargement, ouverture de fichiers, formatage)
    ├── views
    │   ├── account (vues liées au compte : messages, notes, emploi du temps, etc.)
    │   ├── addon
    │   ├── login (écrans de connexion pour tous les fournisseurs)
    │   ├── settings (pages de paramètres)
    │   └── welcome (écran des notes de version, écran de première installation, écran de sélection de compte)
    └── widgets (utilisé dans la page d’accueil)
```
