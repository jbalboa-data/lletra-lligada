# Lletra lligada

Joc per practicar l'escriptura en lletra lligada. Al centre de la pantalla apareix una paraula enfosquida i el nen o la nena l'ha de resseguir amb el dit (tauleta o pantalla digital) o amb el ratolí (ordinador). Si se surt del camí, torna a començar la lletra; si completa la paraula, passa a la següent.

## A qui va dirigit

Alumnat de **1r de primària (6 anys)** que s'inicia en la lectura i l'escriptura de la lletra lligada. Està pensat per fer-lo servir a l'aula, sobretot en pantalles digitals interactives en horitzontal, tot i que també funciona en tauletes i ordinadors.

## Com s'hi juga

1. Obre `index.html` amb un navegador (Chrome, Edge, Safari o Firefox). No cal instal·lar res ni tenir connexió a internet.
2. Tria un nivell al menú o prem **Continuar**.
3. Posa el dit sobre el **punt verd** i segueix la fletxa. Si el nen dubta uns segons, el joc li mostra el recorregut de la lletra.
4. Quan acaba el traç principal, apareixen els punts verds dels traços finals: punts de la i i la j, accents, creu de la t, cua de la ç i punt volat de la l·l.
5. Si se surt del camí, la lletra es posa vermella i es torna a començar **només aquella lletra**.

En completar una paraula es guanyen d'1 a 3 estrelles segons els errors. En acabar cada nivell surt un avís amb el nivell següent.

## Nivells i paraules

30 paraules en 5 nivells, ordenades per nombre de síl·labes. Cada paraula va acompanyada d'una imatge.

| Nivell | Síl·labes | Paraules |
|---|---|---|
| 1 | 1 | sol, gat, tren, flor, braç, drac |
| 2 | 2 | kiwi, zebra, pinya, préssec, pingüí, gofre |
| 3 | 3 | granota, taronja, planeta, guitarra, goril·la, tomàquet |
| 4 | 4 | papallona, hipopòtam, bicicleta, dinosaure, helicòpter, xocolata |
| 5 | 5 | televisió, ambulància, tiranosaure, motocicleta, extraterrestre, biblioteca |

Entre totes les paraules hi surten:

- **Totes les lletres de l'abecedari**, de la *a* a la *z* (la *k* i la *w* a *kiwi*, la *y* a *pinya*).
- **Lletres i dígrafs especials:** ny (*pinya*), l·l (*goril·la*), ll (*papallona*), rr (*guitarra*, *extraterrestre*), ss (*préssec*), ç (*braç*), gü (*pingüí*).
- **Grups consonàntics:** tr, fl, br, dr, pr, fr, gr, pl, cl, bl.
- **Accents i dièresi:** à, é, í, ò, ó, ü.

## Opcions per al docent

- **Selector de nivell:** tots els nivells estan oberts des del principi.
- **Amplada del camí:** *Ample*, *Normal* o *Estret*, per ajustar la dificultat.
- **Navegació:** botons per passar a la paraula anterior o següent, tornar a començar la paraula i saltar a qualsevol paraula del nivell tocant els punts de la barra superior.
- **Progrés:** les estrelles es guarden al mateix dispositiu (al navegador) i es poden esborrar des del menú. No es recull cap dada personal.

## Model de lletra

El joc fa servir un model de lletra lligada escolar, el mateix tipus de lletra que es treballa a l'aula. No necessita cap font instal·lada: cada lletra està guardada dins del joc com un traç central, que el joc dibuixa i fa servir per comprovar el recorregut.

Ordre del traç:

- Les lletres rodones (a, c, d, g, o, q) enllacen pujant per l'esquerra fins a dalt i després fan la rodona.
- La x es fa en dos traços: primer una "ɔ" i després una "c".
- Els punts, els accents, la creu de la t, la cua de la ç i el punt volat es fan al final de la paraula.

## Detalls tècnics

- Un sol fitxer HTML amb CSS i JavaScript integrats, sense dependències externes.
- El dibuix i el seguiment del traç es fan amb Canvas i Pointer Events, de manera que funciona igual amb el dit, el llapis o el ratolí.
- Les imatges són emojis del sistema, i per això es poden veure una mica diferents segons el dispositiu.
