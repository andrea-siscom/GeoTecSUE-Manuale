---
title: Notifica Preliminare (Piemonte)
nav_order: 60
parent: Le mie istanze
---

# Notifica Preliminare (Piemonte)

La *Notifica Preliminare* è un'istanza che è presente solo per gli Enti di Regione Piemonte che hanno deciso di attivarla sul portale GeoTecSUE.
Se l'Ente non ha attivato la *Notifica Preliminare* allora è necessario trasmetterla con il portale regionale di riferimento (per il Piemonte: https://www.mude.piemonte.it/site/notizie/101-rilasci-e-comunicazioni-di-servizio/724-trasmissione-della-notifica-preliminare-di-avvio-lavori-nei-cantieri-edili-di-cui-all-art-99-del-dlgs-81-08-e-smi-tramite-il-sistema-mude-piemonte-alle-aassll-del-piemonte)

## Differenze rispetto alle altre istanze

La *Notifica Preliminare*, una volta correttamente compilata e trasmessa, non viene inviata all'Ente ma, attraverso opportuni servizi messi a disposizione da *MUDE Piemonte*, viene inviata allo *SPRESAL*.
Successivamente, in un tempo normalmente intorno al massimo al paio di ore, la pratica viene *protocollata* dallo *SPRESAL* e a questo punto si conlude l'iter (non è possibile integrare e/o inviare comunicazioni relativamente a questa pratica).
L'Ente non riceve la pratica sul proprio gestionale ma può consultarla esclusivamente sul portale GeoTecSUE (nel proprio *Pannello di Amministrazione*)

## Creazione e compilazione

Come le altre istanze, viene creata utilizzando la voce di menu "Le mie istanze" - "Nuova istanza".
La compilazione segue quanto visto nella sezione [compilare un'istanza](compilare-istanza.html).
Nel caso in cui si voglia inviare un *aggiornamento* di una precedente notifica preliminare, nella sezione *Qualificazione pratica - intervento* è necessario spuntare la voce *Aggiornamento* ed indicare l'*istanza di primo invio*.
L'Istanza di primo invio è un codice numerico di 22 cifre così composto:
- Posizioni 1-2 - Lunghezza 2 - Codice ISTAT regionale - Deve essere "01"
- Posizioni 3-8 - Lunghezza 6 - Codice ISTAT del comune - Solo cifre
- Posizioni 9-18 - Lunghezza 10 - Progressivo - Solo cifre, maggiore di 0
- Posizioni 19-22 - Lunghezza 4 - Anno - Deve essere un anno valido

## Invio dell'istanza

Come per le altre istanze, una volta completata deve essere firmata e quindi inviata. All'atto dell'invio, il sistema GeoTecSUE contatta MUDE e tenta la trasmissione della *Notifica Preliminare*. Nel caso in cui il sistema rilevi un qualsiasi tipo di problema, viene mostrato il seguente messaggio di errore: "Il mancato invio è in fase di analisi: **non è necessario riprovare la trasmissione**, verrà effettuato un nuovo tentativo dai nostri sistemi automatici".
Nel caso in cui si rilevi un qualche problema sulla compilazione dell'istanza, potresti essere ricontattato dalla nostra assistenza.

## Dettaglio della pratica

Il dettaglio della *Notifica Preliminare* ricalca a grandi linee quanto visto nella sezione [visualizzare il dettaglio di una pratica](dettaglio-istanza.html) ma, come detto precedentemente, non è possibile inviare integazioni e/o comunicazioni e non c'è un dialogo con l'Ente di riferimento pertanto tutte le sezioni relative a:
- Trasmissione integrazioni
- Trasmissione comunicazioni
- Ricezione documenti dall'Ente
- Pagamenti PagoPA
non sono presenti nel dettaglio.
Permangono invece le sezioni di *Dati Generali della Pratica*, *Ricevute* e *Tracciabilità*.
Le sezioni aggiuntive sono mostrate di seguito.

### Dati Trasmissione

In questa sezione sono presenti:
- **Numero istanza MUDE**: numero che è stato assegnato in fase di trasmissione da parte di *MUDE Piemonte*. È un codice numero di 22 cifre
- **Data Trasmissione**: data ed ora di trasmissione dell'istanza

### Dati Protocollazione

Se la pratica è già in stato *Protocollata SPRESALWEB* in questa sezione sono presenti:
- **Data Variazione Stato**: data e ora in cui la pratica è passata da *Inviata SPRESALWEB* a *Protocollata SPRESALWEB*
- **Numero Protocollo**: numero del protocollo di *SPRESALWEB* (**non è** il numero di protocollo dell'Ente!)
- **Data Protocollo**: data del protocollo di *SPRESALWEB*
- **Oggetto Notifica MUDE**: descrizione della notifica preliminare
- **Messaggio Notifica MUDE**: ulteriore messaggio fornito da *MUDE*


