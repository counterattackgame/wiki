[Read this page in English](https://counterattackgame.github.io/wiki/shooting)

[Lire cette page en Français](https://counterattackgame.github.io/wiki/fr/shooting)

[Leggi questa pagina in Italiano](https://counterattackgame.github.io/wiki/it/shooting)

[Lê esta página em Português](https://counterattackgame.github.io/wiki/pt/shooting)

[Ritorna all'Home Page](https://counterattackgame.github.io/wiki/it/index)
# Shooting

Tirare è un duello tra il giocatore che effettua il tiro e il portiere.

Il tiro da fuori area riceve una penalità di -1 al dado.

Lo Snapshot riceve una penalità di -1 al dado.

Se il tiro parte da fuori area, il portiere ha un movimento di 1 esagono prima di effettuare la parata perché la palla entra in area di rigore.

1. Se il risultato combinato di dado + Shooting dell'attaccante è maggiore del risultato combinato di dado + Saving del portiere, allora viene segnato il goal!
2. Se il portiere, invece, ha un risultato maggiore, tira il dado:

- Se il risultato è maggiore o uguale all'attributo di Handling, esegui una [Loose Ball](https://counterattackgame.github.io/wiki/it/loose_ball). Se la direzione è dietro o a lato del portiere è Calcio d'Angolo. Se la direzione è davanti al portiere, lanciare il dado per la distanza e il gioco riprende come dopo una [Loose Ball](https://counterattackgame.github.io/wiki/loose_ball).
- Se il dado è minore dell'attributo di Handling, il portiere blocca il pallone. Il possesso cambia in favore della squadra del portiere.

3. Se il risultato è pari, seguire le istruzioni di [Loose Ball](https://counterattackgame.github.io/wiki/it/loose_ball).

## Snapshot

Uno Snapshot sacrifica la precisione a favore di un elemento di sorpresa. Si può effettuare:

- Durante una Fase di Movimento se il giocatore in possesso di palla è nell'area di rigore.
- Subito dopo aver ricevuto un passaggio, sia che il giocatore che riceve palla si trovi in area di rigore che fuori.

Si applicano tutte le stesse regole di un tiro normale, ma l'attributo di Shooting del giocatore subisce un -1 di penalità.

Appena prima che lo Snapshot venga tirato, l'avversario può muovere qualsiasi giocatore di massimo 2 esagoni nel tentativo di deviare il tiro (vedere [Loose Ball](https://counterattackgame.github.io/wiki/it/loose_ball) in caso di deviazione). Il giocatore mosso può essere anche il [portiere](https://counterattackgame.github.io/wiki/goalkeeper).

Con le Regole Avanzate, se si sceglie di muovere di 2 esagono il portiere durante lo Snapshot, questo avrà una penalità di -1 in Saving sul secondo esagono e di -2 sul terzo esagono.

La sequenza delle azioni per lo Snapshot è la seguente:

1. L'attaccante dichiara lo Snapshot.
2. Il difensore muove un giocatore fino a 2 esagoni.
3. L'attaccante dichiara la direzione del tiro. Si vede quali difensori possono tentare di deviare il pallone. Si risolvono eventuali deviazioni e se il pallone è deviato il gioco continua con [Loose Ball](https://counterattackgame.github.io/wiki/it/loose_ball), altrimenti si procede al punto successivo.
4. Si controlla in quale esagono il portiere tenterà di parare il tiro e si calcola qualsiasi potenziale penalità per la parata.
5. I due allenatori lanciano il dado. Se l'attaccante lancia un 1, il tiro è fuori.

Nel caso di uno Shot (tiro normale), la direzione è dichiarata nello stesso momento del tiro stesso e il processo del tiro parte dal terzo punto dell'elenco sopra riportato.

Tieni a mente:

- Un attaccante si è mosso con il pallone fino al limite dell'area (ma non è ancora entrato). Sfugge ad un tentativo di Tackle, e si riposiziona quindi in area. **NON PUÒ** effettuare uno Snapshot.
- Un attaccante si muove all'interno dell'area di rigore col pallone, effettua uno Snapshot ma la palla viene deviata da un difensore o dal portiere e torna in possesso dell'attaccante. L'attaccante **PUÒ** tentare un nuovo snapshot.
- Un attaccante si muove in area, effettua uno snapshot ma il pallone viene deviato dal portiere o da un difensore sui piedi di UN ALTRO attaccante CHE SI È GIÀ MOSSO. Questi **PUÒ** effettuare uno snapshot.

A seguito di un contrasto aereo, un [portiere](https://counterattackgame.github.io/wiki/it/goalkeeper) può ancora muoversi di 1 esagono quando la palla entra in area ed essere scelto come giocatore da muovere di 2 esagoni dopo la dichiarazione di uno snapshot.

## Angoli di tiro difficili

Da certe posizioni in campo, nel range per un tiro, è più difficile fare goal. Tirare dagli esagono segnati con un puntino è possibile, ma il tiro avrà una penalità di -1 al dado.

## Decidere l'esagono dell'eventuale Parata del Portiere

Ricorda sempre che:

- I tentativi di tiro (Snapshot, Shot e [Headed](https://counterattackgame.github.io/wiki/it/heading) viaggiano in linea RETTA.
- Il portiere può solo parare negli esagoni paralleli alla linea di porta. C’è una linea teorica di 7 esagoni per la parata, compreso quello nel quale è posizionato il portiere: 3 esagoni in ogni lato sempre parallelo alla linea di porta.
- Il pallone viaggia su una linea, ma non è un punto. È tondo con un raggio non negativo, dunque mentre viaggia può passare per più esagoni contemporaneamente.
Il portiere para sempre nell'esagono **più vicino** nel quale passa la traiettoria del pallone.

[Ritorna all'Home Page](https://counterattackgame.github.io/wiki/it/index)
