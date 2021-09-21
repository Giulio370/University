# Vettori geometrici

## Piano

Il piano é composto dall'insieme delle coppie (punti) risultati dal prodotto $\R^2 = \R \times \R$

$P=(x,y) \in \R^2$

## Spazio

Lo spazio é composto dall'insieme delle triplette (punti) risultati dal prodotto $\R^3 = \R \times \R \times \R$

$P=(x,y,z) \in \R^3$

## Vettori

Del piano: $\vec{AB} = (x_b-x_a,y_b-y_a)$ dove $A=(x_a,y_a)$ e $B=(x_b,y_b)$

Dello spazio: $\vec{AB} = (x_b-x_a,y_b-y_a,z_a-z_b)$ dove $A=(x_a,y_a,z_a)$ e $B=(x_b,y_b,z_b)$

## Operazioni in $\R^2$ e $\R^3$
### Notazioni:
- Scalare : numero reale

Somma
- $(a_1,a_2),(b_1,b_2) \;\;\; (a_1,a_2)+(b_1,b_2) = (a_1+b_1,a_2+b_2)$

Moltiplicazione
- $k(a_1,b_1) \;\;\; k(a_1,b_1) = (ka_1,kb_1)$

## Operazioni con vettori geometrici

### Somma
- $\vec{AB}+\vec{CD}=(x_b-x_a+x_d-x_c,y_b-y_a+y_d-y_c)$
> - tips:
>  - $\vec{AB}=\vec{CD}\iff A=B \wedge C=D \vee AB,CD$ sono lati opposti di un parallelogramma, cioé $|AB|=|CD|$ e sono paralleli con lo stesso verso
>  - I vettori sono "liberi", dato $AB$ e un punto $C$ esiste $D$ tale che $\vec{AB} = \vec{CD}$. In soldoni posso metterlo dove voglio.

### Regola del Triangolo/Parallelogramma (Valida anche per lo spazio):

Essendo i vettori liberi e quindi potendoli spostare
Se li applico sullo "stesso" punto la somma equivalente alla diagonale
$\vec{AB}+\vec{BC}=(x_c-x_a,y_c-y_a)=\vec{AC}$

### Proprietá
- commutativa
- associativa
- elemento neutro
  - Cioé un vettore $\vec{0}$ tale che $\vec{AB} + \vec{0} = \vec{AB}$
- vettore opposto
  - Dato $\vec{AB}$, esiste il vettore opposto tale che $\vec{AB}+(-\vec{AB})=\vec{0}$

> tips: ($V^2,+$) é un gruppo commutativo(concetto di gruppo in matematica)

### Moltiplicazione per scalare

$t \in \R$ e $\vec{AB} \in V^2$

$t\vec{AB} = (t(x_b-x_a),t(y_b-y_a))$

> tips: $A,B,B^I$ sono allineati $\iff \vec{AB^I} = t\vec{AB}$ per un $t \in \R$

## Rette nel piano
> completamente analogo nello spazio, si aggiunge solamente una variabile.

Retta $r$ passante per i punti $P_1=(x_1,y_1)$ e $P_2=(x_2,y_2)$ distinti. Prendiamo un punto $P$ immaginario.

$P \in r \iff \vec{P_1P}=t\vec{P_1P_2} t \in \R$
> tips: 
>   - $\vec{P_1P_2}$ é il vettore direzione perché indica la direzione della retta.
>   - L'uguaglianza esprime una retta
>   - $\vec{P_1P}$ é un multiplo di $\vec{P_1P_2}$

Possiamo quindi ricondurre l'uguaglianza al sistema di equazioni parametriche(dipendono dal parametro t):

$\begin{cases} x-x_1=t(x_2-x_1) \\ y-y_1=t(y_2-y_1) \end{cases}$
$\begin{cases} x=x_1+t(x_2-x_1) \\ y=y_1+t(y_2-y_1) \end{cases}$
> tips: 
> - rimuovendo $t$ ottengo un equazione cartesiana di $r$
> - per l'esattezza ottengo due piani incidenti espressi nel seguente modo: $\begin{cases} a_1x+b_1y + c_1z = d_1 \\ a_2x+b_2y + c_2z = d_2 \end{cases}$
