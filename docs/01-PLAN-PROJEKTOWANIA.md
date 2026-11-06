# Plan projektowania — Miedziańsk

**Wersja:** 0.6  
**Cel:** od fabularnego pomysłu do spójnego, możliwego do zbudowania GDD oraz grywalnego fragmentu.

## Zasady pracy

- Każdy etap kończymy **akceptacją / korektą / odrzuceniem** propozycji. Dopiero wtedy awansuje do kanonu.
- Fikcję historyczną oznaczamy wyraźnie. Unikamy przypisywania realnym jednostkom i prawdziwemu miastu tajnych zbrodni.
- Sceny projektujemy pod **co gracz robi**, a nie tylko co ogląda.
- Pamiętamy o dwóch bohaterach, maksymalnie 48 godzinach fabuły i mieście zmieniającym stan.
- Priorytetem jest jakość survival horroru; mnożenie systemów, potworów i dzielnic to koszt, a nie automatyczna korzyść.

## Kolejność etapów

| Nr | Status | Temat | Rezultat | Kryterium zakończenia |
|---|---|---|---|---|
| 01 | **ZATWIERDZONY ZARYS** | **Historia Miedziańska: geneza przed 1930 i lata 1930–1992** | Dawne wydobycie miedzi i pochodzenie nazwy, przemysł, garnizon, szpital, rok 1992, małe muzeum | Oś czasu bez sprzeczności, co najmniej 8 lokacji wynikających z historii, decyzja o profilu gospodarczym i muzeum |
| 02 | **W TOKU — układ logiczny zatwierdzony; mapa metryczna do akceptacji** | Geografia i struktura miasta | `07-GEOGRAFIA-I-UKLAD-MIASTA.md`: dolina, rzeka przez Starówkę, przemysł/kopalnie, dworzec, rosyjski Kwadrat, szpital w śródmieściu, mosty i dojazdy | Wybrać kierunki, przeprawy, skalę, połączenia i miejsca kordonu; uwzględnić relacje dzielnic bez sztucznego tunelowania |
| 03 | DO ZROBIENIA | Garnizon i szpital | Dowództwo rosyjskie, Polska komisja, hierarchia, jawna funkcja szpitala, kolejne rozbudowy | Wiadomo kto, co i kiedy kontroluje, skąd zna informacje, jakie ma możliwości |
| 04 | DO ZROBIENIA | Tajny program i epidemia | Pochodzenie, incydent pierwotny, reguły zakażenia, skala i tempo | Zakażenia i reakcja służb spójne z 36 h, brak magicznych wygodnych wyjątków |
| 05 | DO ZROBIENIA | Pełne karty bohaterów | Imiona, motywacje, przeszłość, konflikt, relacja z dwiema osobami poszukiwanymi | Postacie wiarygodne dla wieku i realiów 1981/1992; obie mają podmiotowość |
| 06 | DO ZROBIENIA | Postacie drugoplanowe i frakcje | Władze polskie, jednostki rosyjskie, policja, szpital, mieszkańcy, cywile | Każda ważna frakcja ma cel, wiedzę, zasoby i zmieniające się decyzje |
| 07 | DO ZROBIENIA | Pełna struktura fabuły | Sceny, odkrycia, zwroty, akty, zakończenia | Gracz zna stawkę i cel bez czytania wszystkiego; zegar fabuły nie pęka |
| 08 | DO ZROBIENIA | Mechanika dwóch postaci | Walka, improwizacja, strach, ekwipunek, zagadki i śledztwo | Każdy archetyp ma unikalne skuteczne strategie, bez dominującej postaci |
| 09 | DO ZROBIENIA | Zakażeni i spotkania | Archetypy wrogów, behawior, telegraphy, zasady starć | Każde spotkanie testuje coś innego; ucieczka jest uczciwą opcją |
| 10 | DO ZROBIENIA | Żywe i zmienne dzielnice | Stany przestrzeni, migracja NPC, barykady, kolizje, nawigacja, wydarzenia | Ta sama lokacja przechodzi trzy czytelne stany bez soft-locków |
| 11 | DO ZROBIENIA | Zadania, zagadki i odkrycia | Quest graph, kluczowe dokumenty, opcjonalne wątki | Każde zadanie jest domykalne, bez niezauważalnych zablokowań |
| 12 | DO ZROBIENIA | Dźwięk, grafika i autentyczność | Style guide Polski 1992, ambient, pogoda, język, rekwizyty | Wyraźna tożsamość bez anachronizmów |
| 13 | DO ZROBIENIA | Scope i demo pionowe | Jedna mała grywalna sekwencja: bunkier → bar / żywa ulica | Test napięcia, dwóch stylów gry i jednego zmiennego miejsca |
| 14 | DO ZROBIENIA | Playtest / audyt | Test nowicjusza, speedrunnera, optymalizatora, audyt historii | Lista problemów z ważnością i zaproponowanymi poprawkami |

## Dalszy tok prac

1. **Teraz:** przegląd metrycznej mapy w `08-MAPA-MIASTA-W-SKALI.md` oraz `docs/maps/MIEDZIANSK_1992_PLAN_ROBOCZY.svg`. Układ logiczny został zatwierdzony; skala, granice obszarów i koordynaty są propozycją.
2. **Następnie:** po ocenie metrycznej mapy doprecyzować układ ulic, mosty, wejścia i zasięg faktycznej grywalności. Dopiero potem oznaczyć etap 02 jako ukończony.
3. **Potem:** dopiero precyzować instytucję rosyjską i podziemny program. Historia i geografia muszą uzasadniać ich położenie.
4. **W dalszej kolejności:** projektować przeszłość i motywacje bohaterów na tle tej historii, a nie niezależnie od niej.

## Najważniejsze zależności

`historia miasta → geografia → garnizon/szpital → program biologiczny → logiczny wybuch epidemii → łuki bohaterów i frakcje → scenariusz → mechaniki → poziomy → demo`

Niektóre wątki można opracowywać równolegle, ale połączenia między nimi wymagają weryfikacji.

## Zatwierdzony kierunek etapu 01 — szczegóły nadal otwarte

- **[UZGODNIONE]** Miedziańsk powstał dzięki dawnym złożom miedzi, a później rozwinął się w ośrodek kolejowo-przemysłowy; po 1945 r. stał się dodatkowo miastem garnizonowym.
- **[ZATWIERDZONY KIERUNEK]** Dawne górnictwo wygasło przed 1930 r., lecz przemysł i warsztaty przetrwały. Dokładny rok do ustalenia.
- Czy główny zakład PRL ma produkować maszyny, części elektromaszynowe i urządzenia dla hutnictwa/górnictwa, zamiast być pełną hutą miedzi? (rekomendacja: tak, mniejsza skala łatwiejsza do uzasadnienia).
- **[KANON — KOREKTA]** Jedyny główny szpital miasta leży blisko centrum i przemysłu, ma część polską oraz rosyjskie skrzydło z przepustkami. Dawna propozycja położenia go na dalekim obrzeżu jest anulowana; mały niemiecki schron pozostaje kanonem.
- **[KANON]** Małe muzeum miedzi i historii miasta w centrum. Jego szczegółowa funkcja w kampanii nadal otwarta.
- **[KANON]** Rosyjski kwartał ma sztab w dawnym poniemieckim garnizonie/szkole, mieszkania, szkołę i usługi. Szpital stanowi inny, centralny obiekt o podzielonym dostępie; magazyny i bocznice do rozmieszczenia na mapie.
- Jak mocno pokazać represje z lat 1981–1982 w rodzinnych historiach bohaterów? (otwarte, wymaga taktu i badań).
**[KANON] Nazwa przedwojenna:** **Kupfertal**. Od 1945 r. nazwa polska: **Miedziańsk**. Decyzja zamknięta; patrz `06-NAZEWNICTWO-NIEMIECKIE.md`.
