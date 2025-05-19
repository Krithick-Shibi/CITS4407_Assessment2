# CITS4407_Assessment2

This project contains three Bash scripts which will check the data quality, handle empty cells, clean the data, analyse and answer the research questions like:
 What is the most popular domain and most popular mechanics across the set of games (Appearance in a given game's list counts as 1.)?
 What is the correlation between publication year and average rating, e.g. newer games being preferred over older ones?
 What is the correlation between game complexity and average rating?

## Summary

### 1. empty_cells
The empty_cells script counts the number of empty cells in each column of the uploaded file.

**Usage:**
```bash
./empty_cells <filename> <separator>
```
**Example**
```bash
./empty_cells <bgg_dataset> <;>
```

### 2. Preprocess
The preprocess script cleans and normalize the semicolon-separated datasets
**Usage:** 
```bash
./preprocess <filename.ectention> > <nex_filename.extention>
```
**Example**
```bash
./preprocess <sample.txt> > <sample.tsv>
```
### 3. Analysis
This analysis script Analyze cleaned dataset (tsv) and answers research questions
**Usage:** 
```bash
./analysis <cleaned_filename.tsv>
```
**Example**
```bash
./analysis <sample.tsv>
```
