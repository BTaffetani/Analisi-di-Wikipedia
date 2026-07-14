# Analisi di Wikipedia

## Descrizione del Progetto

L'obiettivo del progetto era l'analisi e la classificazione di un corpus di articoli proveniente da Wikipedia tramite l'utilizzo di tecniche per i Big Data come Pyspark.

## Il Dataset

Il dataset fornito consiste in un file CSV contenente circa 150000 record, ognuno rappresentante un articolo di cui sono stati misurati:

*  Il titolo.
*  Un riepilogo del contenuto.
*  Il corpo dell'articolo.
*  La categoria di riferimento.

## Struttura del Repository

Il progetto è organizzato come segue:

*  `notebooks/`: Il Jupiter Notebook in cui sono descritte le fasi del progetto.
*  `README.md`: Questa guida descrittiva.

Il file CSV contenente i dati è stato importato tramite link esterno direttamente nel progetto, pertanto non è incluso in questo repository.

## Metodologia e Fasi del Lavoro

Una volta importato ed esplorato il dataset, è stato addestrato un modello di classificazione testuale che a partire dai contenuto dell'articolo ne individuasse la categoria, per poi analizzare a fondo le performance del modello. Dati i limiti del software utilizzato, parte del progetto (ad esempio, il clustering sugli errori del modello) è stato svolto in Pandas e Scikit-Learn.

##Tecnologie e Librerie Utilizzate
*  **Linguaggio principale:** Python, Pyspark
*  **Visualizzazione:** Databricks
*  **Altre librerie:** Pandas, Scikit-learn

---
*Progetto realizzato da **[Beatrice Taffetani](https://github.com/BTaffetani/beatrice-taffetani/blob/main/README.md)***
