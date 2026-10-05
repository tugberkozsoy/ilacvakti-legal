---
layout: default
title: Informativa sulla Privacy
permalink: /privacy-it/
---

# MedTime (İlaçVakti) — Informativa sulla Privacy

**Ultimo aggiornamento:** 4 ottobre 2026

MedTime (İlaçVakti) è un'applicazione mobile sviluppata dal Farmacista **Mehmet Tuğberk Özsoy**, progettata per aiutare gli utenti a tenere traccia dei propri farmaci. La vostra privacy è la nostra massima priorità; la presente informativa illustra in modo trasparente quali dati vengono trattati e con quali modalità.

Altre lingue: [English](/ilacvakti-legal/privacy-en/) · [Türkçe](/ilacvakti-legal/privacy-tr/)

---

## 1. Dati Non Raccolti

MedTime **non** raccoglie identificatori personali (nome, e-mail, telefono, codice identificativo, data di nascita, ecc.) dagli utenti, non li invia ai nostri server e non li condivide con terze parti. Non è richiesta la creazione di un account; l'app funziona interamente in modo **anonimo**.

Elenco dettagliato dei dati non raccolti:
- ❌ Reti pubblicitarie, profilazione o tracciamento tra applicazioni (per la misurazione degli annunci sull'App Store, vedere la Sezione 5)
- ❌ Servizi di analisi di terze parti (Google Analytics, Facebook Pixel, ecc.)
- ❌ Dati di localizzazione
- ❌ Contatti, calendario
- ❌ Conservazione di registrazioni audio (il microfono si attiva solo per l'inserimento vocale facoltativo, vedi 3.6)
- ❌ Creazione di account, e-mail, telefono
- ❌ I dati di Apple Salute **non lasciano** il tuo dispositivo (la sincronizzazione opzionale di lettura/scrittura avviene sul dispositivo, vedi 3.5)
- ❌ Il vostro backup iCloud e i dati della condivisione familiare **non arrivano** allo sviluppatore (restano nei vostri account iCloud, vedi 2.1 e 2.2)

---

## 2. Archiviazione Locale (Dati Conservati sul Vostro Dispositivo)

Le informazioni che inserite vengono archiviate **nella memoria interna del vostro dispositivo**; lo sviluppatore non dispone di alcun server che conservi questi dati:

- Nomi dei farmaci, dosaggi, orari dei promemoria
- Nomi dei profili (i nomi da voi forniti) ed eventuale foto del profilo
- Informazioni sulle scorte di farmaci e relative foto
- Cronologia del trattamento, registri di assunzioni/dosi saltate
- Dati relativi alle serie consecutive (streak) e ai badge
- Referti e note sanitarie aggiunti manualmente
- Preferenze relative a tema, lingua, suono delle notifiche e impostazioni

Quando eliminate l'app, questi dati vengono rimossi dal vostro dispositivo. Se il backup iCloud è attivo, il backup resta nel vostro account iCloud (vedi 2.1).

### 2.1 Backup iCloud (attivo per impostazione predefinita, disattivabile)

Se sul vostro iPhone avete effettuato l'accesso a iCloud, l'app salva una volta al giorno un backup dei vostri dati nell'**area privata del vostro account iCloud** (database privato Apple CloudKit). Così farmaci e cronologia tornano quando cambiate telefono o reinstallate l'app.

- Il backup comprende farmaci, profili, referti, misurazioni, cronologia delle dosi, badge/serie e impostazioni dell'app. **Le foto non sono incluse.** Nemmeno le misurazioni importate da Apple Salute; Apple Salute le conserva da sé e l'app le rilegge su un nuovo telefono.
- Il backup è archiviato nei campi crittografati end-to-end di Apple (valori crittografati di CloudKit); la chiave si trova nel vostro Portachiavi iCloud. I backup molto grandi (anni di cronologia) sono conservati come file crittografato su iCloud; con la Protezione avanzata dei dati attiva, anche questo file è crittografato end-to-end.
- Il backup non arriva mai ai server dello sviluppatore; **lo sviluppatore non può accedervi.** Utilizza il vostro spazio iCloud.
- Anche l'elenco dei vostri collegamenti familiari (chi seguite, chi vede le vostre dosi) viene salvato allo stesso modo, così i collegamenti sopravvivono a un nuovo telefono.
- Per disattivarlo: nell'app, Impostazioni › Gestione dati › Backup iCloud. Per eliminarlo: Impostazioni dell'iPhone › [il vostro nome] › iCloud › Gestisci spazio account › MedTime.

### 2.2 Condivisione familiare (facoltativa)

Potete seguire i farmaci di una persona cara dal vostro telefono. La condivisione inizia solo con **un'azione esplicita di entrambe le parti**: chi seguirà invia un link d'invito; la persona seguita vede sul proprio telefono cosa verrà condiviso e **tocca «Accetta».**

- **Condiviso:** i dati delle schede farmaco del profilo condiviso (ad esempio nome, principio attivo, dose, orari, istruzioni e nota del farmaco), le dosi prese o annullate e l'orario in cui sono state segnate, nome e colore del profilo, il fuso orario del dispositivo.
- **Non condiviso:** il Diario dei farmaci (stato d'animo/effetti collaterali), misurazioni di pressione e glicemia, foto, foglietti illustrativi e altri profili.
- I dati vengono trasferiti tramite Apple iCloud (condivisione CloudKit) e archiviati **nell'account iCloud di chi segue**; nomi e dati dei farmaci sono in campi crittografati end-to-end. Se una dose non viene segnata entro il tempo scelto, chi segue riceve un avviso; il calcolo avviene sul suo dispositivo.
- **Lo sviluppatore non può accedere a questi dati**; non passano dai suoi server.
- **Per interrompere:** la persona seguita può farlo in qualsiasi momento da Impostazioni › Famiglia («… vede le tue dosi»), chi segue con «Smetti di seguire» nella schermata della persona. A quel punto i dati condivisi vengono eliminati dall'account iCloud di chi segue.
- Accettare un invito è gratuito; seguire è una funzione Premium (con In famiglia di Apple basta l'abbonamento di un solo membro).

---

## 3. Autorizzazioni

### 3.1 Notifiche
L'autorizzazione alle notifiche viene richiesta per i promemoria dei farmaci. Le notifiche sono pianificate **localmente sul vostro dispositivo**; non è coinvolta alcuna connessione al server.

### 3.2 Fotocamera
L'accesso alla fotocamera viene richiesto solo nella schermata *"Aggiungi Farmaco"*, per scansionare i codici a barre/codici QR sulle confezioni dei farmaci o per scattare foto dei farmaci. Le immagini della fotocamera non vengono inviate a un server.

### 3.3 Foto
L'accesso facoltativo alla libreria fotografica viene richiesto se desiderate aggiungere foto dei farmaci o del profilo. Le foto selezionate vengono copiate esclusivamente nella cartella interna dell'app sul vostro dispositivo.

### 3.4 Ricerca nel Database dei Farmaci
Quando scansionate un codice a barre/codice QR su una confezione di farmaci o cercate un farmaco per nome, viene inviato unicamente quel **numero del codice a barre/codice prodotto o il nome del farmaco** a un servizio ufficiale di database farmaceutico, al fine di recuperare il nome del farmaco e i relativi dettagli (foglietto illustrativo, confezione, data di scadenza, ecc.). Il servizio utilizzato dipende dalla regione del vostro dispositivo: **NosyAPI** (Turchia), il database **U.S. FDA openFDA** (Stati Uniti) o **AEMPS CIMA** (Spagna). In questa richiesta non è incluso alcun dato personale (il vostro nome, i dati del profilo, i dati sanitari, le foto o le immagini della fotocamera) — viene trasmesso unicamente il codice scansionato o il termine di ricerca. Questa funzione è facoltativa; se non la utilizzate, non viene inviato alcun dato.

Potete revocare le autorizzazioni in qualsiasi momento tramite *Impostazioni &gt; MedTime* di iOS.

### 3.5 Apple Salute (HealthKit) — Sincronizzazione opzionale
Gli utenti Premium possono attivare la sincronizzazione *Impostazioni → Apple Salute*. Quando è attiva: (1) le misurazioni di **pressione, glicemia e battito** inserite nell'app e le **dosi di insulina** che segni vengono **scritte** in Apple Salute; (2) le misurazioni di **pressione, glicemia e battito** che il tuo misuratore, glucometro o altre app scrivono in Apple Salute vengono **lette** nel diario delle misurazioni dell'app. Questa funzione è **del tutto opzionale** e **disattivata per impostazione predefinita**.

- I permessi di lettura e scrittura vengono concessi **separatamente** ed esplicitamente tramite la schermata di autorizzazione di iOS; si accede solo ai tipi di dati indicati (elenchi di farmaci, passi, sonno ecc. **non vengono letti**).
- Vengono scritte solo le misurazioni del **tuo profilo**; i profili dei familiari non vengono mai sincronizzati.
- I dati vanno direttamente nell'archivio Salute del tuo dispositivo; **nulla viene inviato a server**. I dati di Salute sono cifrati da Apple.
- Se elimini o modifichi una misurazione nell'app, la copia scritta in Salute viene aggiornata/rimossa di conseguenza.
- Puoi revocare l'accesso in qualsiasi momento da iOS *Impostazioni → Salute → Accesso ai dati e dispositivi → İlaçVakti*.
- I dati sanitari non vengono mai usati per pubblicità, marketing o analisi (conforme alla Regola 5.1.3 dell'App Store).

### 3.6 Microfono e riconoscimento vocale — Facoltativo
Toccando l'icona del microfono nella schermata delle misurazioni puoi inserire la pressione o la glicemia **parlando**. Questa funzione è **del tutto facoltativa**; il microfono non si attiva mai se non tocchi quell'icona.

- La tua voce viene trascritta **sul tuo dispositivo**; l'app **impone** il riconoscimento vocale on-device di iOS. **Nessun audio viene inviato ad alcun server**: la funzione opera anche in modalità aereo.
- **Nessuna registrazione audio viene conservata.** Una volta trascritto il parlato, i dati audio non vengono memorizzati; solo i numeri riconosciuti vengono scritti nei campi a schermo.
- Il valore riconosciuto **non viene salvato direttamente**: viene scritto nel campo e non viene registrato finché non lo controlli e tocchi **Salva**.
- Il microfono è attivo solo in questa schermata e solo quando lo avvii tu; non c'è alcun ascolto in background.
- Puoi revocare l'autorizzazione in qualsiasi momento da iOS *Impostazioni &gt; MedTime*.

---

## 4. Segnalazioni di Arresto Anomalo (Sentry)

Per migliorare la stabilità dell'app, vengono raccolte segnalazioni anonime di arresto anomalo tramite il servizio **Sentry**.

**Dati raccolti:**
- Data e ora dell'arresto anomalo, modello del dispositivo, versione di iOS, versione dell'app
- Messaggio di errore e traccia tecnica dello stack (stack trace)
- Contesto tecnico precedente all'arresto anomalo (ad es. schermate aperte)

**Dati non raccolti:**
- Nome utente, e-mail, indirizzo IP (`sendDefaultPii` disabilitato)
- Screenshot, dati personali sui farmaci, dati sanitari
- Foto o contenuti dei referti

I dati di Sentry sono utilizzati esclusivamente per il miglioramento dell'app; **mai** per finalità di marketing o pubblicità. I dati di Sentry sono conservati per un massimo di **90 giorni**.

Informativa sulla privacy di Sentry: <https://sentry.io/privacy/>

---

## 5. Abbonamento Premium e RevenueCat

MedTime offre un **abbonamento Premium** facoltativo:

| Piano | Prezzo | Funzionalità |
|---|---|---|
| Mensile | 3,99 € | Si rinnova automaticamente |
| Annuale | 29,99 € | Include **7 giorni di prova gratuita**, si rinnova automaticamente |
| A vita | 49,99 € | **Pagamento una tantum**: non è un abbonamento e non si rinnova |

> Gli importi indicati si riferiscono all'App Store dell'area euro (in CHF per la Svizzera). **I prezzi variano in base al Paese**; l'App Store mostra l'importo esatto nella vostra valuta locale prima di completare l'acquisto.

### Gestione dell'Abbonamento
- Gli abbonamenti si rinnovano automaticamente; il pagamento viene addebitato sul vostro account iTunes se non viene annullato almeno **24 ore** prima del termine del periodo in corso.
- Annullamento: *Impostazioni → Apple ID → Abbonamenti* di iOS.
- L'opzione **In Famiglia** è abilitata — un abbonamento può essere condiviso con un massimo di 5 membri della famiglia.
- I pagamenti sono elaborati da Apple; MedTime non ha accesso alle informazioni della carta.

### Accesso Gratuito a Vita per gli Utenti Iniziali
Gli utenti che hanno installato la versione **2.0.1 (build 5) o precedente** ricevono automaticamente l'accesso **Premium gratuito a vita**. Tale condizione è verificata in modo anonimo sul dispositivo utilizzando il campo `originalApplicationVersion` presente sulla ricevuta Apple.

### RevenueCat (Convalida dell'Abbonamento)
Il servizio **RevenueCat** è utilizzato per convalidare lo stato dell'abbonamento. Un identificatore anonimo (App User ID) derivato dal vostro Apple ID e i dati della ricevuta Apple vengono inviati a RevenueCat. Il vostro nome, e-mail o informazioni di contatto **non vengono condivisi**.

Informativa sulla privacy di RevenueCat: <https://www.revenuecat.com/privacy/>

### Misurazione Pubblicitaria (Apple Search Ads)
MedTime pubblica occasionalmente annunci sull'App Store. Per misurare quale annuncio vi ha portato all'applicazione, un *token di attribuzione* generato da Apple **al momento dell'installazione** viene trasmesso a RevenueCat, che chiede ad Apple se l'installazione proviene da un annuncio.

- Il token **non è il vostro identificativo pubblicitario (IDFA)** e non identifica né voi né il vostro dispositivo. Per questo motivo la schermata iOS di *Trasparenza del tracciamento delle app* non viene mostrata: non viene effettuato alcun tracciamento tra applicazioni.
- Apple restituisce esclusivamente informazioni **a livello di campagna**. Tali informazioni non vengono **mai collegate** al vostro nome, al vostro profilo, ai vostri farmaci o ai vostri dati sanitari.
- L'operazione avviene **una sola volta, all'installazione**; in seguito il vostro utilizzo dell'applicazione non viene tracciato a fini pubblicitari.
- L'unico scopo è verificare che il budget pubblicitario sia speso bene; **non** viene utilizzato per indirizzarvi annunci né per vendere dati.

### Termini di Utilizzo
Si applica il Contratto di Licenza con l'Utente Finale (EULA) Standard di Apple: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Condivisione dei Dati

MedTime **non condivide i dati degli utenti con alcuna terza parte, non li vende e non li utilizza per finalità di marketing**. Le uniche eccezioni sono:

- Le ricerche nel database dei farmaci descritte nella Sezione 3.4 (NosyAPI / U.S. FDA openFDA / AEMPS CIMA) — viene trasmesso unicamente il codice scansionato o il nome del farmaco cercato; non contiene alcun dato personale.
- Le segnalazioni anonime di arresto anomalo descritte nella Sezione 4 (Sentry).
- I dati anonimi di convalida dell'abbonamento e il token di attribuzione pubblicitaria non identificante descritti nella Sezione 5 (RevenueCat + Apple).
- La condivisione familiare descritta nella Sezione 2.2, **avviata e approvata da voi** — solo con la persona che avete invitato o di cui avete accettato l'invito, tramite Apple iCloud.

---

## 7. I Vostri Diritti ai sensi del GDPR (Utenti UE)

Se risiedete nell'UE, ai sensi del Regolamento Generale sulla Protezione dei Dati (GDPR) avete il diritto di **accedere, rettificare, cancellare, opporvi al trattamento e ottenere la portabilità dei dati**. Le nostre basi giuridiche sono: la necessità per la fornitura del servizio (Articolo 6(1)(b)) e il legittimo interesse per la segnalazione degli errori (Articolo 6(1)(f)).

---

## 8. I Vostri Diritti ai sensi della KVKK Turca

Ai sensi dell'Articolo 11 della Legge turca sulla Protezione dei Dati Personali (KVKK), avete diritti che includono: sapere se i vostri dati vengono trattati, richiedere informazioni, richiedere la rettifica o la cancellazione, conoscere le terze parti a cui i dati sono stati trasferiti, opporvi ai risultati di un trattamento automatizzato e richiedere un risarcimento. Per esercitare tali diritti, contattate <ilacvaktidestek@gmail.com>. Le richieste ricevono risposta entro **30 giorni**.

---

## 9. Privacy dei Minori

L'app è classificata **4+**. I dati non vengono raccolti consapevolmente da minori di 13 anni. Se un genitore utilizza l'app per aggiungere il profilo di un minore (membro della famiglia), i dati del profilo restano archiviati esclusivamente in locale sul dispositivo.

---

## 10. Sicurezza dei Dati

Poiché i vostri dati sono per lo più archiviati sul vostro dispositivo, essi sono protetti dalla crittografia hardware di iOS (Secure Enclave). La comunicazione con i servizi di terze parti è crittografata tramite HTTPS. I dati dei farmaci nel backup iCloud e nella condivisione familiare sono archiviati nei campi crittografati end-to-end di Apple CloudKit; nessuno, nemmeno lo sviluppatore, può leggerli.

---

## 11. Modifiche alla Presente Informativa

Potremmo aggiornare di tanto in tanto la presente informativa. Le modifiche significative verranno comunicate tramite notifica in-app o note di rilascio. Vi invitiamo a consultare regolarmente la data di *Ultimo aggiornamento*.

---

## 12. Contatti

E-mail: <ilacvaktidestek@gmail.com>
