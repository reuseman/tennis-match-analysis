# TODO

## 1_data_analysis
    - clean the notebook and leave only what's necessary

## 2_data_preparation

### TODO PRIMA DEL CLUSTERING 
- [X] Decidere se droppare righe che non hanno attributi del match o Decidere se droppare colonne attributi del match.
- Vedere instogramma sul numero di partite per capire che treshold dare nello scarto
- Decidere ranking points
- [X] (A) Risolvere dataset pulito/sporco

### TODO J
- [X] Fix feature prendendo ultimo valore o massimo (Altezza, Età, )
- [X] Fare feature engegneering
- [X] Fare instogrammi
- [X] Studiare come aggiustare distribuzioni
- Aggiustare distribuzioni via codice

### Features

#### Prof

- how many times did the player win during a given period
- how many matches the player played in a given period
- a ratio between the previous indicators
- percentage of aces related to the number of first serves made
- number of breakpoints numbers w.r.t. all games

#### Our

##### Simple
- ✓ tornei giocati
- ✓ altezza
- ✓ età
- ✓ mano
- ✓ vittorie tornei/ punteggio ad hoc (nostro ranking)
- ✓ numero (ace, doppi falli, first_in, second_in)/ numero service point (first_in, second_in)
- ✓ numero breakpoint affrontati / numero totale di punti giocati
- ✓ numero breakpoint salvati / numero breakpotin affrontati
- ✓ match giocati
- (J ✓) media ranking
- (J ✓) max min ranking
- (J ✓) varianza ranking
- (J ✓) media spettatori
- (J ✓) media revenue
- (A ✓) match vinti
- (A) varianza vittorie
- (A) rapporto delle precedenti
- (A) entropia vittoria/partite/qualcosa
- (D) numero di game vinti sul totale dei game (rapporto)
- (D) durata media/totale/entropia/varianza minuti partite giocatore

##### Complex
- massimo round che ha raggiunto un giocatore in un torneo
- distanza fra tornei giocati pesata dal numero di partite per torneo (NO perchè dataset incompleto / pochi dati)
- feature tipiche del match, punti, game, ecc...