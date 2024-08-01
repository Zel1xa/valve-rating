### Roster Details<br />
Team Name: Nouns fe<br />
Roster: ashe, jesscas, katalyyst, lunari, raynee<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  610.5<br />
<br />
Final Rank Value (610.5) = Starting Rank Value (646.9) + Head To Head Adjustments (-36.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.190[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 646.9
- 400 + ( ( 0.120 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 646.9


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
|           10 |      144 | 2024-07-28 | TSM Shimmer      | L   | 1.000      | -            | -                | -                | -         |   -12.58 | ashe, jesscas, katalyyst, lunari, raynee |
|            9 |      834 | 2024-06-30 | Lotus fe         | L   | 0.988      | -            | -                | -                | -         |   -15.36 | ashe, daria, jesscas, katalyyst, raynee  |
|            8 |     2646 | 2024-04-19 | FlyQuest RED     | L   | 0.508      | -            | -                | -                | -         |    -5.45 | ashe, katalyyst, Knopk@, lunari, tokkis  |
|            7 |     2873 | 2024-04-11 | Limitless Angels | L   | 0.455      | -            | -                | -                | -         |    -7.27 | ashe, jesscas, katalyyst, lunari, tokkis |
|            6 |     3097 | 2024-04-04 | cleanup crew fe  | W   | 0.408      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     6.12 | ashe, jesscas, katalyyst, lunari, tokkis |
|            5 |     3280 | 2024-03-27 | Karma            | L   | 0.355      | -            | -                | -                | -         |    -5.54 | ashe, jesscas, katalyyst, lunari, tokkis |
|            4 |     3382 | 2024-03-21 | COVEN            | W   | 0.315      | 0.322        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.37 | ashe, jesscas, katalyyst, lunari, tokkis |
|            3 |     3525 | 2024-03-14 | TSM Shimmer      | L   | 0.269      | -            | -                | -                | -         |    -3.56 | ashe, jesscas, katalyyst, lunari, Rice   |
|            2 |     3742 | 2024-03-06 | WG Bandits       | W   | 0.215      | 0.322        | 0.002 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     3.22 | ashe, jesscas, katalyyst, lunari, Rice   |
|            1 |     4300 | 2024-02-13 | COVEN            | W   | 0.068      | 0.143        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.75 | ashe, jesscas, katalyyst, lunari, Rice   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,158.31)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $250.00        | $250.00         |
| 2024-06-30 |      0.988 | $250.00        | $247.12         |
| 2024-04-19 |      0.509 | $1,300.00      | $661.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
