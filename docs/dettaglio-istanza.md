---
title: Dettaglio istanza
nav_order: 40
parent: Le mie istanze
---

# Dettaglio istanza

Cliccando il pulsante 🔍 a fianco di un'istanza inviata oppure importata, si entra all'interno della sezione di *dettaglio* dell'istanza.
Ci sono tre tipologie di dettaglio:
- [Dettaglio "classico"](#dettaglio-classico)
- Dettaglio della *Notifica Preliminare* (solo per i Comuni di Regione Piemonte)
- Dettaglio di una pratica *importata*

---

## Dettaglio classico

Si entra in questo dettaglio dalla lista delle pratiche inviate nel caso in cui la tipologia di pratica **non** sia la *Notifica Preliminare*.
La pagina è strutturata con una serie di sezioni che possono essere presenti o meno a seconda dello stato della pratica, del tipo di pratica, ecc...

### Titolo

Qui viene indicato la **tipologia della pratica** e il numero (**chiave**) della pratica stessa. Nella parte di destra viene evidenziato lo **stato della pratica** ([vedi](nozioni-di-base#il-ciclo-di-vita-di-unistanza)).
Nel caso in cui il professionista abbia indicato che la pratica è una *variante* e ne abbia indicato i riferimenti su **GeoTecSUE** in questa sezione viene inserito il *link* diretto alla variante (apre il dettaglio dell'istanza).

### Comunicazione di ente variato

Nel caso in cui l'Ente abbia cessato di esistere (Unione sciolta, Ente che ha aderito ad un'Unione...) il sistema inserisce un messaggio di errore in cui si segnala che l'Ente non è più attivo, dando (eventuale) indicazione del nuovo Ente in cui è confluito.

### Bottoni di menu

Sono presenti fino a 4 bottoni, che possono essere attivati a seconda dello stato della pratica e del tipo di soggetto che sta accedendo.

#### Bottone Ritorna

Cliccando il bottone *Ritorna*, il **GeoTecSUE** riporta alla pagina dalla quale si proviene (in linea di massima l'*elenco delle istanze*, ma potrebbe essere anche un'altra pagina).

#### Bottone Richiedi Archiviazione

Nel caso in cui il soggetto che sta consultando la pratica sia il *professionista principale* oppure un soggetto condivisore che abbia il ruolo di *amministratore* il bottone sarà visibile nel caso in cui lo stato della pratica lo consenta: è possibile *richiedere archiviazione* di una pratica solo nel caso in cui si trovi in stato *registrata*, *esecutiva*, *verificata* (anche se non usato) e *richiesta integrazioni*.
Cliccando questo bottone, il **GeoTecSUE** predispone la pratica di **Richiesta Archivazione** dell'istanza. Si rimanda alla sezione di compilazione delle istanze in quanto è analoga alla compilazione di un qualsiasi tipo di pratica.

#### Bottone Scarica l'archivio della pratica

Il bottone è sempre attivo e consente di scaricare (come file *.zip*) l'archivio della pratica. In particolare i file che vengono inseriti all'interno dell'archivio sono:
- Il documento dell'istanza (in formato *pdf* e, se previsto, anche la versione *firmata digitalmente*)
- Gli allegati *principali* della pratica se non ancora scaduti
- Le ricevute prodotte (sia per l'istanza principale che per le comunicazioni e le integrazioni)
- I documenti che l'Ente ha prodotto per la pratica (non hanno scadenza)
- Le integrazioni (solo se già protocollate e non ancora scadute)
- I documenti dell'istanza delle comunicazioni associate (se presenti, in formato *pdf* e, se previsto, anche la versione *firmata digitalmente*)
- Gli allegati delle (eventuali) comunicazioni associate se non ancora scaduti
- Il file *xml* della *tracciabilità* della pratica
- Un eventuale file di testo contenente gli errori rilevati

#### Bottone Gestione Soggetti

Il bottone è visibile nel caso in cui il soggetto che sta consultando la pratica si il *professionista principale* oppure un soggetto condivisore che abbia il ruolo di *amministratore*.
Cliccando questo bottone, il **GeoTecSUE** consente la gestione dei *soggetti compilatori* (andando ad aggiungere oppure ad eliminare un soggetto).

### Comunicazione di stato

Nel caso in cui la pratica si trovi in stato *inviata*, *protocollata* o *invio integrazioni*, il sistema comunica che non è possibile *interagire* con la pratica fino a quando lo stato non sarà *registrata*.

### Motivazione di archiviazione

Nel caso in cui la pratica sia stata *archiviata*, il sistema presenta questa sezione contenente anche il motivo dell'archiviazione (prodotto dall'Ente).

### Richiesta di integrazioni attiva

Se è presente una *richiesta integrazioni attiva* da parte dell'Ente allora verrà mostrata questa sezione in cui vengono evidenziati i seguenti dati:
- *Data Richiesta*: data in cui l'Ente ha effettuato la richiesta di integrazione
- *Descrizione*: la descrizione della richiesta di integrazioni (prodotta dall'Ente)
- *Firma necessaria*: nel caso in cui sia presente una spunta verde, allora è necessario caricare solo documenti firmati digitalmente. Se presente una croce rossa, non è necessario caricare documenti firmati digitalmente
- *Dimensione massima del file*: indica la dimensione massima (espressa in *mega byte*) del singolo file
Successivamente, viene proposta la lista dei documenti che vengono richiesti. Per ogni documento è presente la sezione di caricamento del file.
Se un file è già stato caricato, il sistema lo evidenzia e ne consente il *download* oppure la cancellazione.
Se l'Ente lo prevede, è possibile caricare anche altri file oltre a quelli richiesti.

### Pagamenti aperti

Se sono presenti dei pagamenti *aperti* (prodotti dall'Ente oppure pagamenti facoltativi legati alla pratica), in questa sezione vengono mostrati.
Nel caso in cui ci siano uno (o più) pagamenti *facoltativi* legati alla pratica dei quali **non è** ancora stato creato il *codice IUV*, verrà mostrata una tabella contenente i seguenti dati:
- *Descrizione Pagamento*: la descrizione del tipo di pagamento previsto (ad esempio "DIRITTI DI SEGRETERIA", "OBLAZIONE O SANZIONE IN SANATORIA"...)
- *Importo (€)*: l'importo da versare (può essere valorizzato oppure *da valorizzare*)
- Pulsante *Creazione IUV*: consente la creazione dello *IUV* (previa completamente dei dati)
Nel caso in cui uno (o più) pagamenti siano già stati creati (oppure generati dall'Ente), saranno presenti nella tabella contenente i seguenti dati:
- *Descrizione Pagamento*: la descrizione del tipo di pagamento previsto (ad esempio "DIRITTI DI SEGRETERIA", "OBLAZIONE O SANZIONE IN SANATORIA"...)
- *Rata*: se il pagamento è da effettuarsi in un'unica soluzione, sarà valorizzato con 1. Se invece il pagamento è suddiviso in più rate, allora ci sarà il progressivo
- *Scadenza*: indica la data di scadenza dello *IUV*
- *Importo (€)*: l'importo da versare (può essere valorizzato oppure *da valorizzare*)
- *Stato*: indica lo stato in cui si trova il pagamento (vedere l'appendice degli [Stati PagoPA](/GeoTecSUE-Manuale/docs/appendici/pagopa-stati))
- Pulsante *dettaglio* (colore azzurro): consente di visualizzare i dati relativi allo *IUV* emesso (nel caso sia *scaduto*, ne viene data evidenza)
- Pulsante *aggiorna* (colore arancione): nel caso in cui lo *IUV* non sia scaduto, è possibile, mediante questo pulsante, aggiornarne lo stato del pagamento


