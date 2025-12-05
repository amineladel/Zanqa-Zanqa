# 🎮 Zanqa Zanqa – زنقة زنقة

Jeu d’exploration narratif en 3D, développé sous **Unity**, se déroulant dans une médina marocaine vue à travers les yeux d’un enfant.

> Un jeu court, contemplatif, centré sur l’ambiance et la culture plutôt que sur le scoring ou le combat.

---

## 🧭 Concept

- Jeu à la **troisième personne** dans un **labyrinthe de ruelles** inspiré des médinas marocaines.
- Le joueur incarne un **jeune enfant** chargé de faire une course dans la médina… et qui finit par se perdre.
- Objectif : **explorer**, s’orienter, trouver l’élément clé (Moul Hanout) et déclencher la **fin de partie**.
- Mise en avant de la **culture marocaine** (architecture, ambiance sonore, zelliges, signalétique, etc.) sans clichés touristiques.

---

## ✨ Principales fonctionnalités

- Contrôles fluides en 3D (déplacement + caméra libre).
- Système d’**interaction contextuelle** (message “Appuyez sur E” à proximité d’objets clés).
- **État de victoire** avec écran dédié (menu de fin : rejouer, quitter, retour menu).
- Gestion centralisée du jeu via un **GameManager** (singleton, transitions de scènes, pause, curseur, etc.).
- **Ambiance sonore dynamique** :
  - Musique différente entre menu et jeu.
  - Transitions en fondu (crossfade) entre pistes.
- Scène optimisée pour une exploration fluide (lightmapping, hiérarchie propre, assets sélectionnés).

---

## 🛠️ Stack & techniques

- **Moteur** : Unity 3D (URP)
- **Langage** : C#
- **Plateformes ciblées** : Windows, macOS, WebGL (build de démo)
- **Scripts clés** :
  - `GameManager.cs` – gestion globale du jeu, scènes, victoire.
  - `CharacterInteraction.cs` – interactions (proximité, touche E, canvas de victoire).
  - `MainMenuManager.cs` / `VictoryMenuManager.cs` – menus et navigation.
  - `BackgroundMusicManager.cs` / `MusicFader.cs` – musiques et transitions audio.

---

## ▶️ Lancer le projet

1. Cloner le dépôt :

   ```bash
   git clone https://github.com/DrissDriyej/Zanqa-Zanqa.git
   cd Zanqa-Zanqa
    ````

2. Ouvrir le projet dans **Unity Hub** (version LTS ou compatible URP).
3. Ouvrir la scène de menu (ex. `MainMenu.unity`).
4. Cliquer sur **Play** ou effectuer un **Build & Run** via
   `File > Build Settings`.

---

## 🎮 Contrôles

* **ZQSD / WASD** : déplacement
* **Souris** : caméra
* **E** : interagir (objet clé / Moul Hanout)
* **Esc** : menu / pause (selon configuration)

---

## 🔗 Liens utiles

* 💻 Dépôt GitHub : [https://github.com/DrissDriyej/Zanqa-Zanqa](https://github.com/DrissDriyej/Zanqa-Zanqa)
* 📽️ Vidéo de démo : [https://drive.google.com/file/d/1W9F6agc8vkd9CE9uyq-nBqRBVaEWiYpJ/view](https://drive.google.com/file/d/1W9F6agc8vkd9CE9uyq-nBqRBVaEWiYpJ/view)
* 🎵 Musique principale : *Nass El Ghiwane – Mahmouna*

---

## 👥 Auteurs

Projet réalisé dans le cadre de la filière
**Informatique et applications – Ingénierie 3D et technologie des médias**
**ESIEE Paris – 2024–2025**

* **Driss DRIYEJ**
* **Amine LADEL**
