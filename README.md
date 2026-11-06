# MIEDZIAŃSK — dokumentacja projektowa

**Wersja:** 0.8 — 6 listopada 2026  
**Typ:** roboczy pakiet GDD / worldbuilding  
**Projekt:** niezależny survival horror osadzony w fikcyjnym polskim mieście w październiku 1992 roku.

## Spis dokumentów

1. [`docs/00-FUNDAMENTY-I-KANON.md`](docs/00-FUNDAMENTY-I-KANON.md) — wszystko, co już uzgodniono, propozycje oraz decyzje otwarte.
2. [`docs/01-PLAN-PROJEKTOWANIA.md`](docs/01-PLAN-PROJEKTOWANIA.md) — uporządkowany plan dalszego projektowania, priorytety i kryteria ukończenia.
3. [`docs/02-HISTORIA-MIEDZIANSKA-1930-1992.md`](docs/02-HISTORIA-MIEDZIANSKA-1930-1992.md) — **pierwszy punkt planu: historia od dawnych kopalń miedzi do 1992 roku (zatwierdzony kierunek)**.
4. [`docs/03-CHRONOLOGIA-KATASTROFY.md`](docs/03-CHRONOLOGIA-KATASTROFY.md) — wstępna chronologia rozgrywki 13–15 października 1992.
5. [`docs/04-ZRODLA-I-ODDZIELENIE-FIKCJI.md`](docs/04-ZRODLA-I-ODDZIELENIE-FIKCJI.md) — historyczne podstawy i świadome fikcyjne odstępstwa.
6. [`docs/05-MUZEUM-MIEDZI-I-MIASTA.md`](docs/05-MUZEUM-MIEDZI-I-MIASTA.md) — **zatwierdzona mała lokacja muzealna w sercu miasta**.

7. [`docs/06-NAZEWNICTWO-NIEMIECKIE.md`](docs/06-NAZEWNICTWO-NIEMIECKIE.md) — zatwierdzona przedwojenna nazwa Kupfertal.

8. [`docs/07-GEOGRAFIA-I-UKLAD-MIASTA.md`](docs/07-GEOGRAFIA-I-UKLAD-MIASTA.md) — geografia, położenie dzielnic, rzeka, kolej, szpital i węzły komunikacji; zatwierdzony układ logiczny, plan metryczny w przygotowaniu.

9. [`docs/08-MAPA-MIASTA-W-SKALI.md`](docs/08-MAPA-MIASTA-W-SKALI.md) — mapa metryczna, punkty i odległości (propozycja do zatwierdzenia).
10. [`docs/maps/MIEDZIANSK_1992_PLAN_ROBOCZY.svg`](docs/maps/MIEDZIANSK_1992_PLAN_ROBOCZY.svg) — edytowalna wektorowa mapa 1992.
11. [`docs/maps/layout_1992.json`](docs/maps/layout_1992.json) — metryczny model układu miasta.

12. [`docs/09-GARNIZON-I-SZPITAL-JAWNA-CZESC.md`](docs/09-GARNIZON-I-SZPITAL-JAWNA-CZESC.md) — etap 03: historycznie wiarygodna, jawna organizacja garnizonu i szpitala (projekt do zatwierdzenia).

13. [`docs/10-RUBIEZ-TAJNY-PROGRAM-I-KATASTROFA.md`](docs/10-RUBIEZ-TAJNY-PROGRAM-I-KATASTROFA.md) — etap 04: projekt ukrytego ośrodka i zarzewia epidemii, **do zatwierdzenia**; powiązania bohaterów w odrębnej części III.

## Zasada prowadzenia dokumentacji

Każde ustalenie należy oznaczać jednym ze stanów:

- **KANON / UZGODNIONE** — użytkownik jednoznacznie zaakceptował albo sam zaproponował.
- **PROPOZYCJA** — projekt do zatwierdzenia; nie staje się kanonem przez samo zapisanie.
- **OTWARTE** — pytanie bez decyzji.
- **FAKT HISTORYCZNY** — informacja z potwierdzonym źródłem; nie mieszać z fikcją.

To **nowa gra**, niezależna od „Weleszy”. Dokumentacja znajduje się w dedykowanym repozytorium gry na gałęzi `main`. Repozytorium gry: https://github.com/DawidWrona92/Miedziansk. Nie modyfikować niezależnego repozytorium Welesza-Retro.

## Co zmieniono w wersji 0.2

- Ustalono związek nazwy Miedziańsk z dawnymi lokalnymi złożami i wydobyciem miedzi.
- Dodano historię miasta sprzed roku 1930 oraz ciągłość między niemiecką i polską gospodarką.
- Opracowano jednobudynkowe muzeum z wystawą „Miedź na ziemiach polskich” jako **propozycję do zatwierdzenia**.
- Dodano historyczne źródła dotyczące Miedzianki, Leszczyny, Legnicy i odkrycia nowych złóż w 1957 roku.
- Potwierdzono kanon fabularny: ucieczka postaci nie oznacza końca Miedziańska ani atomowego zniszczenia miasta.
## Zmiany w wersji 0.3

- Zatwierdzono dotychczasowy kierunek historii miasta i cały uzgodniony fundament projektu 6 listopada 2026 r.
- Etap 01 (historia): zatwierdzony zarys; kolejny etap 02 (geografia).
- Wersja 0.4: ostatecznie przyjęto **Kupfertal** jako jedyną nazwę niemiecką do 1945 r.; **Miedziańsk** pozostaje nazwą polską po 1945 r. Usunięto alternatywę nazewniczą z kanonu.

## Zmiany w wersji 0.5

- Zaakceptowano założenia geograficzne: dolina rzeczna, przepływ rzeki przez Stare Miasto, dawne zalane kopalnie pod/obok późniejszych terenów przemysłowych, miasto zniszczone w obronie Festung Kupfertal (fikcyjne), kontrast kamienic i bloków.
- Zatwierdzono centralne położenie jednego miejskiego szpitala oraz istnienie odseparowanego skrzydła rosyjskiego; dawny opis szpitala na peryferyjnym wzgórzu jest nieaktualny.
- Rozpoczęto etap 02: szkic topografii, dzielnic, kolei, mostów, tras i propozycja mapy logicznej. Szczegóły liczbowo-topograficzne pozostają propozycjami do akceptacji.

## Zmiany w wersji 0.6

- Zatwierdzono układ logiczny miasta z etapu 02, zgodnie z decyzją autora.
- Opracowano propozycję skali 6 × 4 km, kilometrowej siatki, tras, mostów, torów, głównych obiektów i obszarów.
- Dodano źródło danych metrycznych JSON i wektorową mapę SVG. Współrzędne i skala wymagają jeszcze przeglądu; to nie jest pełny poziom gry.

## Zmiany w wersji 0.7

- Autor zatwierdził metryczny układ Miedziańska i odległości; **etap 02 zakończony** na poziomie mapy koncepcyjnej. Konkretny whitebox ulic pozostaje zadaniem level designu, a nie warunkiem cofającym zatwierdzenie.
- Przemieszczenie między lokacjami może odbywać się pieszo, krótkim przejazdem samochodem lub przeskokiem narracyjnym/cutscenką; nie wymaga pełnej symulacji każdego kilometra.
- Rozpoczęto **etap 03**, w którym oddzielnie przygotowano realistyczną, jawną organizację garnizonu, szpitala i kompetencji polsko-rosyjskich, bez projektowania tajnego laboratorium i patogenu.

## Zmiany w wersji 0.8

- Autor zatwierdził realistyczną, jawną część garnizonu i Szpitala Miejskiego (etap 03).
- Rozpoczęto etap 04: tajny podziemny program. Nowa nazwa „Rubież”, szczegóły badań, dwufalowa eskalacja i koncepcja zakażonych są **propozycjami** wymagającymi akceptacji.
- Historycznym punktem odniesienia są rzeczywiste wydarzenia kwietnia–września 1992 r. wokół zakończenia radzieckiego programu biologicznego. Nie są dowodem na tajne prace w Legnicy.
- Projekt osobistego uwikłania dziennikarki i oficera w program został świadomie przesunięty do części III.
