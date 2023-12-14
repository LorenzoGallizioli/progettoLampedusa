# 📋 ToDo List per il Progetto di Analisi Basket

## 🤔 Brainstorming per il Progetto
- [ ] **Brainstorming per Nuove Formule**: Trovare alternative alle formula "Dean's 4" che non utilizzino `blk` e `stl`. 
  - Esplorare variabili alternative.

## 🧮 Creazione di Formule
- [ ] **Formule con Blk e Stl**: Creare formule specifiche che utilizzino `blk` (palle stoppate) e `stl` (palle recuperate) per il quesito 4.
  - Analizzare l'impatto di `blk` e `stl` sulle prestazioni della squadra.
  - Sviluppare il modello con queste variabili.

## 💻 Sistemazione del Codice
- [ ] **Organizzazione del Codice in Chunk**: Sistemare e organizzare il codice in chunk
  - Rivedere il flusso del codice.
  - Commentare il codice.
  - Ottimizzare il codice.
  - Abbellire i grafici con colori e label differenti dal profe (anche i numeri negli assi non usare quelli di default)
  - aggiungere il dataset in tabelle ordinate (usare tipo bootstrap per R).
  - Nel report DEFINITIVO NON INSERIRE I GRAFICI, i grafici devono essere inseriti da un'altra parte.

## Avvanzamento del Progetto
- DIVIDERE il dataset in train e test (validation) così che si fitta il modello sul train e si guarda la capacità predittiva su nuovi dati, questo serve per evitare di over-fittare i dati di train e fare un modello che si adatta solo ai dati visti dal modello.
- Valutare gli outlier se eliminarlo o tenerne solo conto (univariato e multivariato)
Gli outlier univariato da tenerne solo conto
Gli outlier multivariato lo si definisce dalla diagnostica e in quel caso bisogna eliminarli perchè variano di molto la statistica.
- Ultimare il modello di regressione lineare
- Spiegare le analisi PRELIMINARI E DELLA VARIABILE RISPOSTA:
  1) motivando il perchè abbiamo usato una data variabile risposta ed a chi può servire per fare questa statistica
  2) spiegare i grafici
- Multicollinearità
- Variabili Dummy
- Interazione
- Test F per R^2
- Test ANOVA
- Capire se le variabili non significative possiamo eliminarle o meno (se non sono significative, mandale a fanculo)
- Analisi dei residui e diagnostica
- confrontare altri modelli (Poisson, Gamma, Dicotomica)
- modello logistico
  per chi ha intenzione di usare var. risposta dicotomica e INTERPRETARE (odds rapporto tra p(Y=1) e p(Y=0)
- intervallo di predict e previsione
- Confronto LASSO vs modello di regressione e valutare il migliore per fare previsione (RMSE più alto vince) (glmnet)
- METODO DI CONFRONTO DEI MODELLI: inserire la definizione
