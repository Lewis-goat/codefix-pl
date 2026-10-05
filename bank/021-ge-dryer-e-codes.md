---
title: Kody błędów suszarek GE: termistory, bezpieczniki i tachometr
description: Kody E1, E3–E6, E4, E8 i E11 suszarek GE: wyłącznik drzwi, czujniki NTC, bezpiecznik termiczny i tachometr — przyczyny, diagnostyka i koszty.
---

GE należy do nielicznych dużych producentów, którzy nie publikują oficjalnej listy kodów błędów swoich suszarek — pomocna bywa dopiero [strona producenta GE Appliances](https://www.geappliances.com/) z instrukcjami konkretnych modeli. Kody istnieją, płytka sterująca zapisuje je w pamięci, ale nikt nie tłumaczy właścicielom, co oznaczają. Da się jednak wychwycić schemat: usterki grupują się wokół czterech obszarów — obwodu drzwi, dwóch czujników temperatury, bezpieczników termicznych grzałki oraz silnika napędowego z tachometrem. W naszym [dziale suszarek GE](https://pl.codefixcoffee.com/ge/dryer/) opisujemy każdy kod osobno; ten tekst pokazuje, jak cała rodzina się zazębia i gdzie czekają pułapki związane z rocznikiem.

## Zanim zaczniesz: odczytaj zapisany kod

W suszarkach GTD i GFD z 2016 roku i nowszych ostatni zapisany błąd odczytasz samodzielnie. Przy wyłączonej suszarce przytrzymaj razem przyciski **Signal** i **Temp** przez pięć sekund — wejdziesz do trybu serwisowego, a na wyświetlaczu pojawi się najnowsza usterka. Jeśli maszyną steruje aplikacja SmartHQ, lista zapisanych kodów jest dostępna także tam. Chcesz jedynie wyczyścić pamięć? Odłącz suszarkę od zasilania na pięć minut.

## E1: obwód drzwi

[E1](https://pl.codefixcoffee.com/ge/dryer/e1/) oznacza, że płytka sterująca nie widzi zamkniętych drzwi. Zdecydowanie częściej to usterka mechaniczna niż elektroniczna: zużyta zapadka, wygięty języczek zaczepu albo wyłącznik, który przestał klikać.

- Zamknij drzwi zdecydowanie i naciśnij Start — niedomknięte drzwi to najczęstsza przyczyna.
- Obejrzyj języczek zaczepu w drzwiach: wygięta lub urwana blaszka nie naciska wyłącznika.
- Odłącz zasilanie, zdejmij panel przedni i sprawdź wtyczkę wyłącznika drzwi; wyłącznik, który przyciskany nie klika, nadaje się do wymiany — część kosztuje ok. 10–25 €.

## E3 do E6: czujniki temperatury

Suszarki GE monitorują temperaturę powietrza dwoma czujnikami NTC: wlotowym na obudowie grzałki oraz wylotowym na obudowie wentylatora. [Rodzina E3–E6](https://pl.codefixcoffee.com/ge/dryer/e3-to-e6/) zapala się, gdy któryś z nich ma przerwę albo zwarcie. Nie zawsze winny jest sam czujnik — luźne lub skorodowane okablowanie odpowiada za podobną liczbę przypadków, a naprawdę zapchany kanał wydechowy potrafi przegrzać zdrową suszarkę na tyle, że czujniki zgłoszą alarm.

1. Odłącz zasilanie na 30 sekund i uruchom maszynę ponownie.
2. Wyczyść filtr włókien i upewnij się, że cała trasa wydechowa jest drożna.
3. Otwórz obudowę i sprawdź wtyczki czujników oraz wiązkę pod kątem luźnych, skorodowanych styków.
4. Zmierz czujnik omomierzem — w temperaturze pokojowej prawidłowa wartość to ok. 10 kΩ; przerwa oznacza wymianę.

Nowy czujnik NTC to wydatek rzędu 10–25 €. Uwaga: w części modeli E6 to zamiast tego kod ograniczonego przepływu powietrza, więc przed zakupem części potwierdź znaczenie dla swojego wariantu.

## E4: bezpiecznik termiczny

[E4](https://pl.codefixcoffee.com/ge/dryer/e4/) to kod braku grzania: bęben się kręci, ale pranie nie schnie, bo zadziałał bezpiecznik termiczny. Bezpiecznik nie przepala się bez powodu — ograniczony przepływ powietrza (filtry, zapchany kanał) pozwala grzałce się przegrzać i rozerwać obwód. Najpierw przywróć drożność, bo inaczej nowy bezpiecznik poleci tak samo szybko. I pod żadnym pozorem nie mostkuj bezpiecznika: to jedyna część, która nie pozwala, żeby prawdziwe przegrzanie skończyło się pożarem.

1. Wyczyść filtr włókien i całą trasę wydechową aż do wylotu na zewnątrz.
2. Zmierz bezpiecznik termiczny i termostat graniczny na obudowie grzałki; wymień element z przerwą.
3. Uruchom krótki cykl z chwilowo odłączonym kanałem, żeby potwierdzić powrót grzania, po czym podłącz wszystko z powrotem.

Sam bezpiecznik kosztuje 5–15 €, termostat graniczny 10–25 €.

## E8 i E11: tachometr i silnik

[E8](https://pl.codefixcoffee.com/ge/dryer/e8/) to kod tachometru we współczesnych suszarkach GE: płytka sterująca załączyła silnik, ale nie doczekała się sygnału o prędkości obrotów. Przyczyny bywają różne — luźne przewody tachometru, zakleszczony bęben (zrzucony pasek albo ciało obce za nim), wreszcie awaria samego tachometru lub silnika. Ponieważ tachometr jest częścią zespołu napędowego, potwierdzona jego awaria oznacza wymianę silnika za 80–150 €; pasek to wydatek 15–25 €.

E11 dotyczy tej samej okolicy, ale inaczej: silnik nie wykonuje tego, czego żąda płytka. Winowajcą bywa zużyty pasek, zakleszczona rolka bębna, a czasem włącznik rozruchowy silnika lub sam silnik. Zanim cokolwiek wymontujesz, zakręć bęben ręką — wyraźny opór wskazuje na rolki lub łożyska, a nie na silnik. Silnik, który buczy i nie rusza przy zdjętym pasku, do wymiany; komplet rolek to 20–40 €.

## Różnice między rocznikami

Trzy pułapki łapią użytkowników najczęściej. Po pierwsze, ten sam numer nie zawsze oznacza tę samą usterkę: w starszych egzemplarzach i wersjach kombi E8 dotyczy oświetlenia bębna albo odprowadzania wody, a nie tachometru — ustal dokładnie, jaką masz suszarkę, zanim kupisz części. Po drugie, E6 bywa kodem przepływu powietrza albo kodem czujnika, zależnie od modelu. Po trzecie, tryb serwisowy Signal+Temp opisany wyżej działa w maszynach GTD/GFD od 2016 roku; w starszych pozostaje ci to, co wyświetlacz pokaże w momencie awarii. Rodzinę dopełniają E7 (problem z zasilaniem — suszarka nie widzi obu połówek swojego zasilania) oraz E14 (zakleszczony przycisk na panelu); żaden z nich nie dotyczy grzania.

### Suszarki GE w Polsce

W Polsce suszarki GE trafiają się niemal wyłącznie jako import z USA, więc przed podłączeniem sprawdź tabliczkę znamionową i skonsultuj zasilanie z elektrykiem — amerykańskie egzemplarze różnią się systemem wtyczek i częstotliwością sieci. Części zamienne (czujniki NTC, bezpieczniki, paski) zamawiaj po pełnym numerze modelu z tabliczki; polskie sklepy sprowadzają je zwykle na zamówienie, co wydłuża dostawę o kilka dni. Przy suszarce z wydmuchem kontroluj też wylot przewodu na zewnątrz — latem blokuje go kurz, a zimą szron i nawiany śnieg.

## Ile kosztują naprawy

Naprawy na poziomie czujników i wyłączników są tanie: wyłącznik drzwi 10–25 €, czujniki NTC 10–25 €, bezpieczniki termiczne 5–15 €, paski 15–25 €, rolki bębna 20–40 €. Najdroższy jest silnik napędowy — 80–150 € — i w starszej suszarce to już decyzja ekonomiczna, a nie oczywista konieczność. Wizyta technika to ok. 120–250 € za diagnozę plus część; przy pracach w obwodzie silnika to rozsądny wydatek, jeśli nie chcesz otwierać obudowy samodzielnie.
