# Button People — web

Statický web (HTML + CSS), hostovaný na GitHub Pages, repozitář `cizekmikulas-hash/web-button-people`.

## Cache-busting style.css

Kdykoliv upravíš `style.css`, **zvyš číslo verze v query parametru** odkazu na styl ve **všech** HTML souborech, např. `style.css?v1` → `style.css?v2` → `style.css?v3` …

- Odkaz `<link rel="stylesheet" href="style.css?vN">` je ve všech 12 HTML souborech.
- Číslo musí být po úpravě jednotné napříč všemi soubory.
- Důvod: GitHub Pages / prohlížeče jinak servírují starou cache CSS.
