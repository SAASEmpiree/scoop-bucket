# Bucket Scoop de SAASEmpiree

Installez nos applications open source, **local-first**, en une commande sous
Windows avec [Scoop](https://scoop.sh).

## Atelier — boîte à outils de fichiers 100 % locale

```powershell
scoop bucket add saasempiree https://github.com/SAASEmpiree/scoop-bucket
scoop install atelier
```

Mise à jour : `scoop update atelier`. Désinstallation : `scoop uninstall atelier`.

> L'application n'est pas encore signée. Au premier lancement, si Windows
> SmartScreen affiche « Windows a protégé votre ordinateur » : cliquez sur
> **« Informations complémentaires » → « Exécuter quand même »** (une seule fois).

Dépôt du projet : <https://github.com/SAASEmpiree/atelier-fichiers> ·
Sur macOS : `brew install --cask saasempiree/tap/atelier`.
