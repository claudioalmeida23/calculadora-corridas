# calculadora-corridas

Aplicativo web estático "No Caminho Certo" — Calculadora de Corridas com mapa (Leaflet + OSRM).
Publicação sugerida via GitHub Pages.

## Deploy rápido
1. Crie repositório no GitHub com o nome `calculadora-corridas`.
2. Envie os arquivos: `index.html`, `style.css`, `script.js`, `manifest.json`, `sw.js` e a pasta `assets/`.
3. Ative Pages em Settings → Pages → branch `main` → `/root`.

## Notas
- O app usa Nominatim (OpenStreetMap) e OSRM públicos; em alguns domínios/hosts CORS pode bloquear. Se houver erro de rota ou geocoding, use um proxy ou serviço próprio.
- O reconhecimento de voz usa `webkitSpeechRecognition` disponível em navegadores Chromium.
