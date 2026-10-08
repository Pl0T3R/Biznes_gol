# Kwiaciarnia Aniellska – strona demonstracyjna

Strona-wizytówka przygotowana jako **demo do rozmowy sprzedażowej** z właścicielką,
panią Małgorzatą Banasiewicz (Kwiaciarnia Aniellska, ul. Jana Matejki 2A lok. 3, 72-100 Goleniów).

Całość to jeden plik: `index.html`. Działa po dwukliku, bez serwera i bez instalowania czegokolwiek.
Zdjęcia dokłada się do folderu `img/` (lista plików: [`img/README.md`](img/README.md)).

> **Uwaga:** strona ma ustawione `noindex, nofollow`, więc Google jej nie zaindeksuje, dopóki tego nie zmienisz.
> Wszystko, czego nie dało się potwierdzić, jest oznaczone jako widoczny placeholder (różowe podkreślenie z przerywaną kreską).

---

## Koncept: „Pod aureolą – kwiaty z anielską starannością”

- Nazwa **Aniellska** (zawsze przez podwójne „ll”!) kojarzy się z „anielska”, a w ofercie są figurki aniołów.
  Motyw to więc pióra i cienka złota aureola, bez kiczu: żadnych pucułowatych aniołków ani brokatu.
- Logo to typograficzny znak SVG: w słowie „Aniellska” litery „ll” są narysowane jako dwie lotki piór,
  a nad „A” unosi się złota aureola.
- Paleta: perła, mgiełka, lila zmierzchu, złota aureola, róż świtu i zieleń parku.
  Fonty: Bodoni Moda (nagłówki) i Mulish (tekst). Oba mają polskie znaki.
- Układ oparty na kołach i łukach. Każde zdjęcie stoi w „aureoli”, czyli kole, owalu albo łuku z cienką złotą obwódką.
- Ton: ciepły, sąsiedzki („Wracasz z parku? Wpadnij po kilka świeżych kwiatów”), zwroty na „Ty”, kwiaciarnia mówi „my”.

## Co jest na stronie

1. **Nagłówek**: logo, menu (O nas · Oferta · Upominki · Zamów · Galeria · Kontakt) i przycisk „Zadzwoń”.
   Przykleja się do góry i zmniejsza przy przewijaniu. Na telefonie jest dostępne menu rozwijane.
2. **Hero** „Kwiaty z *anielską* starannością”: duże koło z bukietem, dwa małe okręgi (anioł i karnet),
   wolno obracająca się kropkowana orbita i skrzydła w tle. Plakietka **„Otwarte teraz / Zamknięte – otwieramy…”**
   jest liczona na żywo w strefie czasowej Europe/Warsaw, z dopiskiem „godziny do potwierdzenia”.
3. **Pasek wyróżników**: od 2016 roku w Goleniowie, bukiety na indywidualne zamówienie, dostawa (zapytaj), prezent w jednym miejscu.
4. **O nas**: historia oparta wyłącznie na potwierdzonych faktach, miejsca na zdjęcia wnętrza i właścicielki
   (to drugie tylko za zgodą), placeholder na cytat właścicielki i na historię nazwy.
5. **Oferta**: 4 karty „kameo” z potwierdzoną ofertą, pasek „Dostawa pod wskazany adres”
   i osobny rząd **„Na szczególne okazje – zapytaj”** (flower box, ślub, oprawa pogrzebowa, stroiki).
   Te usługi **nie są potwierdzone**, więc są podane jako zaproszenie do pytania, a nie obietnica.
6. **Anioły i upominki – „Prezent w jednym miejscu”**: przewijana półka (strzałki, klawiatura, przewijanie palcem)
   z figurkami aniołów, karnetami, wazonami, doniczkami, kwiatami sztucznymi i pakowaniem, plus 3 pomysły na prezent,
   które jednym kliknięciem ustawiają konfigurator.
7. **Konfigurator „Ułóżmy bukiet razem”**: okazja, kolorystyka, styl, budżet, **dodatki**, termin,
   odbiór lub dostawa, bilecik (licznik znaków i 3 gotowe życzenia), imię i telefon.
   - Na żywo rysuje się **„tacka prezentowa”**: obok bukietu pojawiają się wybrane dodatki.
   - Podgląd wiadomości wygląda jak **złoty karnet**, po którym przy najechaniu przesuwa się delikatny połysk.
   - Przyciski: **Wyślij SMS** (otwiera aplikację SMS z gotową treścią na 607 647 115), **Wyślij e-mail**
     (na gosia-banasiewicz@wp.pl z tematem i treścią), **Kopiuj treść**, **Zadzwoń**.
   - Walidacja po polsku: data nie może być w przeszłości, telefon musi mieć 9 cyfr, adres jest wymagany przy dostawie.
     Formularz podpowiada też, gdy wybrany dzień to niedziela albo godzina wypada poza godzinami otwarcia.
   - Nic nie jest nigdzie wysyłane: formularz tylko przygotowuje treść w przeglądarce.
   - Po poprawnym wypełnieniu raz spada kilka piórek (wyłączone przy „ograniczonym ruchu” w systemie).
8. **Kalendarz okazji**: 4 najbliższe święta kwiatowe z odliczaniem dni. Złota aureola domyka się, gdy termin się zbliża.
   Bez JavaScriptu widać same daty (bez odliczania), więc nic się nie dezaktualizuje.
   Liczy się dla dowolnej daty, z Wielkanocą (algorytm Meeusa/Jonesa/Butchera) i końcem roku szkolnego
   (ostatni piątek czerwca). Przycisk „Ułóż bukiet na tę okazję” ustawia konfigurator.
9. **Galeria „Spod naszych rąk”**: filtry (Wszystkie / Bukiety / Rośliny / Upominki / Okazje / Sztuczne)
   i podgląd na pełnym ekranie. Działa z klawiatury: Esc zamyka, strzałki przełączają, fokus nie ucieka i wraca na miejsce.
   Podgląd obsługuje zarówno ilustracje, jak i prawdziwe zdjęcia.
10. **Opinie** (jedyny ciemny pas): **„Historia jednego bukietu”** to sparafrazowana prawdziwa opinia z pkt.pl (styczeń 2024),
    bez nazwiska. Obok ocena 5,0 z podanym źródłem, najczęściej chwalone cechy według podsumowań opinii
    i 3 puste karty na prawdziwe opinie. Przyciski prowadzą do opinii w Google i na Facebook.
11. **Porady**: krótkie, praktyczne wskazówki pielęgnacji kwiatów ciętych, roślin doniczkowych, storczyków i kwiatów sztucznych.
12. **FAQ „Zanim zadzwonisz”**: rozwijane pytania (zamawianie, wyprzedzenie, dostawa, płatności, oprawa pogrzebowa, upominki, godziny).
13. **Kontakt „Wpadnij po drodze z parku”**: własny schemat dojazdu (Park 750-lecia i ul. Matejki, „schemat poglądowy – nie w skali”).
    Przycisk **„Pokaż mapę”** wczytuje mapę Google dopiero po kliknięciu, co jest lepsze dla prywatności i szybkości.
    Są też adres, telefon, e-mail, Facebook, tabela godzin z wyróżnionym dzisiejszym dniem, „Wyznacz trasę” i NIP.
14. **Stopka**: dane firmy, rok liczony automatycznie, „Projekt i wykonanie: [Twoje studio]”.
15. **Telefon**: na ekranach do 760 px na dole jest stały pasek akcji: Zadzwoń / Trasa / Zamów.

Do tego:

- **Tryb edycji**: dopisz `?edycja` do adresu albo naciśnij **Shift+E**. Wszystkie placeholdery dostaną ramki,
  przy miejscach na zdjęcia pojawi się nazwa pliku, a panel pokaże ich listę. Kliknięcie pozycji przewija do niej stronę.
- Strona działa też bez JavaScriptu: cała treść jest widoczna, a JS tylko ją wzbogaca.
- Dostępność: link „Przejdź do treści”, jeden `h1`, regiony strony, widoczny fokus, kontrast WCAG AA
  (sprawdzone w axe-core, bez błędów) i obsługa „ograniczonego ruchu”.
- SEO: tytuł, opis, Open Graph, JSON-LD `Florist` z adresem, telefonem, godzinami i linkiem do Facebooka.

## Jak edytować dane firmy

Na początku skryptu, na dole pliku `index.html`, jest obiekt **`CONFIG`** z komentarzem „EDYTUJ TUTAJ”.
Telefon, e-mail, adres, godziny, Facebook i NIP zmieniasz **tylko tam**, a strona sama wstawi je w nagłówku, kontakcie,
stopce, plakietce „Otwarte”, tabeli godzin i konfiguratorze.

- `hoursConfirmed: false` zostaw do czasu potwierdzenia godzin. Potem ustaw `true`, a dopiski „do potwierdzenia” znikną.
- `hoursNotes` to notatki przy sobocie i niedzieli. Po potwierdzeniu usuń je albo opróżnij.
- Dane strukturalne **JSON-LD** w `<head>` są statyczne. Po zmianie danych popraw je też tam.
- Kolory i fonty są w `:root` na początku `<style>`.
- Teksty wstawiane przez skrypt (np. podpowiedzi w kalendarzu, plakietka „Otwarte”) przechodzą przez funkcję `nb()`,
  która dokłada twarde spacje po „w”, „z”, „i”, „o” itd. W HTML używaj po prostu `&nbsp;`, tak jak w reszcie pliku.

## Placeholdery do uzupełnienia

### Zdjęcia (25)
Pełna lista nazw, proporcji i rozmiarów: [`img/README.md`](img/README.md).

### Teksty i dane

| Sekcja | Co uzupełnić | Uwagi |
|---|---|---|
| Pasek / O nas | „10 lat z Goleniowem”, pieczęć „10 lat w 2026” | Tylko po potwierdzeniu daty otwarcia (znany jest wyłącznie rok 2016) |
| O nas | Cytat właścicielki | Wyłącznie jej własne słowa |
| O nas | Historia nazwy „Aniellska” (podwójne „ll”) | Od imienia czy gra słów z „anielska”? |
| O nas | Zdjęcie właścicielki, ewentualnie zdrobnienie „Gosia” | Tylko za zgodą |
| Oferta | Ceny „od __ zł”: kwiaty cięte, bukiety, rośliny, kwiaty sztuczne | |
| Oferta | „Na szczególne okazje – zapytaj”: flower box, ślub, wieńce i wiązanki, stroiki | Najpierw potwierdzić, **czy** kwiaciarnia to robi. Jeśli nie, usunąć kartę |
| Oferta / FAQ / Konfigurator | Obszar i koszt dostawy | Dostawa pod adres jest potwierdzona opiniami, ale zasięgu, kosztu ani dostawy „na dziś” nie znamy |
| Upominki / Konfigurator | Ceny upominków i dodatków | |
| Konfigurator | Przedziały budżetu: „do __ zł”, „__–__ zł”, „od __ zł” | Tekst przycisku trafia do wiadomości SMS i e-mail |
| Opinie | Aktualna ocena w Google (5,0 według e-goleniow.pl i infogoleniow.pl) | Sprawdzić przed publikacją |
| Opinie | Miejsce w Orłach Florystyki 2025 | Źródła podają 1. **lub** 2. miejsce. To ranking z opinii internautów, nie nagroda jury |
| Opinie | 3 prawdziwe opinie klientów (treść i podpis) | Za zgodą autorów, z podaniem źródła |
| FAQ | Czas realizacji zamówień | |
| FAQ | Formy płatności (gotówka, karta, BLIK, przelew) | Karta i NFC mają tylko jedno źródło, więc nie zostały podane |
| Konfigurator / FAQ | Zamówienia przez SMS, e-mail i Messengera | Przyciski SMS i e-mail działają, ale warto potwierdzić, że właścicielka chce tak przyjmować zamówienia |
| FAQ | Zakres oprawy pogrzebowej (wieńce, wiązanki) | Na razie tylko „zadzwoń i zapytaj”. Uzupełnić po rozmowie albo usunąć pytanie |
| FAQ / Kontakt | Godziny: soboty, niedziele, przed świętami | Obecne godziny pochodzą z jednego katalogu |
| Kontakt | Jak trafić do lokalu 3 (wejście, szyld, parking) | |
| Stopka | „Projekt i wykonanie: [Twoje studio]” | Twoja nazwa i link |
| `<head>` | Domena: `canonical`, `og:url`, `og:image` | Są gotowe, zakomentowane linie |

## Fakty użyte na stronie i ich źródła

| Fakt | Źródło |
|---|---|
| Nazwa „Kwiaciarnia Aniellska”, właścicielka Małgorzata Banasiewicz, NIP 8561592781, działalność aktywna, PKD 47.76.Z | CEIDG przez owg.pl i krs-online.com.pl |
| Działalność od 2016 r. (bez dokładnej daty) | CEIDG i katalogi (owg.pl, krs-online.com.pl, panoramafirm.pl) |
| Adres: ul. Jana Matejki 2A lok. 3, 72-100 Goleniów | CEIDG i katalogi firm (panoramafirm.pl, pkt.pl) |
| Telefon komórkowy 607 647 115, e-mail gosia-banasiewicz@wp.pl | Katalogi firm (m.in. panoramafirm.pl, pkt.pl) |
| Godziny Pn–Pt 9:00–17:00, Sob 9:00–14:00 (**do potwierdzenia**) | Tylko jeden katalog firm, a pkt.pl podaje niedzielę jako dzień zamknięty |
| Facebook: facebook.com/kwiaciarniaaniellska | facebook.com/kwiaciarniaaniellska |
| Oferta: kwiaty cięte i doniczkowe, kwiaty sztuczne, wiązanki i bukiety, bukiety na indywidualne zamówienie, karnety, doniczki, wazony, figurki aniołów, pakowanie | Opis na Facebooku, panoramafirm.pl, pkt.pl, e-goleniow.pl, infogoleniow.pl |
| Dostawa kwiatów pod wskazany adres | Opinia na pkt.pl (01.2024), e-goleniow.pl |
| „Historia jednego bukietu”: bukiet z dostawą do domu wnuczki, która „nigdy w życiu nie dostała tak pięknych kwiatów” | Opinia na pkt.pl z 6.01.2024 (sparafrazowana, bez nazwiska) |
| Ocena 5,0 w Google i najczęściej chwalone cechy (piękne bukiety, miła obsługa, świeże kwiaty, zamówienia indywidualne, doradztwo, ceny) | Zestawienia e-goleniow.pl i infogoleniow.pl |
| Wysokie miejsca w rankingach z opinii: Orły Florystyki 2025 (Goleniów), e-goleniow.pl „Najlepsze firmy 2026” | orlyflorystyki.pl, e-goleniow.pl (miejsce do potwierdzenia) |
| Okolica: Park 750-lecia (największy park miejski, wejście m.in. od Matejki), lewobrzeżna część miasta nad Iną, sąsiednie sklepy pod Matejki 2–2C | pl.wikipedia.org (Park 750-lecia Goleniowa), mapa.targeo.pl |
| Współrzędne w JSON-LD (ok. 53.5618 N, 14.823 E) | Katalogi firm (przybliżone) |

### Czego celowo NIE ma na stronie (brak potwierdzenia)

- dostawy „tego samego dnia”, obszaru i kosztu dostawy;
- wieńców, florystyki ślubnej i dekoracji sal jako specjalności (są tylko jako „zapytaj”);
- „1. miejsca w Orłach Florystyki”, przedstawiania rankingów jako nagród jury, dokładnej liczby opinii i hasła „najlepsza kwiaciarnia w Goleniowie”;
- adresu w Osinie, sponsoringu szkoły w Osinie, sprzedaży hurtowej, sklepu internetowego, Poczty Kwiatowej, Interflory, Instagrama i TikToka;
- płatności kartą, NFC i BLIK jako pewnych, godzin niedzielnych i przedświątecznych;
- wzmianek o bliskości cmentarza, imion autorów opinii i wypowiedzi właścicielki w pierwszej osobie.

## Pytania do właścicielki (warto zadać na spotkaniu)

1. Czy godziny Pn–Pt 9–17 i Sob 9–14 są aktualne? Czy w niedzielę jest zamknięte? Jakie są godziny przed Wszystkimi Świętymi, Walentynkami i Dniem Matki?
2. Dostawa: jaki obszar (Goleniów, gmina, okolice), jaki koszt i czy da się zamówić dostawę na ten sam dzień?
3. Czy robi pani wieńce i wiązanki pogrzebowe, bukiety ślubne, dekoracje kościoła lub sali, stroiki na Wszystkich Świętych?
4. Skąd nazwa „Aniellska” z podwójnym „ll”?
5. Dokładna data otwarcia w 2016 roku. Czy chce pani wykorzystać 10-lecie w promocji?
6. Czy możemy użyć pani zdjęcia, zdrobnienia „Gosia” oraz zdjęć bukietów i wnętrza z Facebooka?
7. Jakie są formy płatności (karta, BLIK, przelew przy zamówieniu telefonicznym)?
8. Czy przyjmuje pani zamówienia SMS-em, e-mailem i przez Messengera?
9. Czy adres w Osinie, który pojawia się w jednym katalogu, to błąd, drugi punkt czy adres korespondencyjny?
10. Które miejsce zajęła kwiaciarnia w Orłach Florystyki 2025 i czy ma pani certyfikat?
11. Jak najłatwiej trafić do lokalu nr 3 (wejście, szyld, parking)?
12. Czy figurki aniołów i kwiaty sztuczne to nadal stała część oferty?

## Checklista przed publikacją

- [ ] Usunąć `<meta name="robots" content="noindex, nofollow">` razem z komentarzem „USUŃ PRZED PUBLIKACJĄ”.
- [ ] Ustawić domenę: odkomentować i uzupełnić `<link rel="canonical">`, `og:url` i `og:image` (pełny adres URL obrazka 1200×630).
- [ ] Dodać zdjęcia do `img/` według `img/README.md` i sprawdzić w trybie `?edycja`, czy nic nie zostało.
- [ ] Potwierdzić z właścicielką godziny (potem `hoursConfirmed: true` w `CONFIG`) i poprawić JSON-LD w `<head>`.
- [ ] Uzupełnić ceny „od __ zł”, przedziały budżetu, ceny dodatków, obszar i koszt dostawy, formy płatności i czas realizacji.
- [ ] Usunąć karty „zapytaj” dla usług, których kwiaciarnia nie wykonuje.
- [ ] Wstawić prawdziwe opinie (za zgodą) albo usunąć puste karty. Sprawdzić aktualną ocenę Google i miejsce w rankingu.
- [ ] Usunąć lub wypełnić wszystkie `[… – do potwierdzenia]` (Shift+E pokaże listę).
- [ ] Wpisać swoje studio w stopce.
- [ ] **Na prawdziwym telefonie** sprawdzić linki `tel:` i `sms:` (iPhone i Android), „Wyślij e-mail”, „Kopiuj treść” (na HTTPS),
      „Wyznacz trasę” i „Pokaż mapę”.
- [ ] Przetestować formularz: walidację, dodatki na tacce, bilecik i przyciski z kalendarza okazji.
- [ ] Opublikować przez HTTPS (wymagane m.in. przez schowek), włączyć kompresję gzip lub brotli.
- [ ] Dodać stronę do profilu Google (Google Business Profile) i na Facebooka kwiaciarni.

## Propozycje domen

Dostępności **nie sprawdzałem**, trzeba ją zweryfikować u rejestratora.

- `aniellska.pl`
- `kwiaciarnia-aniellska.pl`
- `aniellska-goleniow.pl`
- `kwiatyaniellska.pl`
- `aniellska.com.pl`

## Uwagi techniczne

- Jeden plik `index.html` (ok. 222 KB, po kompresji gzip ok. 55 KB; ok. 53 KB to ręcznie rysowane ilustracje SVG). Style i skrypty są w środku, bez bibliotek i bez CDN.
  Z zewnątrz ładują się tylko fonty Google i mapa Google, i to dopiero po kliknięciu.
- Ilustracje zastępcze to rysunki SVG w jednym „sprite’cie” na początku `<body>`, wielokrotnie używane przez `<use>`.
- Brakujące zdjęcia: przeglądarka zgłasza w konsoli błąd 404 dla każdego pliku z `img/`, którego jeszcze nie ma.
  Tak ma być, zdjęcie po prostu zostaje zastąpione ilustracją. Błędy znikną po dodaniu zdjęć.
- Testowane w Chromium (320–1920 px, m.in. 1440, 1024 i 390 px): bez poziomego przewijania i bez błędów JS.
  Kod przechodzi html-validate i axe-core (WCAG 2.1/2.2 AA) bez błędów, także z otwartym menu, podglądem zdjęć,
  panelem edycji i komunikatami błędów formularza. Na telefonie fokus klawiatury nie chowa się pod dolnym paskiem akcji.
