### Roster Details<br />
Team Name: Nouns fe<br />
Roster: ashe, jesscas, katalyyst, lunari, raynee<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [51]( ../standings_americas.md)<br />
<br />
Final Rank Value:  608.2<br />
<br />
Final Rank Value (608.2) = Starting Rank Value (644.2) + Head To Head Adjustments (-36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.289[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 644.2
- 400 + ( ( 0.119 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 644.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      228 | 2024-07-28 | TSM Shimmer      | L   | 1.000      | -            | -                | -                | -         |   -12.62 | ashe, jesscas, katalyyst, lunari, raynee |
|            9 |      900 | 2024-06-30 | Lotus fe         | L   | 0.970      | -            | -                | -                | -         |   -15.07 | ashe, daria, jesscas, katalyyst, raynee  |
|            8 |     2659 | 2024-04-19 | FlyQuest RED     | L   | 0.490      | -            | -                | -                | -         |    -5.33 | ashe, katalyyst, Knopk@, lunari, tokkis  |
|            7 |     2881 | 2024-04-11 | Limitless Angels | L   | 0.437      | -            | -                | -                | -         |    -6.99 | ashe, jesscas, katalyyst, lunari, tokkis |
|            6 |     3105 | 2024-04-04 | cleanup crew fe  | W   | 0.390      | 0.322        | 0.002 (0.000)    | 0.021 (0.003)    | 0 (0.000) |     5.86 | ashe, jesscas, katalyyst, lunari, tokkis |
|            5 |     3280 | 2024-03-27 | Karma            | L   | 0.337      | -            | -                | -                | -         |    -5.26 | ashe, jesscas, katalyyst, lunari, tokkis |
|            4 |     3377 | 2024-03-21 | COVEN            | W   | 0.297      | 0.322        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.20 | ashe, jesscas, katalyyst, lunari, tokkis |
|            3 |     3520 | 2024-03-14 | TSM Shimmer      | L   | 0.251      | -            | -                | -                | -         |    -3.32 | ashe, jesscas, katalyyst, lunari, Rice   |
|            2 |     3731 | 2024-03-06 | WG Bandits       | W   | 0.197      | 0.322        | 0.002 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     2.95 | ashe, jesscas, katalyyst, lunari, Rice   |
|            1 |     4274 | 2024-02-13 | COVEN            | W   | 0.050      | 0.143        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.56 | ashe, jesscas, katalyyst, lunari, Rice   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,130.33)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $250.00        | $250.00         |
| 2024-06-30 |      0.970 | $250.00        | $242.60         |
| 2024-04-19 |      0.491 | $1,300.00      | $637.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
