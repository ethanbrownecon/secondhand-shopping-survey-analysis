# Second-hand Shopping Survey Analysis

An exploratory survey analysis focused on second-hand clothing preferences and
the planning of a campus resale market. The notebook organizes the questions
around respondent characteristics, shopping behavior, timing, purchasing
locations, motivations, and willingness to pay.

## Data and privacy

The original survey includes names and response-level information. It is not
included in this repository. Before running the notebook, place an authorized
copy at `data/secondhand_shopping_survey.csv`. The notebook removes the
timestamp, name, and empty export column before analysis. Do not commit the
source file or other respondent-level records.

## Run the notebook

```bash
python -m pip install -r requirements.txt
jupyter lab analysis.ipynb
```

The survey CSV is required and must contain the columns referenced in the
notebook. Since the underlying responses are not distributed here, the
notebook does not include rendered results.

## Approach

- Summarize responses about audience characteristics and purchasing habits.
- Count multi-select answers such as preferred shopping days and locations.
- Explore motivations and willingness-to-pay responses.
- Use descriptive summaries and visualizations; results describe this survey
  and should not be generalized beyond its respondents.
