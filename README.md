# Luki STICKERS

App web per creare, trasformare e organizzare sticker.

## Prova l'app

[Apri Luki STICKERS](https://sartoriluca65.github.io/LukiStickers/)

## Funzioni

- Crea sticker da foto e da tavole già composte.
- Applica direzioni artistiche e rimuove lo sfondo sul dispositivo.
- Organizza sticker in pacchetti, esporta PNG e prepara sticker per WhatsApp, TikTok e Instagram.
- Supporta immagini HEIC/HEIF.

I pacchetti, gli sticker e le preferenze restano nel browser dell'utente. Le immagini personali non vengono caricate nel repository.

La generazione di nuove illustrazioni con IA è facoltativa e richiede una chiave API Gemini. Gli abbonamenti consumer di ChatGPT, Copilot o Gemini non autorizzano automaticamente un'app esterna a usare i rispettivi modelli. Gli effetti locali restano disponibili senza collegare un servizio AI.

## Sviluppo

Apri `index.html` tramite un server statico. Il codice del Worker in `worker/index.js` è mantenuto come riferimento per l'endpoint IA ospitato separatamente.
