# Le repaire — Portfolio d'Helder Salvador

Portfolio interactif en forme de salon cypherpunk : une scène 3D isométrique (Three.js) où chaque meuble raconte une facette du parcours — PredCast, ingénierie blockchain, enseignement, lectures, musique, sport — envahie par une jungle de plantes low-poly.

## Caractéristiques

- **Un seul fichier** : `index.html` (Three.js + GSAP via CDN, tout le reste inline)
- Scène 3D isométrique avec 10 zones cliquables et zooms caméra
- Séquence d'ouverture : terminal cyberpunk + iris optique
- Ambiance sonore de jungle 100 % synthétisée en Web Audio API (aucun asset)
- Personnage animé qui se balade dans la pièce
- Direction artistique : néon Bitcoin vs végétal organique
- Responsive, navigable au clavier, `prefers-reduced-motion` respecté

## Déploiement

Poussé sur `main` → déployé automatiquement sur GitHub Pages via `.github/workflows/deploy.yml`.

Pour activer : Settings → Pages → Source : **GitHub Actions**.

## Développement local

Ouvrir `index.html` dans un navigateur. C'est tout.
