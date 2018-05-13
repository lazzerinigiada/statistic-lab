# Vettorizzazione
Un vettore è una sequenza ordinata di oggetti dello stesso tipo (es. number, character, logical) e si costruisce attraverso l'utilizzo della funzione c() cioè concatenate.
## vettore_number <- c(1,2,3) 
Gli oggetti all'interno del vettore devono essere separati da virgole
## vettore_character <- c("a","b","c")
Gli oggetti character devono essere inseriti tra virgolette perchè vengano riconosciuti come testo
## vettore_logical <- c(TRUE,FALSE,NA)
Gli oggetti logical devono essere scritti in maiuscolo.

## Funzioni applicate ai vettori
Un semplice esempio dell'utilità dei vettori si ha con la funzione sum() che è in grado di sommare tutti gli elementi all'inteno del vettore.

Le funzioni applicate ad un vettore agiscono su tutti gli elementi che lo compongono. Di seguito viene riportato un esempio.

Nome <- ("Giada", "Gaia", "Gabriele")

Cognome <- "Lazzerini"

Pasta (Nome, Cognome)

[1] "Giada Lazzerini" "Gaia Lazzerini" "Gabriele Lazzerini"



Si possono inoltre combinare più vettori. 

Per trasformare un codice in vettore si può usare la funzione vectorize().
