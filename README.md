# eurydice-ai-song-generator
Automated song generator with AI assistance, by Eurydice Reinert Cend 
# Eurydice – Reinert Cend

**Eurydice** est une application mobile générative de chansons, propulsée par l’IA.  
Elle permet de créer automatiquement des morceaux chantés à partir de texte, avec une orchestration vocale et musicale fine, des effets naturels, et un mixage intégré.

---

## Fonctionnalités principales

### Application mobile Flutter
- Choix de voix chantées IA (Soprano, Alto, Ténor, etc.)
- Ambiances musicales variées : lyrical, spiritual, techno, tragique...
- Instruments modulables : piano, violon, gong, balafon, tambourin…
- Sons naturels : oiseaux, cascades, vagues, calebasse sur l’eau
- Structure de chanson : 1–3 couplets + refrain
- Interface de mixage avec réglages volumes, intensité, signature rythmique
- Export audio `.mp3`, `.wav`, `.aiff` et partage vers Spotify / Instagram / TikTok

### Backend IA (FastAPI)
- `/generate-voice` : génération de voix chantée à partir de texte
- `/generate-music` : création d’un accompagnement musical IA
- `/add-effects` : ajout d’effets sonores naturels
- `/mix-and-export` : mixage final et export du morceau

---

## Arborescence du projet


Eurydice_Full_Project/ ├── frontend/ # App mobile Flutter │ └── lib/screens/ ├── backend/ # Backend IA FastAPI │ └── app/ │ ├── main.py # Endpoints IA │ └── lyrics_soprano_example.txt

---

## Installation locale

### 1. Prérequis
- Flutter SDK
- Python 3.10+
- pip install -r requirements.txt (bientôt fourni)

### 2. Lancer le frontend Flutter
```bash
cd frontend
flutter pub get
flutter run
cd backend/app
uvicorn main:app --reload
Auteur
Reinert Cend
Créateur du projet Eurydice
Vision : unir poésie, IA vocale, émotion et musique en un outil créatif accessible à tous

Licence
MIT – Utilisation libre avec mention de l’auteur et du projet.
© 2025 Reinert Cend – Tous droits réservés.
