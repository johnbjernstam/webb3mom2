# Automatiserings-processens syfte
Automatiseringen kan användas till flera olika saker, t.ex:
* Komprimering av filer.

* Konkatenering av filer.

* Automatisering av en specifik uppgift som att t.ex slå ihop två js filer.

* * *

# Verktyg jag använt och anledningen till det
* Visual Studio Code - Det är det program jag använt mest och känner mig mest bekväm med, fungerar bra tillsammans med git med vilket är ett stort plus!

* Git Bash - Jag har använt Git Bash tidigare men det var längesedan, kändes helt ok att börja komma igång med det igen.

* * *

# Mitt system
Hjärtat i mitt system är foldern "src" Här ligger de filer jag arbetar med som sedan skickas till katalogen "dist" för publicering.

Jag har sju tasks:
* imagemin - Kopierar mina bilder från /images i /src till /images i /dist.
* copyphp - Kopierar mina php-filer från /src till /dist.
* sass - Kopierar mina sass-filer från /sass i /src till /css i /src.
* css - Kopierar mina css-filer från /css i /src till /css i /dist.
* scripts - Kopierar mina js-filer från /js i /src till /js i /dist.
* run - Startar och kör alla tasks.
* watch - Körs i bakgrunden och lyssnar till förändringar i de filer jag arbetar med.
* * *
