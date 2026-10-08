# Kwiaciarnia Lotos (Goleniów): strona demonstracyjna

Gotowa strona one-page dla **Kwiaciarni „LOTOS” Katarzyny Walczak**, ul. Aleksandra Puszkina 1A, 72-100 Goleniów. Przygotowana jako demo do rozmowy z właścicielką. Wszystko jest w jednym pliku `index.html` (style i skrypt w środku). Z zewnątrz ładują się tylko Google Fonts, a mapa Google dopiero po kliknięciu „Pokaż mapę”.

> **To jest demo.** Strona ma `noindex, nofollow`, a wszystko, czego nie dało się potwierdzić w źródłach, jest oznaczone jako placeholder. Przed publikacją przejdź checklistę na końcu.

## Koncepcja: „Lotos pod Bramą – kwiaty o każdej porze”

Trzy rzeczy wyróżniają Lotos spośród kwiaciarni w Goleniowie. Na nich oparty jest cały projekt:

1. **Nazwa.** Lotos wyrasta z mułu i rozkwita czysty, jest symbolem spokoju i nowego początku. Logo to lotos rysowany jedną linią, a jego środkowy płatek ma kształt gotyckiego łuku.
2. **Miejsce.** Stare miasto, sąsiedztwo XV-wiecznej Bramy Wolińskiej. Wszystkie zdjęcia są wpisane w gotyckie łuki („arkada”), a nad kontaktem i w stopce jest autorska panorama starego miasta z bramą i kościołem św. Katarzyny.
3. **Czas.** Strona idzie rytmem dnia: jasne sekcje, w środku nocny pas „Kwiaty o każdej porze” (dwa kwiatomaty 24/7), potem znów dzień. Lotos w plakietce „Otwarte / Zamknięte” otwiera się z kwiaciarnią i zamyka wieczorem.

Paleta: Mleko lotosu `#FBF5F2`, Płatek `#F4E6E3`, Głęboka woda `#1C3540`, Lotos `#A63D63`, Cegła Bramy `#9A4630`, Liść `#4F6E4C`, Latarnia `#E2B467` (tylko na ciemnym tle). Fonty: Cormorant Garamond (nagłówki), Jost (tekst), Cinzel (drobne napisy). Wszystkie mają polskie znaki.

## Co zawiera demo

| Sekcja | Co robi |
|---|---|
| Nagłówek | Logo lotosu, menu, telefon (click-to-call), mała plakietka „Otwarte do 18:00”. Przy przewijaniu zmniejsza się i przykleja do góry. Na telefonie dostępne menu z obsługą klawiatury (Esc, pułapka fokusu) |
| Hero | „Kwiaty spod Bramy Wolińskiej”, bukiet w gotyckim łuku, okrągła wstawka „Kwiatomat 24/7”, plakietka z **lotosem, który się otwiera** (liczona na żywo w czasie Europe/Warsaw, w niedzielę uczciwie: „godziny do potwierdzenia”) |
| Pasek zaufania | Tradycja, dostawa także w dniu zamówienia, kwiatomaty 24/7, 10% z Kartą Rodziny/Seniora |
| O nas | Historia oparta wyłącznie na faktach, miejsce (Brama Wolińska, mural z mapą Lubinusa 1618, kościół św. Katarzyny), placeholder cytatu właścicielki |
| Interludium | „Lotos wyrasta z mułu i rozkwita czysty…” z dużą ilustracją lotosu na wodzie |
| Oferta | 6 kart ze zdjęciami + 4 karty „Zapytaj także” + baner 10% z Kartą Rodziny/Seniora. Ceny jako „od __ zł” |
| Pamięć | Pas sezonowy (bez różu): stroiki, wieńce, dowóz – zapytaj. Odliczanie do 1 listopada i dzień tygodnia liczone automatycznie, w październiku znaczek „Teraz w kwiaciarni” |
| Kwiatomaty (nocny pas) | 3 kroki (ekran → płatność → odbiór), **interaktywny schemat** z pinezkami (klik/Enter otwiera kartę z „Wyznacz trasę”), karty obu lokalizacji |
| Galeria „Arkada bukietów” | 12 łuków z przesuniętą linią bazową, filtry kategorii, lightbox (strzałki, Esc, fokus w oknie i powrót fokusu) |
| Najbliższe okazje | 4 najbliższe okazje liczone na żywo dla dowolnej daty (Wielkanoc algorytmem Meeusa/Jonesa/Butchera, koniec roku szkolnego wg reguły „piątek po 20 czerwca”). Przycisk ustawia okazję w formularzu |
| Zamów bukiet | Konfigurator: okazja, kolorystyka (podgląd bukietu zmienia kolory i styl na żywo), styl, budżet, termin, odbiór/dostawa, bilecik z licznikiem, dane. Gotowa treść → **Zadzwoń** / **Wyślij SMS** (na komórkę 668 572 086) / **Wyślij e-mail** / **Kopiuj**. Walidacja po polsku, nic nie jest wysyłane z przeglądarki |
| Opinie | 3 eleganckie placeholdery (bez zmyślonych opinii), ogólny ton opinii, linki do Google, Facebooka, Instagrama |
| Porady | Kwiaty cięte, rośliny doniczkowe, „na cmentarz” |
| FAQ | 8 pytań (details/summary), braki oznaczone placeholderami |
| Kontakt | Panorama Goleniowa rysująca się przy przewinięciu, adres, telefony, e-mail, tabela godzin z wyróżnionym „dziś”, kwiatomaty z trasami, Facebook i Instagram, NIP, mapa Google ładowana po kliknięciu |
| Stopka + pasek mobilny | Panorama nocą, dane, „Projekt i wykonanie: [Twoje studio]”, rok z JS. Na telefonie stały pasek Zadzwoń / Trasa / Zamów |

**Tryb edycji:** dopisz `?edycja` do adresu albo wciśnij **Shift+E**. Wszystkie miejsca do uzupełnienia dostaną obrys, a panel pokaże listę (klik przewija do miejsca): **25 miejsc na zdjęcia (23 pliki), 36 tekstów, 5 miejsc do sprawdzenia na miejscu**.

## Jak podmienić zdjęcia

Wgraj pliki o nazwach z `img/README.md` do folderu `img/`. Strona sama zastąpi rysunki zdjęciami. Każdy placeholder ma przygotowany polski tekst alternatywny (`alt`).

## Gdzie edytować dane firmy

Na początku `<script>` na dole `index.html` jest obiekt **`CONFIG` („EDYTUJ TUTAJ”)**: nazwa, telefony, e-mail, adres, godziny, kwiatomaty, linki do Facebooka i Instagrama, NIP, przedziały budżetu. Zmiana tam aktualizuje linki tel/SMS/e-mail, trasy Google, tabelę godzin, plakietkę otwarcia i formularz.
Dane strukturalne **JSON-LD** (`<script type="application/ld+json">` w `<head>`) są statyczne. Przy zmianie godzin, telefonu lub adresu popraw je też tam.

## Placeholdery do uzupełnienia (z właścicielką)

**Zdjęcia:** 23 pliki, lista w `img/README.md`.

**Teksty i dane (oznaczone na stronie jako `ph-text`):**
- O nas: rok, od którego liczyć tradycję `[od 19__ r.]`; cytat Katarzyny Walczak.
- Ceny „od __ zł”: bukiety okolicznościowe, ślubne, wieńce/wiązanki, stroiki, kosze/kompozycje, rośliny.
- Przedziały budżetu w formularzu: `CONFIG.budgets` (teraz „do __ zł”, „__–__ zł”, „powyżej __ zł”).
- Dostawa: zasięg, koszt, do której godziny zamówienia na ten sam dzień.
- Czas realizacji bukietu/wieńca; skład i ceny stroików.
- Dodatki (bileciki, karnety, upominki).
- Płatności w kwiaciarni (gotówka/karta/BLIK), faktury.
- Kwiatomaty: ceny, metody płatności, typowy asortyment.
- Czy przyjmujecie zamówienia SMS-em (668 572 086)?
- Rabat 10% z Kartą Rodziny/Seniora: czy nadal obowiązuje.
- Godziny w niedzielę i wydłużone godziny przed świętami (1.11, Walentynki, Dzień Matki).
- 3 opinie klientów (skopiowane za zgodą z Google/Facebooka) z imieniem i źródłem.
- Galeria: notka „[tu zdjęcia z Instagrama @lotoskwiaciarnia – do podmiany]” pod nagłówkiem. Usuń ją po wgraniu zdjęć.
- Stopka: „Projekt i wykonanie: [Twoje studio]”.
- Domena, canonical, og:url, og:image.

**Do sprawdzenia na miejscu (`ph-verify`, widoczne tylko w trybie edycji):** czy lokal stoi przy samej Bramie Wolińskiej (Targeo ma wpis „Plac Bramy Wolińskiej 1a” z tym samym numerem). Oznaczone są: hasło w hero „Kwiaty spod Bramy Wolińskiej”, napis „PL. BRAMY WOLIŃSKIEJ” na zdjęciu witryny, zdanie w O nas, linijka w Kontakcie i hasło w stopce. To samo hasło jest w `og:title` w `<head>`. Jeśli lokal nie stoi przy bramie, zmień te miejsca, np. na „Spokój lotosu w każdym bukiecie”.

## Fakty użyte na stronie i ich źródła

| Fakt | Źródło |
|---|---|
| Firma: Kwiaciarnia „LOTOS” Katarzyna Walczak, NIP 8561815347, aktywna (od 06.02.2023) | [GoWork](https://www.gowork.pl/kwiaciarnia-lotos-katarzyna-walczak,24913838/dane-kontaktowe-firmy), [cabb.pl](https://cabb.pl/firma/kwiaciarnia-lotos-katarzyna-walczak-8561815347), [kwiaciarnie.one](https://kwiaciarnie.one/wojewodztwo-zachodniopomorskie/goleniow/kwiaciarnia-lotos-katarzyna-walczak) |
| Adres ul. Aleksandra Puszkina 1A, tel. 91 418 39 68, e-mail kwiaciarnialotos.goleniow@wp.pl | GoWork, cabb.pl, katalogi (pkt.pl, Targeo) |
| Komórka 668 572 086 | [Instagram @lotoskwiaciarnia](https://www.instagram.com/lotoskwiaciarnia/), [wGoleniowie.pl](https://wgoleniowie.pl/lokalne/kwiaty-z-automatu-pelna-samoobsluga-w-goleniowiee/) |
| Godziny Pn–Pt 8:00–18:00, Sob 8:00–16:00 (potwierdzone w kilku źródłach) | katalogi, m.in. [godzinyotwarcia24.pl](https://godzinyotwarcia24.pl/Kwiaciarnia-Lotos-Goleni%C3%B3w-KXvnkJ) |
| Marka „Lotos” od lat pod tym adresem i numerem („wieloletnia tradycja”, bez roku) | rejestr poprzedniej firmy ([egospodarka](https://www.firma.egospodarka.pl/raporty-o-firmach/firma,14412605,kwiaciarnia-lotos-walczak-ewa.html)), [pkt.pl](https://www.pkt.pl/firma/lotos-kwiaciarnia-walczak-e-730320) |
| Kwiaty cięte, bukiety, dostawa także w dniu zamówienia | [rodzina.wzp.pl](https://rodzina.wzp.pl/wykaz-ulg/1505/kwiaciarnia-lotos/), [e-goleniow.pl](https://e-goleniow.pl/firmy/kwiaciarnia-goleniow) |
| Bukiety ślubne, okolicznościowe, wieńce pogrzebowe | [findglocal](https://www.findglocal.com/PL/Goleni%C3%B3w/1584789901847148/Kwiaciarnia-Lotos) / evepla |
| Kwiatomaty 24/7: Puszkina 1A i Szczecińska 4c (naprzeciw fontanny), ekran dotykowy, płatność elektroniczna, bukiety odświeżane codziennie przez zespół | [wGoleniowie.pl](https://wgoleniowie.pl/lokalne/kwiaty-z-automatu-pelna-samoobsluga-w-goleniowiee/), Instagram |
| 10% rabatu z Zachodniopomorską Kartą Rodziny i Kartą Seniora | [rodzina.wzp.pl](https://rodzina.wzp.pl/wykaz-ulg/1505/kwiaciarnia-lotos/) |
| Facebook i Instagram | [facebook.com/p/Kwiaciarnia-Lotos-100063581891656](https://www.facebook.com/p/Kwiaciarnia-Lotos-100063581891656/), [instagram.com/lotoskwiaciarnia](https://www.instagram.com/lotoskwiaciarnia/) |
| Ogólny ton opinii (świeże, trwałe kwiaty, miła obsługa, sprawna dostawa), bez liczb | zbiorczo z agregatorów opinii |
| Brama Wolińska (XV w., jedyna zachowana z czterech bram), mural z mapą Lubinusa 1618 na rogu Barnima/Puszkina, kościół św. Katarzyny, prawa miejskie 1268, cmentarz komunalny ul. Przestrzenna 1 | [Wikipedia](https://pl.wikipedia.org/wiki/Brama_Woli%C5%84ska_w_Goleniowie), [infogoleniow.pl](https://infogoleniow.pl/brama-wolinska/), [pomeranica.pl](https://pomeranica.pl/wiki/Ko%C5%9Bci%C3%B3%C5%82_%C5%9Bw._Katarzyny_(Goleni%C3%B3w)), [pomeranica.pl – cmentarz](https://pomeranica.pl/wiki/Cmentarz_komunalny_(Goleni%C3%B3w)) |

### Czego celowo NIE ma na stronie (warto o tym wspomnieć przy rozmowie)

- **Roku założenia.** Źródła się różnią: katalogi podają 1989, rejestr poprzedniej firmy 1991. Nie ma też historii „z matki na córkę”, bo tego nie potwierdzono.
- **Rankingów i ocen** (Orły Florystyki, e-goleniow.pl, infogoleniow.pl, liczby gwiazdek z Google). To zestawienia algorytmiczne i sobie przeczą.
- **Godzin w niedzielę**, cen, zasięgu i kosztu dostawy, płatności, zamówień online, Poczty Kwiatowej/Interflory, liczby pracowników.
- **Sugestii, że Szczecińska 4c to drugi sklep.** To tylko kwiatomat, a strona mówi to wprost.
- Linków do innych „Lotosów” (Bielsk Podlaski, Łabunie, @kwiaciarnia_lotos) i obcych numerów.

## Pytania do właścicielki

1. Czy obecna firma kontynuuje kwiaciarnię p. Ewy Walczak? Od którego roku liczyć tradycję i czy pokazać tę historię?
2. Aktualne godziny, w tym w niedzielę, i wydłużone godziny przed Wszystkimi Świętymi, Walentynkami, Dniem Matki.
3. Czy oba kwiatomaty działają? Od kiedy? Jakie bukiety i ceny? Karta, BLIK?
4. Dostawa: zasięg, koszt, godzina graniczna na ten sam dzień, dowóz na cmentarz lub do domu pogrzebowego?
5. Który numer pokazywać jako główny? Czy można pisać SMS lub WhatsApp na 668 572 086?
6. Czy e-mail kwiaciarnialotos.goleniow@wp.pl jest aktualny i odbierany?
7. Zakres oferty ślubnej (bukiety, butonierki, dekoracje kościoła, sali, auta) i pogrzebowej (wieńce, wiązanki, szarfy, stroiki).
8. Czy rabat 10% na Kartę Rodziny i Kartę Seniora nadal obowiązuje?
9. Czy możemy użyć zdjęć z Instagrama i Facebooka? Czy jest logo lub motyw lotosu?
10. Czy lokal stoi bezpośrednio przy Bramie Wolińskiej (wpis „Plac Bramy Wolińskiej 1a”)? Jak klienci opisują dojazd?
11. Faktury, zamówienia firmowe, stałe dekoracje dla biur i lokali?

## Checklist przed publikacją

- [ ] Usuń `<meta name="robots" content="noindex, nofollow">` (komentarz „USUŃ PRZED PUBLIKACJĄ” w `<head>`).
- [ ] Odkomentuj i uzupełnij `<link rel="canonical">`, `og:url` i `og:image` (najlepiej 1200×630), dopisz `"url"` i `"image"` w JSON-LD.
- [ ] Wgraj zdjęcia do `img/` (lista w `img/README.md`) i sprawdź kadry w łukach.
- [ ] Uzupełnij wszystkie placeholdery (tryb edycji: `?edycja` / Shift+E pokazuje licznik i listę).
- [ ] Potwierdź z właścicielką godziny (też niedzielę), ceny, dostawę, płatności, rabat 10%, działanie kwiatomatów, przyjmowanie SMS-ów. Popraw `CONFIG` i JSON-LD.
- [ ] Na prawdziwym telefonie sprawdź linki `tel:` (oba numery), „Wyślij SMS” (iOS i Android), „Wyślij e-mail”, „Kopiuj treść” (na HTTPS) i „Wyznacz trasę”.
- [ ] Kliknij „Pokaż mapę” i sprawdź pinezkę Google. W razie potrzeby zmień `CONFIG.mapsQuery`.
- [ ] Wpisz swoje studio w stopce. Jeśli strona ma politykę prywatności lub cookies, dodaj link w stopce.
- [ ] Wgraj na hosting z HTTPS. Clipboard API działa tylko w bezpiecznym kontekście, ale jest też wersja awaryjna.
- [ ] Opcjonalnie: wizytówka Google (link do opinii), Google Search Console.

## Propozycje domen

Dostępności tych nazw **nie sprawdzono**. Trzeba to zrobić u rejestratora:

- `lotoskwiaciarnia.pl` (spójne z Instagramem @lotoskwiaciarnia)
- `kwiaciarnialotos-goleniow.pl`
- `lotos-goleniow.pl`
- `kwiatylotos.pl`
- `lotoskwiaty.pl`

Unikaj `kwiaciarnialotos.pl`. Według researchu używa jej inna kwiaciarnia Lotos (Łabunie).

## Uwagi techniczne

- Brak frameworków i zewnętrznych bibliotek. Ilustracje to ręcznie rysowane SVG (sprite z `<symbol>`/`<use>`), więc nie ma zdjęć stockowych.
- Treść jest czytelna bez JavaScriptu (animacje i „pojawianie się” sekcji działają tylko z JS). Respektowane jest `prefers-reduced-motion`.
- Dostępność: jeden `h1`, logiczna kolejność nagłówków, skip link, widoczny fokus, kontrasty AA. Test axe-core (WCAG 2.1/2.2 AA + best practices): 0 naruszeń na desktopie, na telefonie, z otwartym menu, w lightboxie i w trybie edycji.
- W konsoli przeglądarki pojawią się błędy 404 dla brakujących plików w `img/`. To oczekiwane: tak działa automatyczna podmiana. Znikną po wgraniu zdjęć.
- Rozmiar `index.html` to ok. 238 KB (ok. 59 KB po kompresji gzip), więcej niż orientacyjne 180 KB. Większość to ręcznie rysowane ilustracje SVG (ok. 80 KB), które znikną z widoku po wgraniu zdjęć (kod może zostać, nie przeszkadza). Serwer z kompresją gzip/brotli wystarczy, żeby strona ładowała się szybko.
