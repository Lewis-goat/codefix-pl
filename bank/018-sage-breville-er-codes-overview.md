---
title: Kody ER Sage/Breville — jak czytać ukrytą tabelę serwisową
description: Ekspresy Sage i Breville pokazują kody ER z niepublikowanej tabeli serwisowej. Zobacz, jak działa numeracja ER01–ER18 i dlaczego Oracle liczy inaczej.
---

Gdy ekspres Breville zatrzyma się nagle i pokaże na panelu ER05, instrukcja nie powie Ci, co to znaczy. I nie jest to przeoczenie: kody błędów Breville pochodzą z wewnętrznych tabel serwisowych, których firma używa przy naprawach i nie publikuje ich właścicielom. Ten sam sprzęt sprzedawany jest w Wielkiej Brytanii pod marką **Sage** — maszyny są identyczne, różni się tylko logo na obudowie — dlatego kod ER na Sage Barista Touch znaczy dokładnie to samo co na odpowiedniku Breville. [Sekcja Breville/Sage](https://pl.codefixcoffee.com/breville/) obejmuje aktualną ofertę; ten wpis tłumaczy logikę numeracji, żeby także zupełnie nieznany kod powiedział Ci coś użytecznego.

## Dlaczego Breville nie publikuje kodów

Instrukcja użytkownika dotyczy czyszczenia i odkamieniania, nie diagnostyki. Pełne tabele siedzą w trybie serwisowym każdego modelu: chronione hasłem ekrany przygotowane dla techników, z licznikami zapisanych błędów i odczytami czujników na żywo. Skoro kody są narzędziem naprawczym, a nie funkcją konsumencką, Breville nigdy nie wydało ich w publicznym dokumencie — większość właścicieli widzi w życiu jeden jedyny kod: ten, który właśnie wyłączył maszynę. Kontrast z Miele jest wyraźny: tam znaczenia kodów F są wydrukowane w instrukcji obsługi, dlatego [strony kodów Miele](https://pl.codefixcoffee.com/miele/) mogą cytować podręcznik wprost.

## Tabela Barista Touch: od ER01 do ER18

Barista Touch (BES880) i Barista Touch Impress (BES881) — spokrewnione płyty sterujące, wspólna tabela — korzystają z 18 pozycji. Po odszyfrowaniu struktury czyta się ją łatwo: kody czujników przychodzą **grupami po cztery**, po jednej na czujnik, cyklicznie przechodząc przez rozwarcie obwodu przy starcie, rozwarcie w trakcie pracy, zwarcie przy starcie i zwarcie w trakcie pracy.

- **ER01–ER04** — czujnik temperatury grzałki ThermoJet we wszystkich czterech wariantach. [ER01](https://pl.codefixcoffee.com/breville/barista-touch-bes880/er01/) to pozycja „rozwarcie przy starcie”.
- **ER05–ER08** — czujnik temperatury dzbanka mlecznego, mała sonda przy obszarze tacy odczytująca dzbanek, gdy rurka spienia mleko. ER05, czyli rozwarcie przy starcie, to zdecydowanie najczęściej zgłaszany kod Barista Touch i wszystkie cztery pozycje leczy ten sam zabieg.
- **ER09–ER12** — przepływowy czujnik temperatury wody parzenia, według identycznego wzoru czterech wariantów.
- **ER13 i ER14** — błędy zliczania przepływu, przy starcie i w pracy: pompa pracowała, ale maszyna nie potrafiła policzyć przepływającej wody.
- **ER15** — usterka komunikacji między wewnętrznymi modułami elektronicznymi; częściej poluzowana taśma lub mokry złącze niż martwa płyta.
- **ER16 i ER17** — młynek: przegrzany silnik, który wyłączył się w trybie ochronnym, a następnie silnik, który nie wykonał zadania w wyznaczonym czasie.
- **ER18** — zabezpieczenie E-fast, usterka elektryczna lub bezpieczeństwa, np. prąd upływowy; to kod, który potrafi wybić także wyłącznik różnicowoprądowy w Twoim gniazdku.

## Oracle numeruje po swojemu

W rodzinie Oracle ten sam pomysł dostaje dłuższą tabelę. Oracle (BES980) i Oracle Touch (BES990) dzielą listę 32 pozycji, przy czym BES980 wyświetla je jako „Error 1” do „Error 32”, a BES990 dodaje przedrostek ER. Pierwszych szesnaście wpisów podąża za logiką kwartetów czujnikowych: bojler pary w pozycjach 1–4, bojler kawy w 5–8 (z [Error 8](https://pl.codefixcoffee.com/breville/oracle-bes980/error-8/) jako zwarciem czujnika bojlera kawy w trakcie pracy), podgrzewana głowica w 9–12, rurka parowa w 13–16. Dalsza część tabeli obejmuje niedogrzewające się bojlery (17–19), poziom i napełnianie bojlera pary (20 i 21), problemy z przepływomierzem (22 i 23), sondy poziomu i przegrzewanie (24–27), błąd komunikacji płyt pod numerem 28, młynek (29 i 30), silnik ubijania kawy (31) oraz wyciek z bojlera pary albo nieudane napełnienie pod pozycją 32.

Dwie mniejsze tabele domykają rodzinę. Oracle Jet (BES985) ma własną, krótszą listę od E1 do E19, a Dual Boiler (BES920) ukrywa dwucyfrowe kody 00–12 w menu autodiagnostyki zamiast na zwykłym wyświetlaczu — Dual Boiler potrafi więc stać na usterce, której nigdy nie zobaczyłeś na ekranie.

## Jak samodzielnie odczytać ukryty dziennik błędów

Skoro tabele są danymi serwisowymi, historię swojej maszyny odczytasz tymi samymi ekranami serwisowymi. Ścieżki mają techniczny charakter, ale warsztaty dobrze je udokumentowały:

- **Barista Touch i Oracle Touch** — wyłącz maszynę przy gniazdku, przytrzymaj przedni przycisk Power włączając zasilanie ze ściany, puść, gdy pojawi się logo, wpisz hasło serwisowe 00000, a następnie otwórz Error Counter (zapisane usterki) albo Live Debug (temperatury i poziomy wody na żywo).
- **Barista Touch Impress** — identyczna sekwencja przycisków, ale hasłem serwisowym jest 02015.
- **Oracle BES980** — przy podłączonej do prądu, wyłączonej maszynie przytrzymaj razem 1 CUP, 2 CUP i POWER przez co najmniej sekundę; po długim sygnale naciśnij pokrętło SELECT, żeby otworzyć Error Storage i przejrzeć błędy 1–32 wraz z zapisanymi licznikami.

Traktuj te ekrany wyłącznie jako podgląd: zanotuj, co jest zapisane, nie ruszaj ustawień, a dziennik czyść dopiero po wykonanej naprawie — dopiero wtedy zobaczysz, czy kod faktycznie wraca.

## Ile kosztują takie naprawy

Nawet wobec niepublikowanej tabeli ekonomia jest przewidywalna. Zestawy czujników temperatury to około €25–95 w zależności od sondy (czujniki rurki parowej i dzbanka mlecznego należą do droższych), a zestawy o-ringów €10–20; kit naprawczy czujnika mleka kosztuje ok. €30–50 wobec €80–95 za oryginalny moduł. Fabryczne wyceny usterek wewnętrznych poza gwarancją mieszczą się zwykle w €300–500, więc naprawa na poziomie czujnika w niezależnym warsztacie prawie zawsze wychodzi korzystniej. Oryginalne instrukcje i pomoc marki Sage znajdziesz na [stronie Sage Appliances](https://www.sageappliances.co.uk), a Sage-ową wersję tych tabel w [brytyjskiej edycji serwisu](https://pl.codefixcoffee.com/uk/).

### Polska praktyka: import, gwarancja i wtyczka

Marka Sage/Breville nie ma oficjalnej dystrybucji w Polsce, więc maszyny trafiają do nas niemal wyłącznie importem — najczęściej z Wielkiej Brytanii — i gwarancja producenta bywa realizowana tylko w kraju zakupu. Brytyjska wtyczka (typ G) nie wejdzie do polskiego gniazdka: potrzebna jest przejściówka albo wymiana wtyczki na europejską, najlepiej wykonana przez elektryka. Przy okazji sprawdź tabliczkę znamionową — egzemplarze przeznaczone na rynek USA zasilane są napięciem 120 V i w polskiej instalacji uległyby uszkodzeniu.
