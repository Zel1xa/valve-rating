### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1059.4<br />
<br />
Final Rank Value (1059.4) = Starting Rank Value (1025.5) + Head To Head Adjustments (34.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.510[<sup>1</sup>](#table2)
- Bounty Collected: 0.390[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.290[<sup>2</sup>](#table1)

The average of these factors is 0.323<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1025.5
- 400 + ( ( 0.323 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1025.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |       24 | 2024-09-07 | Sangal             | L   | 1.000      | -            | -                | -                | -         |    -4.51 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |       46 | 2024-09-06 | Lynn Vision        | W   | 1.000      | 0.889        | 0.073 (0.065)    | 0.114 (0.101)    | 1 (1.000) |     9.45 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |      119 | 2024-09-04 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -0.86 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |      159 | 2024-09-03 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |    -0.64 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |      242 | 2024-08-30 | Vantage            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.33 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |      245 | 2024-08-30 | Vantage            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.39 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |      475 | 2024-08-26 | MANTRA             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.29 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |      484 | 2024-08-26 | MANTRA             | W   | 1.000      | -            | -                | -                | -         |     1.31 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |      667 | 2024-08-21 | KZG                | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.152 (0.051)    | -         |     3.21 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |      675 | 2024-08-21 | KZG                | W   | 1.000      | 0.333        | 0.003 (0.001)    | -                | -         |     3.32 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |      893 | 2024-08-13 | DXA                | W   | 1.000      | 0.333        | -                | 0.221 (0.074)    | -         |     2.79 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |      900 | 2024-08-13 | DXA                | W   | 1.000      | 0.333        | -                | 0.221 (0.074)    | -         |     2.87 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     1035 | 2024-08-08 | The MongolZ        | L   | 0.993      | -            | -                | -                | -         |    -0.86 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     1092 | 2024-08-07 | BIG                | L   | 0.985      | -            | -                | -                | -         |    -8.32 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     1788 | 2024-07-18 | FURIA              | L   | 0.853      | -            | -                | -                | -         |    -1.44 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     1855 | 2024-07-17 | FaZe               | L   | 0.846      | -            | -                | -                | -         |    -0.51 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2426 | 2024-06-08 | Rooster            | W   | 0.591      | 0.333        | 0.007 (0.001)    | 0.342 (0.067)    | -         |     3.42 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2481 | 2024-06-08 | Mindfreak          | W   | 0.585      | -            | -                | -                | -         |     2.44 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2536 | 2024-06-07 | Rooster            | L   | 0.579      | -            | -                | -                | -         |   -15.13 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2864 | 2024-05-28 | BIG                | L   | 0.515      | -            | -                | -                | -         |    -5.21 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     2885 | 2024-05-27 | Spirit             | L   | 0.509      | -            | -                | -                | -         |    -0.11 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3012 | 2024-05-22 | Mindfreak          | W   | 0.472      | -            | -                | -                | -         |     1.67 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3017 | 2024-05-22 | Mindfreak          | W   | 0.472      | -            | -                | -                | -         |     1.70 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3087 | 2024-05-20 | Canon Event        | W   | 0.460      | -            | -                | -                | -         |     0.57 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3089 | 2024-05-20 | Canon Event        | W   | 0.459      | -            | -                | -                | -         |     0.58 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3458 | 2024-05-08 | Liquid             | L   | 0.380      | -            | -                | -                | -         |    -0.65 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3476 | 2024-05-07 | BetBoom            | W   | 0.374      | 0.889        | 0.229 (0.076)    | 0.535 (0.178)    | 1 (0.374) |     8.64 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3520 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.360      | 0.889        | 0.232 (0.074)    | 0.428 (0.137)    | 1 (0.360) |    10.04 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3536 | 2024-05-04 | Qiang              | W   | 0.353      | 0.889        | 0.036 (0.011)    | 0.389 (0.122)    | 1 (0.353) |     3.21 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3552 | 2024-05-03 | HEROIC             | L   | 0.346      | -            | -                | -                | -         |    -1.24 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3579 | 2024-05-02 | BOSS               | W   | 0.340      | 0.889        | 0.013 (0.004)    | 0.401 (0.121)    | 1 (0.340) |     2.13 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3601 | 2024-05-01 | Natus Vincere      | L   | 0.333      | -            | -                | -                | -         |    -0.05 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3848 | 2024-04-20 | Bad News Kangaroos | W   | 0.259      | -            | -                | -                | -         |     0.97 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3894 | 2024-04-19 | Rooster            | W   | 0.253      | -            | -                | -                | -         |     1.28 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3901 | 2024-04-18 | Mindfreak          | W   | 0.252      | -            | -                | -                | -         |     0.96 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4146 | 2024-04-10 | FaZe               | L   | 0.193      | -            | -                | -                | -         |    -0.11 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4161 | 2024-04-09 | Nemiga             | W   | 0.191      | 0.624        | 0.303 (0.036)    | 0.774 (0.092)    | 1 (0.191) |     4.09 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4211 | 2024-04-08 | Virtus.pro         | L   | 0.185      | -            | -                | -                | -         |    -0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4242 | 2024-04-08 | Cloud9             | W   | 0.178      | 0.624        | 0.023 (0.003)    | -                | 1 (0.178) |     1.20 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4383 | 2024-04-03 | Arcade             | W   | 0.146      | -            | -                | -                | -         |     0.67 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4388 | 2024-04-03 | Arcade             | W   | 0.146      | -            | -                | -                | -         |     0.68 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4511 | 2024-03-27 | KZG                | W   | 0.099      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4516 | 2024-03-27 | KZG                | W   | 0.099      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4781 | 2024-03-13 | Rooster            | W   | 0.006      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4789 | 2024-03-13 | Rooster            | W   | 0.006      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,247.15)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-08 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-08-09 |      1.000 | $2,500.00      | $2,500.00       |
| 2024-07-21 |      0.875 | $10,000.00     | $8,747.22       |
| 2024-06-08 |      0.591 | $3,250.00      | $1,922.01       |
| 2024-06-02 |      0.548 | $4,000.00      | $2,192.22       |
| 2024-05-12 |      0.407 | $23,500.00     | $9,569.72       |
| 2024-04-14 |      0.219 | $6,000.00      | $1,315.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
