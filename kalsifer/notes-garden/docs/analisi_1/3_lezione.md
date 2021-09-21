# Insiemi numerici

$\N = \{0,1,2,3,...\}$ Naturali

$\Z = \{0,\plusmn1,\plusmn2,\plusmn3,...\}$ Interi

$\mathbb{Q} = \{\frac{m}{n},m\in\Z\diagdown\{0\} \}$ Razionali
> tips: $\diagdown$ significa meno

$\R$ Reali

$\mathbb{C}$ Complessi
> tips: sono contenuti uno nell'altro $\N \in \Z \in \mathbb{Q}$ ...

Propietá dei numeri reali:
> tips: definizioni rigorose sul quaderno
- Algebriche
  - somma, prodotto
    - commutativa
    - associativa
    - elemento neutro
      - 0 per la somma a+0=a
      - 1 per la moltiplicazione ax1=a
    - esistenza opposto(inverso)
      - \- per la somma $A+B=0 \quad A+(-A)=0$
      - reciproco per la moltiplicazione $A \times B = 1 \quad B=\frac{1}{A}$
    - distributiva
- Ordinamento
  - Dati due numeri reali x e y so sempre se $x\geq y \lor y \leq x$
    - riflessiva $x \geq x \forall x \in \R$
    - antisimmetrica $x \geq y \wedge y \geq x \rightarrow x=y$
    - transitiva $x \geq y \wedge y \geq z \rightarrow x \geq z$
  - > le proprietá di ordinamento non valgono con i complessi
- Assioma di continuità
  - Siano $A\subseteq\R \quad B\subseteq\R$ due sottoinsiemi non vuoti. Supponiamo che A stia tutto a sx rispetto a B. L'assioma di continuità dice che esiste almeno 1 elemento $c \in \R$ che sia immezzo ad A e B. 
  - > tips:
  - > l'elemento c separatore di A e B
  - > l'elemento separatore non é richiesto essere unico 
  - > l'elemento c puó appartenere ad A oppure B. Se appartiene ad entrambi é unico
  - > L'assioma é valido per i numeri reali ma non per i razionali. Esempio: $\begin{cases}A=\{x\in Q:x\geq0,x^2 < 2\} \\ B=\{x\in R:x\geq0,x^2 > 2\}\end{cases}$ Non esiste $r \in Q:r^2=2$

## Maggiorante e minorante

Sia $A \in \R$ sottoinsieme non vuoto
- Maggiorante: $M \in \R$ é maggiorante se $a \leq M \quad \forall a \in A$
- Minorante: $m \in R$ é minorante se $a \geq M \quad \forall a \in A$
> tips: non tutti gli insiemi ammettono maggioranti e/o minoranti

## Massimo e minimo
Rappresentano gli estremi dell'insieme a cui appartengono. Fanno parte dell'insieme a differenza di maggiorante e minorante.

## Teoremi
> dimostrazioni sul quaderno

Se l'insieme $A$ é limitato superiormente allora il minimo dei maggioranti esiste sempre.

## Caratterizzazione Inf e Sup

- supA = + $\infty$ se non esiste un maggiorante
- minA = - $\infty$ se non esiste un minorante
- supA = $l$ se
  - a $\leq l$
  - $\forall \epsilon > 0 \; \exist \; a \in A \quad a \geq l - \epsilon$
- minA = $l$ se
  - a $\geq l$
  - $\forall \epsilon > 0 \; \exist \; a \in A \quad a \leq l + \epsilon$

## Teorema di Cantor

## Principio di Archimede
Se $a$ e $b$ sono due numeri positivi reali esiste un numero naturale $a \in \R \; b\in \R$ con $a < b$ esiste $x \in A : a<x<b$

Esempio:
$Q$ é denso in $R$

Implicazione:
$\begin{cases}A=\{q\in Q:q \geq 0 \; q^2 < 2\} \rightarrow \sqrt{2} \in \R \\ A_x=\{q \in Q : q \geq 0 \; q^2 < x\} \rightarrow \sqrt{x} \in \R\end{cases}$

La continuitá ci ha permesso di scoprire una nuova funzione, la radice.

$\begin{cases}B=\{q \in Q : q \geq 0 \; q^n < n\} \rightarrow supB = \sqrt{n}\end{cases}$