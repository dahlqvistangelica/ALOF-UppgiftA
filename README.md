# Uppgift A i Webbutveckling FrontEnd
Vår uppgift är att från bootstrap exempel bygga en statisk menybaserad html webbsida.
Webbsidan ska ha ett modernt användargränssnitt som dynamiskt anpassar hur sidan presenteras beroende på skärmstorlek, en så kallad responsiv applikation.

## Gruppmedlemmar:
* Angelica Dahlqvist
* Linnea Fernlund
* Olof Brahm
* Filip Gidlöf

# Valda byggstenar och anpassningar.
### Meny
* Navbar - Sticky-top, expandable toggler med text-brand. Anpassat med knappliknande utseende (nav-pills).
### Välkomstsida
* Hero - "Responsive left-aligned hero with image" - Tog bort knapparna som låg under texten. 
### Om oss
* Features with title - Bytt ut iconerna och skrivit våra namn, tog bort knappen under beskrivningstexten för den var onödig. 
### Favorit bild
* Text-center för att centrera text. 
* w-75 och mx-auto för att tighta till texten och se till att den alltid är centrerad i kolumnen.
* img-fluid för att ha en dynamisk storlek på bilden. rounded och shadow för att piffa till bilden.

### Gallery-Table
* Cards - row cols grid för en responsiv och modern tabell. border -0 för att ta bort inre boxen, pd-0 utan indrag.
* Ratio & object fit - anpassat bilderna med ratio och object fit för att tvinga alla bilder till samma storlek. 
* Lekt med olika färger på knappar

### Bilder med rubrik (Gallery)
* Grid system - Använt Bootstrap row och col-md-4 för att visa 3 bilder per rad på desktop, responsivt anpassat för mindre skärmar.
* img-fluid - Gör bilderna responsiva och anpassar storleken efter skärmen.
* gallery-img - Egen CSS-klass med aspect-ratio: 16/9 för enhetliga bildproportioner och object-fit: cover för att fylla utrymmet utan att förvränga bilden.
* mb-4 - Margin-bottom för jämnt avstånd mellan raderna.

