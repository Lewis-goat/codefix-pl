---
title: Breville/Sage Oracle — para i kody ER: co sprawdzić najpierw
description: Usterki pary w Breville/Sage Oracle: znaczenie kodów Error/ER po stronie pary, procedura przedmuchania na start i kiedy winna jest tylko skala.
---

Strona parowa ekspresu Oracle to jego najbardziej pracowite miejsce: stalowy bojler pary, rurka z automatycznym spienianiem mleka, sondy poziomu i pompa do napełniania, wszystko utrzymywane w temperaturze roboczej codziennie. To również źródło dużej części kodów błędów maszyny. Rodzina Oracle korzysta z 32-pozycyjnej tabeli serwisowej, której Breville nie publikuje, a w Wielkiej Brytanii ten sam sprzęt nosi odznakę **Sage** — kody są identyczne. Zanim założysz awarię podzespołu, wykonaj najpierw tanie kontrole: większość zatrzymań po stronie pary to zapchana końcówka rurki, pominięty przedmuch albo kamień osadzony na sondzie.

## Gdzie w tabeli Oracle mieszają się kody parowe

Oracle (BES980) i Oracle Touch (BES990) współdzielą jedną tabelę; BES980 pokazuje wpisy jako „Error 1” do „Error 32”, a BES990 dodaje przedrostek ER. Wpisy związane z parą kumulują się w pięciu miejscach:

- **Error 1–4** — czujnik temperatury bojlera pary w czterech wariantach: rozwarcie obwodu przy starcie, utrata sygnału w trakcie pracy oraz zwarcie w obu tych sytuacjach. Jedna sonda, cztery sposoby zgłoszenia.
- **Error 13–16** — ten sam kwartet dla czujnika temperatury samej rurki parowej, sondy przerywającej spienianie po osiągnięciu właściwej temperatury mleka. Pracuje w najwilgotniejszym miejscu całej maszyny.
- **Error 18** — bojler pary nie nagrzewa się prawidłowo.
- **Error 20 i 21** — problemy z poziomem wody w bojlerze lub z pompą napełniającą oraz odczyt sondy poziomu niespójny z tym, czego oczekuje płyta.
- **Error 26** — bojler pary przegrzał się powyżej wartości zadanej; **Error 32** to wyciek z bojlera pary albo nieudane napełnienie.

Nie wszystko w okolicy rurki jest przy tym „parowe”: kody 5–8 należą do czujnika bojlera kawy, a [Error 8](https://pl.codefixcoffee.com/breville/oracle-bes980/error-8/) to jego pozycja „zwarcie w trakcie pracy”. Rozdzielenie obu rodzin ułatwia odczyt dziennika — na BES980 przytrzymaj jednocześnie 1 CUP, 2 CUP i POWER przy wyłączonej maszynie, żeby otworzyć Error Storage i przejrzeć wszystkie 32 kody wraz z licznikami.

## Od czego zacząć: procedura przedmuchania

Słaba, „plująca” para albo kod wyświetlony tuż po napoju mlecznym wskazują zwykle na końcówkę rurki, a nie na bojler:

1. Odłącz maszynę od zasilania i pozwól rurce ostygnąć.
2. Wykręć końcówkę pary i namocz ją w gorącej wodzie z odrobiną środka do odkamieniania; każdy otwór przeczyść igłą z dołączonego narzędzia do czyszczenia.
3. Wykonaj przedmuch — około dziesięć sekund pary do tacy kroplowej bez końcówki, a potem jeszcze raz z zamocowaną końcówką.
4. Odtąd przedmuchuj rurkę po każdej sesji z mlekiem; zaschnięte mleko w końcówce to punkt startowy większości tego typu zatrzymań.

Jeśli maszyna monitoruje ciśnienie pary — jak Oracle Jet ze swoim kodem E16 — zabrudzona końcówka potrafi wywołać błąd, zanim jeszcze zauważysz, że para osłabła.

## Twardość wody, kamień i sondy poziomu

Przy twardej wodzie kamień pisze własne kody błędów. Sondy poziomu bojlera pary siedzą stale w gorącej wodzie, a kamienna powłoka działa jak izolator: płyta odczytuje „brak wody”, mimo że bojler jest pełny — i to jest klasyczna droga do Error 20 oraz 21, a także do nieudanego napełniania z Error 32. Osad odkłada się dodatkowo w torze rurki i na wlocie pompy napełniającej. Pełne odkamienianie, obejmujące cykl bojlera pary, to najtańsza diagnostyka, jaką możesz przeprowadzić, i samodzielnie usuwa zaskakująco wiele z tych kodów.

Ten sam wniosek podsuwa bliźniaczy model z rodziny: Dual Boiler chowa kody 00–12 w menu autodiagnostyki, a [kod 00](https://pl.codefixcoffee.com/breville/dual-boiler-bes920/00/) — brak wykrycia czujnika bojlera pary — otwiera tabelę, której pozycje dotyczące poziomu i napełniania zachowują się pod twardą wodą dokładnie tak samo.

## Kiedy odkamieniać, a kiedy rozbierać

Najpierw odkamienianie, potem demontaż — ale warto znać granicę, za którą środek już nie pomaga:

- **Odkamieniaj w pierwszej kolejności** przy kodach poziomu, sond i napełniania (20, 21, 32), przy słabej parze bez żadnego kodu oraz na każdej maszynie, której ostatni cykl minął ponad trzy miesiące temu. Koszt: butelka odkamieniacza.
- **Odkamienianie nie pomoże**, gdy kod czujnika wraca natychmiast na świeżo odkamienionej, rozgrzanej maszynie — niezależnie od tego, czy to pozycja parowa z zakresu 1–4, czy [Error 8](https://pl.codefixcoffee.com/breville/oracle-bes980/error-8/) po stronie kawy. Kod, który przeżywa odkamienianie, wskazuje na samą sondę, jej przewód lub złącze.
- **Zatrzymaj się i sprawdź uszczelki**, jeśli Error 26 wraca: nieszczelny o-ring sondy parowej przepuszcza parę, która nagrzewa przewód czujnika i naśladuje rozpędzający się bojler. Nowe o-ringi sondy są tanie; płyta z triakiem, który nie potrafi wyłączyć grzałki — już nie.
- **Error 18** na maszynie, która w ogóle przestała grzać parę, leży zwykle po stronie grzania — bezpiecznik termiczny, grzałka lub płyta sterująca — a nie kamienia, więc traktuj go jako naprawę, nie jako porządki.

Przy demontażu końcówek i sond przydadzą się fotografie krok po kroku — solidną bazę przewodników naprawczych stanowi [iFixit](https://www.ifixit.com).

## Ile kosztują te części

Oryginalne zestawy czujników temperatury to około €25–95 w zależności od sondy; zespoły rurki parowej, zawierające własny czujnik, kosztują ok. €60–95; zestaw sondy z o-ringami ok. €85, a pompa napełniająca €30–60. Na tym tle fabryczne wyceny usterek wewnętrznych poza gwarancją — zwykle €300–500 — sprawiają, że butelka odkamieniacza na start, a wymiana sondy w niezależnym serwisie w drugiej kolejności to niemal zawsze lepsza arytmetyka. Oryginalne części i wsparcie do maszyn Sage znajdziesz na [stronie Sage Appliances](https://www.sageappliances.co.uk), a Sage-ową wersję tabel kodów w [brytyjskiej edycji serwisu](https://pl.codefixcoffee.com/uk/).

### Woda z polskiego kranu a bojler pary

W większości polskich miast woda wodociągowa jest średnio twarda lub twarda — zwłaszcza na południu kraju, na przykład w Krakowie czy na Śląsku — co wyraźnie przyspiesza osadzanie kamienia w bojlerze pary i na sondach poziomu. Do ekspresu z bojlerem lepiej używać wody filtrowanej (dzbanek z filtrem lub filtr węglowo-jonowy) albo butelkowanej o obniżonej twardości. W takich warunkach odkamienianie warto planować częściej, niż sugeruje wskaźnik maszyny — w praktyce co dwa, trzy miesiące.
