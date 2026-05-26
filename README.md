# 🚗 Theme Cars - Bruce Firmware

[Français](#français) | [English](#english)

---

## Français

Ce pack contient un thème personnalisé pour le firmware Bruce, optimisé avec des images au format BMP 24-bits (sans transparence) pour de meilleures performances.

### 📦 Contenu du pack
* Fichiers `.bmp` (Icônes de l'interface)
* `Theme_Cars.json` (Fichier de configuration du thème)
* `boot.gif` (Animation de démarrage optimisée en 128x64)

### ⚙️ Procédure d'installation (LittleFS)

Pour installer ce thème dans la mémoire interne (**LittleFS**) de votre appareil :

1. **Connectez votre appareil** à votre ordinateur (via l'outil web officiel ou le logiciel compagnon de gestion de fichiers).
2. Ouvrez l'explorateur de fichiers et accédez à la mémoire interne **LittleFS** (disque interne du firmware).
3. Naviguez jusqu'au dossier dédié aux thèmes (généralement `/Themes` ou à la racine du système LittleFS selon votre structure).
4. **Copiez le dossier** `Theme_Cars` (contenant les fichiers `.bmp` et le fichier `Theme_Cars.json`) à cet endroit.
5. Placez le fichier `boot.gif` à la racine du répertoire LittleFS ou dans le dossier spécifié par votre version de Bruce pour les animations de démarrage.
6. **Redémarrez l'appareil** et activez le thème depuis le menu des paramètres de l'interface.

---

## English

This pack contains a custom theme for the Bruce firmware, optimized with 24-bit BMP images (no transparency) for maximum performance.

### 📦 Pack Contents
* `.bmp` files (UI Icons)
* `Theme_Cars.json` (Theme configuration file)
* `boot.gif` (Optimized 128x64 boot animation)

### ⚙️ Installation Procedure (LittleFS)

To install this theme into the device's internal memory (**LittleFS**):

1. **Connect your device** to your computer (using the official web tool or companion file manager software).
2. Open the file explorer and access the internal **LittleFS** storage (internal firmware drive).
3. Navigate to the themes directory (usually `/Themes` or the root of the LittleFS system depending on your build).
4. **Copy the** `Theme_Cars` folder (containing the `.bmp` files and `Theme_Cars.json`) into this directory.
5. Place the `boot.gif` file at the root of the LittleFS directory or inside the designated boot animation folder for your Bruce version.
6. **Reboot the device** and select the theme from the UI settings menu.
