---
title: "Jura błędy 1–5: rodzina termoblokowa od podszewki"
description: "Błędy 1–5 w Jurze dotyczą termobloków, czujników NTC i bezpieczników termicznych. Który kod odpowiada której części i na czym polega pułapka błędu 2?"
---

Kody od 1 do 5 wyglądają w Jurze jak losowy ciąg cyfr, a jednak łączy je jedno: ciepło. Każdy z nich prowadzi do termobloków — kompaktowych, przepływowych grzałek produkujących wodę do kawy i parę — albo do czujników i kordów bezpieczników termicznych, które nad tymi grzałkami czuwają. Gdy raz ogarniesz logikę tej rodziny, sam numer kodu podpowiada, która grzałka się skarży i czy problem leży w pomiarze, w temperaturze czy w zasilaniu.

## Dwa termobloki, pięć kodów

W ekspresie Jura pracują dwa termobloki: kawowy podgrzewa wodę do zaparzania, a parowy zasila sekcję pary i gorącej wody. Każdy ma własny czujnik NTC — rezystor, którego opór zmienia się wraz z temperaturą — meldujący płycie sterującej bieżący stan, i każdy chronią kordy z bezpiecznikami termicznymi, odcinające zasilanie przy przegrzaniu. Błędy 1–5 to język, którym płyta komunikuje, że jeden z tych elementów szwankuje:

- **Błędy 1 i 2** wskazują obwód czujnika termobloku kawowego.
- **Błędy 3 i 4** dotyczą termobloku parowego — odczyt zbyt niski albo przegrzanie.
- **Błąd 5** sygnalizuje, że sama grzałka nie dorabia.

## Strona kawowa

### Błąd 1: usterka czujnika termobloku kawowego

[Błąd 1](https://pl.codefixcoffee.com/jura/automatic-machines/error-1/) oznacza, że płyta nie potrafi wyciągnąć sensownej wartości z czujnika temperatury termobloku kawowego — w rodzinach S, X, J i Z to klasyczna usterka sensora, a w modelach F i E80 zwykle uszkodzenie mechaniczne czujnika. Warto znać jedną osobliwość: maszyna dopiero co dowieziona z zimnego samochodu lub garażu potrafi zgłosić ten kod, choć nic w niej nie jest zepsute. Jeśli pojawia się na rozgrzanym ekspresie i natychmiast wraca po restarcie, obwód czujnika jest rozwarty — winny jest czujnik, jego przewód albo kordy bezpieczników termicznych zasilające blok.

### Błąd 2: czujnik przerwany — albo ekspres po prostu zmarzł

[Błąd 2](https://pl.codefixcoffee.com/jura/automatic-machines/error-2/) to najczęstszy kod Jury w ogóle i ma dwie twarze. Wersja niegroźna: temperatura maszyny spadła poniżej około 10 °C i grzałka celowo pozostała zablokowana do czasu ogrzania — typowe przy dostawach zimą albo dla ekspresu stojącego w chłodnym pomieszczeniu. Wersja poważna: czujnik termobloku kawowego lub kordy bezpieczników termicznych rozwarły obwód.

Diagnozą jest test rozgrzewania. Doprowadź maszynę do temperatury pokojowej — użytkownicy dmuchują pięć minut suszarką na niskim biegu w głąb wnęki zbiornika wody albo wypełniają zbiornik letnią (nie gorącą) wodą — i zrestartuj ją. Kod znika? Nic nie jest zepsute, tylko ustaw ekspres w cieplejszym miejscu. Utrzymuje się na ciepłej maszynie? Obwód czujnika jest rozwarty i wewnątrz trzeba sprawdzić NTC oraz kordy bezpieczników.

## Strona parowa

### Błąd 3: termoblok parowy raportuje za niską temperaturę

[Błąd 3](https://pl.codefixcoffee.com/jura/automatic-machines/error-3/) jest parowym lustrem błędu 1: termoblok parowy nie zgłasza temperatury — przez czujnik, jego przewód albo dlatego, że maszyna wciąż jest zbyt zimna. Jest i dodatkowy trop: gruba warstwa kamienia spowalnia nagrzewanie na tyle, że niektóre wersje oprogramowania przerywają kontrolę, więc pełne odkamienianie powinno wyprzedzać jakikolwiek demontaż. Po otwarciu obejrzyj przewód czujnika w miejscu, w którym się zgina.

### Błąd 4: termoblok parowy się przegrzewa

[Błąd 4](https://pl.codefixcoffee.com/jura/automatic-machines/error-4/) trzeba traktować poważnie. Termoblok parowy rozgrzał się ponad to, czego oczekiwała elektronika — albo czujnik zaniża odczyt (kamień izolujący sensor, skorodowane styki), albo płyta zasilająca nie odcięła grzałki. Sam producent wskazuje błędy 2 i 4 jako dwie najczęstsze naprawy. Po ostudzeniu i odkamienieniu pierwszą wymianą jest czujnik; jeśli blok przegrzewa się ponownie z nowym NTC, płyta nie wyłącza grzałki i wymaga wymiany (budżet 120–250 €). Grzałka, która nie chce się wyłączyć, to ryzyko pożaru — nie zostawiaj maszyny pod napięciem bez nadzoru, dopóki ten kod jest aktywny.

### Błąd 5: grzałka nie osiąga temperatury

[Błąd 5](https://pl.codefixcoffee.com/jura/automatic-machines/error-5/) znaczy, że grzałka dostała polecenie grzania, a temperatura ani drgnęła. W Jurze winne są niemal zawsze kordy bezpieczników termicznych chroniące termoblok — przepadają po epizodzie przegrzania albo po prostu z wiekiem; drugą możliwością jest martwy element termobloku. Zbyt zimna maszyna też potrafi wywołać ten kod, więc najpierw ją ogrzej. Wewnątrz zmierz oba kordy i element: to, co pokazuje przerwę, jest częścią do wymiany — a następnie ustal, dlaczego bezpieczniki padły (kamień, zapieczony przekaźnik albo praca na sucho po opróżnieniu zbiornika).

## Części spinające całą rodzinę

W całej tej rodzinie kodów powracają dwaj bohaterowie: kordy bezpieczników termicznych i czujniki NTC. Oryginalny NTC Jury kosztuje około 25–40 €, zestaw kordów 15–30 €, a termoblok 90–180 €. Przy wymianie czujnika praktycy zawsze wymieniają razem z nim kordy bezpieczników. Jest też wzorzec, który naprawdę ma znaczenie: kord pękający ponownie w ciągu kilku dni nie był pechowy — to płyta zasilająca zatrzaskuje grzałkę w trybie pracy.

Pamiętaj, że obudowy Jury trzymają śruby zabezpieczające, a termobloki pracują na napięciu sieciowym — ta rodzina to naprawa warsztatowa, chyba że masz odpowiednie przygotowanie. Naprawa broni się w maszynach S, Z, GIGA i nowszych seriach E; przy dziesięcioletniej Impressie porównaj wycenę z ceną egzemplarza po regeneracji. Aktualne instrukcje i dane serwisowe publikuje [oficjalna strona Jura](https://www.jura.com), a pozostałe kody zbiera [indeks błędów Jura](https://pl.codefixcoffee.com/jura/).

### Polska wskazówka: zima i domy letniskowe

W Polsce błąd 2 potrafi występować sezonowo — ekspres dowieziony kurierem w mrozie albo stojący zimą w nieogrzewanym pokoju lub domu letniskowym łatwo schładza się poniżej 10 °C. Po transporcie w niskiej temperaturze daj maszynie kilka godzin w cieple, zanim ją włączysz: chroni to elektronikę także przed skropleniami. Dopiero gdy kod wraca mimo rozgrzanej obudowy, szukaj usterki w obwodzie czujnika.
