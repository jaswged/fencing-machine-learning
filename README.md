# fencing-machine-learning

## Download the Data

To download the data make sure you have your kaggle api key setup in ~/.kaggle

`kaggle datasets download -d amichaelsen/fie-fencing-womens-foil-data`

## ToDos

- [x] EDA on data
- [x] Remove `bio.Name`, `bio.url`, `bio.date_accessed`, 
- [ ] Drop `bio.id` after any joins
- [ ] Foil, Epee and Sabre in Ranking are not balanced if needed
  - [ ] Ranking has duplicate rows
- [ ] Bouts has no missing data at all
- [ ] Bouts `upset` is biased towards False
- [ ] Bouts drop date,  
- [ ] Might need tournament df for category to join on bouts? investigate this
- [ ]