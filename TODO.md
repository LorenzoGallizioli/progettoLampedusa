# 📋 ToDo List per il Progetto di Analisi Basket

## 🧠 Brainstorming e Sviluppo delle Formule
- [X] **Brainstorming per Nuove Formule**
  - Trovare alternative alle formula "Dean's 4" che non utilizzino `blk` e `stl`.
  - Esplorare variabili alternative.
- [X] **Formule con Blk e Stl**
  - Creare formule specifiche che utilizzino `blk` (palle stoppate) e `stl` (palle recuperate) per il quesito 4.
  - Analizzare l'impatto di `blk` e `stl` sulle prestazioni della squadra.
  - Sviluppare il modello con queste variabili.

## 💻 Organizzazione e Ottimizzazione del Codice
- [ ] **Organizzazione del Codice in Chunk**
  - [X] Sistemare e organizzare il codice in chunk.
  - Rivedere il flusso del codice.
  - Commentare il codice.
  - Ottimizzare il codice.
  - Abbellire i grafici con colori e label differenti.
  - Aggiungere il dataset in tabelle ordinate (usare tipo bootstrap per R).
  - Nel report definitivo **non inserire grafici**.

## 📊 Analisi Dati e Modellazione
- [X] **Preparazione dei Dati**
  - [X] Dividere il dataset in train e test (validation).
  - [X]Valutare gli outlier (univariato e multivariato).
- [X] **Sviluppo del Modello**
  - [X] Ultimare il modello di regressione lineare.
  - [X] Gestione delle variabili (Multicollinearità, Variabili Dummy, Interazione).
  - [X] Analisi dei residui e diagnostica.
  - [X] Confrontare altri modelli (Poisson, Gamma, Dicotomica, modello logistico).
- [X] **Test Statistici**
  - [X] Test F per R^2.
  - [X] Test ANOVA.
  - Metodo di confronto dei modelli (LASSO vs modello di regressione).

## 📝 Analisi e Reportistica
- [ ] **Spiegazione delle Analisi**
  - Motivazione della scelta della variabile risposta.
  - Spiegazione dei grafici.
- [ ] **Interpretazione dei Risultati**
  - Interpretazione del modello logistico e odds rapporto.
  - Intervallo di predict e previsione.
  - Definizione del metodo di confronto dei modelli.
- [ ] **Presentazione del Progetto**
