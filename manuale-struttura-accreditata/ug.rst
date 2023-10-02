Inserimento istanza di conciliazione (Modello UG, SMA e VSP)
============================================================

In base ai disservizi selezionati e agli operatori coinvolti l'istanza di conciliazione potrà seguire tre distinti iter:

- Andare in negoziazione diretta con l'operatore e se non si è raggiunto l'accordo in tale fase passare alla conciliazione semplificata.
- Andare in negoziazione diretta con l'operatore e se non si è raggiunto l'accordo in tale fase passare alla convocazione dell'udienza.
- Andare direttamente in cociliazione in udienza.

In questa sezione saranno illustrate le azioni possibili in funzione dello stato in cui si trova il procedimento.

L'applicazione mostrerà sull'interfaccia solo i pulsanti delle operazioni permesse nello stato in cui si trova il procedimento.

Il procedimento nel sui iter attraversa vari stadi, ognuno dei quali è identificato da uno stato. Lo stato in cui si trova il procedimento viene visualizzato nella parte in alto, dopodichè vengono mostrate tutte le informazioni inserite in fase di inserimento dell'istanza.

In fondo alla pagina è sempre presente la barra delle azioni nella quale sono presenti i pulsanti per le azioni consentite nello stato in cui si trova il procedimento.

Dalla propria pagina principale è possibile, selezionando la tipologia di utenza, aprire il modulo per la compilazione del formulario di conciliazione.

.. figure:: /media/nuova_conciliazione.png
   :align: center
   :name: nuova-conciliazione
   :alt: Nuova conciliazione

   Nuova conciliazione
   
Il modulo d'inserimento contiene tutti i campi (obbligatori e non) che l'istante è tenuto a compilare.

- Dati relativi alle **parti:**

	- *Istanza presentata da - per conto di*: nome dell'intestatario, che sia una persona fisica o un'azienda.
	- *Recapito telefonico*: anche se non obbligatorio, si consiglia di inserire il recapito telefonico se diverso da quanto inserito nel proprio profilo. Tale dato è usato da operatori e/o conciliatori durante la gestione della controversia per eventuali comunicazioni.
	
.. figure:: /media/altro_recapito.png
   :align: center
   :name: altro-recapito
   :alt: Recapito istante
   
   Recapito istante
	
- Dati relativi alla **controversia**:

	- *Tipo di contratto*: privato o affari
	- *Disservizio riscontrato*: possono essere inseriti più disservizi anche più di uno dello stesso tipo se il disservizio riguarda più di un numero di utenza. Per inserire un disservizio fare click su "CLICCA QUI PER SELEZIONARE I DESSERVIZI". I disservizi presentati dipendono dal tipo di servizio selezionato.
		Per ogni disservizio dovranno essere associate le relative informazioni:

		- data inizio, data richiesta o data fine del disservizio o periodo di disservizio dove applicabile. Se il disservizio è ancora presente allora selezionare il flag "non risolto".
		- oggetto della controversia: Voce, Dati, Voce e Dati, Pay TV, servizi accessori, servizi a sovrapprezzo.
		- numero utenza: telefono o cellulare interessato.
		- numero di linee: se il disservizio riguarda più numeri di linee, indicare il numero di linee per cui si ha il disservizio.
		- con il tasto "Elimina" si può eliminare uno dei disservizi selezionati.
		
.. figure:: /media/disservizio.png
   :align: center
   :name: disservizio
   :alt: Disservizio
   
   Disservizio
   
	- *Codice cliente o numero del contratto*: obbligatorio quando il disservizio riguarda la Pay-Tv oppure la fornitura di più linee telefoniche fisse in diverse regioni o di più numeri di utenze mobili o di diverso tipo (mobile e fisso), o quando non sono stati specificati i numeri di utenza ma solo il numero di linee interessate dal disservizio.
	- *Domicilio del contratto*: regione/provincia indicata dall'utente come domicilio contrattuale. In caso di utente fisso va indicato il luogo ove si trova l'utenza. Se non viene specificato sarà considerata la residenza dell'utente.
	- *Operatore controparte*: selezionare uno tra gli operatori, con possibilità di auto-completamento (specificando l'inizio del nome della società il sistema suggerisce i nomi da selezionare). Gli operatori specificati potranno essere più di uno quando il disservizio riguarda "ritardo nella portabilità del numero" o "ritardo nel passaggio tra operatori". Campo obbligatorio. Se l'operatore controparte non figura tra quelli disponibili va segnalato immediatamente tramite il servizio di Assistenza.
	- *Informazioni aggiuntive*: campo non obbligatorio, da compilare se si vogliono aggiungere dettagli su quanto si vuole conciliare.

- Dati relativi ai **precedenti**:

	- *Precedenti reclami presentati all'operatore*: per ogni reclamo i seguenti dati

		- data presentazione.
		- modalità di presentazione: posta, fax, ecc.
		- codice identificativo reclamo: se disponibile oppure
		- copia della comunicazione: file pdf della comunicazione del reclamo.
		- pulsante "Elimina": per rimuovere il reclamo inserito.

	- Selezione per dichiarare che *non si sono già esperite altre conciliazioni* per i disservizi segnalati.
		
- Dati relativi alle **richieste**:

	- *Descrizione richiesta*: campo testuale, da utilizzare per richieste diverse da quelle relative a pretese economiche.
	- *Valore in euro del rimborso, dell'indennizzo e/o storno globale richiesto*.
	- *Modalità per eventuali rimborsi o indennizzi*: obbligatorio se specificato il valore in euro.
	- *IBAN*: se scelto IBAN come modalità di rimborso.

- *Allegati*: l'istante può inserire della documentazione a corredo del formulario. I file da caricare possono essere in formato pdf, jpg, png, mp3 e wav. I file non possono essere di dimensione superiore a 10Mb ciascuno.

- *Firma*: compilati tutti i campi l'istanza, dovrà essere firmata tramite la generazione di un codice "OTP" che sarà inviato al proprio indirizzo email o dispositivo mobile se specificato. Per ricevere il codice fare click su "Genera OTP".
		
Con il tasto "Salva e invia" l'istanza sarà inserita e protocollata. Il sistema invierà una notifica a tutti gli interessati e al cliente stesso di avvenuto inserimento.

.. toctree::
  :maxdepth: 3
  :hidden:
  :caption: Istanza di conciliazione

  ug/fascicolo-documentale.rst
  ug/negoziazione.rst
  ug/rinuncia.rst
  ug/integrazione.rst
  ug/provvedimento.rst
  ug/udienza.rst
  ug/firma.rst	
