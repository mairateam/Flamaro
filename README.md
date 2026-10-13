# Flamaro: hledanost klíčových slov podle kategorií

Klientský report hledanosti (Google Ads Keyword Planner) pro Flamaro.

- Stránka: https://mairateam.github.io/Flamaro/
- Stránka Brand (Top Grily a Flamaro, samostatný report, přepínač v liště nahoře): https://mairateam.github.io/Flamaro/brand.html
- Záložky nahoře = kategorie (Grily, Kuchyňské spotřebiče, Weber, KitchenAid).
  Kategorie se nikdy nesčítají dohromady.
- Filtr klíčových slov: vyhledávání a zaškrtávání, grafy a tabulky se přepočítají
  jen z vybraných slov. Vybraný pohled je v adrese, odkaz jde sdílet.
- Data: měsíční hledanost v Česku z Google Keyword Planneru.
  Varianty se stejnou měsíční řadou (např. s diakritikou a bez) se počítají jednou.
  Období a datum poslední aktualizace jsou uvedené přímo ve stránce.

Soubory `index.html` a `brand.html` jsou generované (data jsou vložená uvnitř), ručně se neupravuje.
Složka `history/` je archiv měsíčních dat (záloha, stránka ho nečte).
Aktualizace = nové stažení dat z Keyword Planneru, přegenerování stránky a push
do tohoto repa; GitHub Pages ji zveřejní během minuty.
