# Test cache SSR na API

## Jak spustit

Je nutné projekt transpilovat do produkčního kódu, jelikož v devu se cache nepoužívá.

```bash
npm i
npm run build
npm run start
```

Jdi na stránku http://localhost:3000

Data "článku" se načítají z internetu každých 10 sekund na backendu a klientovi je poskytována cache.
