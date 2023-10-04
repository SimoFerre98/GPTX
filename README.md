# GPTXchange
## Introduzione

GPTXChange nasce come un "Exchange" di criptovalute rivoluzionario che unisce le più classiche funzioni presenti in tanti altri exchange del mercato (Binance, Coinbase e molti altri ancora).
GPTXChange fornisce un portafoglio virtuale (o wallet) che memorizzerà tutti gli asset posseduti da ciascun utente. Saranno anche disponibili tutte le principali informazioni sulle crypto presenti nel mercato tramite un apposito feed progettato ad-hoc.
L'Exchange sarà accompagnato da un helper, il fiore all'occhiello di questo progetto. L'helper bot, costruito usando costrutti di intelligenza artificiale, potrà aiutare l'utente in ogni aspetto che riguardi il complesso mondo delle criptovalute. Sarà possibile chiedere informazioni sulle varie funzionalità offerte da GPTXChange oltre che info più generali sull'universo delle crypto e delle blockchain.

## Framework utilizzato

L'applicazione è stata costruita utilizzando il Framework React Native, sviluppato da Meta. React Native permette la realizzazione di applicazioni cross-platform, gode di un ampio utilizzo e di una folta community di supporto. L'utilizzo di un framework cross-platform rende più agevole lo sviluppo dell'applicazione, utilizzando un solo codice sorgente invece di due separati (Android ed iOS), pagando in prestazioni peggiori rispetto all'uso di un linguaggio di programmazione nativo (Kotlin, Java, Swift). Tuttavia tale aspetto rimane marginale nella maggior parte dei casi, dato che non si necessitano prestazioni di tipo real-time (la differenza tra codice nativo e codice React Native non si nota molto in applicazioni di questo tipo).

## Funzionalità dell'app

In linea di massima, l'applicazione consentirà la visualizzazione di alcune criptovalute, scelte dallo staff a seconda della popolarità (e di eventuali difficoltà nella loro implementazione lato codice). Queste saranno presentate nella prima schermata, chiamata anche "Riepilogo" ed accessibile a tutti coloro che utilizzano l'applicazione. 
L'applicazione permette la creazione di un account utente, al quale sono associate le chiavi private degli indirizzi blockchain ad esso assegnato. L'account utente gode di alcune funzionalità di rilievo:
- Accesso tramite email (o nome utente) e password.
- Recupero password tramite email.
Per massimizzare la sicurezza, si pensa di implementare:
- Autenticazione a due fattori, da usare ogni qualvolta si compia un'operazione "Rischiosa", come l'accesso da una posizione sconosciuta oppure l'invio di criptovalute verso un indirizzo esterno a GPTXChange.

Gli elementi della ListView comprendenti le crypto saranno tutti "cliccabili" e, a seguito di tale azione, sarà possibile osservare alcune informazioni di rilievo sull'asset scelto:
- Prezzo attuale nel mercato USD e storico a mezzo grafico.
- Ultime notizie di mercato.
- Funzionalità di acquisto/vendita di criptovalute facendo uso dell'exchange interno.
- Ricezione/Invio di criptovalute da e verso un wallet esterno.
- Volume del mercato nelle ultime 24h.

## Funzionalità dell'helper bot

L'helper bot è una funzionalità ben presente all'interno di GPTXChange. In tutta l'applicazione sarà presente un apposito pulsante al cui tocco ne consegue l'apertura di una finestra di chat. Qui l'utente potrà porre tutte le domande che desidera sull'applicazione in sè o sul mondo delle criptovalute. Le risposte saranno processate con un modello di intelligenza artificiale apposito, che riuscirà a fornire risposte più "umane" e utili all'utente finale (non si tratterà di una semplice FAQ ma di una vera interazione uomo-macchina). 

