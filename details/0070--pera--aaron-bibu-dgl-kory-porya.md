### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.4<br />
<br />
Final Rank Value (956.4) = Starting Rank Value (930.7) + Head To Head Adjustments (25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.371[<sup>2</sup>](#table1)
- Opponent Network: 0.171[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.7
- 400 + ( ( 0.259 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 930.7


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
|           35 |      157 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.73 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      205 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.406 (0.203)    | 0 (0.000) |    11.43 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      241 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.52 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      565 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.86 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      603 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.29 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      672 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.299 (0.100)    | 0 (0.000) |     8.90 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      732 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.47 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      782 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.82 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1100 | 2024-06-13 | Enterprise        | W   | 0.852      | 0.379        | 0.039 (0.013)    | 0.625 (0.202)    | 0 (0.000) |    12.10 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1132 | 2024-06-12 | Rebels            | W   | 0.845      | 0.379        | 0.038 (0.012)    | 0.600 (0.192)    | 0 (0.000) |    15.14 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1154 | 2024-06-11 | ECLOT             | W   | 0.838      | 0.379        | 0.062 (0.020)    | 0.558 (0.177)    | 0 (0.000) |    19.91 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1351 | 2024-06-07 | B8                | L   | 0.811      | -            | -                | -                | -         |    -6.74 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1361 | 2024-06-07 | Aurora            | L   | 0.810      | -            | -                | -                | -         |    -1.03 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1465 | 2024-06-05 | The Prodigies     | W   | 0.798      | -            | -                | -                | 0 (0.000) |     2.69 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1545 | 2024-06-03 | GL Academy        | W   | 0.785      | -            | -                | -                | 0 (0.000) |     6.47 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1654 | 2024-05-30 | Rebels            | L   | 0.758      | -            | -                | -                | -         |   -10.51 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1835 | 2024-05-22 | System5           | W   | 0.705      | -            | -                | -                | 0 (0.000) |     3.90 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1879 | 2024-05-21 | EYEBALLERS        | W   | 0.698      | 0.500        | -                | 0.509 (0.178)    | -         |     8.74 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1918 | 2024-05-20 | Nexus             | W   | 0.691      | 0.379        | 0.014 (0.004)    | 0.465 (0.122)    | -         |     6.55 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2086 | 2024-05-15 | Norway            | W   | 0.658      | 0.500        | 0.006 (0.002)    | -                | -         |     4.36 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2147 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.651      | 0.500        | 0.031 (0.010)    | 0.560 (0.182)    | -         |    11.78 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2373 | 2024-05-04 | FlyQuest          | L   | 0.583      | -            | -                | -                | -         |    -3.55 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2388 | 2024-05-03 | BIG               | L   | 0.576      | -            | -                | -                | -         |    -2.12 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2409 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.570      | 0.889        | 0.254 (0.129)    | 0.553 (0.280)    | 1 (0.570) |    17.62 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2455 | 2024-04-30 | Complexity        | L   | 0.557      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2666 | 2024-04-20 | EYEBALLERS        | L   | 0.491      | -            | -                | -                | -         |    -8.52 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3206 | 2024-04-03 | SAW               | L   | 0.377      | -            | -                | -                | -         |    -2.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3261 | 2024-04-01 | RUSH B            | W   | 0.364      | 0.500        | 0.026 (0.005)    | 0.386 (0.070)    | -         |     5.01 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3538 | 2024-03-15 | Betera            | L   | 0.251      | -            | -                | -                | -         |    -6.17 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3597 | 2024-03-13 | Monte             | L   | 0.238      | -            | -                | -                | -         |    -3.03 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3976 | 2024-02-26 | System5           | L   | 0.132      | -            | -                | -                | -         |    -3.33 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4114 | 2024-02-20 | ex-Preasy         | L   | 0.091      | -            | -                | -                | -         |    -2.01 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4142 | 2024-02-19 | GamerLegion       | L   | 0.084      | -            | -                | -                | -         |    -1.88 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4145 | 2024-02-19 | Cloud9            | L   | 0.083      | -            | -                | -                | -         |    -0.94 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4213 | 2024-02-16 | SINNERS           | L   | 0.064      | -            | -                | -                | -         |    -0.47 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,400.50)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.852 | $10,895.00     | $9,277.90       |
| 2024-06-09 |      0.824 | $500.00        | $412.05         |
| 2024-05-12 |      0.637 | $7,000.00      | $4,460.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
