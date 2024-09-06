### Roster Details<br />
Team Name: Qiang<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [80](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [59]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  915.7<br />
<br />
Final Rank Value (915.7) = Starting Rank Value (880.6) + Head To Head Adjustments (35.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.410[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.180[<sup>2</sup>](#table1)
- LAN Wins: 0.037[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 880.6
- 400 + ( ( 0.246 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 880.6


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
|           36 |      528 | 2024-08-23 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -17.45 | Aaron, Bibu, DGL, kory, Porya      |
|           35 |      555 | 2024-08-22 | BIG               | L   | 1.000      | -            | -                | -                | -         |    -5.61 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      586 | 2024-08-21 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -1.25 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      610 | 2024-08-21 | Sashi             | W   | 1.000      | 0.143        | 0.152 (0.022)    | 0.961 (0.137)    | 0 (0.000) |    22.23 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      976 | 2024-08-09 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -8.59 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      991 | 2024-08-08 | Permitta          | W   | 1.000      | 0.426        | 0.032 (0.013)    | 0.998 (0.425)    | 0 (0.000) |    16.24 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |     1279 | 2024-07-31 | B8                | L   | 0.953      | -            | -                | -                | -         |    -7.22 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |     1328 | 2024-07-30 | Space             | W   | 0.947      | 0.500        | 0.004 (0.002)    | 0.479 (0.227)    | 0 (0.000) |    11.90 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |     1364 | 2024-07-29 | ARCRED            | L   | 0.940      | -            | -                | -                | -         |   -13.50 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1688 | 2024-07-19 | Nexus             | L   | 0.872      | -            | -                | -                | -         |   -19.89 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1726 | 2024-07-18 | Nemiga            | L   | 0.867      | -            | -                | -                | -         |    -6.07 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1795 | 2024-07-17 | Verdant           | W   | 0.860      | 0.333        | 0.011 (0.003)    | 0.365 (0.105)    | 0 (0.000) |     9.11 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1857 | 2024-07-16 | Aurora            | L   | 0.853      | -            | -                | -                | -         |    -2.43 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1907 | 2024-07-15 | Betera            | W   | 0.846      | -            | -                | -                | 0 (0.000) |     3.48 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     2226 | 2024-06-13 | Enterprise        | W   | 0.633      | 0.379        | 0.039 (0.009)    | 0.720 (0.173)    | 0 (0.000) |     9.67 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     2258 | 2024-06-12 | Rebels            | W   | 0.627      | 0.379        | 0.028 (0.007)    | 0.677 (0.161)    | 0 (0.000) |    10.98 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     2280 | 2024-06-11 | ECLOT             | W   | 0.620      | 0.379        | 0.047 (0.011)    | 0.718 (0.168)    | 0 (0.000) |    14.09 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     2477 | 2024-06-07 | B8                | L   | 0.593      | -            | -                | -                | -         |    -4.93 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     2487 | 2024-06-07 | Aurora            | L   | 0.592      | -            | -                | -                | -         |    -1.21 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     2591 | 2024-06-05 | The Prodigies     | W   | 0.580      | -            | -                | -                | 0 (0.000) |     2.14 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2671 | 2024-06-03 | GL Academy        | W   | 0.567      | -            | -                | -                | -         |     4.31 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2780 | 2024-05-30 | Rebels            | L   | 0.540      | -            | -                | -                | -         |    -7.83 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2961 | 2024-05-22 | System5           | W   | 0.487      | -            | -                | -                | -         |     2.89 | Aaron, Bibu, DGL, kory, Porya      |
|           13 |     3005 | 2024-05-21 | EYEBALLERS        | W   | 0.480      | -            | -                | -                | -         |     5.73 | Aaron, Bibu, DGL, kory, Porya      |
|           12 |     3044 | 2024-05-20 | Nexus             | W   | 0.472      | 0.379        | -                | 0.448 (0.080)    | -         |     5.02 | Aaron, Bibu, DGL, kory, Porya      |
|           11 |     3212 | 2024-05-15 | Norway            | W   | 0.440      | -            | -                | -                | -         |     2.83 | Aaron, Bibu, DGL, kory, Porya      |
|           10 |     3273 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.433      | 0.500        | 0.101 (0.022)    | 0.861 (0.187)    | -         |     9.51 | Aaron, Bibu, DGL, kory, Porya      |
|            9 |     3499 | 2024-05-04 | FlyQuest          | L   | 0.365      | -            | -                | -                | -         |    -3.41 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3514 | 2024-05-03 | BIG               | L   | 0.358      | -            | -                | -                | -         |    -1.64 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3535 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.352      | 0.889        | 0.210 (0.066)    | 0.445 (0.139)    | 1 (0.352) |    10.60 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            6 |     3581 | 2024-04-30 | Complexity        | L   | 0.339      | -            | -                | -                | -         |    -0.26 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            5 |     3792 | 2024-04-20 | EYEBALLERS        | L   | 0.273      | -            | -                | -                | -         |    -5.20 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            4 |     4332 | 2024-04-03 | SAW               | L   | 0.159      | -            | -                | -                | -         |    -0.13 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            3 |     4387 | 2024-04-01 | RUSH B            | W   | 0.146      | 0.500        | 0.025 (0.002)    | -                | -         |     2.15 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            2 |     4664 | 2024-03-15 | Betera            | L   | 0.033      | -            | -                | -                | -         |    -0.81 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4723 | 2024-03-13 | Monte             | L   | 0.020      | -            | -                | -                | -         |    -0.26 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,238.57)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      0.880 | $1,250.00      | $1,099.62       |
| 2024-06-13 |      0.633 | $10,895.00     | $6,901.93       |
| 2024-06-09 |      0.606 | $500.00        | $303.01         |
| 2024-05-12 |      0.419 | $7,000.00      | $2,934.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
