# UCI Adult Census Income Analysis

## Descrizione del Progetto
Questo progetto analizza il dataset **UCI Adult Census Income** utilizzando tecniche di **Exploratory Data Analysis (EDA)** e vari modelli di **Machine Learning** per la classificazione del reddito. Il progetto è implementato in un **Jupyter Notebook**.

## Struttura del Progetto
- **EDA e Preprocessing:** Pulizia dei dati, gestione dei valori mancanti, encoding delle variabili categoriali e normalizzazione.
- **Modelli di Machine Learning:**
  - **Support Vector Machine (SVM)**
  - **Decision Tree**
  - **Random Forest**
  - **AdaBoost**
- **Feature Reduction:** Applicazione di tecniche di selezione delle feature per ogni modello.

## Dataset
Il dataset **UCI Adult Census Income** è disponibile pubblicamente ed è utilizzato per predire se il reddito annuale di una persona supera i $50.000. Il dataset contiene informazioni socio-demografiche e lavorative.

### Fonte del dataset
[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)

## Requisiti
Dipendenze librerie Python:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Esecuzione del Notebook
1. Clonare il repository:
   ```bash
   git clone https://github.com/tucob97/Adult_data.git
   ```
2. Accedere alla cartella del progetto:
   ```bash
   cd Adult_data
   ```
3. Avviare Jupyter Notebook:
   ```bash
   jupyter notebook .
   ```
4. Aprire ed eseguire il notebook

## Risultati
I modelli vengono valutati in base alla loro accuratezza e precisione, tramite anche le confusion matrix. Il progetto esplora anche l'impatto della riduzione delle feature sulle prestazioni dei modelli.
