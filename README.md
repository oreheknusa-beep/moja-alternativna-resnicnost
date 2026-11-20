# Moja alternativna resničnost 🌌

Samostojen, mobilno prilagojen prototip spletne igre v slovenščini.

## Kaj vsebuje
- Dnevni izziv: isti scenarij za vse igralce na isti lokalni datum (v tem prototipu se zgodbe ponavljajo po 10 možnih scenarijih).
- Osebna pustolovščina: naključen scenarij iz zbirke 10 zgodb.
- Vsaka zgodba ima tri odločitve in tri različne zaključke.
- Deljenje rezultata s prijatelji (sistemski meni ali kopiranje besedila).
- Prilagodljiv prikaz za telefone.

**Pomembno:** To je začetni prototip brez registracije, skupne baze, AI generiranja, večstopenjskega razvejanja ali dejanskih dvobojev. Statistike drugih igralcev niso prikazane, ker še ni strežnika. »Neskončne« pustolovščine pomenijo ponovno igranje in naključno izbiranje iz desetih zgodb, ne neomejeno novih zgodb.

## Preizkus lokalno
Odpri `index.html` v brskalniku. Za deljenje prek odložišča je lahko potreben HTTPS.

## Objava na GitHub + Render
1. Ustvari **nov** GitHub repozitorij `moja-alternativna-resnicnost` (ne uporabljaj repozitorija Moj AI Partner).
2. Vanj naloži `index.html`, `style.css`, `script.js` in `README.md`.
3. V Renderju izberi **New → Static Site** in poveži novi repozitorij.
4. Build command pusti prazno (če zahteva vrednost, uporabi `echo ready`); Publish directory nastavi na `.`.
5. Objavi stran in preizkusi gumbe na telefonu.

Ni API ključev, zunanjih paketov ali obveznih plačljivih storitev.

## Naslednje faze
1. Skupni dnevni izziv in globalna statistika prek baze.
2. Večstopenjske zgodbe, sistem dosežkov in povabila.
3. AI ustvarjanje novih zgodb z varnim strežniškim API in omejitvami stroškov.
