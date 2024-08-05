### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
<br />
Final Rank Value:  960.1<br />
<br />
Final Rank Value (960.1) = Starting Rank Value (937.7) + Head To Head Adjustments (22.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.169[<sup>2</sup>](#table1)
- LAN Wins: 0.069[<sup>2</sup>](#table1)

The average of these factors is 0.261<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 937.7
- 400 + ( ( 0.261 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 937.7


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
|           35 |        4 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.69 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |       52 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.406 (0.203)    | 0 (0.000) |    11.60 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |       88 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.68 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      412 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.93 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      450 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.48 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      519 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.300 (0.100)    | 0 (0.000) |     8.80 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      579 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.49 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      629 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.53 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |      947 | 2024-06-13 | Enterprise        | W   | 0.880      | 0.379        | 0.040 (0.013)    | 0.622 (0.207)    | 0 (0.000) |    12.40 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |      979 | 2024-06-12 | Rebels            | W   | 0.873      | 0.379        | 0.040 (0.013)    | 0.596 (0.197)    | 0 (0.000) |    15.79 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1001 | 2024-06-11 | ECLOT             | W   | 0.866      | 0.379        | 0.064 (0.021)    | 0.502 (0.165)    | 0 (0.000) |    18.47 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1198 | 2024-06-07 | B8                | L   | 0.839      | -            | -                | -                | -         |    -6.93 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1208 | 2024-06-07 | Aurora            | L   | 0.838      | -            | -                | -                | -         |    -1.06 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1312 | 2024-06-05 | The Prodigies     | W   | 0.826      | -            | -                | -                | 0 (0.000) |     2.77 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1392 | 2024-06-03 | GL Academy        | W   | 0.813      | 0.379        | 0.007 (0.002)    | -                | 0 (0.000) |     6.77 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1501 | 2024-05-30 | Rebels            | L   | 0.786      | -            | -                | -                | -         |   -10.79 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1682 | 2024-05-22 | System5           | W   | 0.733      | -            | -                | -                | 0 (0.000) |     4.05 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1726 | 2024-05-21 | EYEBALLERS        | W   | 0.726      | 0.500        | -                | 0.513 (0.186)    | -         |     9.21 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1765 | 2024-05-20 | Nexus             | W   | 0.719      | 0.379        | 0.014 (0.004)    | 0.465 (0.127)    | -         |     6.79 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     1933 | 2024-05-15 | Norway            | W   | 0.686      | -            | -                | -                | -         |     4.57 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     1994 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.679      | 0.500        | 0.032 (0.011)    | 0.564 (0.192)    | -         |    12.31 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2220 | 2024-05-04 | FlyQuest          | L   | 0.611      | -            | -                | -                | -         |    -3.35 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2235 | 2024-05-03 | BIG               | L   | 0.604      | -            | -                | -                | -         |    -2.92 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2256 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.598      | 0.889        | 0.256 (0.136)    | 0.477 (0.254)    | 1 (0.598) |    18.41 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2302 | 2024-04-30 | Complexity        | L   | 0.585      | -            | -                | -                | -         |    -0.29 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2513 | 2024-04-20 | EYEBALLERS        | L   | 0.519      | -            | -                | -                | -         |    -8.95 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3053 | 2024-04-03 | SAW               | L   | 0.405      | -            | -                | -                | -         |    -2.29 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3108 | 2024-04-01 | RUSH B            | W   | 0.392      | 0.500        | 0.017 (0.003)    | 0.308 (0.060)    | -         |     5.11 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3385 | 2024-03-15 | Betera            | L   | 0.279      | -            | -                | -                | -         |    -6.85 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3444 | 2024-03-13 | Monte             | L   | 0.266      | -            | -                | -                | -         |    -3.17 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3823 | 2024-02-26 | System5           | L   | 0.160      | -            | -                | -                | -         |    -4.04 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     3961 | 2024-02-20 | ex-Preasy         | L   | 0.119      | -            | -                | -                | -         |    -2.58 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     3989 | 2024-02-19 | GamerLegion       | L   | 0.112      | -            | -                | -                | -         |    -2.43 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     3992 | 2024-02-19 | Cloud9            | L   | 0.111      | -            | -                | -                | -         |    -1.17 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4060 | 2024-02-16 | SINNERS           | L   | 0.092      | -            | -                | -                | -         |    -1.05 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,914.63)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.880 | $10,895.00     | $9,582.40       |
| 2024-06-09 |      0.852 | $500.00        | $426.02         |
| 2024-05-12 |      0.665 | $7,000.00      | $4,656.20       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
