Inserimento istanza di provvedimento temporaneo (modello GU5)
=============================================================

L'istanza per l'emissione del provvedimento temporaneo, nel caso in cui sia in corso in ConciliaWeb la relativa conciliazione o definizione, andra presentata tramite l'apposito pulsante presente nella barra delle azioni della conciliazione o definizione in corso.

.. figure:: /media/barra_azioni_provvedimento.png
   :align: center
   :name: barra-azioni-provvedimento
   :alt: Provvedimento barra azioni
   
   Azioni - Provvedimento temporaneo

Nel caso in cui la conciliazione non sia in corso in ConciliaWeb, dalla propria pagina principale è possibile selezionando la tipologia di utenza, aprire il modulo per la compilazione del formulario di richiesta di un provvedimento temporaneo (modello GU5).

.. figure:: /media/nuovo_provvedimento.png
   :align: center
   :name: nuovo-provvedimento
   :alt: Nuovo provvedimento
   
   Nuovo provvedimento

Il modulo d'inserimento contiene tutti i campi (obbligatori e non) che l'istante è tenuto a compilare.

- Dati relativi alle **parti**:

	- *Istanza presentata da - per conto di*: nome dell'intestatario, che sia una persona fisica o un'azienda.
	- *Recapito telefonico*: anche se non obbligatorio, si consiglia di inserire il recapito telefonico se diverso da quanto inserito nel proprio profilo. Tale dato è usato da operatori e/o conciliatori durante la gestione della controversia per eventuali comunicazioni.
	
.. figure:: /media/altro_recapito.png
   :align: center
   :name: altro-recapito
   :alt: Recapito istante
   
   Recapito istante
	
- Dati relativi al **disservizio**:

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

- Dati relativi alla **procedura pendente**: questa sezione sarà compilata automaticamente se la procedura è pendente nel sistema e l'inserimento del provvedimento avviene tramite l'apposito pulsante presente nel dettaglio del procedimento pendente. Altrimenti sarà richiesta la compilazione dei seguenti campi:

	- *Data presentazione istanza*
	- *Organismo*
	- *Identificativo istanza*

- *Allegati*: l'istante può inserire della documentazione a corredo del formulario. I file da caricare possono essere in formato pdf, jpg, png, mp3 e wav. I file non possono essere di dimensione superiore a 10Mb ciascuno.

- *Firma*: compilati tutti i campi l'istanza, dovrà essere firmata tramite la generazione di un codice "OTP" che sarà inviato al proprio indirizzo email o dispositivo mobile se specificato. Per ricevere il codice fare click su "Genera OTP".
		
Con il tasto "Salva e invia" l'istanza sarà inserita e protocollata. Il sistema invierà una notifica a tutti gli interessati e al cliente stesso di avvenuto inserimento.

.. toctree::
  :maxdepth: 3
  :hidden:
  :caption: Provvedimento temporaneo

  gu5/fascicolo-documentale.rst
  gu5/rinuncia.rst
  gu5/risposta-richistruttoria.rst
  gu5/segnmanc-ottemperanza.rst
 