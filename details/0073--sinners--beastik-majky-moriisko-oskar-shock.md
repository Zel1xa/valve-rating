### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.6<br />
<br />
Final Rank Value (946.6) = Starting Rank Value (1090.8) + Head To Head Adjustments (-144.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.436[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.264[<sup>2</sup>](#table1)

The average of these factors is 0.338<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1090.8
- 400 + ( ( 0.338 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1090.8


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
|           79 |       11 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.70 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       29 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -10.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      159 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.57 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      192 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      298 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.70 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      373 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      407 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      490 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.462 (0.201)    | 0 (0.000) |    13.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      619 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | 0 (0.000) |    11.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      684 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      715 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -7.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      728 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1061 | 2024-06-11 | 3DMAX             | L   | 0.847      | -            | -                | -                | -         |    -2.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1073 | 2024-06-11 | ex-Guild Eagles   | W   | 0.845      | -            | -                | -                | 0 (0.000) |     8.56 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1087 | 2024-06-10 | Enterprise        | L   | 0.839      | -            | -                | -                | -         |   -16.04 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1095 | 2024-06-10 | Monte             | L   | 0.839      | -            | -                | -                | -         |   -13.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1099 | 2024-06-10 | 9 Pandas          | L   | 0.839      | -            | -                | -                | -         |   -12.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1106 | 2024-06-10 | PARIVISION        | W   | 0.838      | -            | -                | -                | 0 (0.000) |    15.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1108 | 2024-06-10 | Rare Atom         | L   | 0.838      | -            | -                | -                | -         |   -22.60 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1137 | 2024-06-09 | SAW               | W   | 0.833      | -            | -                | -                | -         |    17.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1145 | 2024-06-09 | 3DMAX             | W   | 0.832      | 0.143        | 0.504 (0.060)    | -                | -         |    24.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1151 | 2024-06-09 | RUSH B            | L   | 0.832      | -            | -                | -                | -         |   -18.01 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1160 | 2024-06-09 | Aurora            | W   | 0.831      | 0.143        | 0.425 (0.050)    | -                | -         |    24.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1192 | 2024-06-08 | Sangal            | L   | 0.827      | -            | -                | -                | -         |    -7.16 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1268 | 2024-06-07 | RUBY              | W   | 0.818      | 0.435        | 0.095 (0.034)    | 0.520 (0.185)    | -         |    10.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1311 | 2024-06-06 | KOI               | L   | 0.813      | -            | -                | -                | -         |   -14.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1371 | 2024-06-05 | RUSH B            | W   | 0.807      | -            | -                | -                | -         |     8.25 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1380 | 2024-06-05 | EYEBALLERS        | L   | 0.806      | -            | -                | -                | -         |   -16.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1433 | 2024-06-04 | VP.Prodigy        | L   | 0.798      | -            | -                | -                | -         |   -15.69 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1471 | 2024-06-02 | UNiTY             | L   | 0.786      | -            | -                | -                | -         |   -14.92 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1488 | 2024-06-01 | GUN5              | L   | 0.781      | -            | -                | -                | -         |   -15.64 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1507 | 2024-06-01 | Sampi             | W   | 0.779      | 0.346        | -                | 1.000 (0.269)    | 1 (0.779) |     7.24 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1539 | 2024-05-31 | UNiTY             | L   | 0.772      | -            | -                | -                | -         |   -15.41 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1557 | 2024-05-30 | B8                | W   | 0.766      | 0.435        | 0.166 (0.055)    | 0.945 (0.315)    | -         |    15.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1584 | 2024-05-29 | brazylijski luz   | W   | 0.760      | -            | -                | -                | -         |     5.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1642 | 2024-05-26 | Sampi             | W   | 0.739      | 0.435        | -                | 1.000 (0.321)    | -         |     7.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1676 | 2024-05-24 | GUN5              | W   | 0.727      | 0.435        | 0.073 (0.023)    | 0.588 (0.186)    | -         |     8.38 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1684 | 2024-05-24 | 9 Pandas          | L   | 0.725      | -            | -                | -                | -         |   -11.51 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1695 | 2024-05-23 | UNiTY             | W   | 0.719      | -            | -                | -                | -         |     9.05 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1701 | 2024-05-23 | Passion UA        | L   | 0.718      | -            | -                | -                | -         |   -11.73 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1819 | 2024-05-20 | VP.Prodigy        | W   | 0.699      | -            | -                | -                | -         |     6.51 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1866 | 2024-05-18 | 1WIN              | L   | 0.686      | -            | -                | -                | -         |   -12.85 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     1952 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.671      | -            | -                | -                | -         |     8.26 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2044 | 2024-05-14 | Passion UA        | W   | 0.660      | 0.435        | 0.172 (0.049)    | 1.000 (0.287)    | -         |     9.99 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2213 | 2024-05-07 | Nemiga            | L   | 0.612      | -            | -                | -                | -         |    -6.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2248 | 2024-05-05 | Endpoint          | W   | 0.599      | -            | -                | -                | -         |     7.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2311 | 2024-05-02 | Gaimin Gladiators | L   | 0.578      | -            | -                | -                | -         |   -10.26 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2338 | 2024-05-01 | B8                | L   | 0.571      | -            | -                | -                | -         |    -9.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2370 | 2024-04-29 | 1WIN              | W   | 0.559      | -            | -                | -                | -         |     5.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2379 | 2024-04-29 | Sangal            | L   | 0.558      | -            | -                | -                | -         |    -7.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2391 | 2024-04-28 | Zero Tenacity     | L   | 0.552      | -            | -                | -                | -         |    -8.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2424 | 2024-04-27 | Zero Tenacity     | L   | 0.544      | -            | -                | -                | -         |    -9.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2439 | 2024-04-26 | PARIVISION        | L   | 0.539      | -            | -                | -                | -         |    -8.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2489 | 2024-04-24 | Endpoint          | L   | 0.526      | -            | -                | -                | -         |   -12.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2525 | 2024-04-22 | HAVU              | W   | 0.512      | -            | -                | -                | -         |     1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2574 | 2024-04-20 | ENCE Academy      | L   | 0.499      | -            | -                | -                | -         |   -13.91 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2629 | 2024-04-19 | ECLOT             | L   | 0.491      | -            | -                | -                | -         |    -6.04 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2719 | 2024-04-17 | Gaimin Gladiators | L   | 0.478      | -            | -                | -                | -         |    -9.63 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2744 | 2024-04-16 | BLEED             | L   | 0.471      | -            | -                | -                | -         |   -10.07 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2774 | 2024-04-14 | Passion UA        | W   | 0.458      | 0.371        | 0.172 (0.029)    | 1.000 (0.170)    | -         |     5.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2863 | 2024-04-10 | 3DMAX             | W   | 0.434      | 0.500        | 0.504 (0.109)    | 1.000 (0.217)    | -         |    13.02 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2890 | 2024-04-10 | UNiTY             | W   | 0.431      | -            | -                | -                | -         |     4.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     2916 | 2024-04-09 | 9 Pandas          | W   | 0.427      | 0.500        | 0.082 (0.017)    | -                | -         |     4.80 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     2967 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.418      | -            | -                | -                | -         |     4.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3018 | 2024-04-05 | Nexus             | W   | 0.400      | -            | -                | -                | -         |     2.62 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3110 | 2024-04-03 | Rebels            | W   | 0.385      | -            | -                | -                | -         |     4.40 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3153 | 2024-04-01 | Aurora            | W   | 0.374      | 0.500        | 0.425 (0.079)    | -                | -         |    11.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3176 | 2024-03-29 | ex-Sprout         | W   | 0.353      | -            | -                | -                | -         |     0.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3390 | 2024-03-17 | ECLOT             | L   | 0.274      | -            | -                | -                | -         |    -2.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3396 | 2024-03-17 | UNiTY             | W   | 0.273      | -            | -                | -                | 1 (0.273) |     2.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3411 | 2024-03-16 | Sampi             | W   | 0.266      | -            | -                | -                | 1 (0.266) |     2.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3422 | 2024-03-15 | UNiTY             | L   | 0.260      | -            | -                | -                | -         |    -5.44 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3491 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.247      | -            | -                | -                | -         |     2.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3543 | 2024-03-11 | brazylijski luz   | L   | 0.233      | -            | -                | -                | -         |    -6.15 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3755 | 2024-03-03 | Gaimin Gladiators | L   | 0.180      | -            | -                | -                | -         |    -3.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4048 | 2024-02-18 | Monte             | L   | 0.086      | -            | -                | -                | -         |    -1.71 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4094 | 2024-02-16 | 500               | W   | 0.074      | -            | -                | -                | -         |     0.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4097 | 2024-02-16 | PERA              | W   | 0.073      | -            | -                | -                | -         |     0.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4102 | 2024-02-16 | 500               | L   | 0.073      | -            | -                | -                | -         |    -2.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,214.82)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.861 | $545.00        | $468.98         |
| 2024-06-09 |      0.833 | $10,000.00     | $8,330.32       |
| 2024-06-02 |      0.786 | $1,306.00      | $1,027.02       |
| 2024-06-02 |      0.786 | $2,000.00      | $1,572.31       |
| 2024-03-17 |      0.274 | $2,984.00      | $816.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
