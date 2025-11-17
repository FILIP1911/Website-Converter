# Website-Converter

Kratek opis
----------
Website-Converter je orodje za avtomatizirano pretvorbo vsebine spletnih strani v druge formate (npr. Markdown, PDF, statične datoteke ali prilagojene izvoze). Ta repozitorij vsebuje izvorno kodo, konfiguracije in primere uporabe.

Glavne značilnosti
-------------------
- Pretvorba HTML strani v Markdown ali druge tekstovne formate
- Shranjevanje in organizacija prenesenih assetov (slike, CSS, JS)
- Enostaven vmesnik (CLI ali API) za množične pretvorbe
- Možnost razširitve z dodatnimi izvoznimi formati

Hitri začetek
------------
1. Kloniraj repozitorij:
```bash
git clone https://github.com/FILIP1911/Website-Converter.git
cd Website-Converter
```

2. Namesti odvisnosti
- Če je projekt Node.js:
```bash
npm install
# ali
yarn install
```
- Če je projekt Python:
```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows
pip install -r requirements.txt
```

3. Zagon (primer)
- CLI:
```bash
# primer ukaza za pretvorbo
npm start -- convert https://example.com --output ./out
# ali (Python)
python main.py --url https://example.com --out ./out
```

Opombe:
- Nadomesti ukaze z ustreznimi za tvoj projekt (poglej package.json, setup.py ali README v izvoru).
- Če so potrebne dodatne konfiguracije (API ključi, proxy, omejitve zahtevkov), jih dodaj v konfiguracijsko datoteko ali v .env.

Primer uporabe
--------------
```bash
# Pretvori eno stran v Markdown in shrani v ./converted
website-converter convert https://example.com --format md --out ./converted
```

Struktura repozitorija
----------------------
- /src ali /lib — izvorna koda
- /bin — izvršljivi skripti ali CLI
- /tests — enotski testi
- README.md — ta dokument
- package.json / pyproject.toml — metapodatki in odvisnosti

Prispevanje
-----------
Hvala za prispevek! Predlagam naslednji potek:
1. Odpri issue z opisom spremembe/bug-a.
2. Ustvari vejo po vzoru: feature/kratak-opis ali fix/kratak-opis.
3. Pošlji pull request z opisom in primeri, kako testirati spremembe.
4. Upoštevaj slog kode (dodaj .editorconfig / linter), če še ni.

Licenca
-------
Dodaj ustrezno licenco (npr. MIT) ali obvestilo o licenci tukaj.

Kontakt / Avtor
---------------
Filip (FILIP1911) — http(s)://github.com/FILIP1911

Kaj urediti v tem README
------------------------
- Zamenjaj generične ukaze z dejanskimi ukazi iz tvoje codebase (package.json, setup skripte).
- Dopolni točne predpogoje (npr. verzije Node/Python, dodatne knjižnice).
- Dodaj primere vhodnih/izhodnih datotek in posnetke zaslona, če ima UI.
- Če želiš, ti lahko pripravim README natančno po vsebini repozitorija — povej, želiš da pogledam package.json, glavne datoteke ali to naredim sam.
