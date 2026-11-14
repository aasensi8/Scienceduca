# Scienceduca

Web en català de materials didàctics, aplicacions i jocs de ciències.

## Estructura

- `index.html`: inici.
- `materials/`: catàleg de materials; seccions de física i química en preparació.
- `jocs/`: catàleg de jocs.
- `jocs/elementa/index.html`: pàgina del joc.
- `jocs/elementa/joc.html`: joc Elementa autònom, amb la pausa de 2 segons i la llicència originals.
- `assets/`: estils, navegació compartida i icona.

## GitHub Pages

A Settings → Pages, trieu **Deploy from a branch**, branca **main**, carpeta **/(root)**. No cal cap instal·lació ni compilació. Tots els enllaços són relatius per admetre la publicació sota el nom del repositori.

## Afegir recursos

Creeu una carpeta dins de `materials/` o `jocs/`, amb el seu `index.html`. Afegiu l’enllaç al catàleg i al menú compartit de les pàgines. Manteniu els camins relatius segons la profunditat de la carpeta.

## Llicència

Continguts educatius originals d’iAducació: CC BY-SA 4.0, llevat d’indicació contrària. Cal citar iAducació, enllaçar la llicència, indicar els canvis i compartir les adaptacions sota la mateixa llicència. Continguts de tercers i codi font exclosos. No s’atorga una llicència de programari al codi font en aquest repositori.

## Identitat visual (14 de novembre de 2026)

El bàner `assets/scienceduca-banner.png` és un retall directe de la imatge original «Logo de Gato y Texto SCIENCEDUCA.png» (1254 × 1254): rectangle x=0, y=340, amplada=1254, alçada=480. No s’ha regenerat ni redibuixat el logotip. La textura `assets/chalk-texture.jpg` prové d’un fragment buit del mateix original.

`site.css`, `activities.css` i `sidebar.css` comparteixen una identitat de pissarra negra, guix blanc i accent vermell. Els colors dels diagrames científics es conserven per mantenir-ne la interpretació. El menú funciona amb hover en ordinador i amb un botó en qualsevol dispositiu, admet teclat i Escape, i marca la pàgina actual. Els jocs incrustats utilitzen el menú de la pàgina contenidora; oberts directament, mostren el seu propi menú.

Validació: 12 pàgines a 390, 768 i 1440 píxels; cap desbordament horitzontal ni error de JavaScript. Comprovats enllaços locals, menú hover/teclat/Escape, conversor de litres i enviament de respostes del laboratori. Les regles i els càlculs de les activitats es mantenen.
