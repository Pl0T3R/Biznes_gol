# Kwiaciarnia „Ewelinka” (Goleniów) – strona demonstracyjna

Gotowa, jednoplikowa strona‑wizytówka przygotowana jako **demo do rozmowy sprzedażowej** z właścicielką
kwiaciarni. Wszystko, czego nie dało się potwierdzić w publicznych źródłach, jest widocznym
**placeholderem** – nic nie jest zmyślone.

- Plik strony: `index.html` (cały HTML, CSS i JS w jednym pliku, ok. 216 KB / ok. 53 KB po kompresji gzip – bez zdjęć).
- Zdjęcia: folder `img/` – lista nazw plików w [`img/README.md`](img/README.md).
- Podgląd: wystarczy otworzyć `index.html` w przeglądarce (działa też z dysku, bez serwera).
- **Tryb edycji:** dopisz `?edycja` do adresu (np. `index.html?edycja`) albo naciśnij **Shift+E**.
  Wszystkie miejsca do uzupełnienia dostają czerwoną ramkę, a w rogu pojawia się panel z listą
  (kliknięcie przewija do danego miejsca). Bardzo przydatne podczas rozmowy z właścicielką.

---

## 1. Koncepcja: „Szyld od 1997 – kwiaciarnia po sąsiedzku”

Klasyczny sklep z szyldem: butelkowa zieleń, mosiężne ramy, kość słoniowa, bordo chryzantemy.
Emaliowany szyld „Ewelinka” jako logo, **okno wystawowe** w hero, odręczny **bilecik**, **kartki z kalendarza**
i mosiężna **oś czasu od 1997 roku**, która biegnie wzdłuż lewego marginesu całej strony
(na ekranach ≥ 1100 px) – każda sekcja „wisi” na niej jak kolejny rozdział historii sklepu.
Bardzo czytelne kroje (Atkinson Hyperlegible Next, bazowo 18 px), duży przycisk „Zadzwoń”,
przełącznik „A+ Większy tekst” – z myślą o starszych klientach, którzy zamawiają telefonicznie.

Kroje: Young Serif (nagłówki), Atkinson Hyperlegible Next (tekst), Pinyon Script (tylko logo i podpis na bileciku) –
wszystkie z Google Fonts, z pełnymi polskimi znakami.

## 2. Co zawiera demo

| Sekcja | Co robi |
|---|---|
| Pasek sezonowy | W październiku: „Wszystkich Świętych – niedziela, 1 listopada…”, w grudniu: odliczanie do Bożego Narodzenia. Liczy się sam, można go zamknąć. |
| Nagłówek | Szyld‑logo (SVG), menu, przełącznik **A+ Większy tekst** (zapamiętywany), duży przycisk z numerem telefonu. Na telefonie rozwijane menu. Nagłówek zmniejsza się przy przewijaniu. |
| Hero | Zielona „fasada” z oknem wystawowym (3 miejsca na zdjęcia), bilecik „Zaprasza [Wanda Bartosz]”, przyciski Zadzwoń / Napisz SMS / Zamów bukiet, tabliczka godzin (sama przełącza się na „Otwarte teraz / Zamknięte – otwieramy…”, gdy wpiszesz godziny). |
| Pas z licznikiem | „Od września 1997 roku · 29 lat w Goleniowie · do 30‑lecia: N dni” – liczone na żywo; po 1.09.2027 samo zmienia się na „30 lat z Goleniowem”. |
| Nasza historia | Oś czasu: 1997 (fakt) → 2 kamienie milowe do uzupełnienia → Dziś → wrzesień 2027 (30‑lecie, odliczanie). Karta „Skąd nazwa „Ewelinka”?”, cytat właścicielki na bileciku, informacja o adresie. |
| Oferta | 4 karty z potwierdzonych kategorii (bukiety, kompozycje, wiązanki ślubne, wieńce) + lista „Prosimy pytać także o…” (sformułowana jako zaproszenie do pytania, nie obietnica). Ceny jako `od __ zł`. |
| Pamięć (zielony pas) | Stroiki, wiązanki, wieńce; „1 listopada 2026 wypada w niedzielę – warto zamówić wcześniej” (liczone automatycznie na każdy rok); informacja o Cmentarzu Komunalnym przy ul. Przestrzennej 1. W październiku sekcja dostaje znacznik „Teraz – przed Wszystkimi Świętymi”. |
| Zamówienie na bileciku | Konfigurator: okazja, rodzaj, kolorystyka, styl, budżet, termin, odbiór/dostawa, treść bileciku (licznik znaków), imię i telefon. Podgląd na żywo jako bilecik wysuwający się z koperty. Akcje: **Zadzwoń**, **Wyślij SMS** (gotowa treść w `sms:`), **Kopiuj treść**, **Pokaż dużymi literami** (pełnoekranowe podsumowanie do przeczytania przez telefon). Walidacja po polsku. Nic nie jest nigdzie wysyłane. |
| Kartki z kalendarza | 4 najbliższe okazje (m.in. Dzień Babci, Walentynki, Dzień Kobiet, Wielkanoc liczona algorytmem, Dzień Matki, zakończenie roku szkolnego, Dzień Edukacji Narodowej, Wszystkich Świętych, Wigilia) z dniem tygodnia i odliczaniem. Przycisk „Zamów na tę okazję” ustawia konfigurator. |
| Nasza wystawa (galeria) | 10 kafelków z filtrami (Wszystkie / Bukiety / Śluby / Okazje / Pamięć / Rośliny) i powiększeniem (klawiatura: Esc, strzałki). |
| Państwa słowa | Wyłącznie 3 miejsca na prawdziwe opinie + link „Zobacz opinie w Google”. Bez gwiazdek i liczb. |
| Porady | „Żeby kwiaty postały dłużej” – kwiaty cięte, rośliny w doniczce, na cmentarzu. |
| FAQ | 7 pytań (zamówienia, wyprzedzenie, dostawa, płatności, pogrzeb, ślub, godziny) – nieznane odpowiedzi jako placeholdery. |
| Kontakt i dojazd | Adres, duży numer, SMS, tabela godzin z podświetlonym dniem dzisiejszym, inne kanały (placeholdery), NIP/REGON, zdjęcie szyldu, mapa Google ładowana **dopiero po kliknięciu** „Pokaż mapę”, „Wyznacz trasę”. |
| Stopka | Logo, kontakt, nawigacja, dane firmy, „Projekt i wykonanie: [Twoje studio]”, rok liczony automatycznie. |
| Telefon | Przyklejony dolny pasek: Zadzwoń / Trasa / Zamów. |

Jakość: semantyczny HTML, jeden `h1`, link „Przejdź do treści”, widoczny fokus, kontrast WCAG AA
(axe‑core: 0 błędów), `prefers-reduced-motion`, poprawny HTML (html‑validate: 0 błędów),
brak poziomego przewijania od 320 px, strona w pełni czytelna bez JavaScriptu.

## 3. Wszystkie placeholdery do uzupełnienia

Najwygodniej: otwórz `index.html?edycja` – panel pokazuje aktualną listę i liczbę (teraz: 22 zdjęcia + 51 pól tekstowych).
W kodzie każde pole to `<span class="ph-text" data-ph="opis">…</span>` – po uzupełnieniu zamień cały `span` na zwykły tekst.

### Zdjęcia (22)
Lista nazw i opisów: [`img/README.md`](img/README.md). Wrzucenie pliku o właściwej nazwie automatycznie zastępuje ilustrację.

### Teksty i dane

| Gdzie | Co uzupełnić |
|---|---|
| Hero, bilecik | Podpis „Zaprasza Wanda Bartosz” – **imię i nazwisko tylko za zgodą właścicielki** (w przeciwnym razie np. „Zapraszamy!”). |
| Hero, tabliczka | Godziny otwarcia → wpisać w `CONFIG.hours` (patrz pkt 5). |
| Historia | Wspomnienie pierwszych lat; 2 kamienie milowe (rok + wydarzenie + opis); plany na 30‑lecie; historia nazwy „Ewelinka”; cytat właścicielki + podpis (za zgodą); czy ul. Sportowa 12 to punkt sprzedaży. |
| Oferta | 4 ceny „od __ zł”; potwierdzony zakres oferty (lista „Prosimy pytać także o…” – usunąć pozycje, których nie ma). |
| Pamięć | Do kiedy przyjmowane są zamówienia na Wszystkich Świętych; czy jest punkt/stoisko przy ul. Przestrzennej (cmentarz). |
| Konfigurator | 3 przedziały budżetu (`do __ zł`, `__–__ zł`, `powyżej __ zł`) – w HTML w etykietach **i** w atrybutach `value`; informacja o dostawie. |
| Opinie | 3 prawdziwe opinie z podpisem (za zgodą autorów); link do wizytówki Google. |
| FAQ | Bukiet na ten sam dzień; ile dni wcześniej zamawiać wieńce/stroiki; dostawa; formy płatności; szarfy z napisem; godziny. |
| Kontakt | Godziny (7 dni); czy adres to punkt sprzedaży / drugi punkt; e‑mail (jeśli jest); Facebook (jeśli powstanie); wizytówka Google. |
| Stopka | „Projekt i wykonanie: [Twoje studio]” – nazwa i link studia. |
| `<head>` | Domena: `canonical`, `og:url`, `og:image` (zakomentowane). |

## 4. Fakty użyte na stronie i ich źródła

| Fakt | Źródło |
|---|---|
| Nazwa „Kwiaciarnia „Ewelinka””, kategoria: kwiaciarnia | Panorama Firm, CEIDG (nazwa firmy w rejestrze) |
| Właścicielka: Wanda Bartosz (na stronie tylko jako placeholder do zgody) | CEIDG / Oferteo / Targeo |
| Adres: ul. Sportowa 12, 72‑100 Goleniów | Panorama Firm |
| Telefon komórkowy: 504 727 452 | Panorama Firm |
| NIP 856‑115‑22‑08, REGON 811135790 | Oferteo, Targeo (dane rejestrowe) |
| Działalność od 1 września 1997 r. (29 lat w 2026, 30‑lecie we wrześniu 2027) | Dane rejestrowe powtarzane przez Panorama Firm, Oferteo, Targeo |
| Oferta: bukiety (w tym urodzinowe), kompozycje, wiązanki (w tym ślubne), wieńce | Słowa kluczowe i opis wpisu Panorama Firm („kwiaty, wieńce, bukiety”) – poziom katalogu |
| Ul. Sportowa – ta sama ulica co Stadion Miejski / OSiR (Sportowa 25), niedaleko śródmieścia | goleniow.pl, bip.osir.goleniow.pl, katalogi ulic |
| Cmentarz Komunalny w Goleniowie – ul. Przestrzenna 1 | pomeranica.pl, Targeo |
| Gmina co roku uruchamia bezpłatną komunikację na cmentarz na Wszystkich Świętych | goleniow.pl |
| 1 listopada 2026 = niedziela | liczone (strona liczy to automatycznie dla każdego roku) |

Linki źródłowe:
- https://panoramafirm.pl/zachodniopomorskie,goleniowski,goleni%C3%B3w,sportowa,12/ewelinka_kwiaciarnia_wanda_bartosz-amiwyo_soo.html
- https://www.oferteo.pl/kwiaciarnia-ewelinka-bartosz-wanda/firma/2143009
- https://mapa.targeo.pl/kwiaciarnia-ewelinka-bartosz-wanda-przestrzenna-72-100-goleniow~14258554/przedsiebiorstwo-firma/adres
- https://pomeranica.pl/wiki/Cmentarz_komunalny_(Goleni%C3%B3w)
- http://www.goleniow.pl/kontakt/item/7981-bezp%C5%82atna-komunikacja-miejska-na-cmentarz-i-zmiana-organizacji-ruchu-w-dniu-wszystkich-%C5%9Bwi%C4%99tych
- https://bip.osir.goleniow.pl/artykul/dane-teleadresowe

### Czego celowo NIE ma na stronie (nie dodawać bez potwierdzenia)
- Skład węgla / opał – w Oferteo widnieje tytuł „Skład Węgla – Kwiaciarnia Ewelinka”, to prawdopodobnie błędna automatyczna kategoria.
- Stoisko przy cmentarzu lub na ul. Przestrzennej (to tylko adres rejestrowy) i pewność, że Sportowa 12 to sklep z witryną.
- Godziny otwarcia, otwarcie w niedziele i święta, dostawa, zamówienia online, płatność kartą/BLIK.
- Numer stacjonarny 91 418 38 10 (niezweryfikowany, prawdopodobnie nieaktualny).
- Oceny, gwiazdki, liczba opinii, cytaty klientów, nagrody, rankingi („Orły Florystyki”), hasła typu „najlepsza kwiaciarnia”.
- Wsparcie hospicjum w Policach, pochodzenie nazwy, „firma rodzinna od pokoleń”, liczba pracowników, dyplomy, konkretne gatunki/ceny/pochodzenie kwiatów.
- Facebook, Instagram, e‑mail – nie znaleziono żadnych.

## 5. Jak edytować (dla wykonawcy)

Na górze skryptu (na końcu `index.html`) jest obiekt **`CONFIG` – „EDYTUJ TUTAJ”**:

```js
var CONFIG = {
  name: 'Kwiaciarnia Ewelinka',
  phone: '504 727 452',
  phoneIntl: '+48504727452',
  phoneIsMobile: true,      // false = ukrywa przyciski SMS
  email: '',                // po wpisaniu pojawi się przycisk „Wyślij e-mail” w konfiguratorze
  address: { street: 'ul. Sportowa 12', postalCode: '72-100', city: 'Goleniów' },
  since: '1997-09-01',
  jubileeDate: '2027-09-01',
  hours: null,              // patrz niżej
  socials: { facebook: '', instagram: '', google: '' }
};
```

**Godziny otwarcia** – po potwierdzeniu wpisz np.:
```js
hours: {
  1: [['09:00', '17:00']], 2: [['09:00', '17:00']], 3: [['09:00', '17:00']],
  4: [['09:00', '17:00']], 5: [['09:00', '17:00']], 6: [['09:00', '13:00']],
  0: []   // niedziela: nieczynne
},
```
(0 = niedziela … 6 = sobota; można podać kilka przedziałów dziennie). Wtedy automatycznie:
tabliczka w hero pokazuje „Otwarte teraz · do 17:00” lub „Zamknięte – otwieramy jutro o 9:00”
(czas liczony w strefie Europe/Warsaw), tabela w Kontakcie wypełnia się godzinami, a odnośniki
„do potwierdzenia” w konfiguratorze i FAQ zamieniają się w link do sekcji Kontakt.
Godziny dopisz też do JSON‑LD w `<head>` (`openingHoursSpecification`).

Inne miejsca:
- **Okazje w kalendarzu** – tablica `OCCASIONS` w skrypcie (nazwa, data, podpowiedź, ustawienia konfiguratora).
- **Treść SMS** – funkcje `lines()` i `message()` w skrypcie.
- **Kolory i kroje** – zmienne CSS na początku `<style>` (`--green`, `--bordo`, `--brass`…).
- **Ilustracje** – rycinowe SVG w ukrytym „sprite” na początku `<body>` (symbole `p-…` to pojedyncze kwiaty, `s-…` to gotowe sceny).
- **Dane strukturalne** (`application/ld+json` w `<head>`) – muszą zgadzać się z `CONFIG`; `sameAs` dodawać tylko dla prawdziwych profili.

Pamięć przeglądarki (`localStorage`) służy tylko do zapamiętania przełącznika A+ i zamknięcia paska sezonowego. Strona nie używa ciasteczek ani analityki.

## 6. Lista kontrolna przed publikacją

- [ ] Rozmowa z właścicielką: zgoda na publikację imienia i nazwiska (bilecik, cytat, zdjęcie, alt zdjęcia `historia-wlascicielka.jpg`).
- [ ] Potwierdzić adres punktu sprzedaży (Sportowa 12? Przestrzenna?) i ewentualnie dopisać drugi punkt.
- [ ] Wpisać godziny w `CONFIG.hours` i w JSON‑LD; sprawdzić godziny w okresie Wszystkich Świętych.
- [ ] Uzupełnić ceny „od __ zł”, przedziały budżetu, dostawę, płatności, terminy (tryb `?edycja` → lista).
- [ ] Dodać zdjęcia do `img/` (nazwy z `img/README.md`) i obejrzeć stronę na telefonie.
- [ ] Wstawić prawdziwe opinie (za zgodą) albo usunąć sekcję do czasu ich zebrania; założyć wizytówkę Google i podlinkować.
- [ ] Usunąć `<meta name="robots" content="noindex, nofollow">` (oznaczone komentarzem „USUŃ PRZED PUBLIKACJĄ”).
- [ ] Odkomentować i uzupełnić `canonical`, `og:url`, `og:image` (pełne adresy z domeną).
- [ ] Wpisać „Projekt i wykonanie” w stopce.
- [ ] Na prawdziwym telefonie (Android i iPhone) przetestować: „Zadzwoń”, „Napisz SMS”, „Wyślij SMS” z konfiguratora (czy treść się wkleja), „Wyznacz trasę”, „Pokaż mapę”.
- [ ] Sprawdzić stronę w trybie `?edycja` – licznik placeholderów powinien wynosić 0.
- [ ] Wgrać na hosting z HTTPS (np. statyczny hosting) i dodać stronę w Google Search Console.

## 7. Propozycje domen (dostępność do sprawdzenia u rejestratora)

- `kwiaciarniaewelinka.pl`
- `ewelinka-goleniow.pl`
- `kwiaty-ewelinka.pl`
- `ewelinkakwiaty.pl`
- `kwiaciarnia-ewelinka-goleniow.pl`

## 8. Pomysły na rozmowę z właścicielką

- **Wszystkie Święta za chwilę:** 1 listopada 2026 to niedziela – strona od razu pokazuje pasek sezonowy i sekcję „Pamięć”. Dobry argument, żeby wystartować jeszcze w październiku.
- **30‑lecie we wrześniu 2027:** licznik dni do jubileuszu jest już na stronie – pretekst do odświeżenia wizerunku, jubileuszowej oferty i zebrania zdjęć/wspomnień do osi czasu.
- **Lokalność kontra pośrednicy:** na hasło „kwiaciarnia Goleniów” dziś wygrywają ogólnopolskie serwisy. Własna strona z adresem, numerem i mapą (plus wizytówka Google) pomaga odzyskać te wyszukiwania.
- **Klienci zamawiający telefonicznie:** duży przycisk „Zadzwoń”, A+ dla czytelności i „Pokaż dużymi literami” – strona nie zmusza nikogo do zamawiania online.
- Pytania otwarte do zadania: punkt sprzedaży i godziny, dostawa i płatności, zakres oferty (stroiki, znicze, rośliny, kwiaty sztuczne), zdjęcia realizacji, e‑mail / media społecznościowe, historia nazwy, plany na 30‑lecie, wpis „Skład Węgla” w Oferteo, numer stacjonarny 91 418 38 10.

## 9. Uwagi techniczne

- Dopóki w `img/` nie ma zdjęć, przeglądarka zgłasza w konsoli błędy 404 dla brakujących plików
  (to zamierzone – w ten sposób strona sama wykrywa wrzucone zdjęcia). Znikają po dodaniu zdjęć.
- Zewnętrzne zasoby: tylko Google Fonts i (po kliknięciu) mapa Google. Brak frameworków i CDN.
- Kod strony powstał z kilku plików źródłowych złożonych w jeden `index.html`; można go edytować bezpośrednio.
