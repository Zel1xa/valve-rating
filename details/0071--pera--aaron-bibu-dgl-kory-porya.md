### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  957.9<br />
<br />
Final Rank Value (957.9) = Starting Rank Value (930.3) + Head To Head Adjustments (27.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.430[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.065[<sup>2</sup>](#table1)

The average of these factors is 0.259<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 930.3
- 400 + ( ( 0.259 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 930.3


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
|           35 |      181 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.73 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      229 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.439 (0.220)    | 0 (0.000) |    11.53 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      265 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.26 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      589 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.79 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      627 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.25 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      696 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.294 (0.098)    | 0 (0.000) |     8.99 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      756 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.42 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      806 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.84 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1124 | 2024-06-13 | Enterprise        | W   | 0.845      | 0.379        | 0.039 (0.013)    | 0.616 (0.197)    | 0 (0.000) |    12.14 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1156 | 2024-06-12 | Rebels            | W   | 0.838      | 0.379        | 0.038 (0.012)    | 0.591 (0.188)    | 0 (0.000) |    15.00 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1178 | 2024-06-11 | ECLOT             | W   | 0.831      | 0.379        | 0.062 (0.019)    | 0.549 (0.173)    | 0 (0.000) |    19.79 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1375 | 2024-06-07 | B8                | L   | 0.804      | -            | -                | -                | -         |    -6.67 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1385 | 2024-06-07 | Aurora            | L   | 0.803      | -            | -                | -                | -         |    -1.00 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1489 | 2024-06-05 | The Prodigies     | W   | 0.791      | -            | -                | -                | 0 (0.000) |     2.67 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1569 | 2024-06-03 | GL Academy        | W   | 0.778      | -            | -                | -                | 0 (0.000) |     6.41 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1678 | 2024-05-30 | Rebels            | L   | 0.751      | -            | -                | -                | -         |   -10.45 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1859 | 2024-05-22 | System5           | W   | 0.698      | -            | -                | -                | 0 (0.000) |     3.87 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1903 | 2024-05-21 | EYEBALLERS        | W   | 0.691      | 0.500        | -                | 0.500 (0.173)    | -         |     8.69 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1942 | 2024-05-20 | Nexus             | W   | 0.684      | 0.379        | 0.014 (0.004)    | 0.457 (0.118)    | -         |     6.53 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2110 | 2024-05-15 | Norway            | W   | 0.651      | 0.500        | 0.006 (0.002)    | -                | -         |     4.31 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2171 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.645      | 0.500        | 0.031 (0.010)    | 0.550 (0.177)    | -         |    11.68 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2397 | 2024-05-04 | FlyQuest          | L   | 0.576      | -            | -                | -                | -         |    -3.57 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2412 | 2024-05-03 | BIG               | L   | 0.570      | -            | -                | -                | -         |    -2.10 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2433 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.564      | 0.889        | 0.254 (0.127)    | 0.544 (0.273)    | 1 (0.564) |    17.41 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2479 | 2024-04-30 | Complexity        | L   | 0.550      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2690 | 2024-04-20 | EYEBALLERS        | L   | 0.485      | -            | -                | -                | -         |    -8.39 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3230 | 2024-04-03 | SAW               | L   | 0.370      | -            | -                | -                | -         |    -2.27 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3285 | 2024-04-01 | RUSH B            | W   | 0.357      | 0.500        | 0.026 (0.005)    | 0.380 (0.068)    | -         |     4.92 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3562 | 2024-03-15 | Betera            | L   | 0.244      | -            | -                | -                | -         |    -6.01 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3621 | 2024-03-13 | Monte             | L   | 0.232      | -            | -                | -                | -         |    -2.97 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     4000 | 2024-02-26 | System5           | L   | 0.125      | -            | -                | -                | -         |    -3.16 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4138 | 2024-02-20 | ex-Preasy         | L   | 0.084      | -            | -                | -                | -         |    -1.87 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4166 | 2024-02-19 | GamerLegion       | L   | 0.078      | -            | -                | -                | -         |    -1.74 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4169 | 2024-02-19 | Cloud9            | L   | 0.077      | -            | -                | -                | -         |    -0.88 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4237 | 2024-02-16 | SINNERS           | L   | 0.058      | -            | -                | -                | -         |    -0.41 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,277.87)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.845 | $10,895.00     | $9,205.27       |
| 2024-06-09 |      0.817 | $500.00        | $408.72         |
| 2024-05-12 |      0.631 | $7,000.00      | $4,413.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
