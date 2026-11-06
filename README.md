# MERIDIAN — strona doradcy finansowego

Projekt koncepcyjny do portfolio. Marka, doradca, dane kontaktowe i opisy usługi są fikcyjne. Portret stockowy Unsplash: photo-1519085360753-af0119f7cbe7; biuro: photo-1497366754035-f200968a6e72. Fonty Google Fonts: DM Sans i Playfair Display.

## Gotowe pliki

Zawartość `dist` to kompletna strona: `index.html`, `styles.css`, `script.js`, `favicon.svg`, `.nojekyll` i folder `images`. Bez instalacji frameworka i bez kompilacji.

Na GitHub Pages wgraj **zawartość dist** bezpośrednio do repozytorium, zachowując folder `images`. Settings → Pages → Deploy from a branch → main → /(root). Wszystkie adresy plików są względne, dzięki czemu działają również pod `/nazwa-repozytorium/`.

Podgląd lokalny: otwórz `dist/index.html`, albo uruchom `node preview.cjs` i odwiedź http://127.0.0.1:8778.

## Interakcje

- Menu mobilne, sekcje z animacjami respektującymi ograniczenie ruchu w systemie.
- Panele usług z wyborem tematu formularza.
- Kalkulator miesięcznego odkładania: max(0, cel − już odłożone) / liczba miesięcy, zaokrąglenie w górę do pełnego złotego. Bez odsetek, inflacji, opłat i podatków. Nie stanowi porady ani prognozy.
- FAQ i informacje o prywatności w dostępnym oknie dialogowym.
- Formularz z walidacją, lokalnym podsumowaniem i możliwością resetu. Nie wysyła danych, nie umawia konsultacji i nie zapisuje danych na serwerze.

Edycja treści: `dist/index.html`; wygląd: `dist/styles.css`; zachowanie: `dist/script.js`. Zdjęcia ilustracyjne zapisane lokalnie. Pliki HTML/CSS/JS w paczce do GitHub Pages znajdują się bezpośrednio w katalogu głównym.
