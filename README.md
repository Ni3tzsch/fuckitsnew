# DJASSApp Landing Page

Landing page Next.js de DJASSApp, convertie depuis la version statique `betawebsite`.

## Lancer en local

```bash
npm install
npm run dev
```

Puis ouvrir `http://localhost:3000`.

## Scripts

```bash
npm run dev
npm run build
npm run start
npm run lint
```

## Formulaire

Le formulaire de liste d'attente utilise Resend côté serveur. Configurer la variable suivante pour activer l'envoi :

```bash
RESEND_API_KEY=...
```

L'email de destination est défini dans `config/content.ts`.

## Assets principaux

Les assets convertis depuis `betawebsite` sont dans `public/` :

- `favicon.svg`
- `apple-touch-icon.png`
- `djassapplogo.svg`
- `djassapp-phones-optimized.png`
- `djassapp-phones-small.png`
