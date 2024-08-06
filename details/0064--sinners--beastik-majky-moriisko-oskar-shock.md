### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  992.3<br />
<br />
Final Rank Value (992.3) = Starting Rank Value (1151.2) + Head To Head Adjustments (-158.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.2
- 400 + ( ( 0.366 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1151.2


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
|           81 |        4 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.296)    | 0 (0.000) |    16.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       38 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       74 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       96 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.16 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      244 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      280 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      384 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      459 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.05 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      493 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      576 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.438 (0.190)    | 0 (0.000) |    12.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      706 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.514 (0.223)    | 0 (0.000) |    10.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      775 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.96 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      804 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      817 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1177 | 2024-06-11 | 3DMAX             | L   | 0.831      | -            | -                | -                | -         |    -2.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1191 | 2024-06-11 | ex-Guild Eagles   | W   | 0.829      | -            | -                | -                | -         |     7.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1205 | 2024-06-10 | Enterprise        | L   | 0.824      | -            | -                | -                | -         |   -16.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1213 | 2024-06-10 | Monte             | L   | 0.823      | -            | -                | -                | -         |   -13.78 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1217 | 2024-06-10 | 9 Pandas          | L   | 0.823      | -            | -                | -                | -         |   -12.90 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1224 | 2024-06-10 | PARIVISION        | W   | 0.823      | -            | -                | -                | -         |    14.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1226 | 2024-06-10 | Rare Atom         | L   | 0.822      | -            | -                | -                | -         |   -19.98 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1256 | 2024-06-09 | SAW               | W   | 0.817      | -            | -                | -                | -         |    16.35 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1264 | 2024-06-09 | 3DMAX             | W   | 0.817      | 0.143        | 0.509 (0.059)    | -                | -         |    23.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1270 | 2024-06-09 | RUSH B            | L   | 0.816      | -            | -                | -                | -         |   -18.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1279 | 2024-06-09 | Aurora            | W   | 0.816      | 0.143        | 0.421 (0.049)    | -                | -         |    23.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1313 | 2024-06-08 | Sangal            | L   | 0.811      | -            | -                | -                | -         |    -7.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1392 | 2024-06-07 | RUBY              | W   | 0.803      | 0.435        | 0.095 (0.033)    | 0.491 (0.171)    | -         |     9.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1435 | 2024-06-06 | KOI               | L   | 0.798      | -            | -                | -                | -         |   -11.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1495 | 2024-06-05 | RUSH B            | W   | 0.791      | -            | -                | -                | -         |     7.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1504 | 2024-06-05 | EYEBALLERS        | L   | 0.790      | -            | -                | -                | -         |   -17.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1558 | 2024-06-04 | VP.Prodigy        | L   | 0.783      | -            | -                | -                | -         |   -16.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1597 | 2024-06-02 | UNiTY             | L   | 0.770      | -            | -                | -                | -         |   -15.39 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1614 | 2024-06-01 | GUN5              | L   | 0.765      | -            | -                | -                | -         |   -16.26 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1634 | 2024-06-01 | Sampi             | W   | 0.763      | 0.346        | -                | 1.000 (0.264)    | 1 (0.763) |     6.30 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1666 | 2024-05-31 | UNiTY             | L   | 0.757      | -            | -                | -                | -         |   -15.92 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1684 | 2024-05-30 | B8                | W   | 0.751      | 0.435        | 0.164 (0.054)    | 0.934 (0.305)    | -         |    14.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1712 | 2024-05-29 | brazylijski luz   | W   | 0.744      | -            | -                | -                | -         |     4.79 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1770 | 2024-05-26 | Sampi             | W   | 0.724      | 0.435        | -                | 1.000 (0.315)    | -         |     6.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1804 | 2024-05-24 | GUN5              | W   | 0.711      | 0.435        | 0.072 (0.022)    | 0.562 (0.174)    | -         |     7.15 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1812 | 2024-05-24 | 9 Pandas          | L   | 0.709      | -            | -                | -                | -         |   -12.47 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1823 | 2024-05-23 | UNiTY             | W   | 0.704      | -            | -                | -                | -         |     7.86 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1829 | 2024-05-23 | Passion UA        | L   | 0.702      | -            | -                | -                | -         |   -12.26 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1947 | 2024-05-20 | VP.Prodigy        | W   | 0.683      | -            | -                | -                | -         |     5.43 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1995 | 2024-05-18 | 1WIN              | L   | 0.671      | -            | -                | -                | -         |   -12.96 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2081 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.655      | -            | -                | -                | -         |     7.04 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2173 | 2024-05-14 | Passion UA        | W   | 0.644      | 0.435        | 0.173 (0.048)    | 1.000 (0.280)    | -         |     9.00 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2343 | 2024-05-07 | Nemiga            | L   | 0.596      | -            | -                | -                | -         |    -6.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2378 | 2024-05-05 | Endpoint          | W   | 0.583      | -            | -                | -                | -         |     5.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2441 | 2024-05-02 | Gaimin Gladiators | L   | 0.563      | -            | -                | -                | -         |   -11.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2468 | 2024-05-01 | B8                | L   | 0.556      | -            | -                | -                | -         |   -10.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2500 | 2024-04-29 | 1WIN              | W   | 0.543      | -            | -                | -                | -         |     5.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2509 | 2024-04-29 | Sangal            | L   | 0.542      | -            | -                | -                | -         |    -7.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2521 | 2024-04-28 | Zero Tenacity     | L   | 0.537      | -            | -                | -                | -         |    -9.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2554 | 2024-04-27 | Zero Tenacity     | L   | 0.529      | -            | -                | -                | -         |    -9.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2570 | 2024-04-26 | PARIVISION        | L   | 0.524      | -            | -                | -                | -         |    -9.44 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2620 | 2024-04-24 | Endpoint          | L   | 0.510      | -            | -                | -                | -         |   -12.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2656 | 2024-04-22 | HAVU              | W   | 0.496      | -            | -                | -                | -         |     1.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2705 | 2024-04-20 | ENCE Academy      | L   | 0.483      | -            | -                | -                | -         |   -13.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2760 | 2024-04-19 | ECLOT             | L   | 0.475      | -            | -                | -                | -         |    -6.85 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2850 | 2024-04-17 | Gaimin Gladiators | L   | 0.462      | -            | -                | -                | -         |   -10.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2875 | 2024-04-16 | BLEED             | L   | 0.456      | -            | -                | -                | -         |   -10.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2905 | 2024-04-14 | Passion UA        | W   | 0.443      | 0.371        | 0.173 (0.028)    | -                | -         |     4.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2994 | 2024-04-10 | 3DMAX             | W   | 0.418      | 0.500        | 0.509 (0.106)    | 1.000 (0.209)    | -         |    12.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3021 | 2024-04-10 | UNiTY             | W   | 0.415      | -            | -                | -                | -         |     3.28 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3047 | 2024-04-09 | 9 Pandas          | W   | 0.411      | -            | -                | -                | -         |     3.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3098 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.402      | -            | -                | -                | -         |     3.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3149 | 2024-04-05 | Nexus             | W   | 0.384      | -            | -                | -                | -         |     1.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3241 | 2024-04-03 | Rebels            | W   | 0.369      | -            | -                | -                | -         |     3.43 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3284 | 2024-04-01 | Aurora            | W   | 0.358      | 0.500        | 0.421 (0.075)    | -                | -         |    10.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3307 | 2024-03-29 | ex-Sprout         | W   | 0.338      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3526 | 2024-03-17 | ECLOT             | L   | 0.258      | -            | -                | -                | -         |    -3.42 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3532 | 2024-03-17 | UNiTY             | W   | 0.257      | -            | -                | -                | 1 (0.257) |     2.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3547 | 2024-03-16 | Sampi             | W   | 0.250      | -            | -                | -                | 1 (0.250) |     1.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3559 | 2024-03-15 | UNiTY             | L   | 0.245      | -            | -                | -                | -         |    -5.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3629 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.231      | -            | -                | -                | -         |     2.08 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3682 | 2024-03-11 | brazylijski luz   | L   | 0.218      | -            | -                | -                | -         |    -6.02 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3894 | 2024-03-03 | Gaimin Gladiators | L   | 0.164      | -            | -                | -                | -         |    -3.80 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4187 | 2024-02-18 | Monte             | L   | 0.071      | -            | -                | -                | -         |    -1.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4234 | 2024-02-16 | 500               | W   | 0.058      | -            | -                | -                | -         |     0.14 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4237 | 2024-02-16 | PERA              | W   | 0.058      | -            | -                | -                | -         |     0.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4242 | 2024-02-16 | 500               | L   | 0.057      | -            | -                | -                | -         |    -1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,952.16)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.845 | $545.00        | $460.47         |
| 2024-06-09 |      0.817 | $10,000.00     | $8,174.31       |
| 2024-06-02 |      0.771 | $1,306.00      | $1,006.65       |
| 2024-06-02 |      0.771 | $2,000.00      | $1,541.11       |
| 2024-03-17 |      0.258 | $2,984.00      | $769.62         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
