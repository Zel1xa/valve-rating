### Roster Details<br />
Team Name: Qiang<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [82](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [61]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  907.8<br />
<br />
Final Rank Value (907.8) = Starting Rank Value (871.7) + Head To Head Adjustments (36.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.410[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.244<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 871.7
- 400 + ( ( 0.244 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 871.7


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
|           36 |      565 | 2024-08-23 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -17.19 | Aaron, Bibu, DGL, kory, Porya      |
|           35 |      592 | 2024-08-22 | BIG               | L   | 1.000      | -            | -                | -                | -         |    -5.70 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      623 | 2024-08-21 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -1.24 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      647 | 2024-08-21 | Sashi             | W   | 1.000      | 0.143        | 0.151 (0.022)    | 0.926 (0.132)    | 0 (0.000) |    22.25 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |     1013 | 2024-08-09 | Sashi             | L   | 0.999      | -            | -                | -                | -         |    -8.57 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |     1028 | 2024-08-08 | Permitta          | W   | 0.994      | 0.426        | 0.032 (0.013)    | 0.968 (0.410)    | 0 (0.000) |    16.31 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |     1316 | 2024-07-31 | B8                | L   | 0.941      | -            | -                | -                | -         |    -6.92 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |     1365 | 2024-07-30 | Space             | W   | 0.935      | 0.500        | 0.004 (0.002)    | 0.463 (0.217)    | 0 (0.000) |    11.85 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |     1401 | 2024-07-29 | ARCRED            | L   | 0.928      | -            | -                | -                | -         |   -13.31 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1725 | 2024-07-19 | Nexus             | L   | 0.860      | -            | -                | -                | -         |   -19.54 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1763 | 2024-07-18 | Nemiga            | L   | 0.855      | -            | -                | -                | -         |    -5.89 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1832 | 2024-07-17 | Verdant           | W   | 0.848      | 0.333        | 0.011 (0.003)    | 0.353 (0.100)    | 0 (0.000) |     9.08 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1894 | 2024-07-16 | Aurora            | L   | 0.841      | -            | -                | -                | -         |    -2.46 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1944 | 2024-07-15 | Betera            | W   | 0.834      | -            | -                | -                | 0 (0.000) |     3.55 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     2263 | 2024-06-13 | Enterprise        | W   | 0.622      | 0.379        | 0.039 (0.009)    | 0.697 (0.164)    | 0 (0.000) |     9.49 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     2295 | 2024-06-12 | Rebels            | W   | 0.615      | 0.379        | 0.028 (0.007)    | 0.656 (0.153)    | 0 (0.000) |    10.74 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     2317 | 2024-06-11 | ECLOT             | W   | 0.608      | 0.379        | 0.047 (0.011)    | 0.698 (0.161)    | 0 (0.000) |    13.75 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     2514 | 2024-06-07 | B8                | L   | 0.581      | -            | -                | -                | -         |    -4.68 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     2524 | 2024-06-07 | Aurora            | L   | 0.580      | -            | -                | -                | -         |    -1.24 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     2628 | 2024-06-05 | The Prodigies     | W   | 0.568      | -            | -                | -                | 0 (0.000) |     2.16 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2708 | 2024-06-03 | GL Academy        | W   | 0.555      | -            | -                | -                | -         |     4.27 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2817 | 2024-05-30 | Rebels            | L   | 0.528      | -            | -                | -                | -         |    -7.68 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2998 | 2024-05-22 | System5           | W   | 0.475      | -            | -                | -                | -         |     2.90 | Aaron, Bibu, DGL, kory, Porya      |
|           13 |     3042 | 2024-05-21 | EYEBALLERS        | W   | 0.468      | -            | -                | -                | -         |     5.66 | Aaron, Bibu, DGL, kory, Porya      |
|           12 |     3081 | 2024-05-20 | Nexus             | W   | 0.461      | 0.379        | -                | 0.432 (0.075)    | -         |     4.93 | Aaron, Bibu, DGL, kory, Porya      |
|           11 |     3249 | 2024-05-15 | Norway            | W   | 0.428      | -            | -                | -                | -         |     2.81 | Aaron, Bibu, DGL, kory, Porya      |
|           10 |     3310 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.421      | 0.500        | 0.102 (0.021)    | 0.837 (0.176)    | -         |     9.29 | Aaron, Bibu, DGL, kory, Porya      |
|            9 |     3536 | 2024-05-04 | FlyQuest          | L   | 0.353      | -            | -                | -                | -         |    -3.21 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3551 | 2024-05-03 | BIG               | L   | 0.346      | -            | -                | -                | -         |    -1.62 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3572 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.340      | 0.889        | 0.232 (0.070)    | 0.428 (0.130)    | 1 (0.340) |    10.24 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            6 |     3618 | 2024-04-30 | Complexity        | L   | 0.327      | -            | -                | -                | -         |    -0.27 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            5 |     3829 | 2024-04-20 | EYEBALLERS        | L   | 0.261      | -            | -                | -                | -         |    -4.93 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            4 |     4369 | 2024-04-03 | SAW               | L   | 0.147      | -            | -                | -                | -         |    -0.12 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            3 |     4424 | 2024-04-01 | RUSH B            | W   | 0.134      | 0.500        | 0.026 (0.002)    | -                | -         |     1.98 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            2 |     4701 | 2024-03-15 | Betera            | L   | 0.021      | -            | -                | -                | -         |    -0.51 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4760 | 2024-03-13 | Monte             | L   | 0.008      | -            | -                | -                | -         |    -0.10 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,004.38)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      0.868 | $1,250.00      | $1,084.72       |
| 2024-06-13 |      0.622 | $10,895.00     | $6,772.05       |
| 2024-06-09 |      0.594 | $500.00        | $297.05         |
| 2024-05-12 |      0.407 | $7,000.00      | $2,850.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
