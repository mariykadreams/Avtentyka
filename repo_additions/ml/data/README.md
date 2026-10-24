# Дані

`raw/` не комітимо: ліцензія MSR-SSLA дозволяє лише некомерційне використання.
Ноутбук `ml/notebooks/mrpc_eda.ipynb` сам завантажує файли
`msr_paraphrase_train.txt` і `msr_paraphrase_test.txt` у `ml/data/raw/`, якщо їх немає.

Джерело: Dolan W. B., Brockett C. Automatically Constructing a Corpus of Sentential Paraphrases, 2005.
Офіційна сторінка: https://www.microsoft.com/en-us/download/details.aspx?id=52398

Для .gitignore:

    ml/data/raw/
    ml/data/mrpc_features.csv
