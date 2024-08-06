### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [65](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  994.3<br />
<br />
Final Rank Value (994.3) = Starting Rank Value (1151.9) + Head To Head Adjustments (-157.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.376[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.9
- 400 + ( ( 0.365 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1151.9


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
|           81 |       20 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.578 (0.289)    | 0 (0.000) |    16.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       54 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.90 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       90 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      112 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      260 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.28 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      296 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.36 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      400 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      475 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.14 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      509 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      592 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    12.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      722 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |    10.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      791 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.68 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      820 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      833 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1193 | 2024-06-11 | 3DMAX             | L   | 0.828      | -            | -                | -                | -         |    -2.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1207 | 2024-06-11 | ex-Guild Eagles   | W   | 0.826      | -            | -                | -                | -         |     7.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1221 | 2024-06-10 | Enterprise        | L   | 0.820      | -            | -                | -                | -         |   -16.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1229 | 2024-06-10 | Monte             | L   | 0.820      | -            | -                | -                | -         |   -13.73 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1233 | 2024-06-10 | 9 Pandas          | L   | 0.819      | -            | -                | -                | -         |   -12.89 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1240 | 2024-06-10 | PARIVISION        | W   | 0.819      | -            | -                | -                | -         |    14.34 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1242 | 2024-06-10 | Rare Atom         | L   | 0.818      | -            | -                | -                | -         |   -19.77 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1272 | 2024-06-09 | SAW               | W   | 0.813      | -            | -                | -                | -         |    16.18 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1280 | 2024-06-09 | 3DMAX             | W   | 0.813      | 0.143        | 0.510 (0.059)    | -                | -         |    23.65 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1286 | 2024-06-09 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -18.14 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1295 | 2024-06-09 | Aurora            | W   | 0.812      | 0.143        | 0.420 (0.049)    | -                | -         |    23.83 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1329 | 2024-06-08 | Sangal            | L   | 0.807      | -            | -                | -                | -         |    -7.03 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1408 | 2024-06-07 | RUBY              | W   | 0.799      | 0.435        | 0.095 (0.033)    | -                | -         |     9.20 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1451 | 2024-06-06 | KOI               | L   | 0.794      | -            | -                | -                | -         |   -11.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1511 | 2024-06-05 | RUSH B            | W   | 0.787      | -            | -                | -                | -         |     7.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1520 | 2024-06-05 | EYEBALLERS        | L   | 0.787      | -            | -                | -                | -         |   -17.28 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1574 | 2024-06-04 | VP.Prodigy        | L   | 0.779      | -            | -                | -                | -         |   -16.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1613 | 2024-06-02 | UNiTY             | L   | 0.766      | -            | -                | -                | -         |   -15.37 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1630 | 2024-06-01 | GUN5              | L   | 0.761      | -            | -                | -                | -         |   -16.17 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1650 | 2024-06-01 | Sampi             | W   | 0.759      | 0.346        | -                | 1.000 (0.263)    | 1 (0.759) |     6.28 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1682 | 2024-05-31 | UNiTY             | L   | 0.753      | -            | -                | -                | -         |   -15.89 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1700 | 2024-05-30 | B8                | W   | 0.747      | 0.435        | 0.170 (0.055)    | 0.912 (0.296)    | -         |    14.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1728 | 2024-05-29 | brazylijski luz   | W   | 0.740      | -            | -                | -                | -         |     4.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1786 | 2024-05-26 | Sampi             | W   | 0.720      | 0.435        | -                | 1.000 (0.313)    | -         |     6.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1820 | 2024-05-24 | GUN5              | W   | 0.708      | 0.435        | 0.072 (0.022)    | 0.550 (0.169)    | -         |     7.12 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1828 | 2024-05-24 | 9 Pandas          | L   | 0.706      | -            | -                | -                | -         |   -12.45 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1839 | 2024-05-23 | UNiTY             | W   | 0.700      | -            | -                | -                | -         |     7.76 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1845 | 2024-05-23 | Passion UA        | L   | 0.699      | -            | -                | -                | -         |   -12.17 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1963 | 2024-05-20 | VP.Prodigy        | W   | 0.679      | -            | -                | -                | -         |     5.39 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     2011 | 2024-05-18 | 1WIN              | L   | 0.667      | -            | -                | -                | -         |   -12.90 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2097 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.652      | -            | -                | -                | -         |     7.03 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2189 | 2024-05-14 | Passion UA        | W   | 0.641      | 0.435        | 0.173 (0.048)    | 1.000 (0.278)    | -         |     8.97 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2359 | 2024-05-07 | Nemiga            | L   | 0.592      | -            | -                | -                | -         |    -6.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2394 | 2024-05-05 | Endpoint          | W   | 0.580      | -            | -                | -                | -         |     5.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2457 | 2024-05-02 | Gaimin Gladiators | L   | 0.559      | -            | -                | -                | -         |   -11.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2484 | 2024-05-01 | B8                | L   | 0.552      | -            | -                | -                | -         |   -10.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2516 | 2024-04-29 | 1WIN              | W   | 0.540      | 0.435        | -                | 0.718 (0.168)    | -         |     5.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2525 | 2024-04-29 | Sangal            | L   | 0.539      | -            | -                | -                | -         |    -7.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2537 | 2024-04-28 | Zero Tenacity     | L   | 0.533      | -            | -                | -                | -         |    -9.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2570 | 2024-04-27 | Zero Tenacity     | L   | 0.525      | -            | -                | -                | -         |    -9.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2586 | 2024-04-26 | PARIVISION        | L   | 0.520      | -            | -                | -                | -         |    -9.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2636 | 2024-04-24 | Endpoint          | L   | 0.506      | -            | -                | -                | -         |   -12.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2672 | 2024-04-22 | HAVU              | W   | 0.492      | -            | -                | -                | -         |     1.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2721 | 2024-04-20 | ENCE Academy      | L   | 0.479      | -            | -                | -                | -         |   -13.83 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2776 | 2024-04-19 | ECLOT             | L   | 0.472      | -            | -                | -                | -         |    -6.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2866 | 2024-04-17 | Gaimin Gladiators | L   | 0.459      | -            | -                | -                | -         |   -10.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2891 | 2024-04-16 | BLEED             | L   | 0.452      | -            | -                | -                | -         |   -10.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2921 | 2024-04-14 | Passion UA        | W   | 0.439      | 0.371        | 0.173 (0.028)    | -                | -         |     4.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     3010 | 2024-04-10 | 3DMAX             | W   | 0.414      | 0.500        | 0.510 (0.106)    | 1.000 (0.207)    | -         |    12.29 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3037 | 2024-04-10 | UNiTY             | W   | 0.412      | -            | -                | -                | -         |     3.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3063 | 2024-04-09 | 9 Pandas          | W   | 0.408      | -            | -                | -                | -         |     3.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3114 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.399      | -            | -                | -                | -         |     3.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3165 | 2024-04-05 | Nexus             | W   | 0.380      | -            | -                | -                | -         |     1.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3257 | 2024-04-03 | Rebels            | W   | 0.365      | -            | -                | -                | -         |     3.40 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3300 | 2024-04-01 | Aurora            | W   | 0.354      | 0.500        | 0.420 (0.074)    | -                | -         |    10.63 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3323 | 2024-03-29 | ex-Sprout         | W   | 0.334      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3542 | 2024-03-17 | ECLOT             | L   | 0.254      | -            | -                | -                | -         |    -3.36 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3548 | 2024-03-17 | UNiTY             | W   | 0.253      | -            | -                | -                | 1 (0.253) |     2.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3563 | 2024-03-16 | Sampi             | W   | 0.247      | -            | -                | -                | 1 (0.247) |     1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3575 | 2024-03-15 | UNiTY             | L   | 0.241      | -            | -                | -                | -         |    -5.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3645 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.228      | -            | -                | -                | -         |     2.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3698 | 2024-03-11 | brazylijski luz   | L   | 0.214      | -            | -                | -                | -         |    -5.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3910 | 2024-03-03 | Gaimin Gladiators | L   | 0.161      | -            | -                | -                | -         |    -3.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4203 | 2024-02-18 | Monte             | L   | 0.067      | -            | -                | -                | -         |    -1.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4250 | 2024-02-16 | 500               | W   | 0.054      | -            | -                | -                | -         |     0.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4253 | 2024-02-16 | PERA              | W   | 0.054      | -            | -                | -                | -         |     0.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4258 | 2024-02-16 | 500               | L   | 0.053      | -            | -                | -                | -         |    -1.55 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,889.81)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.841 | $545.00        | $458.46         |
| 2024-06-09 |      0.814 | $10,000.00     | $8,137.27       |
| 2024-06-02 |      0.767 | $1,306.00      | $1,001.81       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,533.70       |
| 2024-03-17 |      0.254 | $2,984.00      | $758.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
