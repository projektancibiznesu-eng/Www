# Kongres Gospodarczy Kobiet Biznesu 2026 — strona www

Strona Kongresu Gospodarczego Kobiet Biznesu: **5–6 listopada 2026, Butelkownia, Warszawa, start 11:00**.
Organizator: Polish Women Chamber of Commerce. Częścią Kongresu jest premiera magazynu **Business Women IMPACT** (6 listopada).

Strona to plik `index.html` i folder `assets/` (bez budowania) — wystarczy wgrać oba na hosting.

- **Kolory (bordo PWCC #710001 i złoto)**: blok `:root` na początku `<style>` (`--navy` = bordo, `--gold` = złoto). Czcionki: Playfair Display + DM Sans.
- **Adres e-mail zgłoszeń (biuro@polishwomenchamber.pl) i odliczanie (5.11.2026, 11:00)**: obiekt `CONFIG` w ostatnim `<script>`.
- **Grafiki** (`assets/`): `patricia-claudia-mitro.jpg` (baner i okładka magazynu), `pwcc-logo.png` / `pwcc-logo-gold.png` (logo organizatora na jasne / bordowe tło), `pwcc-emblem.png` (godło w logo Kongresu w menu).
- **Logotypy pozostałych partnerów**: miejsca oznaczone w sekcji Partnerzy.
- **Wersja angielska (PL / EN)**: przełącznik w pasku menu. Tłumaczenia są w słowniku `I18N_EN` w `index.html` — każdy nowy polski tekst trzeba tam dopisać z angielskim odpowiednikiem. Wybór języka jest zapamiętywany; link `?lang=en` otwiera stronę od razu po angielsku, a osoby z przeglądarką w innym języku niż polski widzą automatycznie wersję angielską.
