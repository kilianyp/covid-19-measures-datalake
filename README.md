# covid-19-measures-datalake
Repository containing information when and where which measurement was implemented.
The purpose is to be able to take these events into account when predicting the spread.

# Dataset description
Currently, I am planning to have these columns. Let me know if you think something should be added.

- country: Country
- region: A more granular part of the country
- measure: A text description of the implemented measurement
- date: Date when the measurement was implemented
- category: A more broader categorization of the measurement
    - events: sporting, music events
    - public life: school, university, parks
    - travel: borders, public transport
    - shop: business
- severity: On a scale from 1-5
    - 1: information: the government issues information, but does not enforce
    - 2: warning: the government warns, but does not enforce
    - 3: restrict > 1000: Gatherings of more than a 1000 people are cancelled
    - 4: restrict > 100: Gatherings of more than 100 people are cancelled
    - 5: lockdown: Complete lockdown, max 2 people and families
- source: Source of this information


The information is manually extracted mostlty from [wikipedia](https://en.wikipedia.org/wiki/Category:2019%E2%80%9320_coronavirus_pandemic_by_country_and_territory).

Contributions welcome.

Copied from https://github.com/CSSEGISandData/COVID-19

This GitHub repo and its contents herein, including all data, mapping, and analysi, all rights reserved, is provided to the public strictly for educational and academic research purposes. The Website relies upon publicly available data from multiple sources, that do not always agree. I hereby disclaims any and all representations and warranties with respect to the Website, including accuracy, fitness for use, and merchantability. Reliance on the Website for medical guidance or use of the Website in commerce is strictly prohibited.
