### Roster Details<br />
Team Name: Nouns fe<br />
Roster: ashe, jesscas, katalyyst, lunari, raynee<br />
Global Rank: [186](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  610.9<br />
<br />
Final Rank Value (610.9) = Starting Rank Value (647.2) + Head To Head Adjustments (-36.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.190[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 647.2
- 400 + ( ( 0.120 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 647.2


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
|           10 |      140 | 2024-07-28 | TSM Shimmer      | L   | 1.000      | -            | -                | -                | -         |   -12.58 | ashe, jesscas, katalyyst, lunari, raynee |
|            9 |      830 | 2024-06-30 | Lotus fe         | L   | 0.990      | -            | -                | -                | -         |   -15.38 | ashe, daria, jesscas, katalyyst, raynee  |
|            8 |     2642 | 2024-04-19 | FlyQuest RED     | L   | 0.510      | -            | -                | -                | -         |    -5.46 | ashe, katalyyst, Knopk@, lunari, tokkis  |
|            7 |     2869 | 2024-04-11 | Limitless Angels | L   | 0.457      | -            | -                | -                | -         |    -7.30 | ashe, jesscas, katalyyst, lunari, tokkis |
|            6 |     3093 | 2024-04-04 | cleanup crew fe  | W   | 0.410      | 0.322        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     6.14 | ashe, jesscas, katalyyst, lunari, tokkis |
|            5 |     3276 | 2024-03-27 | Karma            | L   | 0.357      | -            | -                | -                | -         |    -5.57 | ashe, jesscas, katalyyst, lunari, tokkis |
|            4 |     3378 | 2024-03-21 | COVEN            | W   | 0.317      | 0.322        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.38 | ashe, jesscas, katalyyst, lunari, tokkis |
|            3 |     3521 | 2024-03-14 | TSM Shimmer      | L   | 0.270      | -            | -                | -                | -         |    -3.58 | ashe, jesscas, katalyyst, lunari, Rice   |
|            2 |     3738 | 2024-03-06 | WG Bandits       | W   | 0.217      | 0.322        | 0.002 (0.000)    | 0.022 (0.002)    | 0 (0.000) |     3.24 | ashe, jesscas, katalyyst, lunari, Rice   |
|            1 |     4296 | 2024-02-13 | COVEN            | W   | 0.070      | 0.143        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.77 | ashe, jesscas, katalyyst, lunari, Rice   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,160.47)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $250.00        | $250.00         |
| 2024-06-30 |      0.990 | $250.00        | $247.47         |
| 2024-04-19 |      0.510 | $1,300.00      | $663.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
