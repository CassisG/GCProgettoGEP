# GCProgettoGEP

# ShippingZERO

ShippingZERO è un servizio di logistica specializzato nelle consegne a domicilio, che agevola l'utente nella visualizzazione e nella gestione 
dei propri prodotti acquistati effettuati online.
L'utente al momento del pagamento, in caso di necessità, potrà decidere di accumulare molteplici prodotti in magazzino e farseli spedire in un'unica volta, 
ad una data (e ora) prestabilita, permettendo di risparmiare sui costi di spedizione (oltre ad avere la possibilità di tracciare i propri ordini).

# Requisiti funzionali:
- Il sistema deve consentire all'utente di visualizzare i prodotti acquistati effettuati online e di gestire i propri prodotti (aggiungere o rimuovere dal "magazzino personale")
- Il sistema deve consentire all'utente di indicare una data e un'ora prestabilita per la spedizione dei prodotti accumulati
- Il sistema deve calcolare il costo totale della spedizione in base ai prodotti selezionati
- Il sistema deve permettere all'utente di effettuare il pagamento per la spedizione
- Il sistema deve generare una conferma di spedizione con tutti i dettagli dell'ordine e dei prodotti inclusi

# Requisiti non funzionali:
- Il sistema deve essere facile da usare e intuitivo per l'utente
- Il sistema deve garantire la sicurezza dei dati personali dell'utente
- Il sistema deve consentire la tracciabilità della spedizione per l'utente
- Il sistema deve essere disponibile 24/7 per gestire i propri prodotti in ogni momento

# Requisiti di sistema:
- Il sistema deve essere accessibile tramite il sito o l'applicazione
- Il sistema deve essere compatibile con diversi sistemi operativi e dispositivi
- Il sistema deve essere in grado di gestire molti prodotti e ordini da parte degli utenti
- Il sistema deve essere integrabile con i sistemi di pagamento online
- Il sistema deve essere in grado di generare e inviare la conferma di spedizione via email

# Requisiti di dominio:
- Il sistema deve tenere traccia delle dimensioni e del peso dei prodotti per calcolare correttamente i costi di spedizione
- Il sistema deve essere in grado di gestire le diverse destinazioni di spedizione, sia nazionali che internazionali

# Diagramma Use Case
http://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso),
[Utente]-(Visualizza Profilo),
[Utente]-(Lista Prodotti Ordinati),
[Utente]-(Il tuo Magazzino),
(Il tuo Magazzino)<(Aggiungi Prodotto),
(Il tuo Magazzino)<(Rimuovi Prodotto),
[Utente]-(Spedisci),
(Spedisci)>(Inserisci data e ora di arrivo),
(Inserisci data e ora di arrivo)>(Scegli indirizzo),
(Scegli indirizzo)>(Pagare Spedizione)

