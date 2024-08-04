### Roster Details<br />
Team Name: PERA<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [49]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.5<br />
<br />
Final Rank Value (958.5) = Starting Rank Value (931.1) + Head To Head Adjustments (27.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.431[<sup>1</sup>](#table2)
- Bounty Collected: 0.371[<sup>2</sup>](#table1)
- Opponent Network: 0.171[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.260<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.1
- 400 + ( ( 0.260 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 931.1


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
|           35 |      152 | 2024-07-31 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.80 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      200 | 2024-07-30 | Space             | W   | 1.000      | 0.500        | 0.006 (0.003)    | 0.406 (0.203)    | 0 (0.000) |    11.35 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      236 | 2024-07-29 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -16.61 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      560 | 2024-07-19 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -23.94 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      598 | 2024-07-18 | Nemiga            | L   | 1.000      | -            | -                | -                | -         |    -8.38 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |      667 | 2024-07-17 | Verdant           | W   | 1.000      | 0.333        | 0.015 (0.005)    | 0.299 (0.100)    | 0 (0.000) |     8.80 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |      727 | 2024-07-16 | Aurora            | L   | 1.000      | -            | -                | -                | -         |    -2.53 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |      777 | 2024-07-15 | Betera            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.15 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1095 | 2024-06-13 | Enterprise        | W   | 0.854      | 0.379        | 0.039 (0.013)    | 0.625 (0.202)    | 0 (0.000) |    12.14 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1127 | 2024-06-12 | Rebels            | W   | 0.847      | 0.379        | 0.038 (0.012)    | 0.599 (0.192)    | 0 (0.000) |    15.18 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1149 | 2024-06-11 | ECLOT             | W   | 0.841      | 0.379        | 0.062 (0.020)    | 0.558 (0.178)    | 0 (0.000) |    19.96 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1346 | 2024-06-07 | B8                | L   | 0.813      | -            | -                | -                | -         |    -6.76 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1356 | 2024-06-07 | Aurora            | L   | 0.813      | -            | -                | -                | -         |    -1.05 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     1460 | 2024-06-05 | The Prodigies     | W   | 0.801      | -            | -                | -                | 0 (0.000) |     2.70 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     1540 | 2024-06-03 | GL Academy        | W   | 0.787      | -            | -                | -                | 0 (0.000) |     6.50 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     1649 | 2024-05-30 | Rebels            | L   | 0.761      | -            | -                | -                | -         |   -10.55 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     1830 | 2024-05-22 | System5           | W   | 0.707      | -            | -                | -                | 0 (0.000) |     3.92 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     1874 | 2024-05-21 | EYEBALLERS        | W   | 0.701      | 0.500        | -                | 0.509 (0.178)    | -         |     8.77 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     1913 | 2024-05-20 | Nexus             | W   | 0.693      | 0.379        | 0.014 (0.004)    | 0.465 (0.122)    | -         |     6.57 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2081 | 2024-05-15 | Norway            | W   | 0.661      | 0.500        | 0.006 (0.002)    | -                | -         |     4.37 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2142 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.654      | 0.500        | 0.031 (0.010)    | 0.560 (0.183)    | -         |    11.83 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2368 | 2024-05-04 | FlyQuest          | L   | 0.586      | -            | -                | -                | -         |    -3.54 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           13 |     2383 | 2024-05-03 | BIG               | L   | 0.579      | -            | -                | -                | -         |    -2.13 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           12 |     2404 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.573      | 0.889        | 0.255 (0.130)    | 0.553 (0.282)    | 1 (0.573) |    17.70 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           11 |     2450 | 2024-04-30 | Complexity        | L   | 0.560      | -            | -                | -                | -         |    -0.28 | Aaron, Bibu, Ciocardau, DGL, Porya |
|           10 |     2661 | 2024-04-20 | EYEBALLERS        | L   | 0.494      | -            | -                | -                | -         |    -8.56 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            9 |     3201 | 2024-04-03 | SAW               | L   | 0.380      | -            | -                | -                | -         |    -2.29 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3256 | 2024-04-01 | RUSH B            | W   | 0.367      | 0.500        | 0.026 (0.005)    | 0.386 (0.071)    | -         |     5.05 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3533 | 2024-03-15 | Betera            | L   | 0.254      | -            | -                | -                | -         |    -6.24 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     3592 | 2024-03-13 | Monte             | L   | 0.241      | -            | -                | -                | -         |    -3.06 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     3971 | 2024-02-26 | System5           | L   | 0.134      | -            | -                | -                | -         |    -3.40 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     4109 | 2024-02-20 | ex-Preasy         | L   | 0.094      | -            | -                | -                | -         |    -2.06 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     4137 | 2024-02-19 | GamerLegion       | L   | 0.087      | -            | -                | -                | -         |    -1.94 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     4140 | 2024-02-19 | Cloud9            | L   | 0.086      | -            | -                | -                | -         |    -0.96 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4208 | 2024-02-16 | SINNERS           | L   | 0.067      | -            | -                | -                | -         |    -0.49 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,449.90)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      1.000 | $1,250.00      | $1,250.00       |
| 2024-06-13 |      0.854 | $10,895.00     | $9,307.15       |
| 2024-06-09 |      0.827 | $500.00        | $413.39         |
| 2024-05-12 |      0.640 | $7,000.00      | $4,479.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
