# docs_to_csvs
Go through a folder and convert .txt or .docx files with a CSV-like format to CSV

## folder structure

So the script will run through all folders, get the .txt files and convert to CSV
Also will handle .zip files full of .txt files

Put the script in the same directory, so something like

```
|-- CECL-TDR.ED.026.NAFCU JAMES AKIN,0.pdf
|-- CECL.docx
|-- CR 2022-06.zip
```

Will become

```
|-- CECL-TDR.ED.026.NAFCU JAMES AKIN,0.pdf
|-- CECL.docx
|-- CR 2022-06
|   |-- ATM Locations.txt
|   |-- Acct-DescGrants.txt
|   |-- Acct-DescTradeNames.txt
|   |-- AcctDesc.txt
|   |-- Credit Union Branch Information.txt
|   |-- FOICU.txt
|   |-- FOICUDES.txt
|   |-- FS220.txt
|   |-- FS220A.txt
|   |-- FS220B.txt
|   |-- FS220C.txt
|   |-- FS220D.txt
|   |-- FS220G.txt
|   |-- FS220H.txt
|   |-- FS220I.txt
|   |-- FS220J.txt
|   |-- FS220K.txt
|   |-- FS220L.txt
|   |-- FS220M.txt
|   |-- FS220N.txt
|   |-- FS220P.txt
|   |-- FS220Q.txt
|   |-- FS220R.txt
|   |-- Grants.txt
|   |-- Readme.txt
|   |-- Report1.txt
|   `-- TradeNames.txt
|-- CR 2022-06.zip
|-- CR 2022-06_CSVs
|   |-- ATM Locations.csv
|   |-- Acct-DescGrants.csv
|   |-- Acct-DescTradeNames.csv
|   |-- AcctDesc.csv
|   |-- Credit Union Branch Information.csv
|   |-- FOICU.csv
|   |-- FOICUDES.csv
|   |-- FS220.csv
|   |-- FS220A.csv
|   |-- FS220B.csv
|   |-- FS220C.csv
|   |-- FS220D.csv
|   |-- FS220G.csv
|   |-- FS220H.csv
|   |-- FS220I.csv
|   |-- FS220J.csv
|   |-- FS220K.csv
|   |-- FS220L.csv
|   |-- FS220M.csv
|   |-- FS220N.csv
|   |-- FS220P.csv
|   |-- FS220Q.csv
|   |-- FS220R.csv
|   |-- Grants.csv
|   |-- Readme.csv
|   |-- Report1.csv
|   `-- TradeNames.csv
|-- Credit Unions.docx
```
