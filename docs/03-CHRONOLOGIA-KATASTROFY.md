# Chronologia katastrofy: 13–15 października 1992

**STATUS:** główna rama dat i pora pierwszego śniegu — ZATWIERDZONE 6.11.2026; szczegółowe godziny i wydarzenia — PROPOZYCJA.

Cała historia trwa **około 36 godzin**. Tempo rozgrywki nie musi odpowiadać tempu czasu rzeczywistego; dopuszczalne przeskoki przy zmianach perspektywy. Nie ustalamy jeszcze dnia miesiąca końca, dopóki nie zamkniemy scenariusza — 15 października nad ranem jest propozycją.

| Czas | Oficer / laboratorium | Dziennikarka / miasto | Stan przestrzeni |
|---|---|---|---|
| **13.10 17:00** | Prolog: nadzoruje wywózkę w podziemiach; dochodzi do awarii i ataku, kolega go ratuje | Przygotowuje hotelowe spotkanie | Miasto żywe, ruszają zmiany w fabryce, działają sklepy |
| **13.10 19:00** | Nieprzytomny albo ukryty w części schronu | Rozmowa w hotelowym barze; pierwsza gwałtowna scena | Pierwsze syreny; mieszkańcy nadal nie rozumieją zagrożenia |
| **13.10 21:00** | Odzyskuje przytomność; próbuje wydostać się z kompleksu | Próbuje zdobyć informacje i bezpieczną drogę przez centrum | Lokalna policja i pogotowie działają, pojedyncze blokady |
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
- Dlaczego dziennikarka nie uciekła samochodem o 19:00? Potrzebuje konkretnej motywacji i fizycznych ograniczeń.
- Dlaczego rosyjski dowódca nie ewakuuje wszystkiego przed 17:00? Tajny, nielegalny albo politycznie trudny ładunek i spóźnione przygotowania.
- Dlaczego większość miasta nadal żyje rankiem? Infekcja rozwija się ogniskowo, służby i cywile miejscami skutecznie się bronią.
- Dlaczego żołnierz nie może po prostu ujawnić stopnia i wyjechać przez kordon? Możliwy status „zakażony/niezidentyfikowany”, brak łączności, sprzeczne komendy — **propozycje, nie rozwiązanie kanoniczne**.