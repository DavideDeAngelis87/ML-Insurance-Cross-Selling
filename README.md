# Machine Learning for Insurance Cross-Selling Optimization

## Descrizione del Progetto
Il progetto si focalizza sullo sviluppo di un modello predittivo per ottimizzare le strategie di **Cross-Selling** all'interno di una compagnia assicurativa. L'obiettivo è identificare i clienti che hanno già sottoscritto una polizza sanitaria e che mostrano una maggiore propensione all'acquisto di un'assicurazione per veicoli. 

Attraverso l'analisi dei dati demografici, dei veicoli e dello storico assicurativo, il modello permette di passare da un approccio di marketing massivo a uno mirato, migliorando il tasso di conversione e riducendo i costi di acquisizione.

## Workflow Tecnico e Metodologia
Il progetto segue le fasi standard di un processo di Data Science:

1. **Exploratory Data Analysis (EDA):** analisi delle correlazioni tra variabili (es. età del veicolo, danni precedenti) e la variabile target per comprendere i driver del comportamento d'acquisto.
2. **Data Preprocessing:** gestione di variabili categoriche tramite *Encoding* e scalatura delle feature numeriche per uniformare gli input del modello.
3. **Handling Class Imbalance:** trattamento dello sbilanciamento delle classi (tipico dei contesti di vendita dove le conversioni sono una minoranza) per evitare bias nel modello.
4. **Modellazione Predittiva:** implementazione di un modello di classificazione basato su Regressione Logistica
5. **Evaluation Metrics:** valutazione delle performance non solo tramite l'Accuracy, ma focalizzandosi su **Precision, Recall e AUC-ROC**.

## Tech Stack
* **Linguaggio:** Python
* **Librerie:** `Scikit-learn`, `Pandas`, `NumPy`.
* **Visualizzazione:** `Matplotlib`, `Seaborn`.

## Impatto Business
- **Targeting Mirato:** capacità di dare priorità ai contatti con alta probabilità di conversione, ottimizzando le risorse del dipartimento vendite.
- **Data-Driven Strategy:** fornitura di insight sulle caratteristiche del cliente "ideale" per il prodotto assicurativo veicoli.
- **ROI Optimization:** riduzione dello spreco di budget in campagne dirette a segmenti di clientela non interessati.

## Struttura del Repository
- `Progetto_Cross_selling.ipynb`: notebook completo con l'intero ciclo di vita del progetto, dalla pulizia dei dati alla valutazione finale.
- `insurance_cross_sell.csv`: dataset utilizzato per l'analisi
