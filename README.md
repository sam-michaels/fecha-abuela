# Hoy es

A full-screen page that shows today's date in Spanish, for an iPad mini 2 (iOS 12). It updates on its own when the day changes.

Live at: https://sam-michaels.github.io/fecha-abuela/

## What it shows

- **Hoy es**
- The day of the week (big), e.g. **SÁBADO**
- The date, e.g. *7 de noviembre de 2026*
- **Y la hora es** and a 12-hour clock without seconds, e.g. *3:30 p. m.*

## Settings

Touch the screen with **5 fingers at once**. A small gear appears in the bottom-right corner for 5 seconds; tap it. On a computer, press the **A** key instead.

The panel is in Spanish:

- **Colores**: one of six colour schemes
- **Reloj**: show or hide the clock and its "Y la hora es" line
- **Horario de noche**: the screen goes black from *Desde* to *Hasta* (10 p. m. to 8 a. m. by default). A touch on the black screen shows the date dimly for 1 minute. Switch it off with *Pantalla negra de noche*.
- **Tamaño de letra**: make each line bigger or smaller (50–250 %). Lines that would run off the screen still shrink to fit.

Tap **Listo** to close it, or it closes by itself after 1 minute. Settings are saved on the iPad.

If the gear never appears, turn off **Settings → General → Multitasking & Dock → Gestures** on the iPad. Those system gestures use 4–5 fingers and can catch the touch first.

## iPad setup

1. Open the link in **Safari** → Share button → **Add to Home Screen**. Opening it from the home-screen icon fills the whole screen.
2. **Settings → Display & Brightness → Auto-Lock → Never**, so the screen stays on. Keep the iPad plugged in.
   iOS 12 can't turn the screen off and on by a schedule, so the app shows a black screen at night instead. Leave **Settings → General → Accessibility → Display Accommodations → Auto-Brightness** on so the backlight dims by itself in a dark room.
3. Optional: **Settings → General → Accessibility → Guided Access** turns on a mode that locks the iPad to this one app. Start it by triple-clicking the Home button while the app is open.
4. Check that **Settings → General → Date & Time → Set Automatically** is on, so the date is always right.

## Testing

Add `?prueba=YYYY-MM-DDTHH:MM` to the URL to preview a given moment, e.g. `index.html?prueba=2026-09-30T08:05`.

The script uses only older JavaScript (ES5) so that it runs on Safari for iOS 12.
