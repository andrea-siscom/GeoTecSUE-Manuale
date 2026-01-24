---
title: Stati PagoPA
parent: Appendici
nav_order: 1
---

Questa appendice descrive gli **stati del PagoPA** così come vengono gestiti e visualizzati nel portale **GeoTecSUE**.

Gli stati derivano dal sistema di pagamento e vengono rappresentati nel portale tramite **icone** e **messaggio descrittivi**.

| Codice | Icona (portale) | Stato | Descrizione | Significato operativo |
|------:|----------------|------|-------------|-----------------------|
| — | ❌ | Senza IUV | Nessun IUV associato | Pagamento non generato |
| 0 | ❌ | Senza IUV | Pagamento privo di IUV | Nessuna operazione avviata |
| 2 | ⏳ | In attesa di IUV | Generazione IUV in corso | Attendere |
| 10 | ✔️ | IUV generato | IUV creato | Pagamento disponibile |
| 14 | 🛣️ | Pagamento inoltrato | Pagamento avviato | In corso |
| 15 | 👍 | Pagamento accettato | Preso in carico | Attesa esito |
| 16 | 👍 | Pagamento autorizzato | Autorizzato dal PSP | Attesa conferma |
| 17 | 🔄 | Pagamento differito | Esito differito | Verifica successiva |
| 19 | 🛣️ | In attesa di esito | In verifica | Attendere |
| 20 | 👍 | Pagamento eseguito | Pagamento completato | Esito positivo |
| 21 | 👍 | Pagamento eseguito parzialmente | Pagamento parziale | Saldo incompleto |
| 30 | 👎 | Pagamento non eseguito | Fallito | Nessun incasso |
| 31 | 👎 | Non eseguito (termini) | Scaduto | Nuovo pagamento |
| 32 | 🔁 | Pagamento stornato | Storno effettuato | Importo restituito |
| 33 | 👎 | Pagamento revocato | Revocato | Non valido |
| 40 | 👎 | Pagamento scaduto | IUV scaduto | Non pagabile |
| 90 | 👎 | Pagamento annullato | Annullato | Non valido |
| 100 | 💶 | Pagamento incassato | Incassato | Contabilizzato |
