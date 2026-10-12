# Osservazioni — Esercitazione 0

Gruppo: 100


Componenti (nome, cognome e username GitHub di entrambi): Emanuele Manetti Em4nu3l3; Alessandro Olivieri 0l1vier1.

URL del repository condiviso: https://github.com/emanuelemanetti06-pixel/esercitazione-0-template 

Chi ha usato la tastiera nello step 1 e nello step 2: Emanuele Manetti, Alessandro Olivieri

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato: ./hello, viene mostrato a schermo ciò che viene richiesto al codice di stampare.

Che cosa ho capito su sorgente ed eseguibile: Il codce eseguibile dipende dalla compilazione di quello sorgente; modifiche effettuate al codice sorgente non influiscono su quello eseguibile se non viene prima compilato.

Output richiesto e comportamento del programma prima della modifica: L'output richiesto era la stampa a schermo di "Hello, computational physics!", e prima delle modifiche questa avveniva come previsto

Esito dopo la modifica e spiegazione della correzione: La modifica, con l'aggiunta di "> output.txt" al comando di esecuzione, ha portato alla stampa del messaggio sul file output.txt anziché a schermo

## Step 1 — Git

Quali file ho incluso nel commit e perché: Nel commit abbiamo incluso hello.c ed osservazioni.md poiché sono i due file ad aver subito modifiche rispetto alla versione nella repository.

Come ho verificato che la versione provata sia presente su GitHub: Abbiamo aperto i file direttamente da github verificando che la versione presente nella repository corrispondesse a quella di cui era stato fatto il git push.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: Utilizzando il comando git pull le modifiche fatte direttamente dalla repository sono state salvate sul file inizialmente clonato sul terminale. Dunque dopo aver fatto la prima clonazione non è necessario ripeterne altre, poiché le eventuali modifiche apportate ai file in repository possono essere recuperate con il comando git pull. 

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: ciao 12 3.5, echo $? ha dato 0,  ciao 12 3.5

Che cosa posso concludere: Il programma funziona correttamente quando gli argomenti sono validi.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: ciao dodici 3.5, echo $? ha dato 0, ciao 0 3.5

Che cosa ho capito su testo, conversioni e stampa: la parte del testo rimane invariata poiché è valida, la conversione con atoi invece fallisce e restituisce 0, mentre quella con atof rimane invariata per la validità dell'argomento. Il programma non segnala errori e stampa comunque i valori convertiti.

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: Quella con argomenti validi funziona normalmente, mentre con dodici la conversione restituisce 0.

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: Primo test: ciao 12 3.5 , Secondo test: ciao 0 3.5 .  In entrambi i casi il terminale non mostra errori ed echo $? restituisce 0 per entrambe le prove. L'unica differenza sta nella conversione del dodici in 0.


Come un controllo automatico può riconoscere un errore: confrontando output atteso ed effettivo e verificando che le conversioni avvengano correttamente e gli eventuali 0 non siano dovuti ad errori di conversione.

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: Serve ricompilare se cambio logica, formula o intrpretazione degli argomenti direttamente nel codice, se invece solo gli argomenti forniti in input devono variare allora non è necessario e basta appunto cambiare tali argomenti.

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:


Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
