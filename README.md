# fencing-machine-learning

## Download the Data

To download the data make sure you have your kaggle api key setup in ~/.kaggle

`kaggle datasets download -d amichaelsen/fie-fencing-womens-foil-data`

## Hypothesis

Model will predict that points in bout table are highest predictor

Use Shap to validate. Then train without those columns

## ToDos

- [x] EDA on data
- [x] Remove `bio.Name`, `bio.url`, `bio.date_accessed`, 
- [x] Drop `bio.id` after any joins
- [ ] Foil, Epee and Sabre in Ranking are not balanced if needed
  - [ ] Ranking has duplicate rows
- [x] Bouts has no missing data at all
- [x] Bouts `upset` is biased towards False
- [x] Bouts drop date
- [ ] Might need tournament df for category to join on bouts? investigate this
- [x] Bouts drop 'fencer_curr_pts', 'opp_curr_pts', 'tournament_ID' for now
- [x] Compare bout age vs bio age in EDA
- [x] Remove age from bio since its in bouts