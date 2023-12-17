# Patent Intensity 
Patent factor to be fed into factor model. Calculated with (# patents / market cap) / (average patent/market cap ratio for sector)

- Currently only checking for stocks listed on nyse, amex, nasdaq


# Data
- patent_factor.csv: output of code. Tickers and corresponding patent intensity factor that can be fed into the model, see image below
- KPSS.dta: patent data. download from https://github.com/KPSS2017/Measuring-Technological-Innovation-Over-the-Long-Run-Replication-Kit/tree/master/input_data
- market_cap.csv: market cap of each stock, may want to update periodically
- patent_sector.csv: maps patent to ticker to sector
	- This is outputted from the create data section, you won't need the following files if you don't need to recreate this table
	- Run on Google Collab if it takes too long to run locally 
- nasdaq/nyse/amex_permco.csv: translates permno to tickers, downloaded from https://wrds-www.wharton.upenn.edu/pages/get-data/center-research-security-prices-crsp/annual-update/tools/translate-to-permcopermno/
	- WRDS can take list of tickers as input, download here: - https://github.com/rreichel3/US-Stock-Symbols



