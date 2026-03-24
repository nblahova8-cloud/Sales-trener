# Sales Trenér AI 💼

AI aplikace pro trénink obchodních dovedností — roleplay hovory, lekce od trenéra, hodnocení výkonu.

## Spuštění lokálně

```bash
npm install
npm run dev
```

Otevři `http://localhost:5173`

## Nasazení na Vercel

1. Nahraj repo na GitHub
2. Jdi na [vercel.com](https://vercel.com) → New Project → importuj repo
3. Vite se detekuje automaticky → klikni Deploy

## Struktura

```
src/
  SalesTrener.jsx   # Celá aplikace
  main.jsx          # Vstupní bod
```

## Konfigurace

V `src/SalesTrener.jsx` na řádku ~5 vlož svůj OpenAI API klíč:

```js
const OPENAI_API_KEY = "sk-proj-...";
```

## Technologie

- React 18 + Vite
- Claude API (lekce, roleplay AI zákazník)
- OpenAI TTS API (hlasy trenérů)
- Web Speech API (rozpoznávání řeči)
