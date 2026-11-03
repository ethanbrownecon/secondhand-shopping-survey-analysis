# Second Hand Shopping Survey Analysis

An exploratory analysis of survey responses about second hand clothing, built for a data management and data science course at Berry College to inform the planning of a campus resale market.

## Question

Who would shop at a campus second hand clothing market, and what do they want in terms of timing, location, motivation, and price?

## Why it matters

A resale market only works if it matches what shoppers prefer. Summarizing the survey gives organizers a data based starting point for choosing days, locations, and pricing.

## Approach

The notebook organizes the questions around respondent characteristics, shopping behavior, timing, purchase locations, motivations, and willingness to pay. It counts multi select answers such as preferred shopping days and locations and uses descriptive summaries and charts. Results describe this survey's respondents and should not be generalized beyond them.

## Data and privacy

The original survey includes names and response level information, so it is not included. To run the notebook, add an authorized copy at `data/secondhand_shopping_survey.csv`. The notebook drops the timestamp, name, and empty export columns before analysis. Do not commit the source file or any respondent level records.

## Run

```bash
python -m pip install -r requirements.txt
jupyter lab analysis.ipynb
```
