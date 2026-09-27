# Family Smile Editor PRO V3

Editor ricostruito attorno a tre sole aree realmente personalizzabili:
1. Mese
2. Nome campagna (1/2 righe, prima più piccola)
3. Sottotitolo campagna

Le aree sono ridisegnate nel template SVG e quindi non contengono più le vecchie scritte sotto.

## Avvio
```bash
docker compose down
docker compose build --no-cache
docker compose up -d --force-recreate
```

Apri `http://IP-SERVER:8191`.

## Stack
Nginx Alpine + HTML/CSS + SVG nativo + Google Fonts + jsPDF.
L'auto-fit usa SVG getBBox() nel sistema 1024×1536.
