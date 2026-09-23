# Kongres Gospodarczy Kobiet Biznesu 2026 — kongresgospodarczypwcc.pl

Strona Kongresu Gospodarczego Kobiet Biznesu: **5–6 listopada 2026, Butelkownia, Warszawa, start 11:00**.
Organizator: Polish Women Chamber of Commerce.

- **Dzień I (5.11, 11:00–17:00)** — Global Women Chamber of Commerce, spotkanie zamknięte.
- **Dzień II (6.11, od 11:30)** — Business Women IMPACT 2026 dla 500 uczestników; o 18:00 premiera magazynu **Business Women IMPACT**.

Strona to plik `index.html` i folder `assets/` (bez budowania) — wystarczy wgrać je na hosting wraz z `robots.txt` i `sitemap.xml`. Plik `CNAME` ustawia domenę kongresgospodarczypwcc.pl przy hostingu na GitHub Pages; na innym hostingu można go pominąć.

**Program** jest w sekcji `#program` (zakładki Dzień I / Dzień II) — każdy punkt to jeden `<li>` z godziną w `<time>`.

- **Kolory (bordo PWCC #710001 i złoto)**: blok `:root` na początku `<style>` (`--navy` = bordo, `--gold` = złoto). Czcionki: Playfair Display + DM Sans.
- **Adres e-mail zgłoszeń (biuro@polishwomenchamber.pl) i odliczanie (5.11.2026, 11:00)**: obiekt `CONFIG` w ostatnim `<script>`.
- **Grafiki** (`assets/`): `patricia-claudia-mitro.jpg` (baner i okładka magazynu), `pwcc-logo.png` / `pwcc-logo-gold.png` (logo organizatora na jasne / bordowe tło), `pwcc-emblem.png` (godło w logo Kongresu w menu).
- **Logotypy pozostałych partnerów**: miejsca oznaczone w sekcji Partnerzy.
- **Wersja angielska (PL / EN)**: przełącznik w pasku menu. Tłumaczenia są w słowniku `I18N_EN` w `index.html` — każdy nowy polski tekst trzeba tam dopisać z angielskim odpowiednikiem. Wybór języka jest zapamiętywany; link `?lang=en` otwiera stronę od razu po angielsku, a osoby z przeglądarką w innym języku niż polski widzą automatycznie wersję angielską.

## Podstrona oferty magazynu — `/magazyn/`

`magazyn/index.html` to oferta reklamowa i partnerska **Business Women IMPACT 2026/2027** (na podstawie PDF „Oferta wizualna”): oferta w 60 sekund, kolportaż druk i cyfrowy, interaktywna mapa 140 stron, wymiary reklam, okładki, pakiety, subskrypcje, zasady i formularz zapytania (wybrane miejsca trafiają do e-maila).

- **Ceny, strony i działy**: tablice `SECTIONS`, `COVERS`, `PACKAGES` i `DIST` na początku ostatniego `<script>` — mapa, tabele i zestawienie budują się z nich automatycznie.
- **Adres zapytań**: obiekt `CONFIG` w tym samym skrypcie.
