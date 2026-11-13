# Fábrica de Tornillos y Remaches LM

Página de una sola pantalla, pensada para celular, para agendar, confirmar o reprogramar una cita por WhatsApp sin llamar.

- Sitio estático: un solo archivo `index.html` (sin dependencias, sin build).
- No guarda datos ni pide información sensible. Los datos solo viajan en el mensaje de WhatsApp (`wa.me`).
- WhatsApp destino: +52 5551646921 (se cambia en la constante `NUM` dentro de `index.html`).

## Publicar en Vercel

1. Sube este repositorio a GitHub.
2. En vercel.com/new, importa el repositorio.
3. Framework Preset: **Other**. Deja vacíos Build Command y Output Directory.
4. Pulsa **Deploy**.
