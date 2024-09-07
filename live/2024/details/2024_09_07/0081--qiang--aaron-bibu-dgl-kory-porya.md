### Roster Details<br />
Team Name: Qiang<br />
Roster: Aaron, Bibu, DGL, kory, Porya<br />
Global Rank: [81](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [60]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  915.3<br />
<br />
Final Rank Value (915.3) = Starting Rank Value (880.0) + Head To Head Adjustments (35.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.410[<sup>1</sup>](#table2)
- Bounty Collected: 0.356[<sup>2</sup>](#table1)
- Opponent Network: 0.179[<sup>2</sup>](#table1)
- LAN Wins: 0.036[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 880.0
- 400 + ( ( 0.245 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 880.0


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
|           36 |      533 | 2024-08-23 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -17.40 | Aaron, Bibu, DGL, kory, Porya      |
|           35 |      560 | 2024-08-22 | BIG               | L   | 1.000      | -            | -                | -                | -         |    -5.61 | Aaron, Bibu, DGL, kory, Porya      |
|           34 |      591 | 2024-08-21 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -1.25 | Aaron, Bibu, DGL, kory, Porya      |
|           33 |      615 | 2024-08-21 | Sashi             | W   | 1.000      | 0.143        | 0.152 (0.022)    | 0.960 (0.137)    | 0 (0.000) |    22.24 | Aaron, Bibu, DGL, kory, Porya      |
|           32 |      981 | 2024-08-09 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -8.58 | Aaron, Bibu, DGL, kory, Porya      |
|           31 |      996 | 2024-08-08 | Permitta          | W   | 1.000      | 0.426        | 0.032 (0.013)    | 0.999 (0.426)    | 0 (0.000) |    16.28 | Aaron, Bibu, DGL, kory, Porya      |
|           30 |     1285 | 2024-07-31 | B8                | L   | 0.949      | -            | -                | -                | -         |    -7.18 | Aaron, Bibu, DGL, kory, Porya      |
|           29 |     1333 | 2024-07-30 | Space             | W   | 0.943      | 0.500        | 0.004 (0.002)    | 0.479 (0.226)    | 0 (0.000) |    11.88 | Aaron, Bibu, DGL, kory, Porya      |
|           28 |     1369 | 2024-07-29 | ARCRED            | L   | 0.936      | -            | -                | -                | -         |   -13.43 | Aaron, Bibu, DGL, kory, Porya      |
|           27 |     1693 | 2024-07-19 | Nexus             | L   | 0.868      | -            | -                | -                | -         |   -19.79 | Aaron, Bibu, DGL, kory, Porya      |
|           26 |     1731 | 2024-07-18 | Nemiga            | L   | 0.863      | -            | -                | -                | -         |    -6.03 | Aaron, Bibu, DGL, kory, Porya      |
|           25 |     1800 | 2024-07-17 | Verdant           | W   | 0.856      | 0.333        | 0.011 (0.003)    | 0.365 (0.104)    | 0 (0.000) |     9.09 | Aaron, Bibu, DGL, kory, Porya      |
|           24 |     1862 | 2024-07-16 | Aurora            | L   | 0.849      | -            | -                | -                | -         |    -2.42 | Aaron, Bibu, DGL, kory, Porya      |
|           23 |     1912 | 2024-07-15 | Betera            | W   | 0.842      | -            | -                | -                | 0 (0.000) |     3.49 | Aaron, Bibu, DGL, kory, Porya      |
|           22 |     2231 | 2024-06-13 | Enterprise        | W   | 0.629      | 0.379        | 0.039 (0.009)    | 0.720 (0.172)    | 0 (0.000) |     9.63 | Aaron, Bibu, DGL, kory, Porya      |
|           21 |     2263 | 2024-06-12 | Rebels            | W   | 0.623      | 0.379        | 0.028 (0.007)    | 0.677 (0.160)    | 0 (0.000) |    10.91 | Aaron, Bibu, DGL, kory, Porya      |
|           20 |     2285 | 2024-06-11 | ECLOT             | W   | 0.616      | 0.379        | 0.047 (0.011)    | 0.719 (0.168)    | 0 (0.000) |    14.00 | Aaron, Bibu, DGL, kory, Porya      |
|           19 |     2482 | 2024-06-07 | B8                | L   | 0.589      | -            | -                | -                | -         |    -4.89 | Aaron, Bibu, DGL, kory, Porya      |
|           18 |     2492 | 2024-06-07 | Aurora            | L   | 0.588      | -            | -                | -                | -         |    -1.20 | Aaron, Bibu, DGL, kory, Porya      |
|           17 |     2596 | 2024-06-05 | The Prodigies     | W   | 0.576      | -            | -                | -                | 0 (0.000) |     2.13 | Aaron, Bibu, DGL, kory, Porya      |
|           16 |     2676 | 2024-06-03 | GL Academy        | W   | 0.563      | -            | -                | -                | -         |     4.28 | Aaron, Bibu, DGL, kory, Porya      |
|           15 |     2785 | 2024-05-30 | Rebels            | L   | 0.536      | -            | -                | -                | -         |    -7.78 | Aaron, Bibu, DGL, kory, Porya      |
|           14 |     2966 | 2024-05-22 | System5           | W   | 0.483      | -            | -                | -                | -         |     2.87 | Aaron, Bibu, DGL, kory, Porya      |
|           13 |     3010 | 2024-05-21 | EYEBALLERS        | W   | 0.476      | -            | -                | -                | -         |     5.68 | Aaron, Bibu, DGL, kory, Porya      |
|           12 |     3049 | 2024-05-20 | Nexus             | W   | 0.468      | 0.379        | -                | 0.447 (0.079)    | -         |     4.98 | Aaron, Bibu, DGL, kory, Porya      |
|           11 |     3217 | 2024-05-15 | Norway            | W   | 0.436      | -            | -                | -                | -         |     2.80 | Aaron, Bibu, DGL, kory, Porya      |
|           10 |     3278 | 2024-05-14 | ALTERNATE aTTaX   | W   | 0.429      | 0.500        | 0.101 (0.022)    | 0.862 (0.185)    | -         |     9.43 | Aaron, Bibu, DGL, kory, Porya      |
|            9 |     3504 | 2024-05-04 | FlyQuest          | L   | 0.361      | -            | -                | -                | -         |    -3.39 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            8 |     3519 | 2024-05-03 | BIG               | L   | 0.354      | -            | -                | -                | -         |    -1.62 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            7 |     3540 | 2024-05-02 | Ninjas in Pyjamas | W   | 0.348      | 0.889        | 0.210 (0.065)    | 0.444 (0.137)    | 1 (0.348) |    10.48 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            6 |     3586 | 2024-04-30 | Complexity        | L   | 0.335      | -            | -                | -                | -         |    -0.26 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            5 |     3797 | 2024-04-20 | EYEBALLERS        | L   | 0.269      | -            | -                | -                | -         |    -5.13 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            4 |     4337 | 2024-04-03 | SAW               | L   | 0.155      | -            | -                | -                | -         |    -0.12 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            3 |     4392 | 2024-04-01 | RUSH B            | W   | 0.142      | 0.500        | 0.026 (0.002)    | -                | -         |     2.09 | Aaron, Bibu, Ciocardau, DGL, Porya |
|            2 |     4669 | 2024-03-15 | Betera            | L   | 0.029      | -            | -                | -                | -         |    -0.71 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     4728 | 2024-03-13 | Monte             | L   | 0.016      | -            | -                | -                | -         |    -0.20 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,159.90)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-20 |      0.876 | $1,250.00      | $1,094.62       |
| 2024-06-13 |      0.629 | $10,895.00     | $6,858.30       |
| 2024-06-09 |      0.602 | $500.00        | $301.01         |
| 2024-05-12 |      0.415 | $7,000.00      | $2,905.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
