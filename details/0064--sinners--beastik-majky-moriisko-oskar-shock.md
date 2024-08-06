### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  993.3<br />
<br />
Final Rank Value (993.3) = Starting Rank Value (1151.0) + Head To Head Adjustments (-157.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.376[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.0
- 400 + ( ( 0.365 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1151.0


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
|           81 |       12 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.578 (0.289)    | 0 (0.000) |    16.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       46 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       82 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      104 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      252 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      288 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      392 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      467 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.10 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      501 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      584 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    12.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      714 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.502 (0.218)    | 0 (0.000) |    10.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      783 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      812 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      825 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.60 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1185 | 2024-06-11 | 3DMAX             | L   | 0.829      | -            | -                | -                | -         |    -2.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1199 | 2024-06-11 | ex-Guild Eagles   | W   | 0.827      | -            | -                | -                | -         |     7.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1213 | 2024-06-10 | Enterprise        | L   | 0.821      | -            | -                | -                | -         |   -16.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1221 | 2024-06-10 | Monte             | L   | 0.821      | -            | -                | -                | -         |   -13.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1225 | 2024-06-10 | 9 Pandas          | L   | 0.820      | -            | -                | -                | -         |   -12.89 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1232 | 2024-06-10 | PARIVISION        | W   | 0.820      | -            | -                | -                | -         |    14.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1234 | 2024-06-10 | Rare Atom         | L   | 0.819      | -            | -                | -                | -         |   -19.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1264 | 2024-06-09 | SAW               | W   | 0.814      | -            | -                | -                | -         |    16.23 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1272 | 2024-06-09 | 3DMAX             | W   | 0.814      | 0.143        | 0.510 (0.059)    | -                | -         |    23.68 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1278 | 2024-06-09 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -18.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1287 | 2024-06-09 | Aurora            | W   | 0.813      | 0.143        | 0.421 (0.049)    | -                | -         |    23.85 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1321 | 2024-06-08 | Sangal            | L   | 0.808      | -            | -                | -                | -         |    -7.10 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1400 | 2024-06-07 | RUBY              | W   | 0.800      | 0.435        | 0.095 (0.033)    | 0.480 (0.167)    | -         |     9.18 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1443 | 2024-06-06 | KOI               | L   | 0.795      | -            | -                | -                | -         |   -11.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1503 | 2024-06-05 | RUSH B            | W   | 0.788      | -            | -                | -                | -         |     7.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1512 | 2024-06-05 | EYEBALLERS        | L   | 0.787      | -            | -                | -                | -         |   -17.30 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1566 | 2024-06-04 | VP.Prodigy        | L   | 0.780      | -            | -                | -                | -         |   -16.23 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1605 | 2024-06-02 | UNiTY             | L   | 0.767      | -            | -                | -                | -         |   -15.37 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1622 | 2024-06-01 | GUN5              | L   | 0.762      | -            | -                | -                | -         |   -16.22 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1642 | 2024-06-01 | Sampi             | W   | 0.760      | 0.346        | -                | 1.000 (0.263)    | 1 (0.760) |     6.27 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1674 | 2024-05-31 | UNiTY             | L   | 0.754      | -            | -                | -                | -         |   -15.89 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1692 | 2024-05-30 | B8                | W   | 0.748      | 0.435        | 0.170 (0.055)    | 0.912 (0.296)    | -         |    14.10 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1720 | 2024-05-29 | brazylijski luz   | W   | 0.741      | -            | -                | -                | -         |     4.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1778 | 2024-05-26 | Sampi             | W   | 0.721      | 0.435        | -                | 1.000 (0.313)    | -         |     6.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1812 | 2024-05-24 | GUN5              | W   | 0.709      | 0.435        | 0.072 (0.022)    | 0.550 (0.169)    | -         |     7.11 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1820 | 2024-05-24 | 9 Pandas          | L   | 0.707      | -            | -                | -                | -         |   -12.45 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1831 | 2024-05-23 | UNiTY             | W   | 0.701      | -            | -                | -                | -         |     7.80 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1837 | 2024-05-23 | Passion UA        | L   | 0.699      | -            | -                | -                | -         |   -12.19 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1955 | 2024-05-20 | VP.Prodigy        | W   | 0.680      | -            | -                | -                | -         |     5.40 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     2003 | 2024-05-18 | 1WIN              | L   | 0.668      | -            | -                | -                | -         |   -12.92 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2089 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.652      | -            | -                | -                | -         |     7.02 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2181 | 2024-05-14 | Passion UA        | W   | 0.642      | 0.435        | 0.173 (0.048)    | 1.000 (0.279)    | -         |     8.98 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2351 | 2024-05-07 | Nemiga            | L   | 0.593      | -            | -                | -                | -         |    -6.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2386 | 2024-05-05 | Endpoint          | W   | 0.581      | -            | -                | -                | -         |     5.83 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2449 | 2024-05-02 | Gaimin Gladiators | L   | 0.560      | -            | -                | -                | -         |   -11.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2476 | 2024-05-01 | B8                | L   | 0.553      | -            | -                | -                | -         |   -10.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2508 | 2024-04-29 | 1WIN              | W   | 0.541      | -            | -                | -                | -         |     5.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2517 | 2024-04-29 | Sangal            | L   | 0.539      | -            | -                | -                | -         |    -7.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2529 | 2024-04-28 | Zero Tenacity     | L   | 0.534      | -            | -                | -                | -         |    -9.36 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2562 | 2024-04-27 | Zero Tenacity     | L   | 0.526      | -            | -                | -                | -         |    -9.71 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2578 | 2024-04-26 | PARIVISION        | L   | 0.521      | -            | -                | -                | -         |    -9.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2628 | 2024-04-24 | Endpoint          | L   | 0.507      | -            | -                | -                | -         |   -12.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2664 | 2024-04-22 | HAVU              | W   | 0.493      | -            | -                | -                | -         |     1.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2713 | 2024-04-20 | ENCE Academy      | L   | 0.480      | -            | -                | -                | -         |   -13.85 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2768 | 2024-04-19 | ECLOT             | L   | 0.472      | -            | -                | -                | -         |    -6.80 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2858 | 2024-04-17 | Gaimin Gladiators | L   | 0.460      | -            | -                | -                | -         |   -10.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2883 | 2024-04-16 | BLEED             | L   | 0.453      | -            | -                | -                | -         |   -10.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2913 | 2024-04-14 | Passion UA        | W   | 0.440      | 0.371        | 0.173 (0.028)    | -                | -         |     4.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     3002 | 2024-04-10 | 3DMAX             | W   | 0.415      | 0.500        | 0.510 (0.106)    | 1.000 (0.208)    | -         |    12.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3029 | 2024-04-10 | UNiTY             | W   | 0.412      | -            | -                | -                | -         |     3.25 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3055 | 2024-04-09 | 9 Pandas          | W   | 0.409      | -            | -                | -                | -         |     3.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3106 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.399      | -            | -                | -                | -         |     3.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3157 | 2024-04-05 | Nexus             | W   | 0.381      | -            | -                | -                | -         |     1.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3249 | 2024-04-03 | Rebels            | W   | 0.366      | -            | -                | -                | -         |     3.42 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3292 | 2024-04-01 | Aurora            | W   | 0.355      | 0.500        | 0.421 (0.075)    | -                | -         |    10.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3315 | 2024-03-29 | ex-Sprout         | W   | 0.335      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3534 | 2024-03-17 | ECLOT             | L   | 0.255      | -            | -                | -                | -         |    -3.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3540 | 2024-03-17 | UNiTY             | W   | 0.254      | -            | -                | -                | 1 (0.254) |     2.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3555 | 2024-03-16 | Sampi             | W   | 0.248      | -            | -                | -                | 1 (0.248) |     1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3567 | 2024-03-15 | UNiTY             | L   | 0.242      | -            | -                | -                | -         |    -5.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3637 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.229      | -            | -                | -                | -         |     2.07 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3690 | 2024-03-11 | brazylijski luz   | L   | 0.215      | -            | -                | -                | -         |    -5.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3902 | 2024-03-03 | Gaimin Gladiators | L   | 0.162      | -            | -                | -                | -         |    -3.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4195 | 2024-02-18 | Monte             | L   | 0.068      | -            | -                | -                | -         |    -1.53 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4242 | 2024-02-16 | 500               | W   | 0.055      | -            | -                | -                | -         |     0.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4245 | 2024-02-16 | PERA              | W   | 0.055      | -            | -                | -                | -         |     0.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4250 | 2024-02-16 | 500               | L   | 0.054      | -            | -                | -                | -         |    -1.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,905.40)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.842 | $545.00        | $458.96         |
| 2024-06-09 |      0.815 | $10,000.00     | $8,146.53       |
| 2024-06-02 |      0.768 | $1,306.00      | $1,003.02       |
| 2024-06-02 |      0.768 | $2,000.00      | $1,535.56       |
| 2024-03-17 |      0.255 | $2,984.00      | $761.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
