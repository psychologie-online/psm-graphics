psm-graphics
============

Projekt je nastavený pro [Compass](http://compass-style.org) skrze konfigurační soubor
`config.rb`.

## Návod
1. Naklonovat repo do požadované složky
2. Stačí nainstalovat Compass: `sudo gem install compass`
3. Navést terminál do psm-graphics (root projektu): `cd path_to_psm-graphics` (na OSX stačí přetáhnout složku do okna Terminalu)
4. Nastavit automatickou kompilaci z scss do css: `compass watch`

* `scss/foundation/_settings.scss`: definuje všechny proměnné pro Foundation i pro custom styly
* `scss/app.scss`: pro custom styly
