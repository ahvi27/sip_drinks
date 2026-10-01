# SIP — React drinks website

## Run in VS Code
Requires Node.js 22.13+ (Node 24 is suitable).
Extract the ZIP and open the sip-react folder containing package.json.
Open a terminal in that folder:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite, usually http://localhost:5173.
Do not double-click index.html. If npm reports ENOENT, your terminal is not in the folder containing package.json.

## Build
```bash
npm run build
npm run preview
```
Deploy the generated dist folder to a static hosting provider.

## Edit
- src/App.tsx: drink menu, prices, ingredients and content.
- src/styles.css: dark theme and responsive layout.
- public/drinks.jpg: generated drink photograph.

Includes filters, search, and accessible drink details. Brand content and ETB prices are illustrative. No ordering or payments.
