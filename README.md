# Family Smile Editor PRO

Avvio:
```bash
docker compose up -d --build
```
Poi apri http://localhost:8080

Funzioni:
- layout protetto
- testi/prezzo/telefono/indirizzo modificabili
- 5 palette
- catalogo SVG: check-up, sbiancamento, igiene, ortodonzia, implantologia, pediatrica
- PNG HD 3x
- PDF A4
- preset salvabili nel browser

Nota: html2canvas e jsPDF sono caricati da CDN. Per installazione totalmente offline, scaricare le due librerie in `assets/vendor/` e sostituire gli URL CDN.

- Cinque miniature cliccabili della locandina (Fucsia, Blu, Verde acqua, Arancione, Viola), con evidenziazione della palette selezionata.
