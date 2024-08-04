### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [69](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.8<br />
<br />
Final Rank Value (956.8) = Starting Rank Value (928.8) + Head To Head Adjustments (28.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.8
- 400 + ( ( 0.259 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 928.8


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
|           35 |      118 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      166 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.406 (0.203)    | 0 (0.000) |    11.61 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      201 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.52 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      526 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.90 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      561 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.69 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      633 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.299 (0.100)    | 0 (0.000) |     8.79 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      692 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.56 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      743 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.18 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1060 | 2024-06-13 | Enterprise        | W   | 0.859      | 0.379        | 0.039 (0.013)    | 0.624 (0.203)    | 0 (0.000) |    12.22 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1092 | 2024-06-12 | Rebels            | W   | 0.852      | 0.379        | 0.038 (0.012)    | 0.599 (0.193)    | 0 (0.000) |    15.32 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1114 | 2024-06-11 | ECLOT             | W   | 0.845      | 0.379        | 0.063 (0.020)    | 0.559 (0.179)    | 0 (0.000) |    20.04 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1311 | 2024-06-07 | B8                | L   | 0.818      | -            | -                | -                | -         |    -6.78 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1321 | 2024-06-07 | Aurora            | L   | 0.817      | -            | -                | -                | -         |    -1.06 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1425 | 2024-06-05 | The Prodigies     | W   | 0.805      | -            | -                | -                | 0 (0.000) |     2.75 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1505 | 2024-06-03 | GL Academy        | W   | 0.792      | 0.379        | 0.007 (0.002)    | -                | 0 (0.000) |     6.60 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1614 | 2024-05-30 | Rebels            | L   | 0.765      | -            | -                | -                | -         |   -10.55 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1795 | 2024-05-22 | System5           | W   | 0.712      | -            | -                | -                | 0 (0.000) |     3.98 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1839 | 2024-05-21 | EYEBALLERS        | W   | 0.705      | 0.500        | -                | 0.510 (0.180)    | -         |     9.01 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1878 | 2024-05-20 | Nexus             | W   | 0.698      | 0.379        | 0.014 (0.004)    | 0.465 (0.123)    | -         |     6.68 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2046 | 2024-05-15 | Norway            | W   | 0.665      | -            | -                | -                | -         |     4.46 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2107 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.659      | 0.500        | 0.032 (0.010)    | 0.561 (0.185)    | -         |    11.96 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2333 | 2024-05-04 | FlyQuest          | L   | 0.590      | -            | -                | -                | -         |    -3.52 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2348 | 2024-05-03 | BIG               | L   | 0.583      | -            | -                | -                | -         |    -2.11 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2369 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.578      | 0.889        | 0.223 (0.114)    | 0.553 (0.284)    | 1 (0.578) |    17.82 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2415 | 2024-04-30 | Complexity        | L   | 0.564      | -            | -                | -                | -         |    -0.29 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2625 | 2024-04-20 | EYEBALLERS        | L   | 0.499      | -            | -                | -                | -         |    -8.55 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3165 | 2024-04-03 | SAW               | L   | 0.384      | -            | -                | -                | -         |    -2.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3220 | 2024-04-01 | RUSH B            | W   | 0.371      | 0.500        | 0.017 (0.003)    | 0.386 (0.072)    | -         |     4.94 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3497 | 2024-03-15 | Betera            | L   | 0.258      | -            | -                | -                | -         |    -6.32 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3556 | 2024-03-13 | Monte             | L   | 0.246      | -            | -                | -                | -         |    -3.05 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3934 | 2024-02-26 | System5           | L   | 0.139      | -            | -                | -                | -         |    -3.50 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4072 | 2024-02-20 | ex-Preasy         | L   | 0.098      | -            | -                | -                | -         |    -2.15 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4100 | 2024-02-19 | GamerLegion       | L   | 0.092      | -            | -                | -                | -         |    -2.01 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4103 | 2024-02-19 | Cloud9            | L   | 0.091      | -            | -                | -                | -         |    -1.02 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4170 | 2024-02-16 | SINNERS           | L   | 0.072      | -            | -                | -                | -         |    -0.66 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,533.36)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.859 | $10,895.00     | $9,356.59       |
| 2024-06-09 |      0.831 | $500.00        | $415.66         |
| 2024-05-12 |      0.644 | $7,000.00      | $4,511.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
