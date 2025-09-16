# sports-betting-strat

## Up Down Market Analysis
- This is a simplifed tool meant for a simple over/under market (will a player perform more or higher of some stat from a previous game)
- Finds highest EV configuration of certain stats (each stat is seperated into a different parlay)
- Useful when there are promos for risk-free 1->2 pick parlay

## Paired Parlay Strategy (Tested not very good)
- This strategy is meant to try and find +EV parlay pairs using dependent stats on a single player
- TODO: Implement a etter lines approximation, currently just a running mean weighted towards the latest result (historical approximation)
