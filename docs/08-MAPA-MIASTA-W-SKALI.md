# Miedziańsk 1992 — roboczy plan miasta w skali metrycznej

**Etap:** 02 — geografia miasta. **Status:** zatwierdzony UKŁAD LOGICZNY (6.11.2026); **PROPOZYCJA** wymiarów i dokładnych współrzędnych.

**Mapa SVG:** [MIEDZIANSK_1992_PLAN_ROBOCZY.svg](maps/MIEDZIANSK_1992_PLAN_ROBOCZY.svg)  
**Dane źródłowe:** [layout_1992.json](maps/layout_1992.json)

## 1. Co przyjęto jako kanon

Użytkownik 6 listopada 2026 r. zaakceptował układ z dwoma zasadniczymi przeprawami, rzeką płynącą z zachodu na wschód przez Stare Miasto (po obu brzegach), Kwadratem po północno-wschodniej stronie, centralnie położonym szpitalem na południowym brzegu, fabrykami i dawnymi kopalniami od południowego zachodu oraz rozbudowanym dworcem z bocznicami i południową drogą przelotową. Mała kładka dla pieszych pozostaje pomysłem opcjonalnym. **Nie przyjęto nazwy rzeki**, nadal jest otwarta.

## 2. Skala i lokalny układ odniesienia [PROPOZYCJA]

- Arkusz urbanistyczny: **6000 × 4000 m**, około **24 km²**. Nie są to granice administracyjne.
- Lokalny układ `(x, y)` w metrach: początek w południowo-zachodnim narożniku arkusza; `x` rośnie na wschód, `y` na północ.
- Arkusz ma podziałkę co **1000 m** i belkę skali do 2000 m. Nie używamy stałej skali papierowej, która zmieniałaby się przy otwieraniu pliku SVG na ekranie.
- Miedziańsk ma roboczo 35 000 mieszkańców (zaakceptowany przedział 30–40 tys.). Budujemy zróżnicowaną gęstość zabudowy: gęste centrum, osiedla i zakłady w dnie doliny, rzadsza zabudowa na zboczach.
- Główna mapa dla gry nie musi obejmować całego arkusza: roboczy zasięg **[1100,1000]–[4850,3300] m** to pułap dla fragmentów potencjalnie odwiedzanych, a nie zobowiązanie zbudowania 8,6 km² pełnej zawartości. Docelową sieć rzeczywiście eksplorowanych ulic określi level design.

## 3. Położenie najważniejszych obiektów [PROPOZYCJA współrzędnych]

| ID | Obiekt | x (m) | y (m) | Powiązanie |
|---|---|---:|---:|---|
| POI-01 | Rynek | 2700 | 2670 | ZON-01N |
| POI-02 | Hotel | 2260 | 2810 | ZON-01N |
| POI-03 | Muzeum Miedzi | 3110 | 2830 | ZON-01N |
| POI-04 | Most historyczny A | 2780 | 2170 | ZON-02 |
| POI-05 | Most przemysłowy B | 4300 | 2160 | ZON-02 |
| POI-06 | Dawne zatopione szyby | 950 | 1720 | ZON-04 |
| POI-07 | MZE | 1660 | 1550 | ZON-04 |
| POI-08 | Dworzec Główny | 2850 | 940 | ZON-03 |
| POI-09 | Sztab — dawna szkoła | 4250 | 2950 | ZON-06 |
| POI-10 | Szpital Miejski | 3900 | 1770 | ZON-07 |
| POI-11 | Bocznica wojskowa i magazyny | 4550 | 1410 | ZON-09 |
| POI-12 | Wyjazd na drogę przelotową | 5000 | 440 | ZON-09 |

Wszystkie punkty i odległości są **fikcyjnymi parametrami projektu**.

## 4. Odległości w linii prostej [PROPOZYCJA]

| Para miejsc | Odległość |
|---|---:|
| Rynek – Szpital Miejski | 1500 m |
| Rynek – Dworzec Główny | 1740 m |
| Rynek – Sztab — dawna szkoła | 1580 m |
| Rynek – MZE | 1530 m |
| Szpital Miejski – MZE | 2250 m |
| Szpital Miejski – Sztab — dawna szkoła | 1230 m |
| Szpital Miejski – Dworzec Główny | 1340 m |

Nie są to czasy dojścia ani trasy drogowe. Dróg, schodów, tłumów, blokad i dostępnych wejść nie da się na tej podstawie automatycznie wyliczyć.

## 5. Drogi i kolej [PROPOZYCJA szczegółów]

- **Trakt główny A:** Rynek i północne dzielnice → Most historyczny A → południowa Starówka → Dworzec Główny → droga przelotowa.
- **Trakt B:** rosyjski Kwadrat → Most przemysłowy B → wjazd od strony szpitala → połączenie z drogą zewnętrzną. Tą drogą mogą jechać rosyjskie ciężarówki i polskie pojazdy, przed izolacją miasta jest to normalna miejska przeprawa.
- **Aleja przemysłowa:** historyczne szyby i MZE → południowe Stare Miasto → szpital → wschodni wylot.
- **Kolej:** jedna linia główna zachód–wschód, duży dworzec pasażerski i osobne odnogi do MZE oraz magazynów rosyjskich. Bocznica wojskowa leży na terenie kolejowym i ma drogowy dojazd do szpitala, nie jest tajnym torem bez połączeń.
- **Obwodowa droga przelotowa:** blisko południowego krańca arkusza, a nie przez ciasny rynek. Na rok 1992 projektujemy ją jako istniejącą drogę krajową lub regionalną; **nie nazywamy automatycznie współczesną S-ką**.
- **Kładka piesza [OPCJA]:** dodatkowe przejście pomiędzy dwoma mostami, bez możliwości przejazdu pojazdów.
- **Mosty i przejazdy:** położenia mostów przyjęto orientacyjnie. Ich rzeczywiste osie drogowe, nawierzchnie, szerokości, chodniki i nachylenia zostaną sprawdzone przy whiteboxie. Mosty muszą zostać połączone z czytelnymi drogami, a nie być abstrakcyjnymi węzłami.

## 6. Miasto jako system zmieniający się przez 36 godzin

| Stan fabularny | Rdzeń świata | Zmiany na poziomie gry |
|---|---|---|
| 13 X, wieczór | Wszystkie główne węzły działają. Szpital przyjmuje cywilów, dworzec odprawia pociągi, fabryki pracują. | Gęsty ruch NPC, komunikacja i pojazdy, kontrolowane rosyjskie wejście. |
| 13/14 X, noc | Chaos narasta. Służby zamykają wybrane skrzyżowania i szpital. | Blokady przy szpitalu, przejściowe utrudnienia na mostach, zagubione grupy ludzi i pierwszy śnieg. |
| 14 X, rano | Miasto wciąż częściowo żyje, ale transport się załamuje. | Część dzielnic izolowana, wybrane alternatywne przejścia, znane ulice niebezpieczne. |
| 14 X, wieczór | Kordon zewnętrzny jest niebezpieczny, lecz lokalnie wciąż działają punkty oporu. | Inne rozmieszczenie postaci, zapór i wrogów; to samo środowisko, nowy stan. |

**Nie blokować jednocześnie wszystkich przepraw w sposób, który uniemożliwia postęp.** Stan fabularny ma określać konkretne możliwości pokonania rzeki. Także rail cuts, pożary i zawaliska muszą mieć osiągalną drogę obejścia lub uzasadnioną alternatywę.

## 7. Kontrola jakości geograficznej

1. **Rzeka:** Stare Miasto występuje po obu stronach wody, w tym rynek na północy i dawne ulice rzemieślnicze na południu.
2. **Szpital:** przy zabudowie śródmiejskiej i przemyśle, ale na lokalnym podwyższeniu terenu, by jego podziemia nie wymagały nierealistycznej ochrony przed wodą gruntową jak w zalanych kopalniach.
3. **Kwadrat:** osobna enklawa, lecz nie izolowana geograficznie: dojazd do wojskowej bramy, szpitala i bocznicy istnieje od początku.
4. **Dworzec:** odprawa pasażerska i transport towarowy stanowią ten sam węzeł, choć mają różne wejścia, magazyny i place.
5. **Droga przelotowa:** jest dostępna z dwóch stron, ale zewnętrzny kordon może ją zamknąć. Brak łatwego wyjazdu nie wynika z braku dróg.
6. **Spójność historii:** *Festung Kupfertal* wyjaśnia brak części kamienic; powojenne bloki wchodzą w starą siatkę ulic. Miejska zabudowa ma istnieć dla mieszkańców, nie tylko dla potrzeb zombie.
7. **Zalane kopalnie:** ich położenie nie daje automatycznego tunelu od szpitala do fabryki — oba podziemia są osobnymi obiektami.

## 8. Pozostałe decyzje przed finalizacją metrycznej mapy

- Dobrać szerokość rzeki (roboczo około **14 m**), wysokości skarp i lokalne spadki terenu.
- Zatwierdzić skalę całego arkusza i odległości między głównymi obiektami.
- Wybrać, czy ma istnieć opcjonalna kładka piesza oraz gdzie dokładnie leży.
- Przygotować plan konkretnych ulic w centrum i wytyczyć spójne wejścia do szpitala, rosyjskiego Kwadratu oraz magazynów.
- Rozróżnić obiekty widoczne na panoramie od tych, do których można wejść; nie dodawać automatycznie setek wnętrz.

## 9. Uzasadnienie inspiracjami historycznymi

Przedwojenny węzeł Legnicy dysponował dużą stacją kolejową, tunelem dojścia do peronów i rozbudowaną obsługą towarową, co stanowi analogię funkcjonalną, nie 1:1 kopię architektury Miedziańska. Dla układu w pobliżu rzeki inspiracją jest historyczna i współczesna zabudowa Legnicy przy Kaczawie. Patrz `04-ZRODLA-I-ODDZIELENIE-FIKCJI.md`.