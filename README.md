# Portfolio — Valentin LILLIÉ

Reproduction fidèle en site statique (HTML / CSS) du portfolio Canva (`valentin-lillie.my.canva.site`), prête pour un déploiement direct sur **GitHub Pages**.

## Pages incluses

- `index.html` — Welcome (présentation, photo de profil, lien LinkedIn, vidéo de présentation)
- `engineering.html` — Engineering Course & Projects (TIPE Rubik's Cube Solver + vidéo, 7Robot club, jeu Snake en C)
- `mobility.html` — International Mobility (WWOOF en Irlande, ULB, ÉTS Montréal)
- `sustainability.html` — Sustainability & Civic Engagement (Clean walk, Fresque du climat, Forum des métiers, Re-Start)
- `career.html` — Career Development & Summer Jobs (accès aux CV FR/EN + expérience Lalevée et Simon)
- `sport.html` — Sport & other activities (Strava, Running / RUN7, Hiking / 7Randos, Cycling)
- `cv-english.html` — CV complet en anglais
- `cv-french.html` — CV complet en français

## Prévisualisation en local

```bash
python -m http.server 8000
```

Puis ouvrir `http://localhost:8000/` dans un navigateur.

## Déploiement sur GitHub Pages

1. Créer un nouveau dépôt public sur GitHub (par exemple `port-folio`, ou `<ton-pseudo>.github.io` pour une URL à la racine).
2. Relier le dépôt local et pousser la branche `main` :

```bash
git remote add origin https://github.com/<TON-PSEUDO>/<NOM-DU-DEPOT>.git
git push -u origin main
```

3. Sur GitHub, aller dans **Settings → Pages** :
   - **Source** : *Deploy from a branch*
   - **Branch** : `main` / `/ (root)`
   - Cliquer sur **Save**
4. Après ~1 minute, le site est en ligne à l'adresse `https://<ton-pseudo>.github.io/<nom-du-depot>/` (ou `https://<ton-pseudo>.github.io/`).
