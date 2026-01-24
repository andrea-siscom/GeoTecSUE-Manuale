---
title: Stati PagoPA
parent: Appendici
nav_order: 1
---

Questa appendice descrive gli **stati del PagoPA** così come vengono gestiti e visualizzati nel portale **GeoTecSUE**.

Gli stati derivano dal sistema di pagamento e vengono rappresentati nel portale tramite **icone** e **messaggio descrittivi**.

| Codice | Icona (portale) | Stato | Descrizione | Significato operativo |
|------:|----------------|------|-------------|-----------------------|
| — | ❌ `glyphicon-remove` | Senza IUV | Nessun IUV associato | Pagamento non generato |
| 0 | ❌ `glyphicon-remove` | Senza IUV | Pagamento privo di IUV | Nessuna operazione avviata |
| 2 | ⏳ `glyphicon-hourglass` | In attesa di IUV | Generazione IUV in corso | Attendere |
| 10 | ✔️ `glyphicon-ok` | IUV generato | IUV creato | Pagamento disponibile |
| 14 | 🛣️ `glyphicon-road` | Pagamento inoltrato | Pagamento avviato | In corso |
| 15 | 👍 `glyphicon-thumbs-up` | Pagamento accettato | Preso in carico | Attesa esito |
| 16 | 👍 `glyphicon-thumbs-up` | Pagamento autorizzato | Autorizzato dal PSP | Attesa conferma |
| 17 | 🔄 `glyphicon-transfer` | Pagamento differito | Esito differito | Verifica successiva |
| 19 | 🛣️ `glyphicon-road` | In attesa di esito | In verifica | Attendere |
| 20 | 👍 `glyphicon-thumbs-up` | Pagamento eseguito | Pagamento completato | Esito positivo |
| 21 | 👍 `glyphicon-thumbs-up` | Pagamento eseguito parzialmente | Pagamento parziale | Saldo incompleto |
| 30 | 👎 `glyphicon-thumbs-down` | Pagamento non eseguito | Fallito | Nessun incasso |
| 31 | 👎 `glyphicon-thumbs-down` | Non eseguito (termini) | Scaduto | Nuovo pagamento |
| 32 | 🔁 `glyphicon-retweet` | Pagamento stornato | Storno effettuato | Importo restituito |
| 33 | 👎 `glyphicon-thumbs-down` | Pagamento revocato | Revocato | Non valido |
| 40 | 👎 `glyphicon-thumbs-down` | Pagamento scaduto | IUV scaduto | Non pagabile |
| 90 | 👎 `glyphicon-thumbs-down` | Pagamento annullato | Annullato | Non valido |
| 100 | 💶 `glyphicon-euro` | Pagamento incassato | Incassato | Contabilizzato |
