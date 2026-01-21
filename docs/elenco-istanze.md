---
title: Elenco istanze
nav_order: 30
parent: Le mie istanze
---

# Elenco istanze

In questo capitolo vengono messe in evidenza le tre possibili sezioni che possono essere presenti:
- [Pratiche in fase di compilazione](#pratiche-in-fase-di-compilazione)
- [Pratiche inviate](#pratiche-inviate)
- [Pratiche importate](#pratiche-importate)

---

## Pratiche in fase di compilazione

La sezione **Lista Pratiche in fase di compilazione** mostra tutte le istanze ancora modificabili. Ogni riga rappresenta una pratica e le colonne hanno la seguente funzione:

### Colonne dell'elenco

1. **Modifica**: contiene il pulsante ✏️ (*giallo*) per accedere alla pratica e proseguirne la compilazione [vedi](interfaccia-e-convenzioni#modifica-pulsante-giallo)
2. **Cancella**: contiene il pulsante 🗑️ (*rosso*) per eliminare la pratica. Prima dell'eliminazione definitiva, il sistema richiederà una *conferma* [vedi](interfaccia-e-convenzioni#cancellazione-pulsante-rosso)
3. **Gestione soggetti compilatori**: contiene il pulsante 👤 (*blu* oppure *verde*) per gestire i *soggetti compilatori* della pratica [vedi](nozioni-di-base#altri-soggetti-compilatori). Il ruolo dei *soggetti compilatori* è spiegato nella [sezione apposita](nozioni-di-base#professionista-principale-ed-altri-soggetti-compilatori)
4. **PDF**: contiene l'icona del PDF nel caso in cui sia già stato generato il PDF dell'istanza, vuoto altrimenti. Cliccando l'icona è possibile procedere al *download* del file
5. **P7M**: contiene l'icona del P7M nel caso in cui sia già stato caricato il file firmato digitalmente, vuoto altrimenti. Cliccando l'icona è possibile procedere al *download* del file
6. **Tipo**: contiene la tipologia della pratica in compilazione (S.C.I.A., Permesso di Costruire...)
7. **Data Registrazione**: contiene la data in cui è stata registrata l'istanza
8. **Titolare**: contiene cognome e nome del titolare dell'istanza (se è già stato indicato)
9. **Stato Pratica**: contiene lo stato della pratica [vedi](nozioni-di-base#il-ciclo-di-vita-di-unistanza)
10. **PDF**: se la pratica si trova in stato *Completata*, contiene il bottone *Genera* per consentire al sistema la generazione del *PDF* dell'istanza. Una volta cliccato il bottone, comparirà nella quarta colonna l'icona del *PDF* appena generato.

## Pratiche inviate

La sezione **Lista Pratiche inviate** mostra tutte le istanze che sono già state trasmesse all'ente (dallo stato *inviata* in poi). Ogni riga rappresenta una pratica e le colonne hanno la seguente funzione:

### Colonne dell'elenco

1. **Nascondi** o **Mostra**: può contenere il pulsante 👁️ (*rosso*) oppure 🚫 (*azzurro*). Cliccando il pulsante *rosso* la pratica, originariamente nascosta, viene mostrata nella lista. Cliccando il pulsante *azzurro* la pratica viene nascosta dalla lista (l'operazione è sempre reversibile)
2. **Ricevuta di invio**: contiene il pulsante 🎟️ (*verde*) e consente di scaricare immediatamente la ricevuta di invio della pratica. Nel caso in cui la ricevuta di invio non sia (ancora) disponibile, allora al posto del pulsante 🎟️ (*verde*) ci sarà l'icona della clessidra (⏳, senza colore)
3.  **Tipo**: contiene la tipologia della pratica inviata (S.C.I.A., Permesso di Costruire...)
4.  **Data Invio**: contiene la data in cui è stata inviata l'istanza
5.  **Titolare**: contiene cognome e nome del titolare dell'istanza
6. **Stato Pratica**: contiene lo stato della pratica [vedi](nozioni-di-base#il-ciclo-di-vita-di-unistanza)
7. **Descrizione Intervento**: contiene l'oggetto dell'intervento inserito dal professionista. Se supera una certa lunghezza, è possibile vedere il testo completo passando sopra con il *mouse* (con un effetto *tooltip*)
8. **Dettaglio**: contiene il pulsante 🔍 (*verde*) che consente di vedere il dettaglio della pratica [vedi](interfaccia-e-convenzioni#visualizza-dettaglio-pulsante-verde-oppure-giallo)

### Sezione filtri

È possibile filtrare la ricerca delle pratiche inviate utilizzando i seguenti parametri contenuti nel pannello:

* **Dalla data di invio**: si può inserire una data dalla quale far partire la ricerca
* **Alla data di invio**: si può inserire una data alla quale concludere la ricerca
* **Tipo di pratica**: nella tendina sono presenti *solo* le tipologie di pratica che sono state trasmesse. È possibile quindi selezionare una di queste
* **Stato della pratica**: nella tendina sono presenti tutti gli stati della pratica ([vedi](nozioni-di-base#il-ciclo-di-vita-di-unistanza)) a partire da *inviata*
* **Tipo Condivisione**: nella tendina sono presenti le tre possibili voci: *Professionista Principale*, *Amministratore*, *Utente Modifica* ([vedi](nozioni-di-base#professionista-principale-ed-altri-soggetti-compilatori))
* **Includi le pratiche nascoste**: se viene spuntata questa voce, vengono incluse *anche* le pratiche che sono state nascoste
* **Comune**: nel caso in cui l'Ente sia *multi ente* (Unione di Comuni, Comunità Montana o Collinare...) dalla tendina è possibile selezionare un Comune facente parte dell'Ente
* **Titolare**: si può inserire (liberamente) il nominativo del soggetto che si vuole ricercare
* **Chiave della pratica**: si può inserire il codice di 19 cifre che compone la chiave della pratica

Questi campi vengono combinati tra loro e cliccando il bottone *Filtra i risultati* il sistema avvierà la ricerca.

## Pratiche importate

La sezione **Lista Pratiche importate** mostra tutte le istanze che sono state importate dal gestionale in uso presso l'Ente e non presentate attraverso il portale **GeoTecSUE**. Ogni riga rappresenta una pratica e le colonne hanno la seguente funzione:

### Colonne dell'elenco

1.  **Tipo**: contiene la tipologia della pratica importata così come presente sul gestionale in uso presso l'Ente (non è detto che siano le stesse tipologie presenti su **GeoTecSUE**)
2.  **Data Importazione**: contiene la data in cui è stata importata la pratica
3.  **Data Protocollo**: contiene la data di protocollazione della pratica
4.  **Titolare**: contiene cognome e nome del titolare dell'istanza
5.  **Stato Pratica**: contiene lo stato della pratica [vedi](nozioni-di-base#il-ciclo-di-vita-di-unistanza)
6. **Descrizione Intervento**: contiene l'oggetto dell'intervento inserito dal professionista. Se supera una certa lunghezza, è possibile vedere il testo completo passando sopra con il *mouse* (con un effetto *tooltip*)
7. **Dettaglio**: contiene il pulsante 🔍 (*verde*) che consente di vedere il dettaglio della pratica [vedi](interfaccia-e-convenzioni#visualizza-dettaglio-pulsante-verde-oppure-giallo)

### Sezione filtri

È possibile filtrare la ricerca delle pratiche importate utilizzando i seguenti parametri contenuti nel pannello:

* **Dalla data di protocollo**: si può inserire una data di protocollo dalla quale far partire la pricerca
* **Alla data di protocollo**: si può inserire una data di protocollo alla quale concludere la ricerca
* **Dalla data di importazione**: si può inserire una data di importazione dalla quale far partire la pricerca
* **Alla data di importazione**: si può inserire una data di importazione alla quale concludere la ricerca
* **Tipo di pratica**: nella tendina sono presenti *solo* le tipologie di pratica che sono state importate dal gestionale (non è detto che siano le stesse tipologie presenti su **GeoTecSUE**). È possibile quindi selezionare una di queste
* **Stato della pratica**: nella tendina sono presenti tutti gli stati della pratica ([vedi](nozioni-di-base#il-ciclo-di-vita-di-unistanza)) a partire da *registrata*
* **Titolare**: si può inserire (liberamente) il nominativo del soggetto che si vuole ricercare

