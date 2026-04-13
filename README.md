# DawkApp Website

Statyczna strona-wizytówka przygotowana pod `dawkapp.pl` i GitHub Pages.

## Co tu jest

- `index.html` - landing page z CTA do Google Play, sekcjami funkcji, prywatności i Free/Premium
- `privacy.html` - pełna strona polityki prywatności
- `styles.css` - wspólny styl strony
- `app-ads.txt` - plik dla Google AdMob
- `assets/` - logo i favicon
- `CNAME.example` - przykładowa zawartość pliku `CNAME` po zakupie domeny

## Co trzeba uzupełnić przed publikacją

W plikach `index.html` i `privacy.html` podmień placeholdery:

- adres podmiotu publikującego
- dane rejestrowe podmiotu publikującego

Aktualnie strona ma już wpisane:

- email kontaktowy: `cjdevski@gmail.com`
- brand / nazwa aplikacji: `DawkApp`
- adres strony wsparcia: `https://dawkapp.pl`
- datę polityki prywatności: `13 kwietnia 2026`

## Sugerowany minimalny setup

1. Kup domenę `dawkapp.pl`.
2. Wrzuć zawartość tego katalogu do repo, z którego publikujesz GitHub Pages.
3. Włącz GitHub Pages dla tego repo.
4. Gdy domena będzie gotowa, skopiuj `CNAME.example` do pliku `CNAME` i zostaw w nim `dawkapp.pl`.
5. Ustaw własną domenę w konfiguracji GitHub Pages.
6. Dodaj stronę do Google Search Console i zweryfikuj własność domeny.

## Po publikacji

- dodaj link do `dawkapp.pl` na stronie głównej `cjdev-hash.github.io`
- użyj `https://dawkapp.pl/privacy.html` jako oficjalnego linku polityki prywatności
- zachowaj spójne dane firmy z CEIDG/KRS, D-U-N-S, Google Payments i Play Console
