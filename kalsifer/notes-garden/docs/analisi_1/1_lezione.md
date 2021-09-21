# Teoria ingenua degli insiemi

### Si presenta come

- Lista/Elenco es: A={2,5,22,17,pippo,pluto,topolino,★}
    - osservazione 1:
        l'ordine non é rilevante
    - osservazione 2: gli elementi ripetuti contano come solo 1
- Proprietá es: A={tutti gli studenti presenti in aula}

### Notazioni

A,B,C insiemi

a,b,c elementi

$a \in A$ appartiene

$a \notin A$ non appartiene

$A \subseteq B - B \subseteq A$ contenuto o uguale

> Insieme A é contenuto in B. Ogni elemento di A é anche elemento di B.

$\emptyset$ insieme vuoto

> Insieme che non contiene nessune elemento. É sempre contenuto in qualsiasi insieme.

### Operazioni insiemistiche

$A \cup B$ unione

> x tale che $x \in A$ oppure $x \in B$

- oppure (non esclusivo, anche entrambi)
- vel (latino)
- or
- $\vee$

$A \cap B$ intersezione

> x tale che $x \in A$ e $x \in B$

- e
- and
- $\wedge$

$A \setminus B$ differenza

> x tale che $x \in A$ e $x \notin B$

$A \times B$ prodotto cartesiano

> Dati due insiemi A e B, si definisce il loro prodotto cartesiano come l'insieme composto delle coppie **ordinate**.

A={1,d} B={2,g,★} AxB={(1,2),(1,g),(1,★),(d,2),(d,g),(d,★)}
AxA={(1,1),**(1,d)**,**(d,1)**,(d,d)} _conta l'ordine malandrino_

#### Cardinalitá
Se A ha a elementi e B ha b elementi il prodotto cartesiano ha axb elementi

$|A|$ Cardinalitá di A

$| A \times B | = |A||B|$

### Insieme delle parti
Dato un insieme A si indica con $P(A)$ l'insieme composto da tutti i sottoinsiemi di A.
$P(A)={insieme di B: B \subseteq A }$

> : significa tale che

B={2,g,★} P(B)={$\emptyset$,{2}.{g},{★},{2,g},{2,★},{g,★},{2,g,★}}

> cardinalitá particolare: $P(A)=2^{|A|}$