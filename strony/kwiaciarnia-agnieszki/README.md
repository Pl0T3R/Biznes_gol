# Kwiaciarnia Agnieszki (Goleniów): strona demonstracyjna

To strona przygotowana na spotkanie z właścicielką Kwiaciarni Agnieszki przy ul. Króla Władysława Jagiełły 11A w Goleniowie. Wszystko mieści się w jednym pliku `index.html` (CSS, JS i ilustracje są w środku). Na zewnątrz pobierane są tylko fonty Google, a mapa Google dopiero po kliknięciu.

**Status: demo.** Strona ma `noindex, nofollow`. Każda informacja, której nie udało się potwierdzić, jest widocznym placeholderem, a nie wymyśloną treścią.

---

## Szybki start

1. Otwórz `index.html` w przeglądarce (Chrome, Safari, Firefox; najlepiej też na telefonie).
2. **Tryb edycji:** dopisz do adresu `?edycja` (np. `index.html?edycja`) albo naciśnij **Shift+E**. Wszystkie miejsca do uzupełnienia dostaną pomarańczową ramkę, a w rogu pojawi się panel z listą: **21 zdjęć + 45 tekstów**. Kliknięcie pozycji przewija do niej stronę. Przydaje się to na spotkaniu („tu wstawimy Pani zdjęcia i ceny”).
3. Zdjęcia: wrzuć pliki do `img/` pod nazwami z `img/README.md`. Podmienią się same.

---

## Koncepcja: „Pracownia z podpisem – niezapominajka z Jagiełły”

- **Nazwa w dopełniaczu** („Agnieszki”) jest jak podpis, więc logo to podpis odręczny (Caveat) z kropką nad „i” w kształcie niezapominajki.
- **Sąsiad pod nr 12 to Przedszkole Publiczne nr 4 „Niezapominajka”.** Stąd motyw niezapominajki: „nie zapomnij”, czyli kalendarz okazji z przypomnieniami.
- **Ton:** pierwsza osoba, spokojnie, bez pośpiechu. W opisach katalogów i opiniach powtarza się, że wybór bukietu odbywa się tu spokojnie, z doradztwem i dopasowaniem do okazji i budżetu.
- **Styl wizualny:** „notatnik florystki”. Niebieski atrament, papier kraft, taśma washi, notatki na marginesie (na desktopie niebieska linia marginesu z odręcznymi dopiskami), ilustracje tuszem z kolorem przesuniętym jak w druku riso.
- **Paleta:** Papier `#F9F7F1`, Atrament `#1F2A37`, Niezapominajka `#2E5EA6`, Oczko `#E8B53A`, Kraft `#D9C5A3`, Łodyga `#4A6545`. Fonty: Fraunces, Figtree i Caveat (wszystkie z polskimi znakami).

---

## Co jest na stronie

| # | Sekcja | Co zawiera |
|---|--------|------------|
| 1 | Nagłówek | Logo-podpis w SVG/CSS, nawigacja, klik-do-dzwonienia. Przy przewijaniu nagłówek przykleja się i zmniejsza. Na telefonie dostępne menu (Esc zamyka, fokus wraca na przycisk). |
| 2 | Hero „stół pracowni” | Nagłówek z odręcznym wtrąceniem „spokojnie”, przyciski Zamów / Zadzwoń / SMS. Tabliczka „Otwarte · do 17:00” albo „Zamknięte · zapraszam…” liczona na żywo w strefie Europe/Warsaw. Dwa zdjęcia w passe-partout i zawieszka z dedykacją. |
| 3 | O pracowni „Kwiaciarnia z imieniem” | Historia w pierwszej osobie, oparta wyłącznie na potwierdzonych faktach. Placeholder na cytat, imię i rok. Ramka „W skrócie”. |
| 4 | Doradca „Spokojny wybór” | Trzy pytania (dla kogo, nastrój, forma) dają odręczną podpowiedź. Przycisk „Przenieś do zamówienia” wypełnia kartę zamówienia. |
| 5 | Oferta „Co dla Ciebie ułożę” | Najpierw potwierdzone usługi, potem zaproszenia „zapytaj o…” (ślub, dekoracje, dostawa, firmy, dodatki). Ceny jako „od __ zł”. Karta „Kwiaty z dedykacją” ma podgląd tabliczki na żywo. |
| 6 | Galeria „Z mojego stołu” | 9 polaroidów, filtr (Bukiety, Kompozycje, Rośliny, Okazje, Pożegnania) i lightbox: Esc, strzałki, pułapka fokusu, powrót fokusu na kafelek. |
| 7 | „Nie zapomnij!” | 4 najbliższe okazje z odliczaniem, liczone dla każdej daty (Wielkanoc algorytmem Meeusa/Jonesa/Butchera). **„Przypomnij mi”** pobiera plik `.ics` z alarmem 3 dni wcześniej. **„Zamów na tę okazję”** ustawia kartę zamówienia (np. 1.11.2026 to niedziela, więc termin przesuwa się na sobotę 31.10). |
| 8 | Karta zamówienia | Okazja, forma, kolorystyka, styl, budżet, termin, odbiór lub dostawa („zapytam o możliwość”), tabliczka (do 120 znaków, z podglądem), imię i telefon. Na żywo widać podgląd wiadomości. Przyciski: **Wyślij SMS** (`sms:+48695385464?&body=…`), **Kopiuj treść**, **Zadzwoń**, **Napisz na Facebooku**. Walidacja jest po polsku i nic nie wychodzi z przeglądarki. |
| 9 | Opinie i wyróżnienia | Złota Firma, Orły Florystyki i Facebook, zawsze ze źródłem, datą i wyjaśnieniem, jak powstaje wyróżnienie. Motywy z opinii oznaczone jako podsumowanie. 3 puste karty na prawdziwe cytaty i linki do Google i Facebooka. |
| 10 | Fiszki pielęgnacyjne | 6 odwracanych fiszek (przycisk z `aria-expanded`). Bez JS widać obie strony. |
| 11 | FAQ | 8 pytań w `details/summary`, nieznane odpowiedzi jako placeholdery. |
| 12 | Kontakt i dojazd | Adres, wskazówka „w sąsiedztwie Przedszkola nr 4 i Netto”, telefon, Facebook, e-mail (placeholder), tabela godzin z wyróżnionym dniem dzisiejszym. „Pokaż mapę” ładuje iframe dopiero po kliknięciu, jest też „Wyznacz trasę”. |
| 13 | Stopka | Szkic Bramy Wolińskiej, „Kwiaty z Goleniowa – miasta nad Iną”, rok liczony przez JS, NIP i nazwa jako placeholdery, „Projekt i wykonanie: [Twoje studio]”. |
| – | Telefon | Dolny pasek **Zadzwoń / Trasa / Zamów** (≤ 760 px), marginesy 16 px, bez przewijania w poziomie, cele dotyku ≥ 44 px. |

### Co warto pokazać na spotkaniu (w tej kolejności)

1. **Tabliczka z dedykacją.** Wpisz w karcie zamówienia „Dla Mamy – z całego serca” i pokaż podgląd na żywo. Wzór „Z wyrazami współczucia” zmienia ją w stonowaną wersję żałobną.
2. **„Nie zapomnij!”** Pobierz przypomnienie o Wszystkich Świętych i otwórz je w kalendarzu telefonu.
3. **Doradca w 3 pytaniach** wypełnia kartę zamówienia. Potem „Wyślij SMS” na telefonie: gotowa wiadomość trafia na numer kwiaciarni.
4. **Tryb edycji** (`?edycja`) pokazuje, czego jeszcze potrzebujemy od właścicielki.

---

## Jak edytować

- **Dane firmy w jednym miejscu:** na początku `<script>` na dole pliku jest obiekt `CONFIG` z komentarzem „EDYTUJ TUTAJ”. Zawiera nazwę, telefon, e-mail, adres, godziny, Facebook i przedziały budżetu. Skrypt wstawia te dane w linki `tel:`/`sms:`, tabelę godzin, plakietkę „Otwarte”, wiadomość SMS i plik `.ics`.
  - `email: ''` → po wpisaniu adresu pojawi się przycisk **„Wyślij e-mail”** (mailto) i link w sekcji Kontakt.
  - `budzety: ['do __ zł', '__–__ zł', 'od __ zł']` → po wpisaniu kwot znikną placeholdery w karcie zamówienia.
  - `niedzielaPotwierdzona: false` → w tabeli godzin niedziela ma status „[do potwierdzenia]”, a plakietka w niedzielę nie pisze „Zamknięte”.
- **JSON-LD (schema.org Florist)** w `<head>` jest statyczny. Po zmianie godzin lub telefonu popraw go ręcznie.
- **Teksty statyczne z godzinami** (wersja bez JS w hero, ramka „W skrócie”, FAQ, stopka, podpowiedź przy terminie) też trzeba poprawić ręcznie, gdy zmienią się godziny. Szukaj w pliku frazy `9:00–17:00`.
- **Placeholdery tekstowe** to `<span class="ph-text" data-ph="opis">…</span>`. Po uzupełnieniu zamień cały `span` na zwykły tekst.
- **Ilustracje** to symbole SVG (`<symbol>`) na początku `<body>`. Każde miejsce na zdjęcie to `<figure class="ph">` z ilustracją, etykietą i `<img>` (`onload` dodaje klasę `has-photo`, `onerror` usuwa brakujący obrazek).

---

## Do uzupełnienia (placeholdery)

### Zdjęcia: 21 plików
Pełna lista, proporcje i opisy są w **`img/README.md`**.

### Teksty i dane: 45 miejsc

| Obszar | Co uzupełnić |
|--------|--------------|
| O pracowni | Rok, od którego działa kwiaciarnia (`[od 20__ roku]`); cytat właścicielki o tym, jak pracuje; imię właścicielki (tylko jeśli chce występować osobiście); zdjęcie właścicielki (za zgodą) |
| Ceny | „od __ zł” przy: bukietach okolicznościowych, kwiatach ciętych, kompozycjach w koszu i pudełku, kompozycjach w szkle, kwiatach doniczkowych, stroikach i wiankach, wieńcach i wiązankach; 3 przedziały budżetu w `CONFIG.budzety` |
| Dostawa | Czy jest, obszar, koszt, termin (w karcie zamówienia, ofercie i FAQ); dostarczanie wieńców na cmentarz lub do domu pogrzebowego |
| Usługi „zapytaj” | Zakres usług ślubnych (bukiet, butonierki, dekoracje); zamówienia firmowe; dodatki (karnety, upominki) |
| FAQ | Preferowany kanał zamówień (SMS, Messenger?); czas realizacji; formy płatności; niedziele i godziny świąteczne |
| Opinie | 3 prawdziwe cytaty (za zgodą autorów) z podpisem: imię, źródło, data. Aktualizacja liczb w trzech wyróżnieniach. Opcjonalnie logo Złotej Firmy i Orłów Florystyki |
| Kontakt | E-mail; opis wejścia i parkowania; niedziela w tabeli godzin; potwierdzenie godzin |
| Stopka | Pełna nazwa działalności (CEIDG), NIP, „Projekt i wykonanie: [Twoje studio]” |
| Domena | canonical, og:url i og:image w `<head>` (zakomentowane) |

---

## Fakty użyte na stronie i ich źródła

Dane zebrano z wyników wyszukiwania (październik 2026). Strony Facebooka i katalogów nie dało się otworzyć bezpośrednio, dlatego **przed publikacją potwierdź je z właścicielką**.

| Fakt | Źródło |
|------|--------|
| Nazwa „Kwiaciarnia Agnieszki”, adres ul. Króla Władysława Jagiełły 11A, 72-100 Goleniów, tel. 695 385 464 (komórkowy) | teraz-otwarte.pl, firmania.pl, cylex-polska.pl, ana-kwiaty.pl, orlyflorystyki.pl – zgodne dane |
| Godziny Pn–Pt 9:00–17:00, Sob 9:00–14:00 | te same katalogi (potwierdzone w kilku źródłach). **Uwaga:** jeden katalog podawał Wt–Pt 9–17 i Sob 9–13 |
| Profil na Facebooku | https://www.facebook.com/kwiaciarniaagnieszki/ |
| Oferta: kwiaty cięte i doniczkowe, bukiety okolicznościowe na zamówienie, stroiki, wianki, wiązanki, wieńce i wiązanki pogrzebowe (stonowana kolorystyka), kompozycje w doniczkach, koszach, pudełkach i w szkle, kwiaty z dedykacją na tabliczkach, doradztwo i porady pielęgnacyjne | opisy w katalogach (ana-kwiaty.pl, firmania.pl, infogoleniow.pl, e-goleniow.pl) i opis na Facebooku |
| „Prowadzona od lat przez tę samą właścicielkę” | opisy w katalogach |
| Złota Firma: 4,9/5 z 88 opinii (46 FB + 42 Google Maps), dane z 17.05.2026, wyróżnienie automatyczne na podstawie opinii | https://www.zlotafirma.pl/company/kwiaciarnia-agnieszki-3820466, https://www.zlotafirma.pl/how-it-works |
| Orły Florystyki: laureatka w kolejnych edycjach od 2018 r.; ranking Goleniów 2025/2026 – 9,8/10 z 82 opinii; ranking liczony z opinii, nie konkurs jury | https://www.orlyflorystyki.pl/profile-7338-kwiaciarnia-agnieszki, https://www.orlyflorystyki.pl/city-34244-goleniow/2025, https://www.wsparcieflorystow.pl/2018/07/orly-florystyki/, https://mojakruszwica.pl/pl/665_materialy_partnera/13182_orly-florystyki-czyli-reklama-kwiaciarni-w-social-media.html |
| Facebook: 100% poleca, 46 recenzji | profil na Facebooku (wynik wyszukiwania) |
| Motywy z opinii (świeże kwiaty, kompozycje, wyczucie estetyki, doradztwo, serdeczna obsługa, dbałość o detale) – na stronie jako **podsumowanie**, nie cytaty | opisy opinii w katalogach (infogoleniow.pl, e-goleniow.pl, ana-kwiaty.pl) |
| Przedszkole Publiczne nr 4 „Niezapominajka”, ul. Jagiełły 12 | https://pp4.goleniow.bipdlaszkol.pl/dane-teleadresowe/ |
| Netto, ul. Jagiełły 16 | https://mapa.targeo.pl/netto-supermarket-wladyslawa-jagielly-16-72-100-goleniow~4527026/netto-supermarket/adres |
| Ulica mieszkaniowa (zabudowa TBS) | http://www.tbs.goleniow.pl/… (ogłoszenie o lokalach przy Jagiełły 5a) |
| Goleniów nad Iną, Brama Wolińska (szkic w stopce) | https://eturystyka.wzp.pl/en/Discover-Pomorze_heritage-Zabytkowa_zabudowa/a,6343/Old_Town |
| 21 stycznia – imieniny Agnieszki (i Dzień Babci) | np. https://www.se.pl/… (życzenia na imieniny Agnieszki 21.01) |

Daty w kalendarzu okazji to wiedza ogólna. Zakończenie roku szkolnego liczy się jako *najbliższy piątek po 20 czerwca* (rozporządzenie MEN z 11.08.2017 w sprawie organizacji roku szkolnego). Zwykle to ostatni piątek czerwca, ale nie zawsze, np. w 2024 r. był to 21 czerwca. Porady pielęgnacyjne to ogólna wiedza ogrodnicza.

---

## Czego świadomie NIE napisano (warto o tym powiedzieć właścicielce)

- **Nie „najlepsza / nr 1 w Goleniowie”.** Źródła są sprzeczne (w Orłach Florystyki 2025/2026 jest 2. miejsce).
- **Orły Florystyki i Złota Firma to nie konkursy z jury, nie „nagrody branżowe” ani statuetki.** To rankingi liczone z opinii w internecie i tak to opisano. Lata i kolory medali są pominięte do czasu potwierdzenia.
- **Każda liczba ma źródło i datę.** Liczby różnią się między portalami (4,9/88, 9,8/82, 100%/46, starsze 4,8/35).
- **Nie obiecujemy dostawy:** ani tego samego dnia, ani na cmentarz, ani określonego obszaru czy kosztu. Wszędzie jest „zapytaj”.
- **Nie przypisujemy specjalizacji ślubnej**, jest tylko „zapytaj o bukiet ślubny”.
- **Nie podajemy imienia właścicielki, NIP, nazwy prawnej ani roku założenia.** „Agnieszki” pozostaje nazwą kwiaciarni, a nie imieniem właścicielki.
- **Nie podajemy e-maila.** Domena **kwiaciarniaagnieszka.pl należy do innej kwiaciarni** (Długosiodło, woj. mazowieckie).
- Nie wspominamy o sklepie online, płatnościach kartą lub BLIK, otwarciu w niedziele, Instagramie ani zniczach.
- To inna firma niż „Kwiaciarnia Agnieszka” w Nowogardzie i „Kwiaciarnia u Agnieszki” w Żaganiu.

---

## Pytania do właścicielki

1. Imię i nazwisko. Czy chce występować osobiście (zdjęcie, krótka historia, cytat)?
2. Od którego roku działa kwiaciarnia przy Jagiełły 11A?
3. Czy godziny Pn–Pt 9–17 i Sob 9–14 są aktualne? Co z niedzielą? Czy godziny są wydłużone przed 1 listopada i świętami?
4. Dostawa: czy jest, jaki obszar i koszt, czy w dniu zamówienia, czy na cmentarz?
5. Bukiety ślubne i dekoracje: tak czy nie? Czy są zdjęcia?
6. Preferowany kanał zamówień: telefon, SMS, Messenger, e-mail? Czy jest adres e-mail?
7. Formy płatności: gotówka, karta, BLIK, przelew?
8. Czy możemy użyć zdjęć realizacji z Facebooka?
9. Czy pokazać wyróżnienia Orły Florystyki i Złota Firma (z logo)? Które edycje?
10. Oferta na Wszystkich Świętych: stroiki, wiązanki, wianki, a może też znicze?
11. Czy jest Instagram albo inne profile?
12. Dane do stopki: NIP, pełna nazwa działalności.
13. Czy przyjmuje zamówienia firmowe (rośliny do biur, stałe dostawy)?
14. Orientacyjne ceny „od” i przedziały budżetu do karty zamówienia.

---

## Lista kontrolna przed publikacją

- [ ] Usuń `<meta name="robots" content="noindex, nofollow">` i komentarz „USUŃ PRZED PUBLIKACJĄ”.
- [ ] Odkomentuj i uzupełnij `canonical`, `og:url`, `og:image` (obrazek 1200 × 630 px).
- [ ] Dodaj zdjęcia (`img/README.md`). Zgoda na zdjęcia z Facebooka i na wizerunek właścicielki.
- [ ] Potwierdź godziny i zaktualizuj: `CONFIG.godziny`, JSON-LD, teksty statyczne (szukaj `9:00–17:00`), `niedzielaPotwierdzona`.
- [ ] Uzupełnij ceny „od __ zł” i `CONFIG.budzety`.
- [ ] Uzupełnij informacje o dostawie, płatnościach, czasie realizacji, ślubach, zamówieniach firmowych i dodatkach albo usuń te punkty.
- [ ] Wstaw 3 prawdziwe opinie (za zgodą) i zaktualizuj liczby oraz daty w wyróżnieniach.
- [ ] Logo Złotej Firmy i Orłów Florystyki tylko za zgodą właścicielki. Puste placeholdery usuń.
- [ ] Imię właścicielki, cytat, rok: wstaw albo usuń placeholdery.
- [ ] Uzupełnij NIP, pełną nazwę działalności i „Projekt i wykonanie”.
- [ ] Jeśli jest e-mail, wpisz `CONFIG.email`.
- [ ] Przetestuj na **prawdziwym telefonie** (Android + iPhone): `tel:`, **`sms:` z treścią**, „Kopiuj treść”, „Przypomnij mi” (otwarcie `.ics` w Kalendarzu Google/Apple), „Pokaż mapę”, „Wyznacz trasę”, menu, dolny pasek.
- [ ] Rozważ hostowanie fontów u siebie zamiast z Google Fonts (RODO: przeglądarka łączy się z serwerami Google). Polityka prywatności według tego, co zostanie na stronie.
- [ ] Opcjonalnie usuń tryb edycji (wywołanie `run(editor)` w skrypcie). Jest ukryty, więc może zostać.
- [ ] Zrób test Lighthouse po dodaniu zdjęć (waga JPG 200–400 KB) i dodaj link do strony w Profilu Firmy w Google i na Facebooku.

---

## Propozycje domen

Dostępności nie sprawdzałem. Zweryfikuj ją u rejestratora albo w WHOIS (dns.pl).

1. `kwiaciarniaagnieszki-goleniow.pl` – nazwa + miasto, dobre dla wyszukiwań lokalnych
2. `kwiaciarniaagnieszki.com.pl`
3. `kwiaty-jagielly.pl` – nawiązuje do adresu („na Jagiełły”)
4. `agnieszki-kwiaty.pl`
5. `kwiaciarnia-agnieszki.pl` – **uwaga:** łatwo pomylić z `kwiaciarniaagnieszka.pl` (inna firma, Długosiodło)

Nie używaj nazw sugerujących imię właścicielki (np. „od Agnieszki”), dopóki go nie potwierdzisz. Unikaj też „niezapominajka” w domenie, bo myli się z nazwą przedszkola.

---

## Uwagi techniczne i znane ograniczenia

- **Rozmiar:** `index.html` ma ok. 227 KB (po kompresji gzip ok. 61 KB). To powyżej docelowych ~180 KB, bo wszystkie 21 ilustracji są wbudowane jako SVG. Dzięki temu nie ma dodatkowych żądań, a zdjęcia ładują się leniwie.
- **Brakujące zdjęcia** w trybie demo dają w konsoli błędy 404 (`ERR_FILE_NOT_FOUND`) dla plików z `img/`. To zamierzone: po wrzuceniu zdjęć błędy znikną. Innych błędów konsoli nie ma.
- **Bez JavaScriptu** strona jest w pełni czytelna. Nie działają tylko elementy interaktywne: kalendarz pokazuje stałą listę bez odliczania, podgląd wiadomości jest statyczny, fiszki są rozwinięte, a menu leży w nagłówku.
- **Pole daty** pokazuje format zgodny z językiem urządzenia (na polskim telefonie: dd.mm.rrrr).
- **`sms:`** działa na telefonach. Na komputerze zwykle nic nie robi, dlatego obok jest „Kopiuj treść”.
- **„Napisz na Facebooku”** otwiera profil kwiaciarni. Bezpośredni link do Messengera (`m.me/…`) można dodać po potwierdzeniu nazwy użytkownika strony.
- **Dostępność:** jest skip link, landmarki, jeden `h1`, logiczna kolejność nagłówków, widoczny fokus i kontrast WCAG AA (sprawdzone axe-core: 0 naruszeń na 1440 i 390 px). Strona respektuje `prefers-reduced-motion`. Animacje pojawiania działają tylko z JS i nie ukrywają treści przy szybkim przewijaniu.
- **Prywatność:** brak ciasteczek, analityki i formularzy wysyłających dane. Wiadomość z karty zamówienia nie opuszcza urządzenia, dopóki klient sam nie wyśle SMS-a. Mapa Google ładuje się dopiero po kliknięciu.
