[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/maciejskorski/sqlfluff-lineage/blob/main/sqlfluff_lineage.ipynb)
[![nbviewer](https://img.shields.io/badge/render-nbviewer-orange.svg)](https://nbviewer.org/github/maciejskorski/sqlfluff-lineage/blob/main/sqlfluff_lineage.ipynb)

# SQL Lineage with sqlfluff

The repository shows how to use the sqlfluff parser to obtain the table lineage on complex ClickHouse queries.

The main idea is to use [sqlfluff](https://github.com/sqlfluff/sqlfluff) as the parser, and then extract the Abstract Syntax Tree into the convenient [anytree format](https://github.com/c0fec0de/anytree).
See the notebook for the details.

The final result, obtained on a large ClickHouse query, looks as below:

![ClickHouse ETL lineage](lineage_clickhouse.svg)

