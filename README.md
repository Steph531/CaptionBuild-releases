# Caption Build — Téléchargements

Ce dépôt héberge uniquement les versions publiées de **Caption Build**, l'application qui transforme un enregistrement d'écran en short vertical avec sous-titres animés mot par mot. Il ne contient pas de code source.

## Télécharger la dernière version

| Système | Fichier |
|---|---|
| macOS — Apple Silicon (M1, M2, M3…) | [CaptionBuild-mac-apple-silicon.dmg](https://github.com/Steph531/CaptionBuild-releases/releases/latest/download/CaptionBuild-mac-apple-silicon.dmg) |
| macOS — Intel | [CaptionBuild-mac-intel.dmg](https://github.com/Steph531/CaptionBuild-releases/releases/latest/download/CaptionBuild-mac-intel.dmg) |
| Windows 10 / 11 (64 bits) | [CaptionBuild-windows-setup.exe](https://github.com/Steph531/CaptionBuild-releases/releases/latest/download/CaptionBuild-windows-setup.exe) |

Pas sûr de votre Mac ? Menu  → **À propos de ce Mac** : « Puce Apple M… » = Apple Silicon, « Processeur Intel » = Intel.

Toutes les versions et leurs notes : [Releases](https://github.com/Steph531/CaptionBuild-releases/releases).

## Installation

### macOS

1. Ouvrez le `.dmg` et glissez **Caption Build** dans le dossier **Applications**.
2. Au premier lancement, macOS bloque l'application (« Apple n'a pas pu vérifier… »). Cliquez sur **OK**, puis allez dans **Réglages Système → Confidentialité et sécurité**, descendez jusqu'au message concernant Caption Build et cliquez sur **Ouvrir quand même**.
3. Si macOS indique plutôt que l'application « est endommagée », ouvrez le Terminal et lancez :
   ```
   xattr -cr "/Applications/Caption Build.app"
   ```
   puis relancez l'application.

### Windows

1. Lancez `CaptionBuild-windows-setup.exe`.
2. Si Windows affiche « Windows a protégé votre ordinateur », cliquez sur **Informations complémentaires** puis **Exécuter quand même**.

Ces avertissements apparaissent parce que l'application n'est pas encore signée par Apple / Microsoft ; ils disparaîtront dans une prochaine version.

## Mises à jour

Une fois installée, l'application se met à jour automatiquement — pas besoin de revenir ici. Chaque mise à jour est vérifiée par signature cryptographique avant installation.
