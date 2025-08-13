# WrenchMate (PWA MVP)

Camera-first mechanic helper + project tracker. Ready for free deployment on Vercel.

## Local Dev
```
npm install
npm run dev
```
Open http://localhost:3000

## Deploy (Vercel)
- Push this folder to a GitHub repo
- Import the repo at https://vercel.com/new
- Click Deploy (default Next.js settings)

## PWA
- `public/manifest.json`
- `public/sw.js` is registered by `pages/_app.tsx`
- Install on iOS/Android via the browser share menu (Add to Home Screen)

## Customize
- Update UI in `pages/index.tsx`
- Swap icons in `public/icons/*`
- Replace mock API in `pages/api/identify.ts`
