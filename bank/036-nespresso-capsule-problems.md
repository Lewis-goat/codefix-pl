---
title: "Problemy z kapsułkami Nespresso: gdy maszyna wini kapsułkę"
description: "Nespresso często obwinia kapsułkę, choć winowajcą bywa czujnik, brudne okienko lub przerwane odkamienianie. Rozszyfruj miganie diod i kod 1301."
---

Mało która usterka ekspresu tak szybko obwinia użytkownika jak Nespresso Vertuo odmawiający współpracy z kapsułką. Kapsułka wpada, dźwignia opada — a maszyna zachowuje się, jakby środka nie było, albo miga i się poddaje. Linia Vertuo (Next, Plus, Pop, Evoluo) mówi niemal wyłącznie językiem świateł, który Nespresso dokumentuje na swoich stronach pomocy; kody numeryczne w modelach łączonych pochodzą z wyświetlaczy i relacji użytkowników, a nie z oficjalnej tabeli. Obie te „mowy" omawiamy w [sekcji Nespresso](https://pl.codefixcoffee.com/nespresso/) naszego serwisu; ten tekst dotyczy przypadku, w którym maszyna wskazuje na kapsułkę, a kapsułka jest niewinna.

## Jak Vertuo czyta kapsułkę

Kapsułki Vertuo mają kod kreskowy nadrukowany na rantie. Maszyna odczytuje go przez małe okienko w głowicy, następnie przebija folię i rozkręca kapsułkę, przepychając przez nią wodę. Dwie rzeczy muszą się udać:

- **Czujnik musi odczytać kod.** Wystarczą ochlapy kawy i kurz na okienku, by nastąpiła pomyłka.
- **Kapsułka musi siedzieć prosto**, żeby folię dało się przebić czysto, a kapsułka kręciła się bez chybotania.

Gdy zawiedzie którakolwiek z tych rzeczy, maszyna zgłasza problem z kapsułką — nie mówiąc, która strona zawiodła. To właśnie źródło niemal całego zamieszania.

### Objawy wskazujące na maszynę, nie na kapsułkę

- Maszyna zachowuje się, jakby kapsułki nie było, choć jest załadowana, a głowica zamknięta.
- Odrzuca **każdą** kapsułkę — różne opakowania, świeży zapas, oryginalne sztuki.
- Wyczyszczenie okienka i uchwytu poprawia sprawę albo usuwa ją całkowicie.
- W modelach łączonych pojawia się kod z rodziny 1301 — odgałęzienie czujnika kapsułki, szczegółowo opisane na naszej [stronie kodów 1301–1305](https://pl.codefixcoffee.com/nespresso/vertuo-machines/1301-1305/).

Jeśli usterka podąża za maszyną przy każdej kapsułce, jaką masz w domu, przestań kupować nowe opakowania i zacznij sprzątać.

## Kiedy kapsułka faktycznie jest winna

Kapsułki też potrafią zawieść i warto je tanio wykluczyć, zanim ruszysz na maszynę:

- Wgnieciony lub zgnieciony rant — od transportu, magazynowania albo upadku — uniemożliwia kapsułce proste osadzenie, więc przebija się źle i kapie zamiast parzyć.
- Podarta lub wybrzuszona folia na starych sztukach; kapsułki powoli chłoną wilgoć i puchną poza tolerancję.
- Kapsułka zaklinowana w uchwycie po poprzednim cyklu, blokująca osadzenie następnej.

Test rozstrzygający: spróbuj jednej świeżej, oryginalnej kapsułki ze środka nowego opakowania; jeśli parzy bez problemu, wcześniejsze sztuki były problemem. I nigdy nie zamykaj głowicy na siłę ponad kapsułką, która nie leży prawidłowo.

## Wzorce migania wskazujące na kapsułki

Vertuo nie ma dedykowanego mignięcia „zła kapsułka"; jeden przycisk i pierścień światła kodują podsystemy, nie pojedyncze części. Najczęstsze układy:

- **Kolejne lub naprzemienne mignięcia tuż po włączeniu** to tryb grzania. Odczekaj piętnaście do dwudziestu pięciu sekund; to nie jest usterka.
- **Pomarańczowe migotanie w dowolnym rytmie** to rodzina odkamieniania — potrzebne, w trakcie lub zaległe. Pomarańczowe, które nigdy nie gaśnie, zwykle oznacza odkamienianie rozpoczęte i niedokończone.
- **Czerwone światło stałe lub powtarzające się** to stan błędu, typowo przegrzanie albo błąd wewnętrzny. Odłącz ekspres na co najmniej dziesięć minut, pozwól ostygnąć i spróbuj ponownie.

Zanim cokolwiek ruszysz, odczytaj kolor, to, czy światło jest ciągłe czy migające, oraz liczbę mignięć w serii — [dekoder migających świateł Vertuo](https://pl.codefixcoffee.com/nespresso/vertuo-machines/blinking-lights/) przypisuje każdy wzorzec do podsystemu. Reset fabryczny pięcioma naciśnięciami zostaw na sam koniec: kasuje przypomnienia o odkamienianiu i parowanie z aplikacją, a niczego mechanicznego nie naprawia.

## Nakładka 1301: kod, który obwinia kapsułkę

W łączonych Vertuo rodzina kodów 1300 to miejsce, gdzie kłopoty z kapsułkami spotykają się z kłopotami z odkamienianiem. Relacje użytkowników konsekwentnie wiążą 1301 z dwoma stanami: maszyną uwięzioną w trybie odkamieniania (albo zaległym) oraz czujnikiem nieczytającym kapsułki — w towarzystwie sąsiednich kodów tej samej rodziny. Kod wyglądający na skargę na kapsułkę bywa więc skargą na kamień wystawianą pod tym samym numerem. Oficjalna sekwencja obejmuje obie połówki naraz:

1. Reset fabryczny: przy dźwigni w pozycji UNLOCKED naciśnij przycisk pięć razy w ciągu trzech sekund; potwierdzeniem jest pięć pomarańczowych mignięć.
2. Przeprowadź pełny, nieprzerwany cykl odkamieniania środkiem Nespresso — anulowane odkamienianie to klasyczny sposób, w jaki te maszyny utykają w trybie.
3. Wyjmij uchwyt na kapsułki i przetrzyj okienko oraz głowicę, żeby czujnik widział kod kreskowy.
4. Opróżnij i napełnij zbiornik wody, a potem przetestuj maszynę ze świeżą kapsułką.
5. Jeśli problem wraca po wykonaniu wszystkich kroków, skontaktuj się z pomocą Nespresso zamiast próbować dalej — firma zwykle wymienia wadliwe Vertuo w ramach gwarancji, a nie je naprawia.

Dwie przestrogi: nigdy nie odkamieniaj octem, bo uszkadza obwód wodny i może pozbawić Cię prawa do pomocy serwisowej, a budżetowo cała sekwencja nie kosztuje zwykle nic ponad odkamieniacz w cenie około 10–15 €.

## Kontrast: automat na ziarnach

Philips lub Saeco mielący własne ziarna blokuje się po swojemu — zmielona kawa zbija się w twarde zatyczki za [Error 01](https://pl.codefixcoffee.com/philips-saeco/espresso-machines/error-01/) — podczas gdy usterki drogi kawy w maszynie kapsułkowej sprowadzają się niemal zawsze do trzech podejrzanych: okienka kodu kreskowego, przebicia folii albo niedokończonego odkamieniania. Wyczyść okienko, przetestuj jedną sprawdzoną kapsułkę, odczytaj pierścień światła przed działaniem — i maszyna zwykle przestaje obwiniać kapsułki.

### Polska praktyka: pomoc i woda

W Polsce pomoc dla Vertuo załatwisz przez formularz i infolinię opisane na [oficjalnych stronach pomocy Nespresso](https://www.nespresso.com) — zgłoszenia gwarancyjne kończą się zwykle wymianą urządzenia bez wizyty w serwisie. Twarda woda z polskich kranów skraca odstępy między odkamienianiami, więc nie czekaj na pomarańczową diodę i przeprowadzaj pełny cykl co kilka miesięcy, zawsze środkiem przeznaczonym do ekspresów. Oryginalny odkamieniacz dokupisz przy zamówieniu kapsułek w sklepie marki.
