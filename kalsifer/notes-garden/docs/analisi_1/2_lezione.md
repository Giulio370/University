# Le funzioni

Sono compose da:
1. Insieme di partenza A
2. Insieme di partenza B
3. Una serie di regole/leggi.

Una funzione associa ad ogni elemento di $a \in A$ **un unico** elemento di $b \in B$.

$F(): A \rightarrow B$

$b = f(a)$.

## Grafico di una funzione

Definizione: $f() : \{(a,b) \in A \times B : b=f(a)\} \subseteq A \times B$
> tip: il prodotto cartesiano é l'insieme di tutte le coppie dei punti x e y

## Tipi di funzione
- Iniettiva
   - Diciamo che $f()$ é iniettiva se manda elementi distinti di $a$ in elementi distinti di $b$
    - $a_1 \in A$ e $a_2 \in A$ con $a_1 \not ={a_2} \Rrightarrow f(a_1) \not ={f(a_2)}$
    - $f(a_1)=f(a_2) \Rrightarrow a_1 = a_2$
- Surgettiva | *Suriettiva*
  - Diremo che $f()$ é surgettiva se ogni elemento di $B$ é immagine di almento un elemento di $A$
  - $\forall \; b \in B \; \exist \; a \in A : b = f(a)$
- Bigettiva
  - Si dice che $f()$ é bigettiva se é contemporaneamente iniettiva e surgettiva
  - Una funzione $f():A \rightarrow B$ é bigettiva $\iff$ é invertibile, ossia $\iff$ esiste una funzione $g():B \rightarrow A$ tale che 
    - $g(f(a)) = a \; \forall \; a \in A$
    - $f(g(b)) = b \; \forall \; b \in B$
  - > tip: non esiste sempre una funzione inversa
### Recap
- Iniettiva $\iff$ in ogni punto di B arrivano 0 o 1 frecce
- Surgettiva $\iff$ arrivano 1 o + frecce
- Bigettiva $\iff$ arriva 1 e 1 sola freccia

## Immagine e controimmagine
Si dice immagine di A l'insieme dei punti di B raggiunti da frecce che partono da elementi di A

---

Sia $C \in A$.

$f(C) = \{f(a) : a \in C\} \subseteq B$
> tip: definizione per elenco(hyperlink) e non raggruppamento

Sia $D \subseteq B$.

$f(D)^{-1} = \{a \in A : f(a) \in D \}$

Si dice controimmagine di D l'insieme dei punti A da cui partono frecce che arrivano in D

> tips:
> - $f()$ é surgettva $\iff f(a)=B$. Ovvero l'immagina di A é B
> - Per definire la controimmagine non serve l'inveritibilitá di $f()$

## Principio di induzione
### Notazioni:
- $\N$ : insieme dei numeri naturali $\{0,1,2,3,4,5\}$
- $P_n$ : affermazione | (*predicato*) che contiene al suo interno un marametro $n \in N$ che a seconda dei valori di $n$ rende l'affermazione vera o falsa

### Metodologia:
[risorsa online](https://www.youmath.it/lezioni/analisi-matematica/successioni/701-dimostrazioni-con-il-principio-di-induzione.html)

Una dimostrazione per induzione segue due passi fondamentali:
- (i) Passo base - verifica della condizione $P_0$, ovvero di quando $n = 0$
- (ii) Passo induttivo - se $\forall \; n \in \N$ Pn é vera $\rightarrow$ é vera anche $P_{n+1} \rightarrow$ Pn é vera per ogni $n \in \N$

### Esempio
$S(n) = 1+2+3+...+n = \frac {n(n+1)} {2} \; \forall \; n \geq 1$
- (i)
  - Sostituisco n
  - $P(1) = \frac{1(1+1)}{2} = \frac{2}{2} = 1$ 
- (ii)
  - Sostituisco n + 1
  - $P(n+1) = \frac{(n+1)[(n+1)+1]}{2} = \frac{n^2+3n+2}{2}$
  - $S(n) = 1+2+3+...+n+(n+1) = \frac{n^2+3n+2}{2}$
  - $S(n) = \frac {n(n+1)} {2}+(n+1) = \frac{n^2+3n+2}{2}$
  - $\frac {n(n+1)+2(n+1)} = \frac{n^2+3n+2}{2}$