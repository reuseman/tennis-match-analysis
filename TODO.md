# TODO

COMMENTARE COSA STIAMO FACENDO

COMMENTARE RISULTATI DOPO IL REPORT

# DONE

- ~~mettere random seed ad ogni classificatore~~ ALEX
- ~~knn (vedere meglio come funzionano i vari algo)~~ ALEX
- ~~SVM (guardare iperparametri)~~ JACOPO

## CLASSIFICATION

- feature selection:
  togliamo ht, togliamo in_match_statistics, togliamo quelle correlate con mean_rank_points,
  per le feature rimanenti facciamo una analisi di correlazione per eliminare

- parametri da controllare e aggiungerne nuovi:

  - decision tree (provare iperparametri) ✓ DOMENICO
  - naive bayes (provare iperparametri) ✓ DOMENICO
  - random forest (vedere meglio come funziona) DOMENICO
  - adaboost (vedere come funziona e scegliere gli iperametri con i base classifiers (decisiontree e logistic regression)) DOMENICO

  JACOPO

  - neural network (guardare epoch, verificare overfitting) (SECONDARIO -> aggiungere keras e droppout o altro ...)

  ALEX

  - (ruled based)
  - PRIORITÀ SUBITO SUCCESSIVA: partizione giocatori forti/scarsi sbilanciati con oversampling. Ha senso fare l'oversampling?

## GENERALE

1 GRAFICI nella prima parte del REPORT (VA FATTO !!!)
(es:aggiungere schemi nel data understanding e feature engineering -> es.: un grafico con numero di null per ogni attributo)

2 fare il report classificazione

3 time series controllo/aggiunta (SECONDARIO !)

4 controllare tutti i notebook e aggiungere commenti
