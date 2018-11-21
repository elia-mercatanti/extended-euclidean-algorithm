# Extended Euclidean Algorithm

Sviluppo dell'algoritmo esteso di euclide. Permette all'utente di calcolare l'MCD tra due numeri interi e restituisce i
coefficenti dell'identità di Bezout.

Esercizio di programmazione 3.1 per il Corso Data Security and Privacy - Set 2

# Come Utilizzarlo

Il codice sviluppato per questo programma non richiede particolari librerie.
Per testare il codice è sufficente avviare tramite un interprete python il file extended_euclid.py

# Come Funziona

Una volta avviato, il programma richiede all'utente di inserire due numeri interi (anche negativi) per poi utilizzarli
nell'algoritmo esteso di euclide. L'input inserito dall'utente deve essere un intero altrimenti il programma restituisce
un errore che avvisa l'utente di correggere i numeri inseriti.
Una volta che l'utente inserisce due numeri interi (a e b) il programma procedere ad eseguire l'algoritmo esteso di
euclide su quest'ultimi chiamando la funzione ext_euclid(a, b).
Il programma una volta completata l'esecuzione della funzione stampa a video l'MCD tra i due numeri interi (MCD(a, b))
e i coefficenti dell'identità di Bezout (x, y) e successivamente termina la sua esecuzione.

# Casi Speciali

Se vengono inseriti due numeri interi uguali a 0 l'MCD tra i due numeri sarà considerato pari a 0, se invece uno solo
dei due numeri risulta pari a 0 allora l'MCD sarà uguale al numero diverso da 0.

# Author
Elia Mercatanti