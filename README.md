# Portfolio — Laila Aït Ali

Portfolio personnel en français, construit avec React, TypeScript, Vite, Framer Motion et Lucide React.

## Prérequis
- Node.js 18 ou supérieur
- npm

## Installation
```bash
npm install
npm run dev
```
Puis ouvrir l'adresse locale affichée par Vite (généralement http://localhost:5173).

## Vérifier la version de production
```bash
npm run build
npm run preview
```

## Personnalisation prioritaire
1. `src/data/projects.ts` : corriger/compléter les descriptions, statuts, stacks et contributions de chaque projet.
2. `src/App.tsx` : modifier le parcours, les compétences, les liens et les coordonnées.
3. `public/portrait.png` : remplacer par la photo professionnelle définitive si souhaité.
4. Ajouter les captures de projets dans `public/` et les relier aux fiches concernées.

## À compléter avant publication
- Ajouter une adresse e-mail professionnelle si tu souhaites proposer un contact direct par e-mail.
- Ajouter les liens des dépôts GitHub et les démonstrations vérifiées projet par projet.
- Confirmer les titres exacts des certifications et leurs dates.
- Ajouter un CV PDF à télécharger lorsque la version finale est prête.
- Vérifier les statuts des projets, notamment Sanaye3i, IoT et LTE, et distinguer les réalisations des explorations.

## Déploiement
Le projet peut être déployé sur Vercel : importer le dépôt GitHub, conserver `npm run build` comme commande de build et `dist` comme répertoire de sortie.
