# Esercizio: FizzBuzz

## *Consegna*
Scrivi un programma che stampi i numeri da 1 a 100, ma per i multipli di 3, stampi **“Fizz”** al posto del numero, per i multipli di 5 stampi **"Buzz"**, mentre per i numeri che sono sia multipli di 3 che di 5, stampi **"FizzBuzz"**.

Prima di partire a scrivere codice poniamoci qualche domanda:
- Come faccio a sapere se un numero è divisibile per un altro?
- Abbiamo visto qualcosa di particolare che possiamo usare?
---

### *Consigli del giorno*
1. scriviamo sempre prima dei commenti in italiano per capire cosa vogliamo fare
2. proviamo ad immaginare le operazioni che vogliamo far svolgere al nostro programma così come lo faremmo "a mano"
---
###  Nota bene:

prima di tutto, nel file README, indicare tutti i passaggi utili allo svolgimento del programma. Soltanto dopo scrivee la soluzione in JS.

---

## Svolgimento (pseudo-codice):

- imposto un ciclo **for** (a cui assegno una variabile) che conti i numeri da 1 a 100
- all'interno del ciclo for apro un ciclo **if**:
    - **se** la variabile è multiplo di 3
        - stampa *"fizz"*;
    - **altrimenti se** la variabile è multiplo di 5
        - stampa *"buzz"*;
    - **altrimenti se** la variabile è multiplo di 3 e multiplo di 5 (**"&&"**) 
        - stampa *"fizzbuzz"*;
    - **altrimenti**
        - stampa *"valore numerico della variabile"*.