# Flamaro: hledanost klíčových slov podle kategorií

Klientský report hledanosti (Google Ads Keyword Planner) pro Flamaro.

- Stránka: https://mairateam.github.io/Flamaro/
- Záložky nahoře = kategorie (Grily, Kuchyňské spotřebiče, Weber, KitchenAid).
  Kategorie se nikdy nesčítají dohromady.
- Filtr klíčových slov: vyhledávání a zaškrtávání, grafy a tabulky se přepočítají
  jen z vybraných slov. Vybraný pohled je v adrese, odkaz jde sdílet.
- Data: měsíční hledanost v Česku z Keyword Planneru, čísla jsou zaokrouhlená Googlem.
  Varianty se stejnou měsíční řadou (např. s diakritikou a bez) se počítají jednou.
  Období a datum poslední aktualizace jsou uvedené přímo ve stránce.

Soubor `index.html` je generovaný (data jsou vložená uvnitř), ručně se neupravuje.
Složka `history/` je archiv měsíčních dat (záloha, stránka ho nečte).
Aktualizace = nové stažení dat z Keyword Planneru, přegenerování stránky a push
do tohoto repa; GitHub Pages ji zveřejní během minuty.
