# Big data: Analisi di Wikipedia

Svolgimento di un'analisi esplorativa per valutare statisticamente il contenuto informativo offerto da Wikipedia, e classificazione testuale degli articoli. Viene usato Apache Spark.

# Descrizione
Viene fornito un bump di 150k articoli di Wikipedia. Il dataset è composto dalle seguenti colonne:
* **title**: titolo dell'articolo
* **summary**: introduzione dell'articolo
* **documents**: l'articolo completo
* **category**: la categoria associata all'articolo

  
Per ogni categoria, vengono calcolate le seguenti informazioni:
* Numero di articoli
* Numero medio di parole utilizzate
* Numero di parole presenti nell’articolo più lungo
* Numero di parole presenti nell’articolo più corto
* Per ogni categoria, individuare la nuvola di parole più rappresentativa

Inoltre, viene addestrato un classificatore testuale capace di classificare gli articoli che saranno in futuro inseriti, sia considerando la colonna ***summary*** sia la colonna ***documents***.


Per visualizzare il notebook, si può importare il file in formato .dbc (Databricks archive) nel workspace di databricks in  [questo modo](https://docs.databricks.com/en/notebooks/notebook-export-import.html).

