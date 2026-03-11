---
title: Errori di validazione
nav_order: 25
parent: Le mie istanze
description: Riferimento completo a tutti i 108 messaggi di errore di validazione - cause e soluzioni
keywords: [errori, validazione, messaggi errore, campo obbligatorio, errore compilazione, validazione pratica, riferimento errori]
---

# Errori di validazione

Riferimento **completo** a tutti i **108 messaggi di errore** che possono apparire durante la compilazione e validazione di una pratica.

{: .note }
> Quando clicchi **"Valida e Salva"**, il sistema verifica tutti i dati. Se trova errori, appare un messaggio rosso. Usa questa pagina per trovare rapidamente la soluzione.

## Come usare questa guida

1. **Copia il messaggio di errore** esatto che vedi (es. Ctrl+C)
2. **Cerca in questa pagina** con Ctrl+F (Windows) o Cmd+F (Mac)
3. **Trova il codice errore** (ERR_XXX)
4. **Leggi la soluzione** e segui i passaggi
5. **Se non risolve**, consulta [Troubleshooting](troubleshooting.html) o [Assistenza](assistenza-tecnica.html)

{: .warning }
> Questa guida contiene TUTTI gli errori possibili. Molti sono rari. Concentrati sul messaggio che vedi effettivamente.

---

## Indice rapido per categoria

- [Dati Titolare](#titolare) (16 errori)- [Altri Titolari (Co-intestatari)](#co-intestatari) (17 errori)- [Dati Professionista](#professionista) (23 errori)- [Dati Ditta/Società](#ditta-societa) (4 errori)- [Dati Procuratore/Delegato](#procuratore) (3 errori)- [Imprese Esecutrici](#imprese) (11 errori)- [Legale Rappresentante Impresa](#legale-rappresentante) (18 errori)- [Email e PEC Tecnici](#email) (4 errori)- [Dati Catastali](#catasto) (1 errori)- [Codice Fiscale](#codice-fiscale) (1 errori)- [Marca da Bollo](#marca-bollo) (1 errori)- [Errori Tecnici di Sistema](#altro) (9 errori)

---

## Legenda

**Codice**: Identificativo univoco errore (ERR_XXX)  
**Messaggio**: Testo esatto mostrato dal sistema  
**Causa**: Perché appare l'errore  
**Soluzione**: Come risolvere passo-passo

---

## Dati Titolare
**16 errori in questa categoria**

### ERR_007: ATTENZIONE ! CAP di residenza del Titolare non inserito.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del Titolare non inserito.
```
**Causa**: Il campo **CAP** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_008: ATTENZIONE ! CAP di residenza del Titolare non valido.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del Titolare non valido.
```
**Causa**: Il campo **CAP** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Verifica che il CAP sia:
   - Di **5 cifre** esatte
   - Esempio: `10121` (NON `0121` o `10121 `)
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_015: ATTENZIONE ! Città di residenza del Titolare non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Città di residenza del Titolare non inserita.
```
**Causa**: Il campo **Città/Comune di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Città/Comune di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_022: ATTENZIONE ! Codice Fiscale del Titolare non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del Titolare non inserito.
```
**Causa**: Il campo **Codice Fiscale** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_023: ATTENZIONE ! Codice Fiscale del Titolare non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del Titolare non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_033: ATTENZIONE ! Cognome del Titolare non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Cognome del Titolare non inserito.
```
**Causa**: Il campo **Cognome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Cognome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_037: ATTENZIONE ! Comune di nascita del Titolare non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Comune di nascita del Titolare non inserito.
```
**Causa**: Il campo **Comune di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Comune di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_040: ATTENZIONE ! Data di Nascita del Titolare non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Data di Nascita del Titolare non inserita.
```
**Causa**: Il campo **Data di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Data di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_043: ATTENZIONE ! Data di nascita del Titolare non valida (gg/mm/aaaa).
**Messaggio completo**:
```
ATTENZIONE ! Data di nascita del Titolare non valida (gg/mm/aaaa).
```
**Causa**: Il campo **Data di nascita** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Data di nascita"** (evidenziato con sfondo giallo)
3. Verifica che la data sia:
   - Nel formato `GG/MM/AAAA`
   - Esempio: `01/01/1980`
   - Usa il calendario se disponibile
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_050: ATTENZIONE ! Indirizzo di residenza del Titolare non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo di residenza del Titolare non inserito.
```
**Causa**: Il campo **Indirizzo (via/piazza)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Indirizzo (via/piazza)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_056: ATTENZIONE ! Indirizzo e-mail certificata del Titolare non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata del Titolare non valido.
```
**Causa**: Il campo **Email certificata (PEC)** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_064: ATTENZIONE ! Indirizzo e-mail del Titolare non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail del Titolare non valido.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_073: ATTENZIONE ! Nome del Titolare non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Nome del Titolare non inserito.
```
**Causa**: Il campo **Nome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Nome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_080: ATTENZIONE ! Numero civico di residenza del Titolare non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Numero civico di residenza del Titolare non inserito.
```
**Causa**: Il campo **Numero civico** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Numero civico"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_095: ATTENZIONE ! Provincia di nascita del Titolare non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di nascita del Titolare non inserita.
```
**Causa**: Il campo **Provincia di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Provincia di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_099: ATTENZIONE ! Provincia di residenza del Titolare non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di residenza del Titolare non inserita.
```
**Causa**: Il campo **Provincia di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Provincia di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

## Altri Titolari (Co-intestatari)
**17 errori in questa categoria**

### ERR_005: ATTENZIONE ! CAP di residenza del Titolare aggiunto non inserito.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del Titolare aggiunto non inserito.
```
**Causa**: Il campo **CAP** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_006: ATTENZIONE ! CAP di residenza del Titolare aggiunto non valido.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del Titolare aggiunto non valido.
```
**Causa**: Il campo **CAP** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Verifica che il CAP sia:
   - Di **5 cifre** esatte
   - Esempio: `10121` (NON `0121` o `10121 `)
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_014: ATTENZIONE ! Città di residenza del Titolare aggiunto non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Città di residenza del Titolare aggiunto non inserita.
```
**Causa**: Il campo **Città/Comune di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Città/Comune di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_020: ATTENZIONE ! Codice Fiscale del Titolare aggiunto non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del Titolare aggiunto non inserito.
```
**Causa**: Il campo **Codice Fiscale** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_021: ATTENZIONE ! Codice Fiscale del Titolare aggiunto non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del Titolare aggiunto non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_028: ATTENZIONE ! Codice Fiscale della Ditta/Società/Ente del Titolare aggiunto non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale della Ditta/Società/Ente del Titolare aggiunto non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_032: ATTENZIONE ! Cognome del Titolare aggiunto non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Cognome del Titolare aggiunto non inserito.
```
**Causa**: Il campo **Cognome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Cognome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_036: ATTENZIONE ! Comune di nascita del Titolare aggiunto non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Comune di nascita del Titolare aggiunto non inserito.
```
**Causa**: Il campo **Comune di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Comune di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_042: ATTENZIONE ! Data di nascita del Titolare aggiunto non valida (gg/mm/aaaa).
**Messaggio completo**:
```
ATTENZIONE ! Data di nascita del Titolare aggiunto non valida (gg/mm/aaaa).
```
**Causa**: Il campo **Data di nascita** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Data di nascita"** (evidenziato con sfondo giallo)
3. Verifica che la data sia:
   - Nel formato `GG/MM/AAAA`
   - Esempio: `01/01/1980`
   - Usa il calendario se disponibile
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_049: ATTENZIONE ! Indirizzo di residenza del Titolare aggiunto non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo di residenza del Titolare aggiunto non inserito.
```
**Causa**: Il campo **Indirizzo (via/piazza)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Indirizzo (via/piazza)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_055: ATTENZIONE ! Indirizzo e-mail certificata del Titolare aggiunto non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata del Titolare aggiunto non valido.
```
**Causa**: Il campo **Email certificata (PEC)** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_063: ATTENZIONE ! Indirizzo e-mail del Titolare aggiunto non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail del Titolare aggiunto non valido.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_072: ATTENZIONE ! Nome del Titolare aggiunto non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Nome del Titolare aggiunto non inserito.
```
**Causa**: Il campo **Nome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Nome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_079: ATTENZIONE ! Numero civico di residenza del Titolare aggiunto non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Numero civico di residenza del Titolare aggiunto non inserito.
```
**Causa**: Il campo **Numero civico** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Numero civico"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_089: ATTENZIONE ! Partita IVA della Ditta/Società/Ente del Titolare aggiunto non valida (11 caratteri numerici).
**Messaggio completo**:
```
ATTENZIONE ! Partita IVA della Ditta/Società/Ente del Titolare aggiunto non valida (11 caratteri numerici).
```
**Causa**: Il campo **Partita IVA** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Partita IVA"** (evidenziato con sfondo giallo)
3. Verifica che la Partita IVA sia:
   - Di **11 cifre** numeriche
   - Solo numeri, nessuna lettera
   - Esempio: `12345678901`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_094: ATTENZIONE ! Provincia di nascita del Titolare aggiunto non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di nascita del Titolare aggiunto non inserita.
```
**Causa**: Il campo **Provincia di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Provincia di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_098: ATTENZIONE ! Provincia di residenza del Titolare aggiunto non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di residenza del Titolare aggiunto non inserita.
```
**Causa**: Il campo **Provincia di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Altri Titolari"**
2. Trova il campo **"Provincia di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

## Dati Professionista
**23 errori in questa categoria**

### ERR_003: ATTENZIONE ! CAP di residenza del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del Professionista non inserito.
```
**Causa**: Il campo **CAP** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_004: ATTENZIONE ! CAP di residenza del Professionista non valido.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del Professionista non valido.
```
**Causa**: Il campo **CAP** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Verifica che il CAP sia:
   - Di **5 cifre** esatte
   - Esempio: `10121` (NON `0121` o `10121 `)
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_013: ATTENZIONE ! Città di residenza del Professionista non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Città di residenza del Professionista non inserita.
```
**Causa**: Il campo **Città/Comune di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Città/Comune di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_018: ATTENZIONE ! Codice Fiscale del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del Professionista non inserito.
```
**Causa**: Il campo **Codice Fiscale** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_019: ATTENZIONE ! Codice Fiscale del Professionista non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del Professionista non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_031: ATTENZIONE ! Cognome del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Cognome del Professionista non inserito.
```
**Causa**: Il campo **Cognome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Cognome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_035: ATTENZIONE ! Comune di nascita del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Comune di nascita del Professionista non inserito.
```
**Causa**: Il campo **Comune di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Comune di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_039: ATTENZIONE ! Data di Nascita del Professionista non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Data di Nascita del Professionista non inserita.
```
**Causa**: Il campo **Data di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Data di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_041: ATTENZIONE ! Data di nascita del Professionista non valida (gg/mm/aaaa).
**Messaggio completo**:
```
ATTENZIONE ! Data di nascita del Professionista non valida (gg/mm/aaaa).
```
**Causa**: Il campo **Data di nascita** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Data di nascita"** (evidenziato con sfondo giallo)
3. Verifica che la data sia:
   - Nel formato `GG/MM/AAAA`
   - Esempio: `01/01/1980`
   - Usa il calendario se disponibile
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_045: ATTENZIONE ! E-mail Certificata del Professionista non inserita.
**Messaggio completo**:
```
ATTENZIONE ! E-mail Certificata del Professionista non inserita.
```
**Causa**: Il campo **Email certificata (PEC)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_046: ATTENZIONE ! E-mail del Professionista non inserita.
**Messaggio completo**:
```
ATTENZIONE ! E-mail del Professionista non inserita.
```
**Causa**: Il campo **Email** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_048: ATTENZIONE ! Indirizzo di residenza del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo di residenza del Professionista non inserito.
```
**Causa**: Il campo **Indirizzo (via/piazza)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Indirizzo (via/piazza)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_053: ATTENZIONE ! Indirizzo e-mail certificata del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata del Professionista non inserito.
```
**Causa**: Il campo **Email certificata (PEC)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_054: ATTENZIONE ! Indirizzo e-mail certificata del Professionista non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata del Professionista non valido.
```
**Causa**: Il campo **Email certificata (PEC)** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_061: ATTENZIONE ! Indirizzo e-mail del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail del Professionista non inserito.
```
**Causa**: Il campo **Email** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_062: ATTENZIONE ! Indirizzo e-mail del Professionista non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail del Professionista non valido.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_071: ATTENZIONE ! Nome del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Nome del Professionista non inserito.
```
**Causa**: Il campo **Nome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Nome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_076: ATTENZIONE ! Non sono stati salvati i dati del Professionista.
**Messaggio completo**:
```
ATTENZIONE ! Non sono stati salvati i dati del Professionista.
```
**Causa**: I dati non sono stati salvati correttamente. Possibile timeout o errore di connessione.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **""** (evidenziato con sfondo giallo)
3. Verifica la connessione internet
4. Ricompila i dati nella sezione
5. Clicca **"Salva"** e attendi conferma verde
6. Se persiste, contatta [assistenza](assistenza-tecnica.html)

---

### ERR_078: ATTENZIONE ! Numero civico di residenza del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Numero civico di residenza del Professionista non inserito.
```
**Causa**: Il campo **Numero civico** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Numero civico"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_092: ATTENZIONE ! Provincia di nascita del Professionista non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di nascita del Professionista non inserita.
```
**Causa**: Il campo **Provincia di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Provincia di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_093: ATTENZIONE ! Provincia di nascita del Professionista non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di nascita del Professionista non inserito.
```
**Causa**: Il campo **Provincia di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Provincia di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_097: ATTENZIONE ! Provincia di residenza del Professionista non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di residenza del Professionista non inserita.
```
**Causa**: Il campo **Provincia di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Provincia di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_101: ATTENZIONE ! Ruolo del Professionista non selezionato.
**Messaggio completo**:
```
ATTENZIONE ! Ruolo del Professionista non selezionato.
```
**Causa**: Verifica il campo **Ruolo professionista**.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Tecnici incaricati"**
2. Trova il campo **"Ruolo professionista"** (evidenziato con sfondo giallo)

---

## Dati Ditta/Società
**4 errori in questa categoria**

### ERR_029: ATTENZIONE ! Codice Fiscale della Ditta/Società/Ente non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale della Ditta/Società/Ente non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Ditta/Società"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_059: ATTENZIONE ! Indirizzo e-mail certificata della Ditta del Titolare non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata della Ditta del Titolare non valido.
```
**Causa**: Il campo **Email certificata (PEC)** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_067: ATTENZIONE ! Indirizzo e-mail della Ditta del Titolare non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail della Ditta del Titolare non valido.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Titolare"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_090: ATTENZIONE ! Partita IVA della Ditta/Società/Ente non valida (11 caratteri numerici).
**Messaggio completo**:
```
ATTENZIONE ! Partita IVA della Ditta/Società/Ente non valida (11 caratteri numerici).
```
**Causa**: Il campo **Partita IVA** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Ditta/Società"**
2. Trova il campo **"Partita IVA"** (evidenziato con sfondo giallo)
3. Verifica che la Partita IVA sia:
   - Di **11 cifre** numeriche
   - Solo numeri, nessuna lettera
   - Esempio: `12345678901`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

## Dati Procuratore/Delegato
**3 errori in questa categoria**

### ERR_017: ATTENZIONE ! Codice Fiscale del Procuratore/Delegato non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del Procuratore/Delegato non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Procuratore/Delegato"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_052: ATTENZIONE ! Indirizzo e-mail certificata del Procuratore/Delegato non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata del Procuratore/Delegato non valido.
```
**Causa**: Il campo **Email certificata (PEC)** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Procuratore/Delegato"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_060: ATTENZIONE ! Indirizzo e-mail del Procuratore/Delegato non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail del Procuratore/Delegato non valido.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Dati Procuratore/Delegato"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

## Imprese Esecutrici
**11 errori in questa categoria**

### ERR_001: ATTENZIONE ! CAP della sede impresa non inserito.
**Messaggio completo**:
```
ATTENZIONE ! CAP della sede impresa non inserito.
```
**Causa**: Il campo **CAP** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_002: ATTENZIONE ! CAP della sede impresa non valido.
**Messaggio completo**:
```
ATTENZIONE ! CAP della sede impresa non valido.
```
**Causa**: Il campo **CAP** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Verifica che il CAP sia:
   - Di **5 cifre** esatte
   - Esempio: `10121` (NON `0121` o `10121 `)
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_012: ATTENZIONE ! Città della sede impresa non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Città della sede impresa non inserita.
```
**Causa**: Il campo **Città/Comune di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Città/Comune di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_026: ATTENZIONE ! Codice Fiscale dell'impresa non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale dell'impresa non inserito.
```
**Causa**: Il campo **Codice Fiscale** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_027: ATTENZIONE ! Codice Fiscale dell'impresa non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale dell'impresa non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_030: ATTENZIONE ! Codice impresa cassa edile non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Codice impresa cassa edile non inserita.
```
**Causa**: Il campo **** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **""** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_047: ATTENZIONE ! Indirizzo della sede impresa non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo della sede impresa non inserito.
```
**Causa**: Il campo **Indirizzo (via/piazza)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Indirizzo (via/piazza)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_077: ATTENZIONE ! Numero civico della sede impresa non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Numero civico della sede impresa non inserito.
```
**Causa**: Il campo **Numero civico** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Numero civico"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_087: ATTENZIONE ! Partita IVA dell'impresa non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Partita IVA dell'impresa non inserita.
```
**Causa**: Il campo **Partita IVA** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Partita IVA"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_088: ATTENZIONE ! Partita IVA dell'impresa non valida (11 caratteri numerici).
**Messaggio completo**:
```
ATTENZIONE ! Partita IVA dell'impresa non valida (11 caratteri numerici).
```
**Causa**: Il campo **Partita IVA** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Partita IVA"** (evidenziato con sfondo giallo)
3. Verifica che la Partita IVA sia:
   - Di **11 cifre** numeriche
   - Solo numeri, nessuna lettera
   - Esempio: `12345678901`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_091: ATTENZIONE ! Provincia della sede impresa non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia della sede impresa non inserita.
```
**Causa**: Il campo **Provincia di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese esecutrici"**
2. Trova il campo **"Provincia di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

## Legale Rappresentante Impresa
**18 errori in questa categoria**

### ERR_009: ATTENZIONE ! CAP di residenza del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del legale rappresentante non inserito.
```
**Causa**: Il campo **CAP** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_010: ATTENZIONE ! CAP di residenza del legale rappresentante non valido.
**Messaggio completo**:
```
ATTENZIONE ! CAP di residenza del legale rappresentante non valido.
```
**Causa**: Il campo **CAP** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"CAP"** (evidenziato con sfondo giallo)
3. Verifica che il CAP sia:
   - Di **5 cifre** esatte
   - Esempio: `10121` (NON `0121` o `10121 `)
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_016: ATTENZIONE ! Città di residenza del legale rappresentante non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Città di residenza del legale rappresentante non inserita.
```
**Causa**: Il campo **Città/Comune di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Città/Comune di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_024: ATTENZIONE ! Codice Fiscale del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del legale rappresentante non inserito.
```
**Causa**: Il campo **Codice Fiscale** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_025: ATTENZIONE ! Codice Fiscale del legale rappresentante non valido.
**Messaggio completo**:
```
ATTENZIONE ! Codice Fiscale del legale rappresentante non valido.
```
**Causa**: Il campo **Codice Fiscale** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Codice Fiscale"** (evidenziato con sfondo giallo)
3. Verifica che il Codice Fiscale sia:
   - Di **16 caratteri** alfanumerici
   - Lettere **MAIUSCOLE**
   - Senza spazi o caratteri speciali
   - Esempio: `RSSMRA80A01H501U`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_034: ATTENZIONE ! Cognome del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Cognome del legale rappresentante non inserito.
```
**Causa**: Il campo **Cognome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Cognome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_038: ATTENZIONE ! Comune di nascita del legale rappresentante non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Comune di nascita del legale rappresentante non inserita.
```
**Causa**: Il campo **Comune di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Comune di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_044: ATTENZIONE ! Data di nascita del legale rappresentante non valida (gg/mm/aaaa).
**Messaggio completo**:
```
ATTENZIONE ! Data di nascita del legale rappresentante non valida (gg/mm/aaaa).
```
**Causa**: Il campo **Data di nascita** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Data di nascita"** (evidenziato con sfondo giallo)
3. Verifica che la data sia:
   - Nel formato `GG/MM/AAAA`
   - Esempio: `01/01/1980`
   - Usa il calendario se disponibile
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_051: ATTENZIONE ! Indirizzo di residenza del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo di residenza del legale rappresentante non inserito.
```
**Causa**: Il campo **Indirizzo (via/piazza)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Indirizzo (via/piazza)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_057: ATTENZIONE ! Indirizzo e-mail certificata del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata del legale rappresentante non inserito.
```
**Causa**: Il campo **Email certificata (PEC)** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_058: ATTENZIONE ! Indirizzo e-mail certificata del legale rappresentante non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail certificata del legale rappresentante non valido.
```
**Causa**: Il campo **Email certificata (PEC)** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Email certificata (PEC)"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_065: ATTENZIONE ! Indirizzo e-mail del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail del legale rappresentante non inserito.
```
**Causa**: Il campo **Email** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_066: ATTENZIONE ! Indirizzo e-mail del legale rappresentante non valido.
**Messaggio completo**:
```
ATTENZIONE ! Indirizzo e-mail del legale rappresentante non valido.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Email"** (evidenziato con sfondo giallo)
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_074: ATTENZIONE ! Nome del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Nome del legale rappresentante non inserito.
```
**Causa**: Il campo **Nome** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Nome"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_075: ATTENZIONE ! Non sono stati salvati i dati del Legale rappresentante.
**Messaggio completo**:
```
ATTENZIONE ! Non sono stati salvati i dati del Legale rappresentante.
```
**Causa**: I dati non sono stati salvati correttamente. Possibile timeout o errore di connessione.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **""** (evidenziato con sfondo giallo)
3. Verifica la connessione internet
4. Ricompila i dati nella sezione
5. Clicca **"Salva"** e attendi conferma verde
6. Se persiste, contatta [assistenza](assistenza-tecnica.html)

---

### ERR_081: ATTENZIONE ! Numero civico di residenza del legale rappresentante non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Numero civico di residenza del legale rappresentante non inserito.
```
**Causa**: Il campo **Numero civico** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Numero civico"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_096: ATTENZIONE ! Provincia di nascita del legale rappresentante non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di nascita del legale rappresentante non inserita.
```
**Causa**: Il campo **Provincia di nascita** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Provincia di nascita"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_100: ATTENZIONE ! Provincia di residenza del legale rappresentante non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Provincia di residenza del legale rappresentante non inserita.
```
**Causa**: Il campo **Provincia di residenza** è obbligatorio ma vuoto.

**Soluzione**:
1. Vai alla sezione **"Soggetti coinvolti → Imprese → Legale rappresentante"**
2. Trova il campo **"Provincia di residenza"** (evidenziato con sfondo giallo)
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

## Email e PEC Tecnici
**4 errori in questa categoria**

### ERR_083: ATTENZIONE ! PEC del direttore dei lavori architettonici non valida.
**Messaggio completo**:
```
ATTENZIONE ! PEC del direttore dei lavori architettonici non valida.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_084: ATTENZIONE ! PEC del direttore dei lavori strutturali non valida.
**Messaggio completo**:
```
ATTENZIONE ! PEC del direttore dei lavori strutturali non valida.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_085: ATTENZIONE ! PEC del progettista delle opere architettoniche non valida.
**Messaggio completo**:
```
ATTENZIONE ! PEC del progettista delle opere architettoniche non valida.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

### ERR_086: ATTENZIONE ! PEC del progettista delle strutture non valida.
**Messaggio completo**:
```
ATTENZIONE ! PEC del progettista delle strutture non valida.
```
**Causa**: Il campo **Email** contiene un valore non valido o nel formato sbagliato.

**Soluzione**:
3. Verifica che l'email sia:
   - Nel formato `nome@dominio.ext`
   - Senza spazi o caratteri speciali
   - Esempio: `mario.rossi@example.com`
4. Correggi il valore
5. Clicca **"Salva"**
6. Riprova **"Valida e Salva"**

---

## Dati Catastali
**1 errori in questa categoria**

### ERR_069: ATTENZIONE ! Inserire Foglio e Particella dell'Unità Immobiliare.
**Messaggio completo**:
```
ATTENZIONE ! Inserire Foglio e Particella dell'Unità Immobiliare.
```
**Causa**: Verifica il campo **Foglio e Particella catastali**.

**Soluzione**:

---

## Codice Fiscale
**1 errori in questa categoria**

### ERR_068: ATTENZIONE ! Inserire Codice Fiscale del beneficiario/a dell'Unità Immobiliare.
**Messaggio completo**:
```
ATTENZIONE ! Inserire Codice Fiscale del beneficiario/a dell'Unità Immobiliare.
```
**Causa**: Verifica il campo **Codice Fiscale**.

**Soluzione**:

---

## Marca da Bollo
**1 errori in questa categoria**

### ERR_082: ATTENZIONE ! Numero dello scontrino della marca da bollo non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Numero dello scontrino della marca da bollo non inserito.
```
**Causa**: Il campo **Numero scontrino marca da bollo** è obbligatorio ma vuoto.

**Soluzione**:
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

## Errori Tecnici di Sistema
**9 errori in questa categoria**

### ERR_011: ATTENZIONE ! Campo obbligatorio non inserito.
**Messaggio completo**:
```
ATTENZIONE ! Campo obbligatorio non inserito.
```
**Causa**: Il campo **** è obbligatorio ma vuoto.

**Soluzione**:
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_070: ATTENZIONE ! Inserire Nominativo del beneficiario/a dell'Unità Immobiliare.
**Messaggio completo**:
```
ATTENZIONE ! Inserire Nominativo del beneficiario/a dell'Unità Immobiliare.
```
**Causa**: Verifica il campo ****.

**Soluzione**:

---

### ERR_102: ATTENZIONE ! Sede della cassa edile non inserita.
**Messaggio completo**:
```
ATTENZIONE ! Sede della cassa edile non inserita.
```
**Causa**: Il campo **** è obbligatorio ma vuoto.

**Soluzione**:
3. Inserisci il valore richiesto
4. Clicca **"Salva"**
5. Riprova **"Valida e Salva"**

---

### ERR_103: ATTENZIONE: Errore durante il salvataggio della pratica. Il file XML creato risulta Nothing.
**Messaggio completo**:
```
ATTENZIONE: Errore durante il salvataggio della pratica. Il file XML creato risulta Nothing.
```
**Causa**: Verifica il campo ****.

**Soluzione**:

---

### ERR_104: ATTENZIONE: Parametro 'HfChiavePratica' non impostato.
**Messaggio completo**:
```
ATTENZIONE: Parametro 'HfChiavePratica' non impostato.
```
**Causa**: Errore tecnico interno. Parametro di sistema mancante.

**Soluzione**:
1. **Ricarica la pagina** (F5)
2. Se persiste, **esci e riaccedi**
3. Se continua, contatta [assistenza](assistenza-tecnica.html) con screenshot

---

### ERR_105: ATTENZIONE: Parametro 'HfIDPratica' non impostato.
**Messaggio completo**:
```
ATTENZIONE: Parametro 'HfIDPratica' non impostato.
```
**Causa**: Errore tecnico interno. Parametro di sistema mancante.

**Soluzione**:
1. **Ricarica la pagina** (F5)
2. Se persiste, **esci e riaccedi**
3. Se continua, contatta [assistenza](assistenza-tecnica.html) con screenshot

---

### ERR_106: ATTENZIONE: Parametro 'HfQualificazioneIntervento' non impostato.
**Messaggio completo**:
```
ATTENZIONE: Parametro 'HfQualificazioneIntervento' non impostato.
```
**Causa**: Errore tecnico interno. Parametro di sistema mancante.

**Soluzione**:
1. **Ricarica la pagina** (F5)
2. Se persiste, **esci e riaccedi**
3. Se continua, contatta [assistenza](assistenza-tecnica.html) con screenshot

---

### ERR_107: ATTENZIONE: Parametro 'HfTipoIstanza' non impostato.
**Messaggio completo**:
```
ATTENZIONE: Parametro 'HfTipoIstanza' non impostato.
```
**Causa**: Errore tecnico interno. Parametro di sistema mancante.

**Soluzione**:
1. **Ricarica la pagina** (F5)
2. Se persiste, **esci e riaccedi**
3. Se continua, contatta [assistenza](assistenza-tecnica.html) con screenshot

---

### ERR_108: ATTENZIONE: Parametro 'PostBack' non impostato.
**Messaggio completo**:
```
ATTENZIONE: Parametro 'PostBack' non impostato.
```
**Causa**: Errore tecnico interno. Parametro di sistema mancante.

**Soluzione**:
1. **Ricarica la pagina** (F5)
2. Se persiste, **esci e riaccedi**
3. Se continua, contatta [assistenza](assistenza-tecnica.html) con screenshot

---


## Tabella riferimento rapido

Tutti i 108 errori in formato tabellare per ricerca veloce.

| Codice | Messaggio | Categoria |
|--------|-----------|-----------|
| ERR_001 | ATTENZIONE ! CAP della sede impresa non inserito. | Imprese Esecutrici |
| ERR_002 | ATTENZIONE ! CAP della sede impresa non valido. | Imprese Esecutrici |
| ERR_003 | ATTENZIONE ! CAP di residenza del Professionista non inserito. | Dati Professionista |
| ERR_004 | ATTENZIONE ! CAP di residenza del Professionista non valido. | Dati Professionista |
| ERR_005 | ATTENZIONE ! CAP di residenza del Titolare aggiunto non inserito. | Altri Titolari (Co-intestatari) |
| ERR_006 | ATTENZIONE ! CAP di residenza del Titolare aggiunto non valido. | Altri Titolari (Co-intestatari) |
| ERR_007 | ATTENZIONE ! CAP di residenza del Titolare non inserito. | Dati Titolare |
| ERR_008 | ATTENZIONE ! CAP di residenza del Titolare non valido. | Dati Titolare |
| ERR_009 | ATTENZIONE ! CAP di residenza del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_010 | ATTENZIONE ! CAP di residenza del legale rappresentante non valido. | Legale Rappresentante Impresa |
| ERR_011 | ATTENZIONE ! Campo obbligatorio non inserito. | Errori Tecnici di Sistema |
| ERR_012 | ATTENZIONE ! Città della sede impresa non inserita. | Imprese Esecutrici |
| ERR_013 | ATTENZIONE ! Città di residenza del Professionista non inserita. | Dati Professionista |
| ERR_014 | ATTENZIONE ! Città di residenza del Titolare aggiunto non inserita. | Altri Titolari (Co-intestatari) |
| ERR_015 | ATTENZIONE ! Città di residenza del Titolare non inserita. | Dati Titolare |
| ERR_016 | ATTENZIONE ! Città di residenza del legale rappresentante non inserita. | Legale Rappresentante Impresa |
| ERR_017 | ATTENZIONE ! Codice Fiscale del Procuratore/Delegato non valido. | Dati Procuratore/Delegato |
| ERR_018 | ATTENZIONE ! Codice Fiscale del Professionista non inserito. | Dati Professionista |
| ERR_019 | ATTENZIONE ! Codice Fiscale del Professionista non valido. | Dati Professionista |
| ERR_020 | ATTENZIONE ! Codice Fiscale del Titolare aggiunto non inserito. | Altri Titolari (Co-intestatari) |
| ERR_021 | ATTENZIONE ! Codice Fiscale del Titolare aggiunto non valido. | Altri Titolari (Co-intestatari) |
| ERR_022 | ATTENZIONE ! Codice Fiscale del Titolare non inserito. | Dati Titolare |
| ERR_023 | ATTENZIONE ! Codice Fiscale del Titolare non valido. | Dati Titolare |
| ERR_024 | ATTENZIONE ! Codice Fiscale del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_025 | ATTENZIONE ! Codice Fiscale del legale rappresentante non valido. | Legale Rappresentante Impresa |
| ERR_026 | ATTENZIONE ! Codice Fiscale dell'impresa non inserito. | Imprese Esecutrici |
| ERR_027 | ATTENZIONE ! Codice Fiscale dell'impresa non valido. | Imprese Esecutrici |
| ERR_028 | ATTENZIONE ! Codice Fiscale della Ditta/Società/Ente del Titolare aggiunto non valido. | Altri Titolari (Co-intestatari) |
| ERR_029 | ATTENZIONE ! Codice Fiscale della Ditta/Società/Ente non valido. | Dati Ditta/Società |
| ERR_030 | ATTENZIONE ! Codice impresa cassa edile non inserita. | Imprese Esecutrici |
| ERR_031 | ATTENZIONE ! Cognome del Professionista non inserito. | Dati Professionista |
| ERR_032 | ATTENZIONE ! Cognome del Titolare aggiunto non inserito. | Altri Titolari (Co-intestatari) |
| ERR_033 | ATTENZIONE ! Cognome del Titolare non inserito. | Dati Titolare |
| ERR_034 | ATTENZIONE ! Cognome del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_035 | ATTENZIONE ! Comune di nascita del Professionista non inserito. | Dati Professionista |
| ERR_036 | ATTENZIONE ! Comune di nascita del Titolare aggiunto non inserito. | Altri Titolari (Co-intestatari) |
| ERR_037 | ATTENZIONE ! Comune di nascita del Titolare non inserito. | Dati Titolare |
| ERR_038 | ATTENZIONE ! Comune di nascita del legale rappresentante non inserita. | Legale Rappresentante Impresa |
| ERR_039 | ATTENZIONE ! Data di Nascita del Professionista non inserita. | Dati Professionista |
| ERR_040 | ATTENZIONE ! Data di Nascita del Titolare non inserita. | Dati Titolare |
| ERR_041 | ATTENZIONE ! Data di nascita del Professionista non valida (gg/mm/aaaa). | Dati Professionista |
| ERR_042 | ATTENZIONE ! Data di nascita del Titolare aggiunto non valida (gg/mm/aaaa). | Altri Titolari (Co-intestatari) |
| ERR_043 | ATTENZIONE ! Data di nascita del Titolare non valida (gg/mm/aaaa). | Dati Titolare |
| ERR_044 | ATTENZIONE ! Data di nascita del legale rappresentante non valida (gg/mm/aaaa). | Legale Rappresentante Impresa |
| ERR_045 | ATTENZIONE ! E-mail Certificata del Professionista non inserita. | Dati Professionista |
| ERR_046 | ATTENZIONE ! E-mail del Professionista non inserita. | Dati Professionista |
| ERR_047 | ATTENZIONE ! Indirizzo della sede impresa non inserito. | Imprese Esecutrici |
| ERR_048 | ATTENZIONE ! Indirizzo di residenza del Professionista non inserito. | Dati Professionista |
| ERR_049 | ATTENZIONE ! Indirizzo di residenza del Titolare aggiunto non inserito. | Altri Titolari (Co-intestatari) |
| ERR_050 | ATTENZIONE ! Indirizzo di residenza del Titolare non inserito. | Dati Titolare |
| ERR_051 | ATTENZIONE ! Indirizzo di residenza del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_052 | ATTENZIONE ! Indirizzo e-mail certificata del Procuratore/Delegato non valido. | Dati Procuratore/Delegato |
| ERR_053 | ATTENZIONE ! Indirizzo e-mail certificata del Professionista non inserito. | Dati Professionista |
| ERR_054 | ATTENZIONE ! Indirizzo e-mail certificata del Professionista non valido. | Dati Professionista |
| ERR_055 | ATTENZIONE ! Indirizzo e-mail certificata del Titolare aggiunto non valido. | Altri Titolari (Co-intestatari) |
| ERR_056 | ATTENZIONE ! Indirizzo e-mail certificata del Titolare non valido. | Dati Titolare |
| ERR_057 | ATTENZIONE ! Indirizzo e-mail certificata del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_058 | ATTENZIONE ! Indirizzo e-mail certificata del legale rappresentante non valido. | Legale Rappresentante Impresa |
| ERR_059 | ATTENZIONE ! Indirizzo e-mail certificata della Ditta del Titolare non valido. | Dati Ditta/Società |
| ERR_060 | ATTENZIONE ! Indirizzo e-mail del Procuratore/Delegato non valido. | Dati Procuratore/Delegato |
| ERR_061 | ATTENZIONE ! Indirizzo e-mail del Professionista non inserito. | Dati Professionista |
| ERR_062 | ATTENZIONE ! Indirizzo e-mail del Professionista non valido. | Dati Professionista |
| ERR_063 | ATTENZIONE ! Indirizzo e-mail del Titolare aggiunto non valido. | Altri Titolari (Co-intestatari) |
| ERR_064 | ATTENZIONE ! Indirizzo e-mail del Titolare non valido. | Dati Titolare |
| ERR_065 | ATTENZIONE ! Indirizzo e-mail del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_066 | ATTENZIONE ! Indirizzo e-mail del legale rappresentante non valido. | Legale Rappresentante Impresa |
| ERR_067 | ATTENZIONE ! Indirizzo e-mail della Ditta del Titolare non valido. | Dati Ditta/Società |
| ERR_068 | ATTENZIONE ! Inserire Codice Fiscale del beneficiario/a dell'Unità Immobiliare. | Codice Fiscale |
| ERR_069 | ATTENZIONE ! Inserire Foglio e Particella dell'Unità Immobiliare. | Dati Catastali |
| ERR_070 | ATTENZIONE ! Inserire Nominativo del beneficiario/a dell'Unità Immobiliare. | Errori Tecnici di Sistema |
| ERR_071 | ATTENZIONE ! Nome del Professionista non inserito. | Dati Professionista |
| ERR_072 | ATTENZIONE ! Nome del Titolare aggiunto non inserito. | Altri Titolari (Co-intestatari) |
| ERR_073 | ATTENZIONE ! Nome del Titolare non inserito. | Dati Titolare |
| ERR_074 | ATTENZIONE ! Nome del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_075 | ATTENZIONE ! Non sono stati salvati i dati del Legale rappresentante. | Legale Rappresentante Impresa |
| ERR_076 | ATTENZIONE ! Non sono stati salvati i dati del Professionista. | Dati Professionista |
| ERR_077 | ATTENZIONE ! Numero civico della sede impresa non inserito. | Imprese Esecutrici |
| ERR_078 | ATTENZIONE ! Numero civico di residenza del Professionista non inserito. | Dati Professionista |
| ERR_079 | ATTENZIONE ! Numero civico di residenza del Titolare aggiunto non inserito. | Altri Titolari (Co-intestatari) |
| ERR_080 | ATTENZIONE ! Numero civico di residenza del Titolare non inserito. | Dati Titolare |
| ERR_081 | ATTENZIONE ! Numero civico di residenza del legale rappresentante non inserito. | Legale Rappresentante Impresa |
| ERR_082 | ATTENZIONE ! Numero dello scontrino della marca da bollo non inserito. | Marca da Bollo |
| ERR_083 | ATTENZIONE ! PEC del direttore dei lavori architettonici non valida. | Email e PEC Tecnici |
| ERR_084 | ATTENZIONE ! PEC del direttore dei lavori strutturali non valida. | Email e PEC Tecnici |
| ERR_085 | ATTENZIONE ! PEC del progettista delle opere architettoniche non valida. | Email e PEC Tecnici |
| ERR_086 | ATTENZIONE ! PEC del progettista delle strutture non valida. | Email e PEC Tecnici |
| ERR_087 | ATTENZIONE ! Partita IVA dell'impresa non inserita. | Imprese Esecutrici |
| ERR_088 | ATTENZIONE ! Partita IVA dell'impresa non valida (11 caratteri numerici). | Imprese Esecutrici |
| ERR_089 | ATTENZIONE ! Partita IVA della Ditta/Società/Ente del Titolare aggiunto non valida (11 caratteri numerici). | Altri Titolari (Co-intestatari) |
| ERR_090 | ATTENZIONE ! Partita IVA della Ditta/Società/Ente non valida (11 caratteri numerici). | Dati Ditta/Società |
| ERR_091 | ATTENZIONE ! Provincia della sede impresa non inserita. | Imprese Esecutrici |
| ERR_092 | ATTENZIONE ! Provincia di nascita del Professionista non inserita. | Dati Professionista |
| ERR_093 | ATTENZIONE ! Provincia di nascita del Professionista non inserito. | Dati Professionista |
| ERR_094 | ATTENZIONE ! Provincia di nascita del Titolare aggiunto non inserita. | Altri Titolari (Co-intestatari) |
| ERR_095 | ATTENZIONE ! Provincia di nascita del Titolare non inserita. | Dati Titolare |
| ERR_096 | ATTENZIONE ! Provincia di nascita del legale rappresentante non inserita. | Legale Rappresentante Impresa |
| ERR_097 | ATTENZIONE ! Provincia di residenza del Professionista non inserita. | Dati Professionista |
| ERR_098 | ATTENZIONE ! Provincia di residenza del Titolare aggiunto non inserita. | Altri Titolari (Co-intestatari) |
| ERR_099 | ATTENZIONE ! Provincia di residenza del Titolare non inserita. | Dati Titolare |
| ERR_100 | ATTENZIONE ! Provincia di residenza del legale rappresentante non inserita. | Legale Rappresentante Impresa |
| ERR_101 | ATTENZIONE ! Ruolo del Professionista non selezionato. | Dati Professionista |
| ERR_102 | ATTENZIONE ! Sede della cassa edile non inserita. | Errori Tecnici di Sistema |
| ERR_103 | ATTENZIONE: Errore durante il salvataggio della pratica. Il file XML creato risulta Nothing. | Errori Tecnici di Sistema |
| ERR_104 | ATTENZIONE: Parametro 'HfChiavePratica' non impostato. | Errori Tecnici di Sistema |
| ERR_105 | ATTENZIONE: Parametro 'HfIDPratica' non impostato. | Errori Tecnici di Sistema |
| ERR_106 | ATTENZIONE: Parametro 'HfQualificazioneIntervento' non impostato. | Errori Tecnici di Sistema |
| ERR_107 | ATTENZIONE: Parametro 'HfTipoIstanza' non impostato. | Errori Tecnici di Sistema |
| ERR_108 | ATTENZIONE: Parametro 'PostBack' non impostato. | Errori Tecnici di Sistema |


---

## Consigli generali

### Prima di validare ✅

- Compila **tutte le sezioni** dall'inizio alla fine
- Verifica **campi gialli** (obbligatori) siano compilati
- Controlla **formato dati** (CF 16 caratteri, P.IVA 11 cifre, CAP 5 cifre)
- Usa **Anagrafica** per autocompilare dati ricorrenti

### Se ricevi errori ⚠️

- **Leggi attentamente** il messaggio
- **Cerca il codice** ERR_XXX in questa pagina (Ctrl+F)
- **Segui la soluzione** passo-passo
- **Salva** dopo ogni correzione
- **Riprova validazione**

### Errori comuni 🔍

I 5 errori più frequenti:

1. **ERR_022/ERR_023** - Codice Fiscale Titolare mancante/errato
2. **ERR_033/ERR_073** - Cognome/Nome Titolare mancante
3. **ERR_007/ERR_008** - CAP Titolare mancante/errato
4. **ERR_064** - Email Titolare non valida
5. **ERR_050/ERR_080** - Indirizzo/Civico Titolare mancante

---

## Non trovi l'errore? 🆘

Se il messaggio che vedi **non è in questa lista**:

1. Controlla di aver copiato il **messaggio esatto**
2. Consulta [Troubleshooting](troubleshooting.html) per problemi tecnici
3. Consulta [FAQ](faq.html) per domande generali
4. Contatta [Assistenza tecnica](assistenza-tecnica.html) con:
   - Messaggio errore completo
   - Numero pratica
   - Screenshot dell'errore

---

## Prossimi passi

- [Compilare un'istanza](compilare-istanza.html) - Guida completa alla compilazione
- [Troubleshooting](troubleshooting.html) - Problemi tecnici comuni
- [FAQ](faq.html) - Domande frequenti

---

**Ultima revisione**: Marzo 2026  
**Errori documentati**: 108  
**Fonte**: Codice validazione GeoTecSUE
