# Alexa-actionable-notification-rooms-presence

Questo progetto utilizza l'ottimo lavoro di [Keaton Taylor](https://github.com/keatontaylor/alexa-actions) ed è progettato per semplificare il monitoraggio della presenza nelle stanze(area) con l'aiuto di Alexa.

Il processo è semplice: basta selezionare uno o più sensori di movimento e configurare il tempo entro il quale il sensore passa dallo stato 'on' allo stato 'off'.

![image](https://github.com/Home-Assistant-Pro-Team/Alexa-actionable-notification-rooms-presence/assets/62516592/bde76fae-b29c-4da2-9d16-8c5f348d9b66)


Un aspetto unico di questo progetto è la sua capacità di **gestire automaticamente l'automazione in diverse stanze**.
Se in una stanza dove è scattato un sensore di movimento è accesa almeno una luce o un dispositivo media_player, il dispositivo Alexa presente in quella stanza entrerà in azione.
Alexa ti chiederà se c'è ancora qualcuno nella stanza, e se non riceve risposta, provvederà automaticamente a spegnere le luci e i media_player.

Inoltre, il progetto offre una funzione facoltativa di controllo dello stato di [bedpresence](https://github.com/Home-Assistant-Pro-Team/Bed-Presence/tree/main). Se si possiede l'entità che inizia per binary_sensor.bedpresence_, è possibile integrarla nel progetto per monitorare la presenza nei letti. Tuttavia, è importante notare che il progetto funzionerà comunque in modo efficace anche senza questa funzionalità.

Questo progetto è altamente flessibile e in grado di rilevare autonomamente in quale stanza eseguire l'automazione in base all'attivazione dei sensori di movimento.

### Per garantire il corretto funzionamento del progetto, è essenziale assegnare i dispositivi alle aree appropriate, e il sistema opererà in modo completamente autonomo.

## Puoi accedere al progetto dal [link](https://community.home-assistant.io/t/alexa-actionable-notification-rooms-presence/628659)

#### **Supportaci**
Se hai apprezzato questo progetto, ci piacerebbe avere il tuo supporto. Anche un semplice caffè può fare la differenza. 
I fondi raccolti saranno utilizzati per acquistare nuovo materiale e realizzare nuovi progetti. Puoi contribuire cliccando sul pulsante qui sotto. 
Grazie di cuore per il tuo sostegno!

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M1MI00I)
