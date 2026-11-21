# Aktualizace dat
```bash
python3 tools/sikorashop/fetch_pages.py urls.txt raw/pages
python3 tools/sikorashop/parse_shop.py upgates raw/pages raw/parsed.json
python3 tools/sikorashop/build_catalog.py raw/parsed.json sikorashop tools/sikorashop/config.json
HERO_HOLES=1 python3 tools/sikorashop/make_hero.py sikorashop <id produktu> ...
```
Potřeba: Python 3, Pillow, BeautifulSoup4, lxml, curl.
