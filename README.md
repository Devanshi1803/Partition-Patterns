# Partition-Patterns
Data Summarization is a simple term for a short representation of a big theory/data or a paragraph.This is the implementation of algorithm described in [Exploring and Comparing Table Fragments With Fragment Summaries](https://www.researchgate.net/publication/335961828_Exploring_and_Comparing_Table_Fragments_With_Fragment_Summaries) to generate fragment summaries for the fragmented dataset. These are pattern-based summaries for representing and analyzing fragmented datasets. These Fragment summaries can represent dataset in concise and complete manner. It can be used by many imputation methods to repair the dataset. One such method is described in [Query-Oriented Answer Imputation for Aggregate Queries](https://www.researchgate.net/publication/335437648_Query-Oriented_Answer_Imputation_for_Aggregate_Queries).
</br>
The implementation generates the patterns that are covering and minimal in the sense that they contain respectively all complete and all empty patterns of the dataset and no pattern that is subsumed by another pattern in the same dataset.

</br>
</br>
Software Setup:</br>
1. Pandas: Python library</br>
2. Jupyter Notebook</br>
3. PostgreSQL 4. Psycopg2: PostgreSQL database adapter for the Python programming language</br>
