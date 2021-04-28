Angelica Della Vecchia 1746294 
Simone Orelli 1749732

XHTML/CSS Rappresentativo

Indirizzo del repository su GitHub: https://github.com/Cesio-organizzazione-di/HTML-CSS-Rappresentativo

L'esercizio svolto è sulla slides-Lezione-2 ed è il CSS-14.

La pagina web realizzata consta di un solo documento HTML e un file esterno CSS.
Nella suddetta pagina web si trattano i seguenti argomenti: 
- Linguaggi di Markup con relativi esempi (HTML, SGML, XHML);
- XHTML e i suoi elementi (block-level e inline) e attributi (con relativi esempi);
- La gestione del background mediante CSS;
- Caratteristiche dei documenti HTML (Validi e Well-Formed);
- Document Type Definition

La pagina è strutturata nel seguente modo: 

- In alto troviamo un menu fisso composto da 4 voci, ognuna delle quali possiede un sottomenù che compare soltando quando si passa su ciascuna voce col cursore.
  Il menù principale è stato fissato con la proprietà position: fixed. Le voci del menù sono dei link, elementi di una lista, che rimandano al paragrafo corrispondente presente     all'interno del corpo del documento.
  I sottomenù sono stati realizzati sfruttando liste annidate, le quali rimangono nascoste fino al passaggio del cursore sul link (è stata usata la pseudoclasse :hover). Anche
  le voci dei sottomenù sono dei link che rimandano a dei sottoparagrafi all'interno della pagina.
  Come elemento decorativo è stata inserita una transizione ai link che al passaggio del cursore crea l'effetto di sottolineatura (usando la proprietà transition e le pseudoclassi 
  :after, :hover:after);
 
- E' stato scelto un layout a 3 colonne (Holy Grail) il quale è stato realizzato mediante l'uso delle seguenti classi CSS:
   - class corpo (indica la colonna centrale);
   - I titoli dei paragrafi e sottoparagrafi sono collocati nella colonna di destra;
   - Il logo si trova nella colonna di sinistra;
   Affichè i titoli si trovassero allineati a destra dei rispettivi paragrafi (e quindi affinchè si creasse la colonna di destra) è stato necessario scrivere una classe class
   riga. Quindi all'interno del corpo troviamo elementi <div> di classe riga i quali conterranno un paragrafo e il suo sottotitolo associato.
   Attraverso la proprietà display: inline-flex il titolo sarà allineato a destra del paragrafo.

- Infine, abbiamo lavorato sulla robustezza della pagina web, cercando di mantenere un ordine visivo degli elementi della pagina quando viene aumentata la dimensione di 
  quest'ultima tramite lo zoom. 
  A tal proposito abbiamo creato due classi .piccolo e .grande che rappresentano la vista del menù rispettivamente quando la dimensione della pagine è zoomata o meno rispetto al
  100%. La scelta avviene grazie alle regole:
   - @media screen and (min-width: 1400px) per la vista del menù grande;
   - @media screen and (max-width: 1399px) per la vista del menù piccolo;

- Nella colonna di sinistra è stato inserito il logo e il Markup del validatore W3C.

  
   





