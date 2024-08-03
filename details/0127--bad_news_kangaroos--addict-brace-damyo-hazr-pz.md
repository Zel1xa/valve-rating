### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, hazr, pz<br />
Global Rank: [127](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
<br />
Final Rank Value:  784.7<br />
<br />
Final Rank Value (784.7) = Starting Rank Value (762.3) + Head To Head Adjustments (22.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.100[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.3
- 400 + ( ( 0.177 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 762.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2277 | 2024-05-03 | FURIA       | L   | 0.586      | -            | -                | -                | -         |    -0.17 | ADDICT, BRACE, damyo, hazr, pz      |
|           26 |     2324 | 2024-05-01 | ENCE        | L   | 0.573      | -            | -                | -                | -         |    -0.57 | ADDICT, BRACE, damyo, hazr, pz      |
|           25 |     2356 | 2024-04-30 | MOUZ        | L   | 0.565      | -            | -                | -                | -         |    -0.06 | ADDICT, BRACE, damyo, hazr, pz      |
|           24 |     2578 | 2024-04-20 | FlyQuest    | L   | 0.498      | -            | -                | -                | -         |    -1.59 | ADDICT, BRACE, damyo, hazr, pz      |
|           23 |     2582 | 2024-04-19 | Rooster     | W   | 0.497      | 0.143        | 0.010 (0.001)    | 0.275 (0.020)    | 0 (0.000) |     8.26 | ADDICT, BRACE, damyo, hazr, pz      |
|           22 |     2625 | 2024-04-19 | Mindfreak   | W   | 0.492      | 0.143        | 0.004 (0.000)    | 0.214 (0.015)    | 0 (0.000) |     6.00 | ADDICT, BRACE, damyo, hazr, pz      |
|           21 |     2630 | 2024-04-18 | Rooster     | L   | 0.490      | -            | -                | -                | -         |    -7.28 | ADDICT, BRACE, damyo, hazr, pz      |
|           20 |     2879 | 2024-04-10 | Rooster     | W   | 0.431      | 0.333        | 0.010 (0.001)    | 0.275 (0.040)    | 0 (0.000) |     7.20 | ADDICT, BRACE, damyo, hazr, pz      |
|           19 |     2886 | 2024-04-10 | Rooster     | L   | 0.431      | -            | -                | -                | -         |    -6.53 | ADDICT, BRACE, damyo, hazr, pz      |
|           18 |     3112 | 2024-04-03 | DXA         | W   | 0.385      | 0.333        | 0.002 (0.000)    | 0.235 (0.030)    | 0 (0.000) |     4.38 | ADDICT, BRACE, damyo, hazr, pz      |
|           17 |     3117 | 2024-04-03 | DXA         | W   | 0.384      | 0.333        | 0.002 (0.000)    | 0.235 (0.030)    | 0 (0.000) |     4.52 | ADDICT, BRACE, damyo, hazr, pz      |
|           16 |     3238 | 2024-03-27 | Mindfreak   | L   | 0.338      | -            | -                | -                | -         |    -6.98 | ADDICT, BRACE, damyo, hazr, pz      |
|           15 |     3243 | 2024-03-27 | Mindfreak   | W   | 0.338      | 0.333        | 0.004 (0.000)    | 0.053 (0.006)    | 0 (0.000) |     3.73 | ADDICT, BRACE, damyo, hazr, pz      |
|           14 |     3284 | 2024-03-23 | DXA         | W   | 0.311      | 0.315        | 0.002 (0.000)    | 0.235 (0.023)    | 1 (0.311) |     3.78 | ADDICT, BRACE, damyo, hazr, pz      |
|           13 |     3286 | 2024-03-23 | Arcade      | W   | 0.311      | 0.315        | 0.002 (0.000)    | 0.142 (0.014)    | 1 (0.311) |     3.69 | ADDICT, BRACE, damyo, hazr, pz      |
|           12 |     3344 | 2024-03-20 | Canon Event | W   | 0.291      | -            | -                | -                | 0 (0.000) |     1.75 | ADDICT, BRACE, damyo, hazr, pz      |
|           11 |     3345 | 2024-03-20 | Canon Event | W   | 0.291      | -            | -                | -                | -         |     1.78 | ADDICT, BRACE, damyo, hazr, pz      |
|           10 |     3415 | 2024-03-15 | Gods Reign  | L   | 0.264      | -            | -                | -                | -         |    -4.05 | ADDICT, BRACE, hazr, pz, yourwombat |
|            9 |     3435 | 2024-03-14 | GRDX        | W   | 0.257      | 0.432        | 0.002 (0.000)    | -                | 1 (0.257) |     1.76 | ADDICT, BRACE, hazr, pz, yourwombat |
|            8 |     3468 | 2024-03-14 | Aurora      | L   | 0.251      | -            | -                | -                | -         |    -0.05 | ADDICT, BRACE, hazr, pz, yourwombat |
|            7 |     3679 | 2024-03-06 | Vantage     | W   | 0.198      | 0.333        | 0.002 (0.000)    | 0.074 (0.005)    | -         |     2.17 | ADDICT, BRACE, damyo, hazr, pz      |
|            6 |     3681 | 2024-03-06 | Vantage     | W   | 0.198      | 0.333        | -                | 0.074 (0.005)    | -         |     2.20 | ADDICT, BRACE, damyo, hazr, pz      |
|            5 |     3935 | 2024-02-22 | Rooster     | L   | 0.117      | -            | -                | -                | -         |    -1.75 | ADDICT, BRACE, Hatz, hazr, pz       |
|            4 |     3953 | 2024-02-22 | Vantage     | W   | 0.111      | -            | -                | -                | -         |     1.25 | ADDICT, BRACE, Hatz, hazr, pz       |
|            3 |     3956 | 2024-02-21 | FlyQuest    | L   | 0.110      | -            | -                | -                | -         |    -0.34 | ADDICT, BRACE, Hatz, hazr, pz       |
|            2 |     3977 | 2024-02-21 | FlyQuest    | L   | 0.105      | -            | -                | -                | -         |    -0.32 | ADDICT, BRACE, Hatz, hazr, pz       |
|            1 |     3983 | 2024-02-21 | FlyQuest    | L   | 0.105      | -            | -                | -                | -         |    -0.32 | ADDICT, BRACE, Hatz, hazr, pz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,489.55)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.830 | $1,050.00      | $871.84         |
| 2024-05-12 |      0.646 | $3,500.00      | $2,261.55       |
| 2024-03-23 |      0.311 | $3,308.00      | $1,029.54       |
| 2024-03-16 |      0.265 | $5,000.00      | $1,326.62       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
