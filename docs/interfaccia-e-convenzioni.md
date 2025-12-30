---
title: Interfaccia e convenzioni
nav_order: 30
parent: Introduzione
---

# Interfaccia e convenzioni

Questo capitolo descrive gli elementi grafici e le convenzioni utilizzate nell'interfaccia del portale **GeoTecSUE**, al fine di facilitarne l'utilizzo.

---

## Convenzioni grafiche

Il portale **GeoTecSUE** utilizza icone e colori per rappresentare in modo immediato le **azioni disponibili** e il **livello di impatto** delle operazioni eseguibili.

La presente sezione descrive tali convenzioni per facilitarne la comprensione durante l'utilizzo dell'applicazione.

### Pulsanti e colori

I pulsanti (*bottoni*) presenti nel portale sono identificati da un'icona e da un colore, che consentono di riconoscere rapidamente il tipo di azione associata.

| Icona | Colore    | Azione            |
| ----- | --------- | ----------------- |
| ✏️    | 🟡 Giallo | Modifica          |
| 🗑️   | 🔴 Rosso  | Cancellazione     |
| 👤    | 🔵 Blu / 🟢 Verde | Gestione soggetti |

#### ✏️ Modifica (pulsante giallo)

##### Descrizione

Consente la modifica di un dato inserito.
Nella sezione dell'*Elenco istanze* consente di accedere al dettaglio della pratica (o della comunicazione) per proseguirne la compilazione o modificarne i dati inseriti.

##### Note

- Una volta cliccato il pulsante, la sua azione è *sempre reversibile* (propone la modifica ma non la effettua fino a conferma)

##### Dove si trova

- Nell'elenco delle istanze, nella sezione delle pratiche in compilazione (se presenti)
- Nel dettaglio della pratica, nella sezione delle comunicazioni in fase di compilazione (se presenti)
- All'interno della *compilazione* dell'istanza nella sezione della *Localizzazione dell'intervento* (per la modifica di un mappale inserito) e nei *Soggetti coinvolti* (per la modifica di un *titolare*, di un *tecnico incaricato* o di un'*impresa esecutrice*)

#### 🗑️ Cancellazione (pulsante rosso)

##### Descrizione

Consente di eliminare **definitivamente** una pratica (o una comunicazione), un allegato caricato nell'istanza, un **codice IUV** legato ad un **PagoPA** non ancora pagato, un soggetto caricato all'interno dell'istanza (*titolare*, *professionista*, *impresa*)

##### Note

- Prima dell'eliminazione è possibile la richiesta di una conferma esplicita (nel caso di cancellazione di un'istanza in compilazione)
- L'operazione *non è reversibile*

##### Dove si trova

- Nell'elenco delle istanze, nella sezione delle pratiche in compilazione (se presenti)
- Nel dettaglio della pratica, nella sezione delle comunicazioni in fase di compilazione (se presenti)
- All'interno della *compilazione* dell'istanza nella sezione della *Localizzazione dell'intervento* (per la cancellazione di un mappale inserito), nei *Soggetti coinvolti* (per la cancellazione di un *titolare*, di un *tecnico incaricato* o di un'*impresa esecutrice*), nella sezione *PagoPA* (per la cancellazione di un pagamento ancora non effettuato) e nalla sezione degli *Allegati* obbligatori, liberi e facoltativi (per la cancellazione di un allegato caricato)

#### 👤 Gestione soggetti (pulsante blu oppure verde)

##### Descrizione

Consente di gestire i **Soggetti Compilatori** della pratica (per maggiori dettagli vedere la sezione apposita). Il pulsante consente di aggiungere un professionista alla compilazione della pratica oppure a rimuoverlo.

##### Note

- Una volta cliccato il pulsante, la sua azione è *sempre reversibile* (propone la modifica ma non la effettua fino a conferma)
- Il pulsante è di colore blu quando ancora nessun soggetto è stato aggiunto
- Il pulsante è di colore verde quando *almeno* un soggetto è stato aggiunto

##### Dove si trova

- Nell'elenco delle istanze, nella sezione delle pratiche in compilazione (se presenti)
- Nel dettaglio della pratica (in alto a destra) accompagnando all'icona anche il testo *Gestione Soggetti*
