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

## Podstrona Investment Club — `/investment-club/`

Strona Polish Investment Club by PWCC (jasna wersja: krem, bordo, złoto): `investment-club/index.html` + grafiki w `investment-club/img/` (`warszawa.webp` w nagłówku, `og-investment-club.jpg` do udostępnień). Logo i zdjęcie Prezydentki są brane z głównego `assets/`.

- **Harmonogram spotkań**: lista `#meetings` — każde spotkanie to `<li data-date="RRRR-MM-DD">`. Strona sama wyszarza odbyte spotkania i wyróżnia najbliższe.
- **Formularz aplikacyjny** (Google Forms) i kontakt (biuro@polishwomenchamber.pl) — w sekcjach `#dolacz` i `#kontakt`.
- Treści oparte na: Harmonogram v3 ROZSZERZONY, Regulamin Członkowski PIC, prezentacja Polish Investment Club i oferta INVESTMENT CLUB. Strona jest tylko po polsku.
- **Polityka prywatności i klauzula RODO**: `investment-club/polityka-prywatnosci.html` (klauzula dla kandydatów pod kotwicą `#kandydaci` — ten link warto wkleić do formularza Google). Strona Klubu nie używa cookies ani analityki, a czcionki są hostowane lokalnie w `investment-club/fonts/`. Jeśli dodasz np. Google Analytics lub Meta Pixel, trzeba dodać baner zgody i zaktualizować politykę.
