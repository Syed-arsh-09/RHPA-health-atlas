# Raw Data (NFHS Dataset)

The raw dataset used in this project is not included in this repository due to its large size.

## Dataset Sources

This project uses data from:

- National Family Health Survey (NFHS-5)
- Official website: https://dhsprogram.com/

## Files Used

- IR Dataset (Individual Recode) — ~5GB
- KR Dataset (Kids Recode) — ~80MB

## How to Download

1. Go to: https://dhsprogram.com/
2. Create a free account
3. Request access to NFHS-5 India dataset
4. Download:
   - IR file (.DTA)
   - KR file (.DTA)

## Where to Place Files

After downloading, place them in:

data/raw/

Example:

data/raw/
├── ir_data.dta
├── kr_data.dta

## Note

These files are required to run the preprocessing notebooks.