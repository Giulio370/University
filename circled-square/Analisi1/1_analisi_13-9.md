### Disclaimer:
Questi appunti sono funky, non li consiglio particolarmente perché ho dovuto sostituire tutti i simboli matematici con roba scrivibile da tastiera e non ho cazzi di sistemarli visto che per analisi uso il quaderno

# Analisi 1 - Lez. #1 13/9
## Insiemi
La definizione formale di insieme non sarà data. Si studierà la teoria degli insiemi 'ingenua'(v. paradosso di bertrand russel[?]).

### Come si presenta un insieme?
-	per lista di elementi contenuti: A = { 2, 5, 22, 17, pippo, pluto, topolino, stellina, triangolino, un bel paio di scarponi da scii }
	-	l'ordine è irrilevante
	-	gli elementi ripetuti contano come lo stesso elemento { pippo, pippo, pippo } = { pippo }
-	per proprietà: A = { tutti gli studenti in questa aula }

### Notazioni
-	a (simbolo euro/appartenenza) A -> (APP) _a_ appartiene ad _A_;
si può scrivere al contrario [A (e storta) a] e sbarrare per negare 
-	A (c sottolineata) B -> (CONT) A è contenuto in B (è possibile che A e B coincidano); si può scrivere al contrario o sbarrare
-	(o barrata) -> (/0/) insieme vuoto = che non contiene elementi; è contenuto in qualsiasi insieme
-	|A| -> la cardinalità, cioè il numero di elementi che compongono l'insieme
-	: -> tale che

### Operazioni insiemistiche
U = unione
(u sottosopra) = intersezione (INT)
\ = differenza
x tali che x app. a A oppure x app. a B -> A U B (__NON__ esclusivo, OR, o VEL)
x tali che x app. a A e x app. a B -> A INT B (AND)
x tali che x app. a A e x non app. a B -> A\B

#### Esempi
A = { 2, 7, S, pippo, 29 }  
B = { numeri nat. dispari }  
2 APP A U B -> vero  
2 APP A INT B -> falso  
2 APP A \ B -> v
29 APP A INT B -> v
2 APP A -> v
{ 2 } APP A -> f
{ 2 } CONT A -> v
/0/ CONT A -> v
/0/ APP A -> f

### Prodotto cartesiano di insiemi
dati due insiemi A e B, si definisce il loro prodotto cartesiano AxB come l'insieme composto dalle coppie ordinate (a, b) dove a APP A e b APP B

#### Esempio
A = { 1, d }  
B = { 2, t, g }  
AxB = { (1, 2), (1, t), (1, g), (d, 2), (d, t), (d, g) }  
AxA = { (1, 1), (1, d), (d, 1), (d, d) } 
(1, d) e (d, 1) sono __diversi__
__NB:__ |AxB| = |A| x |B|

### Insieme delle parti
Dato un insieme A si indica con _P_(A) l'insieme composto da tutti i sottoinsiemi di A
_P_(A) = { insiemi B : B CONT A }  
|_P_(A)| = 2^|A|

#### Esempio
-	A = { 1, d }  
	_P_(A) = { /0/, {1}, {d}, A }
-	A = { 2, t, g }  
	_P_(A) = { /0/, {2}, {t}, {g}, {2,t}, {2,g}, {t,g}, A }

#### Esercizio mooolto difficile

|_P_(_P_(_P_(_P_(/0/))))|

2 ^ 2 ^ 2 ^ 2 ^ 0 = 16







