# Ruolo degli algoritmi nell'elaborazione dei dati
## Algoritmi
L'**algoritmo** e' una seguenza di passi computazionali che trasformo l'*input* in *output*.
Lo possiamo considerare come uno strumento per risolvere un *problema computazionale*, che specifica in termini generali la relazione input/output desiderata.

Il **problema dell'ordinamento** e' un esempio di problema computazionale e puo' essere definito formalmente nel seguente modo:
-   **input**:  una sequenza di *n* numeri [a<sub>1</sub>, ... , a<sub>n</sub>].
-   **output**: riarrangiamento [a'<sub>1</sub>, ... , a'<sub>n</sub>] della sequenza di input tale che a'<sub>1</sub> $\le$ ... $\le$ a'<sub>n</sub>.

La sequenza iniziale di numeri la possiamo definire **istanza del problema** e deve soddisfare tutti i vincoli imposti dalla definizione del problema.

Un algoritmo si dice **corretto** se per ogni istanza di input termina con l'output corretto, diciamo quindi che un algoritmo **risolve** il problema computazionale dato.
Gli algoritmi errati possono essere comunque utili qualora sia possibile mantenere sotto controllo la percentuale di risultati errati.

## Strutture dati
Una **struttura dati** e' un modo per memorizzare e organizzare i dati e semplificarne accesso e modifica.

## Tecnica
Non e' possibile avere algoritmi per risolvere tutti i problemi, e' possibile pero' apprendere tecniche per progettare e analizzare gli algoritmi, in modo da sviluppare e dimostrarne la correttezza e valutarne l'efficacia.

## Problemi difficili
Ci sono problemi che sono piu' difficili di altri di cui non si conosce una soluzione efficiente questo sottoinsieme di problemi e'' noto come NP-completi.
Anche se non esiste un algoritmo efficiente per i problemi NP-completi, nessuno ha dimostrato che non ne esista uno. Un aspetto interessante e' che se si trovasse una soluzione per uno dei problemi NP-completi si potrebbero risolvere efficacemente tutti i problemi NP-completi.
Molti problemi NP-completi sono simili a problemi di cui conosciamo algoritmi efficienti.
[vedi problema del commesso viaggiatore]

## Parallelismo
E' possibile distribuire tra diverse unita' di calcolo il problema in maniera efficiente accorciando i tempi di risoluzione?

## Efficienza
Ci sono infinite soluzioni per risolvere un prolema computazionale la discriminante principale che va tenuta in considerazione e' l'**efficienza** in termini di tempo e di spazio che ci permette di mettere a funzione la durata per una risoluzione in base alla dimensione dell'input.