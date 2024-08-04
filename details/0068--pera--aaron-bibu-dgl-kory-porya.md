### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.5<br />
<br />
Final Rank Value (956.5) = Starting Rank Value (928.4) + Head To Head Adjustments (28.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.171[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 928.4
- 400 + ( ( 0.258 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 928.4


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
|           35 |      121 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      169 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.406 (0.203)    | 0 (0.000) |    11.60 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      204 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.53 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      529 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.89 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      564 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.69 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      636 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.299 (0.100)    | 0 (0.000) |     8.80 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      695 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.54 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      746 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.20 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1064 | 2024-06-13 | Enterprise        | W   | 0.856      | 0.379        | 0.039 (0.013)    | 0.625 (0.202)    | 0 (0.000) |    12.17 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1096 | 2024-06-12 | Rebels            | W   | 0.849      | 0.379        | 0.038 (0.012)    | 0.599 (0.193)    | 0 (0.000) |    15.26 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1118 | 2024-06-11 | ECLOT             | W   | 0.842      | 0.379        | 0.062 (0.020)    | 0.559 (0.178)    | 0 (0.000) |    19.97 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1315 | 2024-06-07 | B8                | L   | 0.815      | -            | -                | -                | -         |    -6.76 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1325 | 2024-06-07 | Aurora            | L   | 0.814      | -            | -                | -                | -         |    -1.05 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1429 | 2024-06-05 | The Prodigies     | W   | 0.802      | -            | -                | -                | 0 (0.000) |     2.74 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1509 | 2024-06-03 | GL Academy        | W   | 0.789      | -            | -                | -                | 0 (0.000) |     6.57 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1618 | 2024-05-30 | Rebels            | L   | 0.762      | -            | -                | -                | -         |   -10.52 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1799 | 2024-05-22 | System5           | W   | 0.709      | -            | -                | -                | 0 (0.000) |     3.97 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1843 | 2024-05-21 | EYEBALLERS        | W   | 0.702      | 0.500        | -                | 0.510 (0.179)    | -         |     8.97 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1882 | 2024-05-20 | Nexus             | W   | 0.695      | 0.379        | 0.014 (0.004)    | 0.465 (0.122)    | -         |     6.66 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2050 | 2024-05-15 | Norway            | W   | 0.662      | 0.500        | 0.006 (0.002)    | -                | -         |     4.44 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2111 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.656      | 0.500        | 0.031 (0.010)    | 0.560 (0.184)    | -         |    11.90 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2337 | 2024-05-04 | FlyQuest          | L   | 0.587      | -            | -                | -                | -         |    -3.53 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2352 | 2024-05-03 | BIG               | L   | 0.580      | -            | -                | -                | -         |    -2.10 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2373 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.575      | 0.889        | 0.222 (0.114)    | 0.553 (0.283)    | 1 (0.575) |    17.73 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2419 | 2024-04-30 | Complexity        | L   | 0.561      | -            | -                | -                | -         |    -0.29 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2630 | 2024-04-20 | EYEBALLERS        | L   | 0.496      | -            | -                | -                | -         |    -8.51 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3170 | 2024-04-03 | SAW               | L   | 0.381      | -            | -                | -                | -         |    -2.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3225 | 2024-04-01 | RUSH B            | W   | 0.368      | 0.500        | 0.017 (0.003)    | 0.386 (0.071)    | -         |     4.90 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3502 | 2024-03-15 | Betera            | L   | 0.255      | -            | -                | -                | -         |    -6.25 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3561 | 2024-03-13 | Monte             | L   | 0.242      | -            | -                | -                | -         |    -3.02 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3940 | 2024-02-26 | System5           | L   | 0.136      | -            | -                | -                | -         |    -3.42 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4078 | 2024-02-20 | ex-Preasy         | L   | 0.095      | -            | -                | -                | -         |    -2.09 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4106 | 2024-02-19 | GamerLegion       | L   | 0.088      | -            | -                | -                | -         |    -1.95 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4109 | 2024-02-19 | Cloud9            | L   | 0.088      | -            | -                | -                | -         |    -0.99 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4177 | 2024-02-16 | SINNERS           | L   | 0.069      | -            | -                | -                | -         |    -0.64 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,477.15)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.856 | $10,895.00     | $9,323.30       |
| 2024-06-09 |      0.828 | $500.00        | $414.13         |
| 2024-05-12 |      0.641 | $7,000.00      | $4,489.72       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
