---
title: "De'Longhi General Alarm: co ten komunikat naprawdę oznacza"
description: "General Alarm to komunikat-worek De'Longhi, zapisywany jako kod 1101 lub 1512. Co zwykle oznacza, dziesięciominutowa naprawa infuzora i kiedy odpuścić."
---

Ze wszystkiego, co automatyczny ekspres De'Longhi potrafi pokazać na wyświetlaczu, komunikat General Alarm brzmi najgroźniej, a mówi najmniej. I to nie przypadek. Maszyny De'Longhi pokazują głównie słowa, nie kody: Magnifica, Dinamica czy PrimaDonna opisują rodzaj problemu, zamiast serwować numer serwisowy. W tle nowsze modele prowadzą jednak dziennik cyfrowy — 1101, 1454, 2257 i tak dalej — który odczytuje dział serwisu, gdy ekspres do nich trafi. Obie warstwy, słowa i ukryte numery, zestawiamy w dziale De'Longhi, zaczynając od [omówienia General Alarm (kod 1101 / 1512)](https://pl.codefixcoffee.com/delonghi/magnifica-dinamica/general-alarm-code-1101-1512/). Oto, co komunikat znaczy naprawdę i co zrobić najpierw.

## Komunikat-worek, a nie diagnoza

General Alarm to odpowiedź płyty sterującej: wykryłam usterkę, ale nie umiem wskazać winnego podzespołu. Na maszynach pokazujących numery zdarzenie ląduje w pamięci jako kod 1101 albo 1512. Ukryty dziennik bywa gdzie indziej precyzyjniejszy — 1454 to na przykład kod zablokowania młynka — ale General Alarm jest z założenia szeroki, a wyświetlacz z założenia wymijający.

W praktyce na maszynach ECAM i ESAM za dziewięć alarmów na dziesięć odpowiada **infuzor**, czyli wyjmowana grupa zaparzająca. Zatarł się, jest brudny, po czyszczeniu wrócił w złej pozycji albo pył kawowy osiadł na niewielkim czujniku optycznym, który odczytuje jego położenie. Druga najczęstsza przyczyna to kamień w torze wodnym: pompa pracuje pod przeciążeniem, a płyta zgłasza to jako usterkę ogólną, a nie punktową.

W tym rozmytym komunikacie kryje się dobra wiadomość: zdecydowana większość przypadków General Alarm to bezpłatna naprawa zajmująca dziesięć minut.

### Procedura na dziesięć minut

1. Wyłącz ekspres przyciskiem z tyłu, odczekaj 30 sekund i włącz ponownie. Jednorazowy błąd znika już tutaj.
2. Otwórz drzwiczki serwisowe, wciśnij dwa czerwone przyciski i wysuń infuzor.
3. Spłucz go pod bieżącą wodą — bez mydła — poruszając tłoczkiem ręką, i zostaw do wyschnięcia.
4. Zajrzyj do wnęki po infuzorze: w środku jest małe okienko czujnika, przetrzyj je suchą szmatką z pyłu kawowego.
5. Wsuń infuzor aż do kliknięcia, z dźwignią całkowicie opuszczoną, zamknij drzwiczki i uruchom maszynę.

### Twarda woda po polsku

W większości polskich miast woda z kranu jest twarda lub bardzo twarda, więc kamień narasta szybciej niż w krajach o miękkiej wodzie. Jeśli General Alarm wraca mimo czystego infuzora, w polskich warunkach pierwszym podejrzanym jest zwykle zaniedbane odkamienianie — reaguj na pierwszy sygnał ekspresu i przeprowadzaj pełny cykl od razu, zamiast odkładać go na później.

## Dlaczego De'Longhi pokazuje słowa, a nie kody

Za wyświetlaczem stoi prosta filozofia: słowo popycha do działania, numer popycha do szukania w tabeli. Na komunikacie 1101 bez dokumentacji serwisowej nie da się nic zrobić, ale General Alarm przynajmniej każe się zatrzymać i rozejrzeć. Liczbowa warstwa istnieje dla technika z tabelą — dlatego na każdej stronie podajemy obie, zamiast zmuszać do wyboru.

Pozostałe komunikaty De'Longhi trzymają się tej samej logiki i każdy nazywa czynność, której oczekuje od użytkownika. [Water Circuit Empty / Fill Circuit](https://pl.codefixcoffee.com/delonghi/magnifica-dinamica/water-circuit-empty-fill-circuit/) pojawia się, gdy do pompy dostało się powietrze i nie może się zagruntować. [Insert Grounds Container](https://pl.codefixcoffee.com/delonghi/magnifica-dinamica/insert-grounds-container-empty-grounds-container/) włącza się, gdy styki za pojemnikiem biorą mokre fusy albo muł za brak pojemnika. Żaden z nich nie jest diagnozą podzespołu — to po prostu instrukcje.

Odwrotną filozofię reprezentuje Nespresso: maszyny Vertuo zgłaszają większość usterek wzorami migających diod, a nie słowami, i dokładnie dlatego powstał [dekoder wzorów świateł](https://pl.codefixcoffee.com/nespresso/vertuo-machines/blinking-lights/), a opis sygnalizacji producenta znajdziesz na [nespresso.com](https://www.nespresso.com). Całe podejście De'Longhi wraz z pełną rodziną komunikatów obejmuje [centrum De'Longhi](https://pl.codefixcoffee.com/delonghi/).

## Gdy alarm wraca

Przeprowadź pełne odkamienianie. Mocno osadzony kamień w torze wodnym potrafi wywołać alarm nawet przy nienagannie czystym infuzorze, a w maszynach starszych niż rok to rozwiązanie działa częściej niż cokolwiek innego. Jeżeli infuzor nie daje się poruszyć ręką albo widać na nim pękniętą uszczelkę, przestań majstrować i wymień cały zestaw — numer katalogowy 7313251451 lub 7313251441 zależnie od modelu, a sama wymiana to pięć minut. Zalecenia konserwacji producenta znajdziesz w [dziale wsparcia De'Longhi](https://www.delonghi.com).

## Ile to kosztuje

- Nic, w większości przypadków: płukanie, przetarcie okienka czujnika i ponowne uruchomienie.
- Środek do odkamieniania, jeśli przyczyną jest kamień: około €10.
- Zestaw infuzora na wymianę, gdy stary jest pęknięty lub zakleszczony: €35–60.
- Serwis producenta po gwarancji przy automacie: zwykle €250–500 wraz z transportem zwrotnym; niezależne warsztaty ekspresów przy naprawie jednej części wychodzą zazwyczaj taniej.

General Alarm nie jest więc wyrokiem. To przyznanie się maszyny, że nie wie dokładnie, co się zepsuło — a w dziewięciu przypadkach na dziesięć czysty infuzor i przetarty czujnik stanowią całą odpowiedź. Zacznij od procedury powyżej, trzymaj się jej kolejności, a o częściach i serwisie myśl dopiero wtedy, gdy alarm przetrwa płukanie i odkamienianie.
