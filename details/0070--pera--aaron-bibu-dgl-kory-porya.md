### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.8<br />
<br />
Final Rank Value (956.8) = Starting Rank Value (931.2) + Head To Head Adjustments (25.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.371[<sup>2</sup>](#table1)
- Opponent Network: 0.171[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.2
- 400 + ( ( 0.259 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 931.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      170 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.73 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      218 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.445 (0.222)    | 0 (0.000) |    11.55 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      254 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.53 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      578 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.84 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      616 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.29 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      685 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.298 (0.099)    | 0 (0.000) |     8.92 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      745 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.46 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      795 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.82 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1113 | 2024-06-13 | Enterprise        | W   | 0.848      | 0.379        | 0.039 (0.013)    | 0.624 (0.200)    | 0 (0.000) |    12.05 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1145 | 2024-06-12 | Rebels            | W   | 0.841      | 0.379        | 0.038 (0.012)    | 0.598 (0.191)    | 0 (0.000) |    15.05 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1167 | 2024-06-11 | ECLOT             | W   | 0.835      | 0.379        | 0.062 (0.020)    | 0.557 (0.176)    | 0 (0.000) |    19.83 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1364 | 2024-06-07 | B8                | L   | 0.807      | -            | -                | -                | -         |    -6.72 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1374 | 2024-06-07 | Aurora            | L   | 0.807      | -            | -                | -                | -         |    -1.02 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1478 | 2024-06-05 | The Prodigies     | W   | 0.795      | -            | -                | -                | 0 (0.000) |     2.67 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1558 | 2024-06-03 | GL Academy        | W   | 0.781      | -            | -                | -                | 0 (0.000) |     6.42 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1667 | 2024-05-30 | Rebels            | L   | 0.755      | -            | -                | -                | -         |   -10.50 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1848 | 2024-05-22 | System5           | W   | 0.701      | -            | -                | -                | 0 (0.000) |     3.87 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1892 | 2024-05-21 | EYEBALLERS        | W   | 0.695      | 0.500        | -                | 0.507 (0.176)    | -         |     8.68 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1931 | 2024-05-20 | Nexus             | W   | 0.687      | 0.379        | 0.014 (0.004)    | 0.464 (0.121)    | -         |     6.52 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2099 | 2024-05-15 | Norway            | W   | 0.655      | 0.500        | 0.006 (0.002)    | -                | -         |     4.32 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2160 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.648      | 0.500        | 0.031 (0.010)    | 0.557 (0.181)    | -         |    11.70 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2386 | 2024-05-04 | FlyQuest          | L   | 0.580      | -            | -                | -                | -         |    -3.57 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2401 | 2024-05-03 | BIG               | L   | 0.573      | -            | -                | -                | -         |    -2.11 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2422 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.567      | 0.889        | 0.254 (0.128)    | 0.551 (0.278)    | 1 (0.567) |    17.52 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2468 | 2024-04-30 | Complexity        | L   | 0.554      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2679 | 2024-04-20 | EYEBALLERS        | L   | 0.488      | -            | -                | -                | -         |    -8.48 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3219 | 2024-04-03 | SAW               | L   | 0.374      | -            | -                | -                | -         |    -2.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3274 | 2024-04-01 | RUSH B            | W   | 0.361      | 0.500        | 0.026 (0.005)    | 0.385 (0.069)    | -         |     4.95 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3551 | 2024-03-15 | Betera            | L   | 0.248      | -            | -                | -                | -         |    -6.09 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3610 | 2024-03-13 | Monte             | L   | 0.235      | -            | -                | -                | -         |    -3.01 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3989 | 2024-02-26 | System5           | L   | 0.128      | -            | -                | -                | -         |    -3.25 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4127 | 2024-02-20 | ex-Preasy         | L   | 0.088      | -            | -                | -                | -         |    -1.94 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4155 | 2024-02-19 | GamerLegion       | L   | 0.081      | -            | -                | -                | -         |    -1.81 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4158 | 2024-02-19 | Cloud9            | L   | 0.080      | -            | -                | -                | -         |    -0.91 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4226 | 2024-02-16 | SINNERS           | L   | 0.061      | -            | -                | -                | -         |    -0.45 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,339.19)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.848 | $10,895.00     | $9,241.58       |
| 2024-06-09 |      0.821 | $500.00        | $410.38         |
| 2024-05-12 |      0.634 | $7,000.00      | $4,437.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
