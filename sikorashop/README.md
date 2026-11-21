# Sikorashop – koncept nového e-shopu

Statický frontend (HTML + CSS + vanilla JS, bez buildu) pro sikorashop.cz, vizuálně inspirovaný patike.ch – stejný designový jazyk jako předchozí koncepty (tmavý rám, zaoblené plochy, plovoucí pill menu, obří „ghost“ nápisy, carousel s výřezy kabelek, pozadí se přebarvuje podle barvy kůže).

**Jde o neoficiální návrh** – stránka má trvalý pruh „KONCEPT“, vodoznak a `noindex`.

## Co umí
- **Katalog** – 913 produktů: ženy, muži, doplňky a kožešinové lemy podle podkategorií (velké podkategorie omezené na 50 produktů), varianty velikostí.

## Spuštění lokálně
```bash
cd sikorashop && python3 -m http.server 8000
```

## Nasazení
Settings → Pages → Source: **GitHub Actions**. Kořenový `index.html` přesměruje do `sikorashop/`.

## Co ještě chybí do ostrého provozu
- Platby, sklad a objednávky v reálném čase – ceny jsou snímek z 21. 11. 2026, objednávka zatím odchází e-mailem (mailto).
