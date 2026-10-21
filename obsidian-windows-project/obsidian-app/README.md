# OBSIDIAN Desktop (Windows)

Neonově laděná ukázková desktopová aplikace postavená na Electronu. Zprávy se zatím zobrazují lokálně pouze v této aplikaci; pro skutečný chat mezi lidmi je nutné doplnit backend, přihlášení a databázi.

## Spuštění
1. Nainstaluj Node.js LTS.
2. Rozbal projekt do složky.
3. Otevři PowerShell v této složce a spusť:
   ```powershell
   npm install
   npm start
   ```

## Vytvoření instalačního EXE
Na Windows spusť:
```powershell
npm run dist
```
Instalátor bude ve složce `dist` jako soubor `.exe`.

## Poznámky
- První `npm install` potřebuje internetové připojení.
- Tento zdrojový projekt není hotový instalační EXE; EXE se sestaví příkazem výše na Windows.
- Google Fonts se načítají online; systémové fonty jsou připravené jako záloha.
