# sports-betting-strat

## Up Down Market Analysis
- This is a simplifed tool meant for a simple over/under market (will a player perform more or higher of some stat from a previous game)
- Finds highest EV configuration of certain stats (each stat is seperated into a different parlay)
- Useful when there are free square promos for risk-free 1->2 pick parlay
- Option to use Minimal EV which uses either lower bound or upper bound (depending on if its for the probability that a parlay hits or failes) of confidence interval for probabilities
- Simple backtesting funcionality

## Paired Parlay Strategy (Tested not very good)
- This strategy is meant to try and find +EV parlay pairs using dependent stats on a single player
- TODO: Implement a etter lines approximation, currently just a running mean weighted towards the latest result (historical approximation)
