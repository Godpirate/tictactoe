# TicTacToe

Scrivi un’applicazione, composta da una schermata singola, basata sul celebre gioco TicTacToe (“Tris” per i non anglofoni).

L’app dovrà contenere i seguenti metodi e le seguenti caratteristiche:

 ⁃ Un metodo “reset()” che verrà richiamato all’l’inizializzazione o al restart della partita
 ⁃ Una gridview 3x3 che rappresenterà il gioco di per se, con annesso metodo per la gestione del draw della griglia
 ⁃ Un metodo che si occuperà di gestire i turni dei giocatori, che verrà richiamato ogni volta che un giocatore eseguirà la propria azione
 ⁃ Una label che rappresenterà il punteggio 
 ⁃ Un metodo che valuta il risultato al termine della partita o quando verrà fatto tris, e stampa a schermo il vincitore (bonus se fai apparire un alert). Questo metodo dovrà valutare lo stato della partita alla fine di ogni turno, prima del metodo che gestisce i turni, ma dopo il metodo che effettua il draw nella griglia (questo é un consiglio, sei libera di fare come meglio credi per portare a termine il test)

Per iniziare:

Effettuare il fork di questa repository sul proprio account github, fare il clone su VSCode, e quando lo sviluppo sarà terminato, preferibilmente invia la Pull Request sempre tramite GitHub per la valutazione. 

Pro tip:

Ci sono vari modi per portare a termine questo test, come l’utilizzo di stringhe per le X e le O da posizionare dentro container, oppure image assets, gestendo l’input dell’utente tramite un gesture detector in entrambi i casi.

Il test di considererà passato in base a due criteri, ovvero l’esecuzione corretta di una partita “al meglio delle 3” senza intoppi e crash, e alla conseguente valutazione del codice stesso.

Buon lavoro!
