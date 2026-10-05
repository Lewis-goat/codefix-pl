---
title: Kody C w piekarnikach Samsung: rodzina temperatur
description: Kody C-21, C-24 i C-F2 w kuchenkach Samsung: wyłączenie z przegrzaniem, szybki wzrost temperatury przy wentylacji i brak sygnału zwrotnego wentylatora.
---

Kuchenki i piekarniki zabudowane Samsung — serie NE i NX oraz pokrewne NV i NZ — posługują się dwoma „dialektami” błędów. Kody dwuczęściowe, takie jak E-08 czy E-27, opisują elementy grzejne; krótkie, jak SE i tE — sam panel sterowania. Pomiędzy nimi mieści się rodzina C: C-21, C-24 i C-F2, czyli kody temperatur i nadzoru wentylatorów zebrane w [indeksie kodów piekarników Samsung](https://pl.codefixcoffee.com/samsung-oven-error-codes/). Warto traktować je najpoważniej ze wszystkich, bo przynajmniej jeden z nich oznacza, że piekarnik realnie się przegrzał.

## Brak dziennika błędów do odczytania

Piekarniki Samsung nie mają dziennika usterek dostępnego dla użytkownika. Kod świeci na wyświetlaczu, dopóki nie usuniesz przyczyny albo nie odetniesz zasilania w skrzynce (procedury dla rodziny C zakładają 5–10 minut). Jeśli po takim resecie kod wraca, potraktuj go jako realny — kolejne resetowanie i nadzieja niczego nie zmienią.

## C-21: wyłączenie z przegrzaniem

[C-21](https://pl.codefixcoffee.com/samsung/range-wall-oven/c-21/) powstaje, gdy układ bezpieczeństwa melduje, że temperatura w komorze wyszła poza bezpieczne okno, i płytka sterująca odcina grzanie. Zdarzały się zgłoszenia kuchenek nagrzewających się do niebezpiecznych temperatur jeszcze zanim pokazał się kod — to sygnał „przestań gotować”, nie chwilowa kapryśność elektroniki. Najczęstszym winowajcą jest czujnik temperatury komory wraz z wiązką; główna płytka PCB to drugi podejrzany.

1. Odetnij zasilanie na 5–10 minut i powtórz test dokładnie raz; jeśli C-21 wraca przy kolejnym nagrzewaniu, usterka jest rzeczywista.
2. Odłącz kuchenkę, wykręć dwie śruby mocujące sondę czujnika na tylnej ściance komory i wysuń wiązkę, aby odpiąć wtyczkę.
3. Zmierz czujnik multimetrem: w temperaturze pokojowej prawidłowo wypada ok. 1080 Ω. Przerwa albo skrajnie odstający odczyt oznacza wymianę.
4. Obejrzyj wtyczkę wiązki tam, gdzie biegnie blisko elementu grzejnego — nadtopiona izolacja produkuje ten sam kod.
5. Jeżeli czujnik jest sprawny, a kod nadal wraca, płytka źle reguluje pracę grzałek — to naprawa na poziomie serwisu.

## C-24: kontrola gwałtownego wzrostu temperatury

[C-24](https://pl.codefixcoffee.com/samsung/range-wall-oven/c-24/) wykrywany jest w okolicy wentylacji i elektroniki: przedział z układami nagrzewa się szybciej, niż zakłada płytka. Samsung dokumentuje rodzinę C-24/C-25 jako przegrzanie związane właśnie z tą strefą wentylacji. W praktyce winowajca jest jeden z trzech: wentylator chłodzący, który wcale się nie rozkręca, zablokowany przepływ powietrza wokół urządzenia albo umierający termistor nadtemperaturowy, odczytujący zdrową strefę jako gorącą.

Diagnostyka sprowadza się do patrzenia i słuchania. Po resecie zasilania uruchom pieczenie i posłuchaj, czy wraz z nagrzewaniem słychać wentylator konwekcji i chłodzenia — cisza jest odpowiedzią. Sprawdź odstępy montażowe oraz to, czy kratki pod lub za urządzeniem nie są zakryte meblami, folią albo kurzem. Przy odłączonym zasilaniu można zmierzyć termistor nadtemperaturowy na jego wtyczce — pracuje w podobnym przedziale ok. 1000 Ω jak czujnik komory, a egzemplarz z przerwą lub dryfem idzie do wymiany. Martwy wentylator wymień, zanim ugotuje płytę sterującą: ciepło jest tu przyczyną, a elektronika tylko ofiarą.

## C-F2: sygnał zwrotny wentylatora chłodzenia

[C-F2](https://pl.codefixcoffee.com/samsung/range-wall-oven/c-f2/) wygląda jak kod przegrzania, ale zwykle nim nie jest. Rodzina C-F to komunikaty „monitorowany podzespół nie odpowiada”, a w przypadku C-F2 tym podzespołem jest obwód wentylatora chłodzenia: wyświetlacz nie dostaje oczekiwanego sygnału zwrotnego. Albo wentylator faktycznie stoi, albo jego wtyczka jest luźna lub nadtopiona, albo przerwana jest linia sygnałowa prowadząca do płytki.

Zajmuj się tym w kolejności. Po resecie zasilania nagrzej piekarnik i sprawdź, czy wirnik fizycznie się obraca. Kręcący się wentylator przy utrzymującym się kodzie wskazuje na tor sygnałowy: dociśnij wtyczkę wentylatora na płytce i poszukaj przebarwionych ciepłem pinów. Cichy wentylator to najpierw kontrola, czy nic nie blokuje wirnika — kurz albo upuszczona śrubka za panelem — a dopiero potem pomiar uzwojenia pod kątem przerwy. Naprawy wentylatora i wtyczki są tanie; C-F2, które przetrwało obie kontrolole, kieruje podejrzenie na wejście głównej płytki.

### Kuchenka w zabudowie: polskie realia

W Polsce te urządzenia montuje się niemal zawsze w zabudowie, a instrukcja Samsunga wymaga konkretnych odstępów i drożnych otworów wentylacyjnych z tyłu — ciasno przycięta zabudowa potrafi ograniczyć chłodzenie i doprowadzić do kodów z rodziny C. Zanim zaczniesz samodzielne naprawy, sprawdź status gwarancji w [polskim centrum wsparcia Samsung](https://www.samsung.com/pl/support/): kody C-21 i C-F2 dotyczą układów bezpieczeństwa, a serwis ma dla nich dedykowane procedury.

## Ile kosztują części

Czujniki temperatury komory kosztują 15–40 € i są robotą na dziesięć minut ze śrubokrętem — to najczęstsza naprawa w całej rodzinie. Wentylatory chłodzenia: 40–90 €, wiązki: 10–20 €. Główna płytka PCB, 150–300 €, to wydatek, do którego przechodzisz dopiero po odhaczeniu czujnika i wentyladora. Wizyta technika to ok. 120–250 € za diagnozę plus część; przy urządzeniu po gwarancji z usterką na poziomie płytki rozsądnie najpierw przyjąć wycenę, a dopiero potem cokolwiek zamawiać.

Jedna zasada obejmuje całą rodzinę: nie resetuj C-21 w kółko i nie gotuj dalej. Kod oznacza, że płytka zarejestrowała już temperaturę, która jej się nie podobała — kolejne zadziałanie może nastąpić wyżej na skali.
