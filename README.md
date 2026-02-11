# BGC Filter

A Python script for filtering Biosynthetic Gene Cluster (BGC) data from antiSMASH JSON outputs.

## Features

- Parse antiSMASH prediction results (JSON format)
- Filter BGC data based on customizable criteria
- Export structured results to CSV
- Includes MIBiG test dataset for validation

## Requirements

- Python 3.8+
- pandas &gt;= 1.3.0
- numpy &gt;= 1.21.0

## Run

```bash
python3 Antismash_json.py Mibig_Test Mibig_Test_Output.csv
```
