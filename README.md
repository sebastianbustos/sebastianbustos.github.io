# Front-end developer test

## Om testet
Detta test kan användas för att i grova drag kategorisera en kandidats kunskaper inom front-end utveckling.

Testet är medvetet utformat på sådant sätt där kraven är otydligt formulerade och där projektscopet är hårt satt (kundens budget) för att simulera fall som är vanligt förekommande i branschen. En del av testet utgörs av att bedömma hur väl kandidaten förhåller sig till, samt tolkar, de definierade kraven samt projektscope.

### Bedömningskriterier

#### Kodkvalité

* Kandidaten skriver semantisk HTML
* Kandidaten använder inte onödiga HTML element<sup>1</sup>
* Kandidatens HTML-kod validerar enligt W3C
* Kandidaten följer givna standarder i namnsättning av CSS-klasser<sup>2</sup>
* Kandidatens kod är har korrekt indentering
* Kandidaten skriver kommentarer i koden där det behövs
* Kandidaten skriver sina varibelnamn i "Camel case" med inledande gemen bokstav
* Kandidatens applikation bygger korrekt och kastar inga fel

#### Design

* Kandidaten har god känsla för färger och form
* Kandidaten har utformat designen så att den fungerar bra i mindre skärmstorlekar

#### Kompabilitet

* Sidan renderar korrekt i senaste versioner av angivna webbläsare
  * Microsoft Internet Explorer
  * Microsoft Edge
  * Google Chrome
  * Mozilla Firefox
  * Opera
  * Safari

#### Prestanda

* Javascriptfiler är ihopslagna och minifierade
* Stilmallar är ihopslagna och minifierade
* Kandidaten använder så få anrop som möjligt i sin applikation.
* Kandidaten använder inte onödiga plugins<sup>3</sup>

#### Tillgänglighet

* Sidan validerar enligt WCAG 2.0

#### Paketering

* Filpaketets filstruktur är logiskt uppbyggd
* Filpaketets filer är logiskt namngivna
* Kandidatens applikation går att bygga automatiskt<sup>4</sup>
  
---

<sup>1. </sup>*Riktlinjen är så få element som möjligt för att lösa en given uppgift.*

<sup>2. </sup>*OOCSS, SMACSS, BEM.*

<sup>3. </sup>*Med onödiga menas större bibliotek i förhållande till vad som krävs för att lösa uppgiften.*

<sup>4. </sup>*Applikationen går att bygga per automatik med exempelvis Webpack*
