# Laboratorio-Ospedaliero
Il progetto si chiama organizzazione del laboratorio ospedaliero. Un applicazione software sviluppata in Python che permette la gestione delle operazioni di prenotazione tramite CUP e l'uso dei servizi ambulatoriali. 

All'interno troviamo laboratori.CSV che è il 'database', contiene i dati; Le varie classi che sono strutturate per gestire l'interfaccia: cardiology.py | ultrasound.py | managementLaboratory.py | laboratory.py | radiology.py. Utilizzato il diagramma UML (diagramma di classi lab.drawio) per organizzare al meglio i dati e crea un'interfaccia grafica ordinata. Per ultima troviamo l'interfaccia grafica del laboratorio (InterfaceLabb.py), che permette all'utente di interagire con l'applicazione tramite dei pulsanti: 

Pulsante di inserimento che contine: il codice identificativo del laboratorio, il nome del laboratorio, il dipartimento del laboratorio, il medico responsabile del laboratorio, l'attrezzatura utilizzata e la disponibilità per usarla.
- Controllo sul codice identificativo del laboratorio, possono essere inseriti solo numeri. Ti da errore se inserisci un campo vuoto o con lettere.
- Controllo della disponibilità del laboratorio con avviso se il laboratorio è disponibile o no nella GUI.

Pulsante di modifica: troviamo gli stessi campi dell'inserimento, ma nel caso abbiamo sbagliato a compilarli qua si possono modificare, ad esempio, la finestra di un dipartimento o il nome della persona responsabile, verrà modificati nella tabella con il nuovo nome e il nuovo dipartimento sia nel database sia nell'interfaccia.

Pulsante di ricerca: all'interno troverai la ricerca per codice identificativo o per la specializzazione per trovare il laboratorio d'interesse.

Pulsante di eliminazione: selezionando un qualsiasi laboratorio della tabella poi doppioclick su elimina, si eliminerà il laboratorio nel database e nell'interfaccia. 

Pulsante di visualizzazione: Cliccando il pulsante visualizza, visioni tutte le colonne e righe del database (CSV).

Le librerie utilizzate sono: tkinter, csv e varie liberità derivate dalle classi per arricchirle 

Miglioramenti o funzioni da aggiungere in futuro: 
-Migliorare la ricerca con una finestra simile a quella di Google, con la 'finestra suggerita in tempo reale' quando cerchi qualcosa;
-Cancellazione con un solo clic; 
-Aggiunta di grafica di qualità superiore;
-Implementazione Database relazionale (come SQLite).

Video demo su YT:  [https://youtu.be/HrFPr8zUbO](https://youtu.be/HrFPr8zUbOE?si=AOdLAaNasqXzAO42)
