# Domand per Verifica OS e Concorrenza

## 1) descrivere la differenza tra le strutture dati: Coda (Queue) e Lista (Stack), indicando i metodi principali coinvolti

### Stack (Pila)
Struttura LIFO (Last In, First Out)
    L’ultimo elemento inserito è il primo ad essere rimosso

Operazioni principali:
`push()` → inserisce un elemento
`pop()` → rimuove l’ultimo elemento
`top()` / `peek()` → legge l’elemento in cima
Esempio: stack delle chiamate di funzione

### Queue (Coda)
Struttura FIFO (First In, First Out)
Il primo elemento inserito è il primo ad essere rimosso
Operazioni principali:

`enqueue()` → inserimento in coda

`dequeue()` → rimozione dalla testa

`front()` → primo elemento

Esempio: coda dei processi pronti
