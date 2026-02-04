---
title: Compilare un'istanza
nav_order: 20
parent: Le mie istanze
---

# Compilare un'istanza

Dopo aver avviato un'istanza (da **Nuova Istanza** oppure da **Duplica Istanza** oppure dal dettaglio, avviando una nuova comunicazione) il sistema presenta una maschera di compilazione dati ed un menu principale che mette in evidenza la tipologia della pratica in compilazione, lo stato della pratica, il numero (chiave a 19 cifre) e una serie di pulsanti.
L'istanza può essere completata senza seguire alcun tipo di ordine: è possibile inserire prima i dati di localizzazione e poi gli allegati o viceversa.
I campi che hanno lo sfondo giallo sono tutti da compilare obbligatoriamente.

## Menu dell'istanza

In questo pannello sono presenti:
- Pulsante blu con dischetto (*Salva* l'istanza): senza effettuare alcun tipo di verifica, il sistema procede con il salvataggio dell'istanza. Ad avvenuto salvataggio, il sistema darà un messaggio positivo (evidenziato in verde) di *Salvataggio della pratica avvenuto con successo* (con data e ora di salvataggio). Se l'istanza era ancora **In creazione** passerà allo stato **In Compilazione**
- Pulsante verde con dischetto e spunta (*Valida e Salva* l'istanza): a differenza del pulsante precedente, il sistema procede con la **verifica** dei dati (top down) e quindi con il salvataggio. Se il sistema rileva un errore (mancato inserimento di un campo obbligatorio, di un allegato, di un pagamento, di un soggetto o un dato non coerente), darà un messaggio di errore (evidenziato in rosso), posizionandosi nel punto esatto ed indicando il tipo di errore. Non è detto che l'errore sia l'unico: è il primo che il sistema ha incontrato. Nel caso in cui la verifica vada invece a buon fine, il messaggio sarà evidenziato in verde e l'istanza passerà dallo stato **In Compilazione** allo stato **Completata**
- Pulsante rosso con stampante (*Genera la bozza*): presente solo se l'istanza è *almeno* in stato **In Compilazione**. Consente di generare il *pdf* dell'istanza (anche se incompleto) e scaricarlo
- Pulsante azzurro con freccia a sinistra (*Ritorna all'elenco* oppure *Ritorna al dettaglio*): ritorna alla pagina precedente (nromalmente l'Elenco delle istanze oppure il dettaglio della pratica)
- *Tipologia della pratica*: descrizione (estesa) della pratica (ad esempio *Permesso di Costruire*, *S.C.I.A.*...)
- *Stato*: stato attuale dell'istanza (in questa fase può essere soltanto **In creazione**, **In Compilazione**, **Completata**, **Firmata**)
- *Numero*: chiave della pratica (19 cifre)

## Sezioni principali comuni a tutte le pratiche

### Dati titolare

In questa sezione devono essere inseriti (obbligatoriamente) i dati del **titolare principale** dell'istanza. Nel caso in cui si stia compilando una comunicazione collegata ad una pratica, i dati sono automaticamente inseriti, prelevandoli dalla pratica principale. Se si tratta di un'istanza duplicata, nel caso in cui nell'istanza originale fosse stato inserito il titolare, anche in questo caso viene automaticamente compilato.
Solo nel caso di un'istanza nuova, tutti questi dati devono essere inseriti manualmente.
Se è stata caricata l'anagrafica dei richiedenti, è possibile selezionare il soggetto dal menu a discesa (*Seleziona il richiedente*) e quindi cliccare su *Carica Titolare* per autocompilare i dati.

### Dati della ditta/società/ente/altro

In questa sezione (non obbligatoria) è possibile inserire i dati della ditta/società/ente associata al titolare della pratica. I campi diventano obbligatori nel momento in cui dal menu a disce *In qualità di* viene effettuata una selezione (Amministratore, Legale Rappresentante...).
Questa sezione viene autocompilata negli stessi casi previsti da quanto visto per *Dati titolare*.

### Dati del procuratore / delegato

In questa sezione (obbligatoria) è possibile inserire i dati del procuratore. Di *default* sono inseriti i tuoi dati, presi direttamente dal tuo profilo ma possono essere modificati anche eventualmente selezionando dal menu a discesa (*Selezione Proc. / Del.*) se è stata caricata l'anagrafica dei professionisti.

### Localizzazione dell'intervento

In questa sezione è necessario inserire i dati relativi all'indirizzo e numero civico (obbligatori) e ad almeno un dato catastale (Fabbricati oppure Terreni).
Nel caso in cui l'indirizzo sia mancante se l'Ente lo consente è possibile spuntare la voce *Toponimo mancante* ed aggiungerne uno. Se invece l'Ente non consente l'inserimento di toponimi è necessario contattarlo per sapere come comportarsi (o farsi indicare il toponimo corretto che dovrebbe essere presente nel menu a discesa).
Sulla base delle impostazioni dell'Ente, può essere attivata la *cartografia* che può essere con sola base catastale oppure PRGC e avere attive alcune funzionalità quali:
- Ricerca pratiche in cartografia (con icona *squadretta e matita* nella barra laterale della cartografia): consente di ricercare pratiche direttamente sul sistema cartografico
- Importazione mappali in pratica: selezionando i mappali in cartografia, è possibile (mediante apposito pulsante) importarli direttamente sulla pratica (anche le coordinate per i comuni di Regione Lombardia)
- Importazione mappali in cartografia: selezionati i mappali in pratica, vengono automaticamente "accesi" sulla cartografia

Al fondo della sezione è presente la selezione della *destinazione d'uso* (è possibile selezionarne anche più di una).

Per i comuni di Regione Lombardia è inoltre *obbligatorio* l'inserimento delle coordinate.

### Soggetti coinvolti

In questa sezione viene richiesto il caricamento di (eventuali) altri titolari, tecnici incaricati e imprese. In base alle selezioni operate precedentemente (tipologia di pratica ed intervento) determinate sezioni devono essere compilate obbligatoriamente e determinate ruoli professionali devono essere selezionati.
Ad esempio, se si compila una C.I.L.A. e nella sezione *Impresa esecutrice dei lavori* è prevista la possibilità di spuntare la voce *che, in quanto opere di modesta entità che non interessano le specifiche normative di settore, i lavori saranno eseguiti in prima persona, senza alcun affidamento a ditte esterne*, allora non verrà richiesto l'inserimento di imprese.

### PagoPA

In questa sezione sono presenti i pagamenti **obbligatori** e **facoltativi** previsti per l'istanza. Senza aver effettuato il pagamento degli obbligatori, l'istanza non potrà essere completata, mentre è possibile ignorare i pagamenti facoltativi per procedere con la validazione dell'istanza.
Per ogni pagamento previsto è possibile inserire uno IUV in proprio possesso oppure crearlo direttamente in piattaforma. È consigliato il sistema di creazione IUV direttamente su GeoTecSUE in quanto si ha la certezza della corretta tipologia del pagamento e dell'importo richiesto.

### Quadro riepilogativo della documentazione

In questa sezione sono presenti:
- Documenti obbligatori richiesti
- Documenti liberi
- Documenti facoltativi
Non è possibile completare la pratica se non sono stati inseriti *almeno* tutti i documenti obbligatori.
In base alle impostazioni previste dall'Ente, i documenti possono essere richiesti con (o senza) firma digitale e al massimo di una certa dimensione. Per ogni documento richiesto si può allegare uno (o più) documenti che devono soddisfare le caratteristiche richieste.

