# P3steel v2.6
### A new Prusa i3 Steel frame version

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

Read this in:
- [English](https://github.com/iosonopersia/p3steel-v2-6/blob/master/README.md#english)
- [Italian](https://github.com/iosonopersia/p3steel-v2-6/blob/master/README.md#italiano)


# English

## Philosophy
_All changes committed to the pre-existent design have been made with the purpose of avoiding non-functional things and of adding elements I felt were missing. Neither optimizing laser cut times nor cutting down material costs was my priority: my only goal was to make a more functional frame, trying to solve old problems which have been affecting the P3Steel project for years. I just want **the best Prusa-style printer possible**._

_I'm very interested in problems which may have disturbed P3Steel users in these years. Someone may have already tried quick fixing them (for example by making printed parts like the Y-idler made by _ [toolson](http://www.thingiverse.com/thing:1054909)_): it would be much better to try implementing those solutions in a more **structural** way, directly in the printer frame._

## Changes with respect to the [2.5 DXL version by AndrewBCN](http://reprap.org/wiki/P3Steel#Frame_versions):

### **_ADDS_**

1. Two spool holder brackets added with their respective fixing holes;

2. Four elements added to block Y-axis rods (with their respective fixing holes);

3. Two elements added to block Z-axis rods (with their respective fixing holes);

4. Two elements added to reinforce the frame base (with their respective fixing holes);
 
### **_DELETIONS_**

5. Both fixing holes for NEMA17 motors in the lateral panels were eliminated (they both were in rather uncomfortable positions, moreover one of them turned out to be useless because of the mounting position of the power supply which covers it almost completely);

6. Some holes in the front and back base panel were eliminated because of them being too close to the fixing holes previously added (see 4) );

### **_MODIFICATIONS_**

7. I've changed the position of some elements in order to lessen the impact of the already listed adds;

8. I've changed the Y-idler element. I've enlarged it a little just to be able to move the bearing fixing hole. The hole was moved down and forward, then its diameter was reduced to 3.2mm (just like [toolson](http://www.thingiverse.com/thing:1031144) did with his printed parts). This way to assemble the mechanical parts of the printer only M3 screws are needed. It's recommended to use a 20 teeth GT2 pulley with a 3mm bore bearing. Otherwise you can also use the 5mm bore version of the bearing, having firstly drilled the hole up to that diameter;


## Technical enhancements made on the design:

1. All the elements in the design were put in the same (and only) "0" layer;

2. A lot of problems caused by non-correctly closed lines were fixed;

3. Sono state eliminate alcune linee inutili in quanto identiche e sovrapposte
 oppure in quanto a due a due allineate e quindi sostituibili da un'unica
 linea più lunga;

4. All closed lines were converted into polylines;

5. Every piece was converted to a block which has a sintetized name;

6. The design was saved and exported in the following formats:
    - DXF;
    - DWG;
    - PDF;
    - PNG.
    
    
# Italiano

## Filosofia
_Le modifiche apportate al disegno pre-esistente sono state fatte nell'ottica di eliminare ciò che non mi sembrava funzionale e di aggiungere elementi di cui sentivo la mancanza. L'obbiettivo non è stato quello di ottimizzare al massimo nè i tempi per il taglio laser (comunque molto contenuti) nè i costi dovuti alla quantità di materiale necessario: mio unico scopo è stato quello di realizzare un telaio più funzionale e meno affetto da problemi che le precedenti versioni hanno mantenuto invariabilmente nel corso degli anni. Il fine è quello di realizzare **la miglior stampante in stile Prusa i3 possibile**._

_Per questo sono molto interessato a possibili problemi riscontrati negli anni dai possessori di questa stampante. Problemi che magari sono stati sistemati temporaneamente (per esempio tramite la realizzazione di pezzi stampati sostitutivi, come per l'Y-idler nel caso delle modifiche realizzate da_ [toolson](http://www.thingiverse.com/thing:1054909)_): sarebbe molto meglio provare ad implementare tali soluzioni in maniera **strutturale** direttamente nel telaio della stampante._

## Modifiche rispetto alla [versione 2.5 DXL di AndrewBCN](http://reprap.org/wiki/P3Steel#Frame_versions):

### **_AGGIUNTE_**

1. Aggiunta di due braccetti portabobine e dei fori per il loro fissaggio nella parte alta del telaio;

2. Aggiunta di quattro elementi per bloccare le barre lisce dell'asse Y e dei fori per fissarli in corrispondenza dei punti di appoggio delle barre lisce;

3. Aggiunta di due elementi per bloccare le barre lisce dell'asse Z e dei fori per fissarli negli elementi "Z-Top";

4. Aggiunta di due elementi di rinforzo per la parte frontale della base del telaio e dei relativi fori di fissaggio;
 
### **_ELIMINAZIONI_**

5. Eliminazione dei fori necessari al fissaggio di due motori NEMA17 ai supporti laterali del telaio (entrambi in posizioni scomode, uno dei due viene reso inutile dalla presenza dell'alimentatore che ne preclude l'accesso);

6. Eliminazione delle coppie più esterne di fori verticali in entrambi gli elementi di supporto delle barre lisce dell'asse Y (a causa della loro posizione troppo vicina a quella dei fori introdotti dall'aggiunta 4) );

### **_MODIFICHE_**

7. Modifica della posizione di alcuni elementi allo scopo di minimizzare l'aumento di superficie coperta dettato dalle aggiunte sopraelencate;

8. Modifica dell'elemento "Y-idler", deputato al fissaggio di un cuscinetto radiale di sostegno per la cinghia dell'asse Y. Tale elemento è stato leggermente ingrandito per permettere lo spostamento del foro per il fissaggio del cuscinetto. Quest'ultimo è stato abbassato, spostato leggermente in avanti e ridotto ad un diametro di 3.2mm (in linea con le modifiche proposte da [toolson](http://www.thingiverse.com/thing:1031144)). In questo modo per assemblare la meccanica della stampante è sufficiente la sola tipologia di viti M3. È consigliato l'uso di una puleggia GT2 a 20 denti dotata di cuscinetto con diametro interno di 3mm. In alternativa sarà possibile montare la versione da 5mm di diametro interno, previo allargamento del foro tramite l'uso di un trapano;


## Miglioramenti tecnici al disegno:

1. Tutti gli elementi presenti nel disegno sono stati riportati sullo stesso ed unico layer "0";

2. Sono stati risolti numerosi problemi legati a linee che non erano correttamente chiuse;

3. Sono state eliminate alcune linee inutili in quanto identiche e sovrapposte oppure in quanto a due a due allineate e quindi sostituibili da un'unica linea più lunga;

4. Tutte le linee chiuse sono state convertite in polilinee;

5. Ogni pezzo è stato racchiuso in un blocco che ne porta un nome sintetico in lingua inglese;

6. Il disegno è stato salvato e convertito nei seguenti formati:
    - DXF;
    - DWG;
    - PDF;
    - PNG.
