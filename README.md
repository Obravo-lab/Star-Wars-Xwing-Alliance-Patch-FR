<div align="center">

# 🚀 Star Wars : X-Wing Alliance — Pack Langue Française v1.0

**Patch de traduction complète en français pour Star Wars : X-Wing Alliance**  
*Compatible avec la version GOG et les versions CD originales*

[![Téléchargement](https://img.shields.io/github/downloads/Obravo-lab/Star-Wars-Xwing-Alliance-Patch-FR/total?style=for-the-badge&label=T%C3%A9l%C3%A9chargements&color=gold)](https://github.com/Obravo-lab/Star-Wars-Xwing-Alliance-Patch-FR/releases/latest)
[![Dernière version](https://img.shields.io/github/v/release/Obravo-lab/Star-Wars-Xwing-Alliance-Patch-FR?style=for-the-badge&label=Version&color=blue)](https://github.com/Obravo-lab/Star-Wars-Xwing-Alliance-Patch-FR/releases/latest)
[![Licence](https://img.shields.io/badge/Licence-Fan%20Patch-red?style=for-the-badge)](LICENSE)

</div>

---

## 📦 Contenu du patch

Ce pack transforme intégralement l'expérience linguistique du jeu :

| Contenu | Détails |
|---|---|
| 🎙️ **Doublage audio complet** | 6 912 fichiers audio en français — voix des personnages, messages radio, communications de combat |
| 🎬 **Cinématiques en français** | 22 vidéos doublées — intro, briefings de mission, cinématiques de fin |
| 📄 **Fichiers de configuration** | `XWA.Tab` et `Launcher.Tab` adaptés au français |

---

## ⚙️ Installation

### Installation automatique (recommandée)

1. Téléchargez la dernière version depuis l'onglet [**Releases**](https://github.com/Obravo-lab/Star-Wars-Xwing-Alliance-Patch-FR/releases/latest)
2. Extrayez le fichier ZIP
3. Double-cliquez sur **`install.bat`**
4. Le script détecte automatiquement votre installation GOG et copie les fichiers

> Le script sauvegarde automatiquement vos fichiers audio anglais dans `Wave_backup_EN\` avant toute modification.

### Installation manuelle (en cas de problème)

1. Copiez le dossier `Wave\` vers le répertoire d'installation du jeu (ex: `C:\GOG\Star Wars - X-Wing Alliance\Wave\`)
2. Copiez le dossier `Movies\` vers `...\Movies\`
3. Copiez `XWA.Tab` et `Launcher.Tab` à la racine du répertoire du jeu

---

## 🔄 Restaurer la version anglaise

Le script crée automatiquement une sauvegarde dans `Wave_backup_EN\`.  
Pour revenir à l'anglais, copiez son contenu vers le dossier `Wave\` du jeu.

---

## 🖥️ Jouer en 2560×1440 (mode fenêtré)

Pour profiter du jeu en haute résolution avec les hooks XWA :

- `dinput.dll` — Hook principal
- `hook_windowed.dll` + `hook_windowed.cfg` — Mode fenêtré
- `hook_resolution.dll` + `hook_resolution.cfg` — Résolution personnalisée
- `hook_res1200.dll` — Correctif crash > 1200px

👉 Voir le projet [JeremyAnsel/xwa_hooks](https://github.com/JeremyAnsel/xwa_hooks)

---

## ❓ Problèmes fréquents

**`install.bat` ne trouve pas le jeu**  
→ Lancez en tant qu'administrateur (clic droit → *Exécuter en tant qu'administrateur*)  
→ Ou saisissez manuellement le chemin quand le script le demande

**Les voix restent en anglais après installation**  
→ Vérifiez que les fichiers `.wav` ont bien été copiés dans `Wave\`  
→ Relancez le jeu après installation

---

## 📋 Compatibilité

| Version | Compatible |
|---|---|
| GOG (version 2.02) | ✅ Oui |
| CD original (patch 2.02 appliqué) | ✅ Oui |
| Steam | ⚠️ Non testé |

---

## 📜 Crédits

- **Patch original** : XWALP (X-Wing Alliance Language Pack) — équipe de traduction française
- **Repackaging & installateur** : Obravo-lab

*Ce patch est distribué à titre non commercial, à des fins de préservation et d'accessibilité pour les joueurs francophones.*

---

<div align="center">
May the Force be with you 🌟
</div>
