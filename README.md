# Clyf - Serious Game

![clyf](https://user-images.githubusercontent.com/78272736/206232503-3be3ab33-d260-41a0-a4c3-bd21e64bc04d.png)


## Roadmap 
**Martedì 6 Dicembre**
1. Realizzato schema ER
2. Ipotizzata prima versione UI (prima schermata app, palette colori, stile)
3. Ipotizzata prima versione struttura progetto
4. Selezione nel nostro stack di *Firebase* per auth e db 
5. Creato nuovo progetto in Android Studio
6. Implementazione *Firebase* su progetto Android Studio
7. Implementata prima versione di Login e Registrazione con annessa UI (*User Interface non definitiva, propedeutica al testing*)
8. Testing di Login e Registrazione
9. Code Refactoring di gruppo
10. Inserimento di commenti nel codice
11. Commit e push

**Mercoledì 7 Dicembre**
1. Ipotizzato *Firestore Firebase* come db
2. Collegato progetto Android Studio a *Firebase Firestore*
3. Realizzata UI per fase di Accesso e Registrazione
4. Testing di salvataggio dati su *Firestore* (Test riuscito)
5. Collegamento Firestore a salvataggio utente in fase di registrazione
6. Inizio build di interfaccia app per accesso "admin" (predisposizione popup e tasti CRUD)
7. *Create* testato e funzionante
8. Testing
9. Commit e push

**Giovedì 8 Dicembre**
1. Connessione tra varie UI
2. Testing
3. Commit e push

**Venerdì 9 Dicembre**
1. Implementazione CRUD (Create)
2. Ideazione modify CRUD (Update)
3. Creazione popup per modifica (Update)

**Lunedì 12 Dicembre** 
1. Implementazione modify CRUD (Update)
2. Implementazione delete CRUD (Delete)
3. Ulteriore implementazione create - add per aggiungere singoli elementi (Create)
4. Creazione tasto "esci" per tornare a pagina inziale app
5. Testing

**Martedì 13 Dicembre** 
1. Implementazione e predisposizione UI per stampa domande 
2. Bug fix 
3. Testing su app globale 
4. Implementazione tasto "feature" per aggiornamento stampa domande 

**Mercoledì 14 Dicembre** 
1. Test CREATE
2. Test READ
3. Test UPDATE
4. Test DELETE
5. Collegamento crud e predisposizione ad interfaccia realizzata
6. Testing su app globale (Conferma funzionamento totale CRUD)
7. Bug fix
8. Code Refactoring 
9. Dev talk 
10. Commit e push 

## Code Rules

- Data la scelta della metodologia RAD, si fa commit solo se non sono presenti errori nel codice e se è tutto debitamente commentato. La revisione del codice è necessaria: in primo luogo, tutti commettono errori e in secondo luogo, tutti possono trovarne. Assicurarsi che non venga distribuito alcun codice che non sia stato letto da almeno una persona oltre al dev che l'ha scritto (*meglio da più dev assieme*).
- Il commento o ogni blocco di commenti deve essere sempre firmato dalle iniziali del dev come nell'esempio seguente (*s per Simone, f per Filippo, j per Jasmine, g per Giulia*)
 > // Testo del commento - S

- Ogni commit dovrà presentare il nome del dev e descrivere ciò che è stato fatto

- I nomi delle variabili, delle costanti e delle funzioni saranno scritti in inglese e saranno nomi descrittivi
- I nomi di variabili, costanti e funzioni saranno scritti in camelCase
- Commentare ogni variabile e costante sulla stessa riga, descrivendola.
- Le variabili booleane per i controlli avranno la seguente nomenclatura: checkNomeDelControllo
- Documentare al meglio il codice al termine di ogni giornata lavorativa 


## Other Team Rules
- Sono previste riunioni frequenti per verificare lo stato di avanzamento del codice
- Qualità e funzionalità sono in primo piano: meglio meno, ma fatto bene. 
- Chiedere aiuto non è un reato
- Il codice è del team, il risultato è del team, i problemi sono del team.
- Scrivi codice che tutti possano leggere, anche dev esterni al gruppo. Se non si capisce, modifica.


