# Fantasy Football meets Statistics

The project combines the fun of playing Fantasy Football with analytics and prediction modelling using football data.

The goal is to support each Fantasy Football coach, by helping them to select the best 11 players for the following round line-up.

The model uses historical teams' and players' performance to learn the patterns, and generate expected performance for the coach's players set. The expectations are in the shape of Fantasy Football points that would be earned the following match.

The repository is strctured in 4 folders:
- **Sourcing** : set of functions used to download and scrape data from various sources, save it to disk, and handle specific data structure choices
  - Team and players data : downloaded via API from Football API, requires an API key with an associated account
  - Players performance grades : scraped from Gazzetta.it
- **Manipulating** : set of functions to combine the downloaded data into master files, team data files, player data files
- **Utils** : set of functions used across the board, sourced directly from other scripts
- **Modelling** : set of functions to create the data features and targets, train the model, predict, analyse the outcome

The project is currently running in its Beta version, improvements on the datasets, the feature enginnering, and the modelling can be expected.
