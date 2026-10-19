# Malování 🎨

Jednoduché malování v prohlížeči pro děti (KidsPaint!).
Celé je to **jeden soubor `index.html`** – žádný server, žádná instalace, žádné závislosti.
Sourozenec her [PokéHádej](https://github.com/mlutonsky/pokeguess),
[Hádej vlajku](https://github.com/mlutonsky/flaguess) a [Slovíčka](https://github.com/mlutonsky/wordlang).

## Jak malovat

Otevři [`index.html`](index.html) v prohlížeči. Dole je lišta s velkými tlačítky:

- 🖌️ **Nástroj** – tužka, štětec, fix, sprej, hvězdy a guma + posuvník velikosti,
- 🎨 **Barva** – paleta 30 barev,
- 🗑️ **Smazat** – vymaže celý obrázek (s potvrzením),
- 💾 **Uložit** – uloží obrázek jako PNG (na mobilu/tabletu přes sdílení),
- ⛶ **Celá obrazovka** – přepnutí do fullscreenu.

## Technické detaily

- Čistý **HTML + CSS + JavaScript** nad `<canvas>`, bez build kroku a bez frameworků.
- Ovládání myší i dotykem, primárně dělané pro tablet.
- Rozkreslený obrázek se průběžně ukládá do `localStorage`, takže přežije zavření stránky.
- Písma se načítají z Google Fonts (bez připojení se použije záložní písmo).
