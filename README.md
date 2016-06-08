# hedge-favourites
The aim of this project is to pull in the holdings of the largest US hedge funds from SEC 13F forms in order to compare price action to increases/decreases in the portfolio concentration changes.

## Holdings Scrape
- [ ] 1. Map where the information is located and the best way to collect from <https:/www.sec.gov/Archives/edgar/data/[CIK No]/[Accession No-YY-xxxxxx]>. This will probably require an initial step to pull all the html links on each CIK for SEC form 13F, and scrape them to backfill (they will have a different year -> YY and xxxxxx identifier. Then automate the process to pull data from new submissions.
- [ ] 2. Compile list of Funds of Interest (FoI) and their related CIK numbers.
- [ ] 3. On a test CIK, pull all holdings data going back as far as possible (how far is that online?) to a usuable format (.csv?). Should be possible to then loop this code over all relevant CIKs and Accession No's.
    
## Price Data
- [ ] ---[Use a free service such as Yahoo API? Need to investigate where too get price info, tick data not required]---
