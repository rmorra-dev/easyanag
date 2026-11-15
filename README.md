# EasyAnag (v1.0)

**Il connettore desktop portatile per la gestione di anagrafiche e presenze tra Azienda e Studio di Consulenza del Lavoro.**

---

## 💡 L'idea e l'obiettivo
**EasyAnag** nasce per semplificare e rendere sicuro lo scambio informativo mensile tra le aziende clienti e il proprio studio di consulenza del lavoro. 

A differenza dei tradizionali portali web, EasyAnag adotta un approccio **locale e portatile ("Zero-Cloud")**: l'applicazione viene eseguita direttamente sul PC del cliente senza richiedere installazioni invasive, permessi di amministratore o l'esposizione di dati sensibili su server remoti di terze parti.

---

## ✨ Punti di Forza e Architettura

* **🔒 Privacy e Controllo Totale ("Zero-Cloud"):** Tutti i dati anagrafici, contrattuali e le presenze risiedono esclusivamente sul computer o sulla rete locale del cliente tramite un database **SQLite**. La proprietà e la custodia dei dati rimangono interamente in capo all'azienda, semplificando la conformità al GDPR.
* **🚀 Zero Attrito IT:** Distribuita come applicazione standalone portatile, non modifica il registro di sistema e non richiede configurazioni complesse.
* **⏱️ Storicizzazione e Invio "Solo Variazioni":** Ogni dato inserito o modificato è storicizzato con una data di validità (`ASSUNZIONE` o `VARIAZIONE`). Nei flussi periodici verso lo studio vengono esportate **esclusivamente le variazioni** intervenute, riducendo al minimo gli errori di data-entry e i tempi di elaborazione.
* **⚙️ Flessibilità guidata da Schema:** La struttura dei campi, le regole di validazione e le tabelle sono configurabili tramite schema esterno, permettendo di adattare il software alle esigenze specifiche dello studio senza dover riscrivere il programma.

---

## 🛠️ Funzionalità Principali

### 1. Gestione Anagrafiche e Controlli Intelligenti
* Gestione multi-azienda e anagrafiche dipendenti con storico completo per singolo campo e gestione delle **variazioni future**.
* Validazione automatica e controlli di coerenza in tempo reale (Codice Fiscale, Comuni italiani ed esteri, IBAN, date di assunzione/cessazione).
* **Importazione massiva** da file Excel (`.xlsx`) o CSV con report preventivo degli errori.
* Generazione istantanea della **Scheda Anagrafica in PDF** e gestione dei **documenti allegati** alle singole variazioni.

### 2. Modulo Presenze e Voci Cedolino
* Configurazione flessibile di orari di lavoro settimanali, festività e causali/giustificativi (assenze, maggior presenza, lavoro ordinario).
* Generazione rapida del **foglio presenze mensile** con calcolo automatico dei totali e gestione delle voci variabili per il cedolino.
* Esportazione dei **cartellini presenze in PDF** (singolo dipendente o riepilogo aziendale) e tracciati CSV.

### 3. Dashboard Analytics e Reportistica
* Cruscotto interattivo con indicatori KPI su **organico**, **turnover**, **tasso di assenteismo**, scadenze dei contratti a tempo determinato e qualità dei dati.
* Esportazione immediata dei report in formato **CSV**, **Excel** (con grafici) e **HTML** autonomo.

### 4. Sicurezza, Backup e Collaborazione
* **Generazione Flussi per lo Studio:** Creazione di pacchetti dati strutturati in formato JSON pronti per l'acquisizione da parte del consulente.
* **Sistema di Licenze e Accessi:** Gestione mono-utenza o multi-utenza con controllo accessi e limiti configurabili per cliente.
* **Backup Integrato:** Esportazione completa di dati e allegati documentali in archivi `.zip` con verifica d'integrità e promemoria periodici.

---

## 🗺️ Stato del Progetto e Partnership
* **Stato attuale:** Versione 1.0 completa.
* **Obiettivo:** Ricerca di studi di consulenza del lavoro e partner tecnologici interessati a testare o integrare il connettore nei propri flussi operativi.

---

## 📬 Contatti
Sei uno studio di consulenza del lavoro o un potenziale partner interessato al progetto? Contattami per una demo o per approfondire le possibilità di collaborazione:

* **Email:** morraf63@gmail.com
* **LinkedIn:** https://www.linkedin.com/in/raffaele-morra-933a7355/
