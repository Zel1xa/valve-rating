### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  971.7<br />
<br />
Final Rank Value (971.7) = Starting Rank Value (1145.6) + Head To Head Adjustments (-173.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.435[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.6
- 400 + ( ( 0.365 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1145.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           80 |       10 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.99 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       46 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       68 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      216 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.25 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      251 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.56 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      356 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      431 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.86 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      465 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.57 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      548 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    12.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      678 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    10.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      747 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.85 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      776 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      789 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1149 | 2024-06-11 | 3DMAX             | L   | 0.840      | -            | -                | -                | -         |    -2.49 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1163 | 2024-06-11 | ex-Guild Eagles   | W   | 0.838      | -            | -                | -                | 0 (0.000) |     7.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1177 | 2024-06-10 | Enterprise        | L   | 0.833      | -            | -                | -                | -         |   -16.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1185 | 2024-06-10 | Monte             | L   | 0.832      | -            | -                | -                | -         |   -13.75 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1189 | 2024-06-10 | 9 Pandas          | L   | 0.832      | -            | -                | -                | -         |   -12.83 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1196 | 2024-06-10 | PARIVISION        | W   | 0.832      | -            | -                | -                | -         |    14.60 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1198 | 2024-06-10 | Rare Atom         | L   | 0.831      | -            | -                | -                | -         |   -22.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1228 | 2024-06-09 | SAW               | W   | 0.826      | -            | -                | -                | -         |    16.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1236 | 2024-06-09 | 3DMAX             | W   | 0.826      | 0.143        | 0.506 (0.060)    | -                | -         |    23.97 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1242 | 2024-06-09 | RUSH B            | L   | 0.825      | -            | -                | -                | -         |   -18.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1251 | 2024-06-09 | Aurora            | W   | 0.825      | 0.143        | 0.423 (0.050)    | -                | -         |    24.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1285 | 2024-06-08 | Sangal            | L   | 0.820      | -            | -                | -                | -         |    -7.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1364 | 2024-06-07 | RUBY              | W   | 0.812      | 0.435        | 0.095 (0.034)    | 0.501 (0.177)    | -         |     9.14 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1407 | 2024-06-06 | KOI               | L   | 0.807      | -            | -                | -                | -         |   -10.98 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1467 | 2024-06-05 | RUSH B            | W   | 0.800      | -            | -                | -                | -         |     7.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1476 | 2024-06-05 | EYEBALLERS        | L   | 0.799      | -            | -                | -                | -         |   -17.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1530 | 2024-06-04 | VP.Prodigy        | L   | 0.792      | -            | -                | -                | -         |   -16.33 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1569 | 2024-06-02 | UNiTY             | L   | 0.779      | -            | -                | -                | -         |   -15.47 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1586 | 2024-06-01 | GUN5              | L   | 0.774      | -            | -                | -                | -         |   -16.34 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1606 | 2024-06-01 | Sampi             | W   | 0.772      | 0.346        | -                | 1.000 (0.267)    | 1 (0.772) |     6.47 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1638 | 2024-05-31 | UNiTY             | L   | 0.766      | -            | -                | -                | -         |   -16.01 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1656 | 2024-05-30 | B8                | W   | 0.760      | 0.435        | 0.165 (0.055)    | 0.951 (0.314)    | -         |    14.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1684 | 2024-05-29 | brazylijski luz   | W   | 0.753      | -            | -                | -                | -         |     4.97 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1742 | 2024-05-26 | Sampi             | W   | 0.733      | 0.435        | -                | 1.000 (0.319)    | -         |     6.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1776 | 2024-05-24 | GUN5              | W   | 0.720      | 0.435        | 0.073 (0.023)    | 0.570 (0.178)    | -         |     7.37 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1784 | 2024-05-24 | 9 Pandas          | L   | 0.718      | -            | -                | -                | -         |   -12.45 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1795 | 2024-05-23 | UNiTY             | W   | 0.713      | -            | -                | -                | -         |     8.09 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1801 | 2024-05-23 | Passion UA        | L   | 0.711      | -            | -                | -                | -         |   -12.38 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1919 | 2024-05-20 | VP.Prodigy        | W   | 0.692      | -            | -                | -                | -         |     5.61 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1967 | 2024-05-18 | 1WIN              | L   | 0.680      | -            | -                | -                | -         |   -13.15 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2053 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.664      | -            | -                | -                | -         |     7.25 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2145 | 2024-05-14 | Passion UA        | W   | 0.653      | 0.435        | 0.172 (0.049)    | 1.000 (0.284)    | -         |     9.14 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2315 | 2024-05-07 | Nemiga            | L   | 0.605      | -            | -                | -                | -         |    -6.54 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2350 | 2024-05-05 | Endpoint          | W   | 0.592      | -            | -                | -                | -         |     6.08 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2413 | 2024-05-02 | Gaimin Gladiators | L   | 0.572      | -            | -                | -                | -         |   -11.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2440 | 2024-05-01 | B8                | L   | 0.565      | -            | -                | -                | -         |   -10.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2472 | 2024-04-29 | 1WIN              | W   | 0.552      | 0.435        | -                | 0.707 (0.170)    | -         |     5.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2481 | 2024-04-29 | Sangal            | L   | 0.551      | -            | -                | -                | -         |    -7.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2493 | 2024-04-28 | Zero Tenacity     | L   | 0.546      | -            | -                | -                | -         |    -9.49 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2526 | 2024-04-27 | Zero Tenacity     | L   | 0.538      | -            | -                | -                | -         |    -9.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2542 | 2024-04-26 | PARIVISION        | L   | 0.533      | -            | -                | -                | -         |    -9.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2592 | 2024-04-24 | Endpoint          | L   | 0.519      | -            | -                | -                | -         |   -12.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2628 | 2024-04-22 | HAVU              | W   | 0.505      | -            | -                | -                | -         |     1.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2677 | 2024-04-20 | ENCE Academy      | L   | 0.492      | -            | -                | -                | -         |   -14.15 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2732 | 2024-04-19 | ECLOT             | L   | 0.484      | -            | -                | -                | -         |    -6.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2822 | 2024-04-17 | Gaimin Gladiators | L   | 0.471      | -            | -                | -                | -         |   -10.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2847 | 2024-04-16 | BLEED             | L   | 0.465      | -            | -                | -                | -         |   -10.74 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2877 | 2024-04-14 | Passion UA        | W   | 0.452      | 0.371        | 0.172 (0.029)    | -                | -         |     4.86 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2966 | 2024-04-10 | 3DMAX             | W   | 0.427      | 0.500        | 0.506 (0.108)    | 1.000 (0.214)    | -         |    12.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2993 | 2024-04-10 | UNiTY             | W   | 0.424      | -            | -                | -                | -         |     3.42 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3019 | 2024-04-09 | 9 Pandas          | W   | 0.420      | 0.500        | 0.081 (0.017)    | -                | -         |     3.96 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3070 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.411      | -            | -                | -                | -         |     3.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3121 | 2024-04-05 | Nexus             | W   | 0.393      | -            | -                | -                | -         |     2.02 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3213 | 2024-04-03 | Rebels            | W   | 0.378      | -            | -                | -                | -         |     3.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3256 | 2024-04-01 | Aurora            | W   | 0.367      | 0.500        | 0.423 (0.078)    | -                | -         |    11.00 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3279 | 2024-03-29 | ex-Sprout         | W   | 0.347      | -            | -                | -                | -         |     0.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3498 | 2024-03-17 | ECLOT             | L   | 0.267      | -            | -                | -                | -         |    -3.48 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3504 | 2024-03-17 | UNiTY             | W   | 0.266      | -            | -                | -                | 1 (0.266) |     2.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3519 | 2024-03-16 | Sampi             | W   | 0.259      | -            | -                | -                | 1 (0.259) |     1.80 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3531 | 2024-03-15 | UNiTY             | L   | 0.254      | -            | -                | -                | -         |    -5.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3601 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.240      | -            | -                | -                | -         |     2.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3654 | 2024-03-11 | brazylijski luz   | L   | 0.227      | -            | -                | -                | -         |    -6.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3866 | 2024-03-03 | Gaimin Gladiators | L   | 0.173      | -            | -                | -                | -         |    -3.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4159 | 2024-02-18 | Monte             | L   | 0.080      | -            | -                | -                | -         |    -1.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4206 | 2024-02-16 | 500               | W   | 0.067      | -            | -                | -                | -         |     0.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4209 | 2024-02-16 | PERA              | W   | 0.067      | -            | -                | -                | -         |     0.49 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4214 | 2024-02-16 | 500               | L   | 0.066      | -            | -                | -                | -         |    -1.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,104.53)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.854 | $545.00        | $465.41         |
| 2024-06-09 |      0.826 | $10,000.00     | $8,264.81       |
| 2024-06-02 |      0.780 | $1,306.00      | $1,018.47       |
| 2024-06-02 |      0.780 | $2,000.00      | $1,559.21       |
| 2024-03-17 |      0.267 | $2,984.00      | $796.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
