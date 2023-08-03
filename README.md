# Pokemon-Combat-Analyzer
## Aggregation Scenarios using MongoDB

**Note: This file demonstrates the use of MongoDB as the database.**

### Scenario 1 - Ganadores01.combats.json:

This code allows combining information from two collections in the database. Specifically, it looks for details of the Pokémon involved in each combat. Then, it projects only the names of the Pokémon to display the two fighters and the winner's name in each combat.

### Scenario 2 - ContadorDGanadas.combats.json:

In this code, a calculation of Pokémon victories is performed. Combat records are grouped by the winning Pokémon, and the number of victories for each one is counted. The name of the Pokémon and the number of victories are then displayed, sorted from highest to lowest.

