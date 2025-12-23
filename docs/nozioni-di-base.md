---
title: Nozioni di base
nav_order: 20
---

# Nozioni di base

Questo capitolo introduce i concetti fondamentali e l'organizzazione generale del portale **GeoTecSUE**.

---

## Cos'è GeoTecSUE

**GeoTecSUE** è una piattaforma web che consente la trasmissione telematica delle pratiche edilizie alla *Pubblica Amministrazione*. Non è un sistema per la *conservazione* dei dati, ma un meccanismo di *transito* dal professionista verso l'Ente.

Attraverso **GeoTecSUE** è possibile
- compilare e inviare istanze
- rispondere ad eventuali richieste di integrazione
- integrare la pratica con le comunicazioni associate
- monitorare lo stato delle proprie pratiche
- consultare lo storico delle pratiche trasmesse all'Ente
- gestire una propria *anagrafica* di richiedenti, professionisti ed imprese

## Istanza, Pratica, Comunicazione e Integrazione

Nel **GeoTecSUE** ci sono tre elementi fondamentali che possono essere ricondotti al concetto di **istanza**:
- [Pratica](#pratica)
- [Comunicazione](#comunicazione)
- [Integrazione](#integrazione)

### Pratica

La **pratica** è un'istanza che può essere avviata *indipendentemente*: vive di "luce propria", ha il suo *iter* e viene riconosciuta dalla *Pubblica Amministrazione* come un procedimento a sè stante.
Un esempio di **pratica** è il *Permesso di Costruire*.

### Comunicazione

La **comunicazione** è un'istanza che può essere avviata solo in presenza di una pratica già esistente: non vive di "luce propria", ma è "contenuta" all'interno di una pratica, andandone a definire un preciso comportamente.
Un esempio di **comunicazione** è la *Fine Lavori*.

### Integrazione

L'**integrazione** (spontanea oppure richiesta) è simile alla comunicazione: può essere avviata solo in presenza di una pratica esistente. Non vive di "luce propria", ma è contenuta all'interno di una pratica.

Gli enti possono decidere di inibire o consentire la trasmissione di integrazioni libere (o volontarie): pertanto il comportamento del **GeoTecSUE** è condizionato da quanto previsto dall'Ente stesso.

## Il ciclo di vita di un'istanza

Su **GeoTecSUE**, nel suo ciclo di vita, l'istanza passa attraverso diversi stati.

### In Creazione

L'istanza (**pratica** oppure **comunicazione**) è stata appena creata e non ancora salvata.

### In Compilazione

L'istanza (**pratica** oppure **comunicazione**) è stata creata e salvata, ma ancora non è stata completata (campi incompleti, documenti obbligatori mancanti, pagamenti obbligatori non effettuati...)

### Completata

L'istanza (**pratica** oppure **comunicazione**) è stata validata con successo: tutti i campi correttamente completati, i documenti obbligatori correttamente inseriti ed i pagamenti obbligatori effettuati.

### Firmata

Successivamente alla validazione, è stato *generato* e *scaricato* il PDF dell'istanza, **firmato digitalmente** e caricato. Questo è l'ultimo stato in cui si può trovare l'istanza prima dell'effettivo invio all'Ente.

### Inviata

L'istanza (**pratica** oppure **comunicazione**) è stata trasmessa all'Ente. A questo punto il proseguio del ciclo di vita dipenderà dalle azioni svolte dall'Ente.

### Protocollata

L'istanza (**pratica** oppure **comunicazione**) è stata protocollata dall'Ente: è stato quindi attribuito il numero di protocollo e la data di protollo all'istanza. Il professionista non può ancora operare sulla sua pratica inviando comunicazioni o integrazioni.

### Registrata

L'istanza (in questo caso solo più la **pratica**) è stata presa in carico dall'Ufficio di competenza (normalmente l'Ufficio Tecnico) ed è stato assegnato un numero di registrazione ed una data di registrazione. In questa fase può anche essere stato individuato un *responsabile del procedimento* (e del *servizio*).
Quando la **pratica** si trova in stato **registrata** il professionista può nuovamente *interagire* con essa inviando *comunicazioni* e/o (se previsto) *integrazioni*.

### Richiesta Integrazioni

L'Ente ha *registrato* la **pratica** trasmessa e, in fase istruttoria, ha aperto una **richiesta di integrazioni**. Il professionista deve pertanto intervenire sulla pratica (andando nel dettaglio) e caricando i documenti richiesti dall'Ente nell'apposita sezione.

### Invio Integrazioni

Questo stato può essere *successivo* alla sola **richiesta di integrazioni** e viene raggiunto quando il professionista ha caricato i documenti richiesti e li ha trasmessi verso l'Ente.

### Esecutiva

L'Ente, dopo aver effettuato l'istruttoria, rilascia il *provvedimento* collegato alla **pratica** che pertanto diventa **esecutiva**. Alla pratica è stato associato anche un numero provvedimento ed una data del provvedimento (tipicamente per *Permesso di Costruire*, *Autorizzazioni Paesaggistiche*...).

### Richiesta Archiviazione

Il professionista richiede all'Ente l'**archiviazione** della **pratica** mediante opportuna istanza che viene trasmessa a mezzo portale.

### Archiviazione

Questo stato può essere raggiunto *successivamente* ad una **richiesta di archiviazione** (da parte del professionista) oppure direttamente dall'Ente, che pone in **archiviazione** una pratica (presenta errori non conformabili con una richiesta di integrazione, presenta una pratica con tipologia errata, presenta una pratica *SUAP* sullo sportello *SUE*...). Quando la pratica si trova in stato **archiviata** il professionista può vederla sulla sua scrivania del **GeoTecSUE** ma non può operare (non può inviare comunicazioni, integrazioni...).

### Diniego

Questo stato è simile al precedente (**Archiviazione**) con la differenza che può essere raggiunto esclusivamente dall'Ente dopo l'istruttoria. Come nel caso dell'**archiviazione**, il professionista può vederla sulla sua scrivania del **GeoTecSUE** ma non può operare (non può inviare comunicazioni, integrazioni...).

### Revoca Delegato

Questo stato viene raggiunto nel caso in cui ci sia una contestazione da parte del titolare nei confronti del professionista originale della pratica e che quindi decida di *revocare* l'incarico. Come nei due casi precedenti (**archiviazione** e **diniego**) il professionista può vederla sulla sua scrivania del **GeoTecSUE** ma non può operare (non può inviare comunicazioni, integrazioni...).

### Solo per Enti del Piemonte con Notifica Preliminare attivata

#### Inviata SPRESALWEB (via MUDE)

Lo stato indica che la **Notifica Preliminare** è stata trasmessa al *MUDE* ed è in attesa di essere *protocollata*.

#### Protocollata SPRESALWEB

Questo stato può essere raggiunto solo da **Inviata SPRESALWEB (via MUDE)** e conclude il procedimento di trasmissione della **Notifica Preliminare**. Nessun altro stato può essere raggiunto da questo.

## Ciclo di vita di un'istanza: stati non utilizzati (o sconsigliati)

### Rifiutata

Questo stato può essere raggiunto solo nel caso in cui l'Ente abbia ancora attiva la protocollazione manuale delle istanze e, prima della protocollazione della stessa, decida di optarre per un **rifiuto**.
L'uso di questo stato è *sconsigliato*: meglio procedere con la protocollazione, la successiva registrazione e quindi con un'**archiviazione** oppure un **diniego**.
Nel caso di **pratica rifiutata** non vengono associati numeri di protocollo e/o registrazione (nei sistemi dell'Ente non c'è traccia dell'istanza).

### Verificata

La **verifica** di una pratica viene fatta dall'Ente per tutte le pratiche *asseverate* dal professionista: S.C.I.A., C.I.L.A., ecc...
Tale **verifica** può essere fatta puntualmente oppure *a campione*, rispettando l'obbligo di un controllo in misura minima pari ad una determinata percentuale delle pratiche (ancora presente in alcune regioni).
Il concetto di **verifica** è però maggiormente *interno* all'Ente e pertanto non viene trasmesso alla **pratica** su **GeoTecSUE**.

