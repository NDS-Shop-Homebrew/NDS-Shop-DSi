# NDS-Shop (DSi) v1.0.0

## Nouvelles fonctionnalités

- **Port DSi initial** — première version pour Nintendo DS / DSi.
- **7 thèmes de couleurs** — défaut NDS-Shop + Dark/Blue/Amber/Red/Green/Purple.
- **Langue française** — accents corrigés (encodage Latin-1), traduction complète.
- **Screenshots** — captures d'écran DSi ajoutées dans le README.
- **Versioning automatique** — version extraite des tags git à la compilation.
- **Auto-création `databases.txt`** avec URL par défaut.
- **Scripts de build Windows** — `compile.bat`, `clean.bat`.

## Corrections / Améliorations DSi

- **WiFi non-fatal** — l'init WiFi ne crashe plus l'app sans réseau.
- **Buffer download réduit** — 1MiB → 32KiB pour la RAM DS (4MB).
- **FAT fallbacks** — chdir robuste pour melonDS.
- **Chemin de téléchargement par défaut** — `APPDATA_DIR` au lieu de `/NDS-Shop`.

## CI / Release

- Build automatisé DSi sur chaque tag `v*`.
- Publication automatique de la release (`.nds` + `version.txt`).

## Crédits

Basé sur [Kekatsu DS](https://github.com/cavv-dev/Kekatsu-DS) par cavv-dev (MIT licensed).
Base de données : [UDB-Kekatsu-DS](https://github.com/cavv-dev/UDB-Kekatsu-DS).
Concept inspiré par [pkgi-psp](https://github.com/bucanero/pkgi-psp) et [Universal-Updater](https://github.com/Universal-Team/Universal-Updater).