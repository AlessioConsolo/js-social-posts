# js-social-posts

Descrizione\*\*
Ricreiamo un feed social aggiungendo al layout di base fornito, il nostro script JS in cui:

_Milestone 1_ - Prendendo come riferimento il layout di esempio presente nell'html, stampiamo i post del nostro feed attraverso javascript.

_Milestone 2_ - Se clicchiamo sul tasto "Mi Piace" cambiamo il colore al testo del bottone e incrementiamo il counter dei likes relativo.

Salviamo in un secondo array gli id dei post ai quali abbiamo messo il like.
Numero push minimo: 10/12
P.S. Occhio al nome della repo! Ricordatevi che deve essere js-social-posts!

\*\*\*BONUS\*

1. Formattare le date in formato italiano (gg/mm/aaaa)
2. Gestire l'assenza dell'immagine profilo con un elemento di fallback che contiene le iniziali dell'utente (es. Luca Formicola > LF).
3. Al click su un pulsante "Mi Piace" di un post, se abbiamo già cliccato dobbiamo decrementare il contatore e cambiare il colore del bottone.

---

1. Commento/elimino parte del codice HTML che dovrò mostrare tramite JS
2. Creo una variable che vada a recuperare il container che contenga tutti i post dall'html tramite queryselector
3. Creo un forEach in cui destrutturalizzo le chiavi dell'array di oggetti per poi in seguito iniettare nel container l'HTML necessario per la creazione di ogni post con le relative chiavi
4. Creo un eventlistener in grado di aggiungere la classe like-button--liked che al click del bottone transformarmi il testo in verde, e aumentare il numero di like
