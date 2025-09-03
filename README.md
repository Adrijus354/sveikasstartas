# SveikasStartas – React + Tailwind + Vite (Vercel paruošta)

## Greitas startas
```bash
npm install
npm run dev
```
Atidaryk lokaliai: http://localhost:5173

## Svarbios vietos pakeitimams
- `src/App.jsx` → įklijuok Stripe Payment Links į `LINKS.basic/popular/premium`
- `src/App.jsx` → `GOOGLE_FORM_URL` į savo Google Form embed nuorodą
- Porai el. paštas/telefonas ir socialiniai – `ContactPage`, `Footer`

## Build/Deploy į Vercel
- `npm run build` sukuria `dist/`
- Vercel projekte nustatyk: *Framework Preset: Vite*, Build Command: `npm run build`, Output: `dist`
