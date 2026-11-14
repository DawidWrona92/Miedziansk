# Chronologia katastrofy: 13–15 października 1992

**STATUS:** główna rama dat i pora pierwszego śniegu — ZATWIERDZONE 6.11.2026; szczegółowe godziny i wydarzenia — PROPOZYCJA.

Cała historia trwa **około 36 godzin**. Tempo rozgrywki nie musi odpowiadać tempu czasu rzeczywistego; dopuszczalne przeskoki przy zmianach perspektywy. Nie ustalamy jeszcze dnia miesiąca końca, dopóki nie zamkniemy scenariusza — 15 października nad ranem jest propozycją.

| Czas | Oficer / laboratorium | Dziennikarka / miasto | Stan przestrzeni |
|---|---|---|---|
| **13.10 ok. 17:00** | **Kapitan Piotr Bielecki** po wcześniejszym spokojnym rozpoczęciu inspekcji szpitala, rosyjskiego skrzydła, –1 i –2 wraz z **Leszkiem** trafia na załamanie kontroli. Dochodzi do ataków, czasowego użycia **AK-74** i awarii węzła parowego. Leszek ratuje oficera i znika; **przeżywa i wróci w finale**, choć oficer tego nie wie. **–3** pozostaje na późną część gry | Przygotowuje hotelowe spotkanie | Miasto żywe, ruszają zmiany w fabryce, działają sklepy |
| **13.10 ok. 19:00** | Nieprzytomny albo ukryty w części schronu | **Anna Wysocka**, reporterka „Słowa Polskiego”, po przyjeździe pociągiem późnym popołudniem spotyka w barze **kierowcę karetki**. Rozmowę przerywa atak jednego z **wcześniej zakażonych gości**, niezależny od głównej fali szpitalnej | Pierwsze syreny; mieszkańcy nadal nie rozumieją zagrożenia |
| **13.10 ok. 21:00** | Odzyskuje przytomność; próbuje wydostać się z kompleksu | Anna porównuje świadectwa i niezgodne daty wcześniejszych przypadków, korzysta z pamiętanego skrótu i **kieruje się do szpitala**; przejście między scenami i rzeczywiste minuty pozostają elastyczne | Lokalna policja i pogotowie działają, pojedyncze blokady |
| **13.10 23:00** | Wciąż w kompleksie lub przy wyjściu | Widzi nasilające się działania służb | Strefa szpitala zamykana; pierwsze wojskowe punkty kontrolne; niepełny kordon |
| **14.10 02:00** | Wydostaje się na powierzchnię | Dociera w okolice szpitala / wojskowej dzielnicy | **Początek śniegu; spotkanie bohaterów** [rama uzgodniona, godzina robocza] |
| **14.10 04:00** | Współpraca wymuszona zagrożeniem | Pierwsza wspólna próba ucieczki | Kordon rozszerzony, drogi zamykane, sporadyczne starcia |
| **14.10 07:00** | Próba ustalenia kontaktu z wojskiem | Odkrywa, że sytuacja dotyka całego miasta | Mroźny, zaśnieżony poranek; niektóre dzielnice jeszcze kontrolowane |
| **14.10 10:00–17:00** | Wykorzystuje znajomość procedur i sprzętu | Korzysta z wiedzy o dzielnicach, prowadzi śledztwo | **Główny akt eksploracji:** dzielnice mają różne stany kryzysu |
| **14.10 18:00–23:00** | Szuka realnej drogi wyjścia i odpowiedzi | Podejmuje decyzje moralne dotyczące prawdy i ocalałych | Pogarszająca się kontrola służb, część kordonów nadal szczelna |
| **15.10 04:00–05:00** | Finał nieustalony | Finał nieustalony | Nie rozstrzygać z góry losu miasta |

## Fazy stanu dzielnicy

1. **A — Normalność pod presją:** funkcjonują sklepy, transport, mieszkańcy, oświetlenie, straż i Policja; zdarzają się dyskretne incydenty.
2. **B — Kryzys i izolacja:** tłumy, zamknięte sklepy, prowizoryczne posterunki, ograniczona komunikacja, lokalne ogniska zakażenia, pierwsze pożary i bariery.
3. **C — Zerwane połączenia:** pojazdy porzucone, część ulic niedostępna, klatki schodowe zabarykadowane, ocaleni w mieszkaniach, część patroli nadal działa, śnieg, cisza przeplatana walką.

**Implementacja:** niezależne warstwy sceny: (a) architektura stała; (b) dekoracje i rekwizyty wg fazy; (c) NPC, interakcje, zagrożenia; (d) kolizje i graf nawigacji zależny od barykad; (e) lokalne zdarzenia i misje. Sama podmiana assetów rozwiąże część pracy, lecz nie zastąpi aktualizacji stanów świata.

## Pułapki fabularne do rozwiązania

- Skąd polskie dowództwo wie tak szybko, że ma izolować cały Miedziańsk? Potrzebny wiarygodny kanał ostrzegania albo etapowe reagowanie na zgłoszenia.
- Dlaczego Anna nie wróciła od razu **pociągiem** lub innym środkiem transportu, skoro przyjechała koleją? **[KANON MOTYWACJI]** Przyjaciółka zaginęła, ślad prowadzi do szpitala, a informator i sprzeczne dokumenty potwierdzają, że sprawa jest poważna. Dokładne utrudnienia w transporcie i skala ryzyka pozostają do dopracowania; nie używać sztucznej „niewidzialnej ściany”.
- Dlaczego rosyjski dowódca nie ewakuuje wszystkiego przed 17:00? Tajny, nielegalny albo politycznie trudny ładunek i spóźnione przygotowania.
- Dlaczego większość miasta nadal żyje rankiem? Infekcja rozwija się ogniskowo, służby i cywile miejscami skutecznie się bronią.
- Dlaczego żołnierz nie może po prostu ujawnić stopnia i wyjechać przez kordon? Możliwy status „zakażony/niezidentyfikowany”, brak łączności, sprzeczne komendy — **propozycje, nie rozwiązanie kanoniczne**.
## Aneks — podziemny program (propozycja etapu 04)

W dokumencie `10-RUBIEZ-TAJNY-PROGRAM-I-KATASTROFA.md` opisano model **jednego pierwotnego incydentu z około 9–10 października** podczas chaotycznej likwidacji fikcyjnego ośrodka, a następnie dwóch etapów widocznych konsekwencji: dyskretnych przypadków z 10–12 października i gwałtownej fazy objawowej 13 października. **Nie ma drugiego niezależnego wycieku 13 października.** Godziny kampanii (13–15 października) pozostają zgodne z poprzednią ramą; **żadne konkretne źródło zakażenia ani reguła transmisji nie stają się kanonem bez decyzji autora**. Osobisty udział bohaterów zostaje w późniejszej części III.

### Ustalenie przyczynowe — 6 listopada 2026

Pierwszy spór wewnątrz Rubieży kończy się przejęciem oficjalnej decyzji przez zwolenników zatajenia problemu. Zespół przewozi podejrzanych chorych na obserwację do rosyjskiego, zamkniętego skrzydła szpitalnego. W dniu 13 października rozwinięte objawy u pacjentów doprowadzają do gwałtownej utraty kontroli i ponownego konfliktu personelu. Skutki **wcześniejszego** incydentu ujawniają się także w Miedziańsku. Szczegółowa droga zakażenia, mechanizm choroby i rozkład godzin pozostają do dopracowania.

## Korekta dramaturgii epidemii — szpitalny punkt przełomowy (6.11.2026)

Autor chce, aby przed 13 października Policja i inne służby interweniowały przy pojedynczych pogryzieniach, agresji, pobiciach i podpaleniach. Dnia 13 X szpital staje się sceną masowego kryzysu: w zamkniętym rosyjskim skrzydle chorzy wchodzą w fazę objawową, po czym kryzys obejmuje również polską część. W wariancie roboczym **około 200 zakażonych opuszcza CAŁY kompleks szpitalny kilkoma wyjściami podczas narastającego kryzysu**. Nie jest to liczba samych rosyjskich pacjentów. W świecie science fiction R-4 przemiana może trwać od dni do sekund, a rola poszczególnych przypadków będzie różna. Szczegóły i reguły zob. `11-R4-I-ZAKAZENI.md`.

## Część III — proponowany związek bohaterów z chronologią (6.11.2026)

Dodatkowa robocza rozpiska znajduje się w `12-BOHATEROWIE-POWIAZANIA-Z-RUBIEZA.md`. Propozycja: dziennikarka przyjeżdża w poszukiwaniu zaginionej przyjaciółki, planuje spotkanie w hotelu na 13 X wieczorem; oficer i kolega są tego popołudnia na legalnej inspekcji stref technicznych rosyjskiego skrzydła szpitala, gdzie zastaje ich kryzys. Bohater zostaje ranny, kolega go ratuje. **To rozwinięcie nie jest jeszcze zatwierdzone** poza wcześniej uzgodnionymi fundamentami fabuły. Punkt wspólnego spotkania podczas pierwszego śniegu pozostaje kanonem.

### Doprecyzowanie narracyjne prologu i powrotu do podziemi (6.11.2026)

[**KANON**] Pierwotny incydent nastąpił kilka dni wcześniej. Wizyta polskich przedstawicieli Wojska Polskiego w dniu 13 października **zbiega się z konfliktem wewnątrz rosyjskiego zespołu**, przyspiesza możliwe reakcje paniki, lecz nie wywołuje pierwotnego zakażenia. [**KANON**] Prologiczna utrata kontroli rozgrywa się w **radzieckim zapleczu na poziomie –2**; poziom –3 jest **sercem projektu Rubież**, przeznaczonym na późny etap kampanii. [**KANON**] Przyjaciel ratuje oficera, ale **znika po prologu**, więc po spotkaniu dziennikarki i oficera nie tworzy się stały trzyosobowy zespół. **WARIANTY OTWARTE:** przyjaciel ginie / przeżywa i wraca w finale, być może pomagając przekroczyć kordon. Szczegółowy mechanizm awarii technicznej, rozkład prologu i finałowy ratunek pozostają propozycjami.

### Zatwierdzony wariant finału przyjaciela (6.11.2026)

Wcześniejszy wpis **„warianty otwarte: przyjaciel ginie / przeżywa”** został rozstrzygnięty przez autora na rzecz **wariantu B**. Przyjaciel **przeżywa prolog, pozostaje zaginiony przez znaczną część rozgrywki, oficer uważa go za zmarłego, a w finale powraca i ratuje dwoje protagonistów**. Dopuszczone jako kierunki fabularne są dyskretny kontakt radiowy (CB), wydostanie się z dokumentami i wynikami dotyczącymi Rubieży, a także pomoc wpływowego wojskowego oraz gotówka. Dokładne miejsce i moment ratunku, stan kordonu, liczba pośredników i skutek przekazania dowodów pozostają otwarte. Nie wpisywać finałowego ratunku jako już rozplanowanej sceny.

### Uszczegółowiony prolog oficera (v0.16)

**[KANON]** Przed załamaniem sytuacji gracz wchodzi do miejskiego szpitala, ogląda rosyjski sektor, dokumenty, poziom –1 i katalogowane zaplecze –2. Rosyjska eskorta towarzyszy Polakom. Strzeżona klatka schodowa oraz skrzynie z niezgodnym spisem zapowiadają późne odkrycie poziomu –3. **[KANON]** Przyjaciel nazywa się **Leszek**. Po kryzysie i krótkim użyciu AK-74 znalezionego przy poległym rosyjskim wojskowym następuje awaria węzła parowego. Oficer po utracie przytomności budzi się zakrwawiony, z bólem głowy, z tylko pistoletem, dwoma magazynkami i latarką leżącą obok. Leszek jest zaginiony, przeżywa i wróci w finale. **[PROPOZYCJA]** Konkretne minuty, utrata karabinka i przyczyna awarii. Zob. `15-PROLOG-OFICERA-OSTATNI-ZALADUNEK.md`.

### Zatwierdzony początek Anny — decyzje z 14 listopada 2026

Anna Wysocka pracuje w **„Słowie Polskim”** we Wrocławiu i **13 X przyjeżdża pociągiem późnym popołudniem**. Około godziny 19:00 spotyka w hotelu **kierowcę karetki**, świadka interwencji z 10–12 X. Hotelowy atak to **wcześniejszy rozproszony przypadek zakażenia**, nie automatycznie jedna z około 200 osób opuszczających szpital po eskalacji. Po tym zdarzeniu Anna przechodzi **zapamiętanym skrótem**, bada notatkę przyjaciółki, relację medyka o **11 X** i komunikat szpitala wskazujący dopiero **13 X**, wyciąga wniosek o niezgodności dat i **kieruje się do szpitala**. Pierwszy odcinek Anny obejmuje **jedną główną dedukcję, jedną zagadkę przestrzenną i opcjonalne tropy**, bez broni palnej, około **80–90 minut rozgrywki (do testów)**. Szpital pozostaje czynny w warunkach narastającego kryzysu; całe miasto nie jest opustoszałe. Spotkanie z Piotrem nadal nocą **13/14 X podczas pierwszego śniegu**, bez konfliktu z ok. 21:00 jako roboczym zakończeniem początkowego rozdziału. Szczegóły: `16-ANNA-OSTATNI-SPOKOJNY-WIECZOR.md`.
