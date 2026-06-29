# Talend Selection ETL

A Talend Open Studio ETL project that demonstrates reading multiple CSV files, joining datasets, sorting records, filtering data, and exporting the results to text files.

## Features

- Import data from delimited files
- Join datasets using tMap
- Sort records alphabetically
- Filter rows based on email availability
- Export processed data into multiple output files

## Technologies

- Talend Open Studio for Data Integration 8.0.1
- Java
- CSV Files

## Project Structure

- Personne.csv (Input)
- Email.csv (Input)
- tMap
- tSortRow
- tFilterRow
- Output Files
  - out2.txt
  - filter.txt
  - Nv-de.txt

## Workflow

1. Read Personne data.
2. Read Email data.
3. Merge datasets using tMap.
4. Sort data by the `nom` column.
5. Filter rows containing valid email values.
6. Export processed results.

## Learning Objectives

- Working with multiple input sources
- Data mapping and joins
- Sorting and filtering
- File output generation

## Built With

Talend Open Studio for Data Integration 8
