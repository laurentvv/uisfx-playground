# UI SFX Studio & Playground

Projet de test et bac à sable interactif pour la bibliothèque open-source [UI SFX](https://github.com/romainsimon/uisfx) (`uisfx`).

## 📁 Emplacement du projet

```
C:\git\uisfx-playground
```

---

## 🚀 Démarrage rapide

### 1. Installation des dépendances
```bash
npm install
```

### 2. Lancer le serveur de développement
```bash
npm run dev
```
L'interface sera accessible sur :
👉 **`http://localhost:5173/`**

### 3. Compiler pour la production
```bash
npm run build
```

---

## 🎯 Fonctionnalités du Playground

1. **Sélecteur de Personnalité Sonore (12 Packs)** :
   - `minimal`, `soft`, `glass`, `arcade`, `mechanical`, `organic`, `dreamy`, `scifi`, `rubber`, `cinematic`, `studio`, `zen`.
   - Changement instantané avec recalcul des synthèses Web Audio sans rechargement de page.

2. **Simulation de Composants Réels** :
   - **Formulaires & Boutons** : Sauvegarde (`success`), Suppression destructive (`delete`), Annulation (`cancel`), Copie (`copy`).
   - **Toggles & Sélecteurs** : Switch on/off (`toggle-on`, `toggle-off`), Checkboxes (`check`, `uncheck`), Onglets de navigation (`select`).
   - **Traitement Asynchrone & Boucles d'attente (State Loops)** : Démarrage d'un traitement avec boucle continue (`processing`), étapes discrètes (`progress-step`), et clôture propre (`complete`).
   - **Gamification & Récompenses** : `reward`, `level-up`, `streak`, `achievement`.
   - **Glisser-Déposer (Drag & Drop)** : `drag-start`, dépôt valide (`drop`), dépôt rejeté (`invalid-drop`).

3. **Explorateur Complet des 78 Cues** :
   - Filtrage par catégorie (*Input, Selection, Navigation, Editing, Movement, Communication, Feedback, Progress, Loops, Media, System, Reward, Commerce*).
   - Recherche en temps réel.
   - Écoute directe de chaque son au clic.
   - Barre flottante de gestion des boucles d'état actives avec bouton d'arrêt d'urgence.

4. **Contrôles Globaux** :
   - Témoin d'état du contexte Web Audio (Verrouillé / Actif).
   - Curseur de volume (0 à 100%).
   - Bascule Mute / Unmute avec arrêt immédiat des boucles.
   - Bouton d'arrêt d'urgence (`ui.stopAll()`).

---

## 📄 Licence

- **Code** : Licence MIT
- **Fichiers audio & sound design** : Creative Commons Zero (CC0 1.0 Universal - Domaine Public)
