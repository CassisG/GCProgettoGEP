# ShippingZERO

ShippingZERO è un servizio di logistica specializzato nelle consegne a domicilio, che agevola l'utente nella visualizzazione e nella gestione dei propri prodotti acquistati effettuati online. Offre un'opzione innovativa che consente agli utenti di risparmiare sui costi di spedizione accumulando e spedendo i loro ordini in un'unica volta.
L'utente, al momento del pagamento per l'acquisto di un prodotto su un e-commerce partner di ShippingZERO, ha l'opportunità di accumulare molteplici prodotti nel proprio "magazzino personale". Una volta raccolti i prodotti desiderati, l'utente può decidere di farli spedire tutti insieme in un'unica spedizione, ad una data e un'ora prestabilite. Questo approccio consente all'utente di risparmiare sui costi di spedizione, in quanto la spedizione combinata è più conveniente rispetto all'invio separato di ogni singolo ordine.
Inoltre, oltre al vantaggio economico, l'utente ha la possibilità di tracciare i propri ordini e di programmare la spedizione in base alle proprie esigenze, garantendo un'esperienza di acquisto personalizzata e conveniente.

**Requisiti funzionali:**
- Il sistema deve consentire all'utente di visualizzare i prodotti acquistati effettuati online e di gestire i propri prodotti (aggiungere o rimuovere dal "magazzino personale")
- Il sistema deve consentire all'utente di indicare una data e un'ora prestabilita per la spedizione dei prodotti accumulati
- Il sistema deve calcolare il costo totale della spedizione in base ai prodotti selezionati
- Il sistema deve permettere all'utente di effettuare il pagamento per la spedizione
- Il sistema deve generare una conferma di spedizione con tutti i dettagli dell'ordine e dei prodotti inclusi

**Requisiti non funzionali:**
- Il sistema deve essere facile da usare e intuitivo per l'utente
- Il sistema deve garantire la sicurezza dei dati personali dell'utente
- Il sistema deve consentire la tracciabilità della spedizione per l'utente
- Il sistema deve essere disponibile 24/7 per gestire i propri prodotti in ogni momento
- Il sistema deve rispettare le norme sulla privacy imposte dal GDPR

**Requisiti di sistema:**
- Il sistema deve essere accessibile tramite il sito o l'applicazione
- Il sistema deve essere compatibile con diversi sistemi operativi e dispositivi
- Il sistema deve essere in grado di gestire molti prodotti e ordini da parte degli utenti
- Il sistema deve essere integrabile con i sistemi di pagamento online
- Il sistema deve essere in grado di generare e inviare la conferma di spedizione via email

**Requisiti di dominio**
- Il sistema deve tenere traccia delle dimensioni e del peso dei prodotti per calcolare correttamente i costi di spedizione
- Il sistema deve essere in grado di gestire le diverse destinazioni di spedizione, sia nazionali che internazionali

**Diagramma UML**
![diagramma_uml](https://yuml.me/diagram/scruffy/usecase/[Utente]-(Accesso),%20[Utente]-(Lista%20Ordini%20in%20Arrivo),%20[Utente]-(Cronologia%20Ordini),%20[Utente]-(Il%20tuo%20Magazzino),%20[Utente]-(Spedisci),%20[Operatore]-(Lista%20Ordini%20in%20Arrivo),%20[Operatore]-(Cronologia%20Ordini),%20[Operatore]-(Il%20tuo%20Magazzino),%20[Operatore]-(Gestione%20spedizione),%20(Il%20tuo%20Magazzino)%3C(Aggiungi%20Prodotto),%20(Il%20tuo%20Magazzino)%3C(Rimuovi%20Prodotto),%20(Spedisci)%3E(Acquisto%20da%20un%20e_commerce%20esterno),%20(Aggiungi%20Prodotto)%3C(Acquisto%20da%20un%20e_commerce%20esterno),%20(Spedisci)%3E(Inserisci%20Informazioni%20per%20la%20consegna),%20(Inserisci%20Informazioni%20per%20la%20consegna)%3E(Gestione%20spedizione),%20(il%20tuo%20Magazzino)%3C(Spedisci),%20[Utente]-(Inserisci%20Informazioni%20per%20la%20consegna),%20[Utente]-(Aggiungi%20Prodotto),%20[Utente]-(Rimuovi%20Prodotto))
