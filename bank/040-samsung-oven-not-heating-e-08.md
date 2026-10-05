---
title: Piekarnik Samsung się nie nagrzewa — E-08 i okolice
description: Piekarnik Samsung chodzi, ale zostaje zimny, a kod E-08 mówi swoje. Od resetu z bezpiecznika, przez grzałkę i czujnik NTC, po przekaźnik na płycie.
---

Piekarnik, który pracuje, ale pozostaje zimny, psuje się w ponuro przewidywalny sposób: płyta ustawiła temperaturę, komora się nie podniosła, a maszyna zapisała powód. W kuchenkach i piekarnikach Samsung [E-08](https://pl.codefixcoffee.com/samsung/range-wall-oven/e-08/) to kod główny dla tej sytuacji — piekarnik się nie nagrzewa, a podejrzanymi są grzałka pieczenia lub grilla, czujnik temperatury albo przekaźnik na płycie. Krąży wokół niego niewielka rodzina pokrewnych kodów, które zawężają diagnozę. Przechodzimy je w kolejności wartej sprawdzania — zaczynając od kroku, który ludzie najczęściej pomijają.

## Najpierw reset z bezpiecznika

Zanim wyciągniesz jakiekolwiek wnioski, odłącz zasilanie w bezpieczniku na trzy minuty i przywróć je. To nie przesąd — płyta kuchenki, która wpadła w zły stan, potrafi zapisać usterkę grzewczą, której w normalnych warunkach by nie było, a czysty cykl zasilania ją kasuje. Jeśli E-08 wróci przy następnym pieczeniu, usterka jest realna i ruszasz dalej. Ten sam trzyminutowy reset otwiera ścieżkę diagnostyczną niemal każdego kodu z [listy kodów piekarników Samsung](https://pl.codefixcoffee.com/samsung-oven-error-codes/), więc warto wdrożyć go w nawyk.

## Grzałka pieczenia

Grzałka pieczenia to koń roboczy na dnie komory i psuje się widocznie. Przy włączonym piekarniku powinna świecić równomiernie na całej długości. Widoczna przerwa, pęcherz albo wypalony punkt na powierzchni to diagnoza, którą robisz gołym okiem — wymień ją. Grzałka kosztuje 30–60 € i należy do najbardziej opłacalnych napraw piekarnika w ogóle. Jeśli zaś świeci równo, ale piekarnik dalej nie trzyma temperatury, grzałka schodzi z listy podejrzanych, a na jej miejsce wchodzi czujnik — pełna ścieżka decyzyjna czeka na [stronie diagnostycznej E-08](https://pl.codefixcoffee.com/samsung/range-wall-oven/e-08/).

## Czujnik temperatury

Sonda odczytuje temperaturę komory i raportuje ją płycie jako rezystancję. W temperaturze pokojowej sprawny czujnik pokazuje około 1080 omów — i ta jedna liczba stanowi cały test:

1. Odłącz zasilanie w bezpieczniku.
2. Odkręć sondę od tylnej ściany komory (dwa wkręty) i odłącz wtyczkę.
3. Zmierz rezystancję: około 1080 omów w temperaturze pokojowej oznacza sprawny czujnik.
4. Przy poprawnym wyniku ponownie osadź wtyczkę; przy wyniku dalekim od wzorca wymień sondę.

Dwa pokrewne kody podpowiadają kierunek bez miernika. E-27 oznacza czujnik rozwarty — rezystancja za wysoka, powyżej około 2950 omów — co wskazuje na uszkodzoną sondę albo luźną wtyczkę. E-28 to odczyt zwarcia, poniżej około 930 omów — zwarta sonda lub przygnieciona wiązka za piekarnikiem. W obu przypadkach sama sonda kosztuje 20–40 € i wkręca się ją od wnętrza komory.

## Przekaźnik na płycie

Gdy grzałka świeci, a czujnik mierzy się poprawnie, zostaje płyta z przekaźnikami: sterownik nie przełącza zasilania na element grzejny. Przekaźnik, który nigdy się nie domyka, wygląda z wnętrza piekarnika dokładnie tak jak martwa grzałka. To scenariusz za 100–200 € i w starszej kuchence naturalny moment na porównanie wyceny naprawy z wartością całego urządzenia.

## Wariant z blokadą drzwi

Jedno zastrzeżenie przed zakupem części: w części modeli wsparcie Samsung notuje E-08 jako usterkę blokady drzwi, a nie układu grzania — silniczkowej blokady używanej przy samooczyszczaniu, a nie obwodu grzałki. Dlatego przed zamówieniem grzałki zajrzyj do instrukcji swojego modelu. Pokrewnym kodem dla blokady jest E-0E (wyświetlane jako E-0E albo FL), który zwykle pojawia się po cyklu samooczyszczania, gdy przełącznik blokady się zakleszcza albo pada silniczek; cały zespół blokady kosztuje 40–90 €. Nie forsuj drzwi w żadnym z tych przypadków — daj piekarnikowi całkowicie ostygnąć, bo na gorąco i tak się nie odblokuje.

## Kod na odwrotny problem

Skoro już jesteś w tej rodzinie usterek, poznaj [E-0A](https://pl.codefixcoffee.com/samsung/range-wall-oven/e-0a/): przegrzanie piekarnika. Wygląda jak zupełnie inna skarga, ale dzieli dwóch podejrzanych z E-08 — czujnik czytający błędnie (tym razem zaniżający) albo przekaźnik sklejony na stałe, przez co grzałka w ogóle się nie wyłącza. Do E-0A podchodź z większą pilnością niż do braku grzania: przyklejony przekaźnik znaczy, że grzałka świeci dalej, więc natychmiast odłącz zasilanie w bezpieczniku i nie używaj piekarnika, dopóki usterka nie zostanie naprawiona.

## Ile kosztują naprawy

Grzałka pieczenia 30–60 €, czujnik 20–40 €, zespół blokady drzwi 40–90 €, płyta z przekaźnikami 100–200 €. Grzałka i czujnik to jednoznaczne „tak" przy każdym rozsądnym wieku maszyny; płytę się już dyskutuje. Wizyta technika to 120–250 € za diagnozę plus część — uczciwa cena za potwierdzenie, która z trzech opcji jest tą właściwą.

### Wskazówka dla użytkowników w Polsce

Samsung prowadzi w Polsce szeroką sieć autoryzowanych serwisów obsługujących kuchenki i piekarniki, więc przed telefonem przygotuj dokładny numer modelu — znajdziesz go na tabliczce znamionowej na przedniej ramie, tuż po otwarciu drzwi. Z tym numerem pobierzesz instrukcję z [centrum wsparcia Samsung](https://www.samsung.com/pl/support/) i od razu sprawdzisz, czy Twój model nie należy do tych, w których E-08 dotyczy blokady drzwi. Podanie numeru serwisowi skraca diagnozę i chroni przed zamówieniem niewłaściwej części.
