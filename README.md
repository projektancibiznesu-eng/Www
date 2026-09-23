# Business Women IMPACT — strona zapowiedzi

Strona zapowiedzi i inauguracji magazynu **Business Women IMPACT** (Kongres Gospodarczy Kobiet Biznesu, 5–6 listopada 2026, Butelkownia, Warszawa, 11:00).
Wydawca: Polish Women Chamber of Commerce · www.businesswomenimpact.pl

Strona to plik `index.html` i folder `assets/` (bez budowania) — wystarczy wgrać oba na hosting.

- **Kolory marki (bordo i złoto)**: blok `:root` na początku `<style>` (`--navy` = bordo, `--gold` = złoto). Czcionki: Playfair Display + DM Sans.
- **Adres e-mail zgłoszeń (biuro@polishwomenchamber.pl) i odliczanie (5.11.2026, 11:00)**: obiekt `CONFIG` na początku `<script>`.
- **Portret Redaktor Naczelnej**: `assets/patricia-claudia-mitro.jpg` (okładka i sekcja Redakcja).
- **Logo wydawcy PWCC**: `assets/pwcc-logo.png` (bordo, na jasne tło) i `assets/pwcc-logo-gold.png` (złote, na bordo) — w banerze, sekcji Partnerzy i stopce.
- **Logotypy pozostałych partnerów**: miejsca oznaczone w sekcji Partnerzy.
- **Wersja angielska (PL / EN)**: przełącznik w pasku menu. Tłumaczenia są w słowniku `I18N_EN` w `index.html` — każdy nowy polski tekst trzeba tam dopisać z angielskim odpowiednikiem. Wybór języka jest zapamiętywany; link `?lang=en` otwiera stronę od razu po angielsku, a osoby z przeglądarką w innym języku niż polski widzą automatycznie wersję angielską.
