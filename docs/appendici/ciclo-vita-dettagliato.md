---
title: Ciclo di vita dettagliato
parent: Appendici
nav_order: 1
---

Questa appendice descrive gli **stati** possibili durante il ciclo di vita di un'istanza.

## Stati di lavorazione del professionista

## In Creazione

L'istanza è stata appena creata ma non ancora salvata: è uno stato che può durare al massimo pochi minuti, evolvendo poi verso lo stato successivo *In Compilazione* oppure terminare con il non salvataggio dell'istanza.

## In Compilazione

L'istanza è stata salvata ma non è ancora completa in quanto priva della compilazione di tutti i campi obbligatori, degli allegati obbligatori oppure dei pagamenti (con *PagoPA*) richiesti obbligatoriamente.

## Completata

Il sistema ha validato con successo l'istanza in quanto tutti i dati e gli allgati sono stati inseriti correttamente e gli eventuali pagamenti sono stati effettuati. L'istanza è pronta per essere *Firmata* (se l'Ente ne richiede obbligatoriamente la firma) oppure *Inviata*.

# Firmata

Il file dell'istanza, generato dal sistema, è stato correttamente scaricato, è stata apposta firma *CAdES* su tale file ed è stato correttamente caricato. L'istanza è pronta per essere *Inviata*.

# Stati di lavorazione dell'Ente

## Inviata

L'istanza è stata trasmessa all'Ente ed è in attesa dello stato successivo (*Protocollata*). All'atto dell'invio il sistema crea la **ricevuta di invio** scaricabile pochi istanti dopo l'invio dell'istanza dall'elenco delle pratiche inviate oppure dal dettaglio dell'istanza stessa. Da questa fase fino allo stato *Registrata* non è possibile inviare comunicazioni e/o integrazioni.

## Inviata SPRESALWEB (via MUDE)

Questo stato è previsto per i soli Comuni della Regione Piemonte che hanno attivato la trasmissione della *Notifica Preliminare* a mezzo **GeoTecSUE**.
Riguarda esclusivamente le pratiche di *Notifica Preliminare* e all'atto dell'invio il sistema crea la **ricevuta di invio** scaricabile pochi istanti dopo l'invio dell'istanza dall'elenco delle pratiche inviate oppure dal dettaglio dell'istanza stessa.

## Protocollata

L'Ente ha ricevuto la pratica all'*Ufficio Protocollo*, che ha assegnato un numero di protocollo ed una data di protocollo, inserendola nel proprio sistema documentale. In moltissimi casi questa fase è del tutto automatizzata, rendendo la transizione tra *Inviata* e *Protocollata* molto rapida (dell'ordine dei pochi minuti).
All'atto della protocollazione il sistema crea la **ricevuta di protocollazione** scaricabile pochi istanti dopo la protocollazione dell'istanza. Non è ancora possibile inviare comunicazioni e/o integrazioni (fino allo stato *Registrata*).

## Protocollata SPRESALWEB

Come per lo stato *Inviata SPRESALWEB (via MUDE)*, questo stato è previsto per i soli Comuni della Regione Piemonte che hanno attivato la trasmissione della *Notifica Preliminare* a mezzo **GeoTecSUE**.
La protocollazione non viene effettuata dall'Ente ma dal sistema *SPRESAL*, che comunica in modalità *asincrona* l'avvenuta protocollazione. Normalmente la protocollazione avviene nel giro di poche ore.
All'atto della protocollazione il sistema crea la **ricevuta di protocollazione** scaricabile pochi istanti dopo la protocollazione dell'istanza. Non sono previsti ulteriori stati per quanto riguarda le pratiche di *Notifica Preliminare*.

## Registrata

Questo stato riguarda unicamente le pratiche e viene raggiunto nel momento in cui l'Ente, mediante il suo ufficio competente (normalmente l'Ufficio Tecnico), prende in carico la pratica assegnandone un numero di registrazione ed una data di registrazione. Molto spesso, in concomitanza con la registrazione, viene anche indicato (se previsto) il *responsabile del procedimento* (e del *servizio*).
Quando la pratica raggiunge questo stato è possibile interagire integrandola oppure inviando comunicazioni collegate.
All'atto della registrazione il sistema crea la **ricevuta di registrazione**.

# Stati di integrazione documentale o richiesta archiviazione

## Richiesta Integrazioni

L'Ente ha aperto formalmente una richiesta di integrazione e pertanto vengono interrotti i termini ed il sistema si predispone per ricevere i documenti integrativi.
In questa fase, a seconda di come l'Ente ha configurato il proprio **GeoTecSUE**, potrebbe essere possibile il solo caricamento dei documenti integrativi, fermando qualsiasi altra attività in corso (caricamento di una comunicazione, ecc...).
Inoltre, in base alla configurazione, è possibile caricare i soli documenti richiesti oppure ampliare la richiesta di integrazione caricandone anche altri.
Una volta caricati *almeno* tutti i documenti richiesti, è possibile procedere con la trasmissione (lo stato passa a *Invio Integrazioni*).

## Invio Integrazioni

Le integrazioni sono state correttamente caricate e inviate. Lo stato è simile a *Inviata* e nel giro di poco tempo la pratica dovrebbe ritornare allo stato precedente della *Richiesta Integrazioni* (normalmente potrebbe essere lo stato *Registrata* ma in alcuni casi potrebbe anche essere *Esecutiva*).

## Richiesta Archiviazione

Questo stato si raggiunge nel momento in cui viene compilata l'istanza di *Richiesta Archiviazione* e trasmessa verso l'Ente.
Normalmente lo stato successivo è sempre *Archiviata*.

# Stati finali

## Esecutiva

La pratica raggiunge questo stato nel caso in cui l'Ente rilasci il provvedimento (ad esempio per il Permesso di Costruire oppure per l'Autorizzazione Paesaggistica).
Insieme allo stato *Esecutiva* vengono anche trasmessi i dati relativi al numero e alla data del provvedimento rilasciato.
Lo stato raggiunto consente la lavorazione della pratica nella stessa modalità prevista dallo stato *Registrata*.

## Archiviata

Dopo un'esplicita richiesta di archiviazione da parte del professionista oppure dopo una decisione dell'Ente (pratica errata, non conforme, presentata allo sportello sbagliato), la pratica può essere *Archiviata*. Quando raggiunge questo stato non è più possibile operare anche se è visibile sulla propria scriviania.

## Diniego

Lo stato è molto simile ad *Archiviata* (stesso effetto) ma può raggiungere questo stato esclusivamente per una scelta dell'Ente. Quando la pratica raggiunge questo stato non è più possibile operare anche se è visibile sulla propria scriviania.

## Revoca Delegato

La pratica raggiunge questo stato quando il **titolare** della pratica richiede all'Ente (non attraverso il portale) di revocare il delegato. Non è quindi possibile operare sulla pratica (è analoga ad *Archiviata* o *Diniego*) ma lo stato è transitorio, in attesa di essere assegnata ad un nuovo professionista

# Stati non utilizzati (o deprecati)

## Rifiutata

Prima che la pratica possa raggiungere lo stato *Protocollata* da *Inviata* potrebbe essere "intercettata" dall'Ente che la rifiuta (con motivazione) senza che la pratica venga inserita sui sistemi gestionali dell'Ente (protocollo e Ufficio Tecnico). Questo stato è ormai praticamente in disuso in quanto sulla maggior parte degli Enti è presente la *protocollazione automatica* che non consente più un *rifiuto* dell'istanza. È inoltre deprecato l'uso nei casi in cui non sia presente la protocollazione automatica in quanto con il rifiuto non si tiene in alcun modo traccia della pratica (anche per ricerche future)

## Verificata

Sui gestionali in uso dell'Ente molto spesso è possibile indicare che una pratica che non prevede il rilascio di un titolo (ad esempio SCIA o CILA) possa essere *verificata* da parte dell'Ente. Visto che si tratta di tipologie di pratica che non prevedono un coinvolgimento dell'Ente, il concetto di *verifica* è puramente interno ed è sconsigliata la propagazione sul portale.
