# Blade Razon Barber Bot

WhatsApp bot para Blade Razon Barber utilizando la API de OpenAI y Twilio, orquestado con Make para calendario y Sheets.

## Setup

1. Copia `.env.example` a `.env` y rellena tus credenciales.
2. `npm install`
3. `npm run dev` (desarrollo)
4. `npm run build && npm start` (producción)

Configura tu webhook en Twilio a:
```
https://<TU-URL>/whatsapp/webhook
```
