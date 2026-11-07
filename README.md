# Hoy es

A full-screen page that shows today's date in Spanish, for an iPad mini 2 (iOS 12). It updates on its own when the day changes.

Live at: https://sam-michaels.github.io/fecha-abuela/

## What it shows

- The day of the week (big), e.g. **SÁBADO**
- The date, e.g. *7 de noviembre de 2026*
- Part of the day: *Es de mañana* (5:00–11:59), *Es de tarde* (12:00–19:59), *Es de noche* (20:00–4:59)
- A 12-hour clock without seconds, e.g. *10:45 a. m.*

## Settings

Press and hold the **top-right corner** for 3 seconds. Nothing marks the spot on screen. From there you can:

- **Colores**: choose one of six colour schemes,
- **Reloj**: turn the clock on or off,
- **Mañana / tarde / noche**: turn the "Es de mañana / tarde / noche" line on or off.

The panel is in Spanish. Tap **Listo** to close it, or it closes by itself after 1 minute. Settings are saved on the iPad.

## iPad setup

1. Open the link in **Safari** → Share button → **Add to Home Screen**. Opening it from the home-screen icon fills the whole screen.
2. **Settings → Display & Brightness → Auto-Lock → Never**, so the screen stays on. Keep the iPad plugged in.
3. Optional: **Settings → General → Accessibility → Guided Access** turns on a mode that locks the iPad to this one app. Start it by triple-clicking the Home button while the app is open.
4. Check that **Settings → General → Date & Time → Set Automatically** is on, so the date is always right.

## Testing

Add `?prueba=YYYY-MM-DDTHH:MM` to the URL to preview a given moment, e.g. `index.html?prueba=2026-09-30T08:05`.

The script uses only older JavaScript (ES5) so that it runs on Safari for iOS 12.
