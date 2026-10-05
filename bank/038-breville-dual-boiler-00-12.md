---
title: Breville Dual Boiler BES920 — dwucyfrowe kody 00–12
description: Kody 00–12 w ekspresie Breville (Sage) Dual Boiler BES920 zobaczysz tylko w ukrytym menu serwisowym. Rozszyfrowujemy bloki kodów i sposoby napraw.
---

Większość ekspresów Breville ogłasza usterki na zwykłym wyświetlaczu: Barista Touch pokazuje kody ER, Oracle kody „Error", a Oracle Jet numerację z literą E. **Dual Boiler BES920** poszedł własną drogą. Jego tabela błędów to proste kody dwucyfrowe, **od 00 do 12**, ukryte w serwisowym menu self-check, a nie na codziennym ekranie. Nie zobaczysz ich, obserwując panel w zwykły dzień — trzeba znać kombinację przycisków.

Numeracja zasługuje na chwilę uwagi, bo jest wyjątkowo schludna: blok, w którym leży kod, mówi o rodzaju usterki, a wewnątrz bloku kod wskazuje część, która się skarży.

## Odczyt dziennika błędów

Do dziennika wchodzisz z menu serwisowego:

1. Wyłącz ekspres przy gniazdku.
2. Przytrzymaj **EXIT** i **MANUAL** i w tym czasie przywróć zasilanie — pojawi się menu self-check.
3. Naciśnij **MENU**, żeby dojść do pozycji 3, czyli dziennika błędów. Pozycja 4 pokazuje poziom w bojlerach, raportowany jako LLL (niski) lub HHH (wysoki).
4. W dzienniku **MENU** przewija kody od 00 do 12, każdy z zapisaną liczbą wystąpień.
5. Na pozycji „ErSt" przytrzymaj **MANUAL**, aż usłyszysz sygnał — skasuje to zgromadzone kody; licznik filiżanek zostaje nietknięty.

Liczby wystąpień mówią nie mniej niż same kody. Usterka z jedynką sprzed roku to historia; kod, którego licznik rośnie co tydzień, to żywy problem, który właśnie się buduje.

## Co obejmuje rodzina kodów 00

Kody **00–05** tworzą blok czujników temperatury ułożony w trzy pary. W każdej parze niższy numer oznacza czujnik **niewykrywany** — płyta odczytuje go jako przerwę w obwodzie — a wyższy oznacza odczyt wskazujący na **zwarcie**:

- **00 i 01** — czujnik temperatury bojlera pary, niewykryty, potem zwarcie.
- **02 i 03** — czujnik temperatury bojlera kawy, niewykryty, potem zwarcie.
- **04 i 05** — czujnik temperatury podgrzewanej grupy, niewykryty, potem zwarcie.

BES920 ma dwa stalowe bojlery oraz podgrzewaną grupę, więc te trzy czujniki pilnują trzech stref grzewnych maszyny. [Strona kodu 00](https://pl.codefixcoffee.com/breville/dual-boiler-bes920/00/) zajmuje się czujnikiem bojlera pary, ale jej praktyczne rady przenoszą się na pozostałą piątkę: zanim kupisz części, ponownie osadź i obejrzyj wtyczkę czujnika oraz poszukaj wilgoci — woda spięta na złączu raz czyta się jak przerwa, raz jak zwarcie, zależnie od tego, jak woda ułoży się w złączu. Oryginalne zestawy z czujnikiem NTC kosztują około 25–90 € zależnie od wariantu; zestawy o-ringów to 10–20 € i to one często są prawdziwym winowajcą.

## Strona pary kontra strona parzenia

Reszta tabeli dzieli się wzdłuż tej samej linii sprzętowej co pary czujników:

- **Bojler pary:** 06 (problem z pompą przy starcie), 07 (poziom wody lub usterka pompy) oraz 11 (wykryte przegrzanie).
- **Bojler kawy, czyli strona parzenia:** 08 (pompa albo przepływ), 09 (poziom wody) i 10 (przegrzanie).
- **Grupa:** 12 (przegrzanie).

### Kody, które trzymają się razem

Te usterki się zazębiają, dlatego przeczytanie całego dziennika wygrywa z czytaniem jednego kodu. Kod 08 oznacza, że pompa pracowała, a przepływomierz nie zobaczył nic — najczęściej osad na łopatce przepływomierza albo mała pompa bucząca bez ruchu wody, więc odkamienianie jest w obu wypadkach pierwszym ruchem. Kod 11, czyli przegrzanie bojlera pary, zwykle następuje po bojlerze, którego nikt nie uzupełnia — sprawdź, czy 07 albo 08 też ma licznik — bo grzałka grzeje dalej niemal pusty zbiornik; drugą przyczyną bywa nieszczelna uszczelka sondy. Zanim cokolwiek zamówisz, zajrzyj do pozycji 4 menu serwisowego: status poziomu sprzeczny z tym, co słyszysz przy napełnianiu, wskazuje stronę, na której naprawdę siedzi usterka.

Kod 12, przegrzanie grupy, to rzadszy koniec tabeli i ten, gdzie powtarzalność znaczy najwięcej — przegrzanie wracające w kółko wskazuje na płytę zasilającą, która trzyma grzałkę włączoną, a nie na dryf czujnika. Rozkłada to na czynniki [strona kodu 12](https://pl.codefixcoffee.com/breville/dual-boiler-bes920/12/).

## Ile kosztują części

- Odkamieniacz przy kodach przepływu i poziomu: około 10 €, a załatwia realną część przypadków.
- Pompa napełniająca: 30–60 €.
- Sonda bojlera pary z zestawem o-ringów: około 85 €; same o-ringi 10–20 €.
- Bezpiecznik termiczny: 10–20 € — ale najpierw ustal, dlaczego przepalił.
- Triak lub płyta zasilająca: 80–150 €.

Po gwarancji serwis wycenia usterki wewnętrzne Dual Boilera zwykle na 300–500 € i więcej, więc pompa czy czujnik to naprawa warta wykonania we własnym zakresie; przy płycie w starszej maszynie najpierw poproś o wycenę. Woda i sieć elektryczna spotykają się na szczycie bojlera — odłącz wtyczkę, zanim dotkniesz sond.

### Zakup i zasilanie w Polsce

Na polskim rynku BES920 sprzedawany jest jako Sage Dual Boiler i egzemplarze z oficjalnej dystrybucji pracują na 230 V z lokalną wtyczką — maszyny przywiezione z Wielkiej Brytanii mają wtyczkę brytyjską, którą przy urządzeniu pobierającym około 2,4 kW warto na stałe wymienić, zamiast sięgać po przejściówki. Ekspres podłącz do solidnego gniazda wtykowego, najlepiej bez przedłużaczy i listew zasilających. Po gwarancji opłaca się też rozejrzeć za niezależnym serwisem ekspresów — płytę zasilającą często da się naprawić taniej, niż kupując nową.

Sposobem, w jaki pozostałe maszyny z rodziny formułują swoje kody, zajmuje się [dział Breville](https://pl.codefixcoffee.com/breville/) — konstrukcje z kodami ER dzielą pomysły diagnostyczne, ale nie numerację. W Europie marka występuje jako Sage — instrukcje i materiały pomocnicze znajdziesz na [stronie Sage Appliances](https://www.sageappliances.co.uk), a czytelnicy z Wysp mogą korzystać z [brytyjskiej edycji](https://pl.codefixcoffee.com/uk/) serwisu.
