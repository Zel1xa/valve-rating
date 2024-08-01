### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.0<br />
<br />
Final Rank Value (956.0) = Starting Rank Value (1054.8) + Head To Head Adjustments (-98.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.157[<sup>2</sup>](#table1)

The average of these factors is 0.318<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1054.8
- 400 + ( ( 0.318 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1054.8


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
|           80 |      100 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |      134 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      240 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      314 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      350 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.51 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      436 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    13.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      571 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.555 (0.241)    | 0 (0.000) |    12.61 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      642 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -26.10 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      675 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -7.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      689 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -24.20 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |     1040 | 2024-06-11 | 3DMAX             | L   | 0.860      | -            | -                | -                | -         |    -2.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |     1054 | 2024-06-11 | ex-Guild Eagles   | W   | 0.858      | -            | -                | -                | 0 (0.000) |     8.88 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |     1069 | 2024-06-10 | Enterprise        | L   | 0.853      | -            | -                | -                | -         |   -16.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1077 | 2024-06-10 | Monte             | L   | 0.852      | -            | -                | -                | -         |   -13.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1081 | 2024-06-10 | 9 Pandas          | L   | 0.852      | -            | -                | -                | -         |   -12.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1088 | 2024-06-10 | PARIVISION        | W   | 0.851      | -            | -                | -                | 0 (0.000) |    15.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1090 | 2024-06-10 | Rare Atom         | L   | 0.851      | -            | -                | -                | -         |   -23.69 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1120 | 2024-06-09 | SAW               | W   | 0.846      | -            | -                | -                | 0 (0.000) |    17.98 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1128 | 2024-06-09 | 3DMAX             | W   | 0.846      | 0.143        | 0.505 (0.061)    | -                | -         |    24.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1134 | 2024-06-09 | RUSH B            | L   | 0.845      | -            | -                | -                | -         |   -18.34 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1144 | 2024-06-09 | Aurora            | W   | 0.845      | 0.143        | 0.431 (0.052)    | -                | -         |    24.95 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1179 | 2024-06-08 | Sangal            | L   | 0.840      | -            | -                | -                | -         |    -7.20 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1265 | 2024-06-07 | RUBY              | W   | 0.832      | 0.435        | 0.097 (0.035)    | 0.544 (0.197)    | -         |    10.53 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1310 | 2024-06-06 | KOI               | L   | 0.827      | -            | -                | -                | -         |   -14.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1373 | 2024-06-05 | RUSH B            | W   | 0.820      | -            | -                | -                | -         |     8.34 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1382 | 2024-06-05 | EYEBALLERS        | L   | 0.819      | -            | -                | -                | -         |   -17.10 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1436 | 2024-06-04 | VP.Prodigy        | L   | 0.812      | -            | -                | -                | -         |   -15.79 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1476 | 2024-06-02 | UNiTY             | L   | 0.799      | -            | -                | -                | -         |   -15.30 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           52 |     1493 | 2024-06-01 | GUN5              | L   | 0.794      | -            | -                | -                | -         |   -15.18 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           51 |     1513 | 2024-06-01 | Sampi             | W   | 0.792      | 0.346        | -                | 1.000 (0.274)    | 1 (0.792) |     7.18 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           50 |     1545 | 2024-05-31 | UNiTY             | L   | 0.786      | -            | -                | -                | -         |   -15.73 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1563 | 2024-05-30 | B8                | W   | 0.779      | 0.435        | 0.168 (0.057)    | 0.878 (0.297)    | -         |    15.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           48 |     1591 | 2024-05-29 | brazylijski luz   | W   | 0.773      | -            | -                | -                | -         |     6.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           47 |     1651 | 2024-05-26 | Sampi             | W   | 0.753      | 0.435        | -                | 1.000 (0.327)    | -         |     7.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           46 |     1685 | 2024-05-24 | GUN5              | W   | 0.740      | 0.435        | -                | 0.555 (0.179)    | -         |     9.30 | AJTT, beastik, majky, MoriiSko, oskar  |
|           45 |     1693 | 2024-05-24 | 9 Pandas          | L   | 0.738      | -            | -                | -                | -         |   -11.54 | AJTT, beastik, majky, oskar, SHOCK     |
|           44 |     1704 | 2024-05-23 | UNiTY             | W   | 0.733      | -            | -                | -                | -         |     9.16 | AJTT, beastik, majky, MoriiSko, oskar  |
|           43 |     1710 | 2024-05-23 | Passion UA        | L   | 0.731      | -            | -                | -                | -         |   -11.77 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1848 | 2024-05-20 | VP.Prodigy        | W   | 0.712      | -            | -                | -                | -         |     6.77 | AJTT, beastik, majky, MoriiSko, oskar  |
|           41 |     1865 | 2024-05-19 | Zero Tenacity     | W   | 0.707      | 0.435        | 0.139 (0.043)    | 1.000 (0.307)    | -         |    12.49 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           40 |     1901 | 2024-05-18 | 1WIN              | L   | 0.699      | -            | -                | -                | -         |   -12.58 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           39 |     1988 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.684      | -            | -                | -                | -         |     8.54 | AJTT, beastik, majky, oskar, SHOCK     |
|           38 |     2086 | 2024-05-14 | Passion UA        | W   | 0.673      | 0.435        | 0.173 (0.050)    | 1.000 (0.293)    | -         |    10.76 | AJTT, beastik, majky, oskar, SHOCK     |
|           37 |     2261 | 2024-05-07 | Nemiga            | L   | 0.625      | -            | -                | -                | -         |    -5.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           36 |     2296 | 2024-05-05 | Endpoint          | W   | 0.612      | -            | -                | -                | -         |     8.08 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           35 |     2360 | 2024-05-02 | Gaimin Gladiators | L   | 0.592      | -            | -                | -                | -         |    -9.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2388 | 2024-05-01 | B8                | L   | 0.584      | -            | -                | -                | -         |    -9.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2421 | 2024-04-29 | 1WIN              | W   | 0.572      | -            | -                | -                | -         |     6.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2430 | 2024-04-29 | Sangal            | L   | 0.571      | -            | -                | -                | -         |    -6.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2442 | 2024-04-28 | Zero Tenacity     | L   | 0.566      | -            | -                | -                | -         |    -8.48 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2476 | 2024-04-27 | Zero Tenacity     | L   | 0.558      | -            | -                | -                | -         |    -8.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2491 | 2024-04-26 | PARIVISION        | L   | 0.553      | -            | -                | -                | -         |    -8.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2541 | 2024-04-24 | Endpoint          | L   | 0.539      | -            | -                | -                | -         |   -11.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2555 | 2024-04-23 | Nemiga            | W   | 0.533      | 0.435        | 0.324 (0.075)    | -                | -         |    10.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2580 | 2024-04-22 | HAVU              | W   | 0.525      | -            | -                | -                | -         |     2.02 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2632 | 2024-04-20 | ENCE Academy      | L   | 0.512      | -            | -                | -                | -         |   -13.91 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2688 | 2024-04-19 | ECLOT             | L   | 0.504      | -            | -                | -                | -         |    -7.68 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2780 | 2024-04-17 | Gaimin Gladiators | L   | 0.491      | -            | -                | -                | -         |    -9.02 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2806 | 2024-04-16 | BLEED             | L   | 0.484      | -            | -                | -                | -         |    -9.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2836 | 2024-04-14 | Passion UA        | W   | 0.472      | 0.371        | 0.173 (0.030)    | -                | -         |     6.68 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2926 | 2024-04-10 | 3DMAX             | W   | 0.447      | 0.500        | 0.505 (0.113)    | 1.000 (0.223)    | -         |    13.53 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2953 | 2024-04-10 | UNiTY             | W   | 0.444      | -            | -                | -                | -         |     4.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2979 | 2024-04-09 | 9 Pandas          | W   | 0.440      | -            | -                | -                | -         |     5.63 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3030 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.431      | -            | -                | -                | -         |     4.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3081 | 2024-04-05 | Nexus             | W   | 0.413      | -            | -                | -                | -         |     3.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3179 | 2024-04-03 | Rebels            | W   | 0.398      | -            | -                | -                | -         |     5.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3224 | 2024-04-01 | Aurora            | W   | 0.387      | 0.500        | 0.431 (0.083)    | -                | -         |    11.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3247 | 2024-03-29 | ex-Sprout         | W   | 0.367      | -            | -                | -                | -         |     0.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3471 | 2024-03-17 | ECLOT             | L   | 0.287      | -            | -                | -                | -         |    -3.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3477 | 2024-03-17 | UNiTY             | W   | 0.286      | -            | -                | -                | 1 (0.286) |     3.48 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3492 | 2024-03-16 | Sampi             | W   | 0.279      | -            | -                | -                | 1 (0.279) |     2.86 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3504 | 2024-03-15 | UNiTY             | L   | 0.274      | -            | -                | -                | -         |    -5.32 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3578 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.260      | -            | -                | -                | -         |     3.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3632 | 2024-03-11 | brazylijski luz   | L   | 0.247      | -            | -                | -                | -         |    -6.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3850 | 2024-03-03 | Gaimin Gladiators | L   | 0.193      | -            | -                | -                | -         |    -3.56 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     4153 | 2024-02-18 | Monte             | L   | 0.100      | -            | -                | -                | -         |    -1.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4200 | 2024-02-16 | 500               | W   | 0.087      | -            | -                | -                | -         |     0.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4203 | 2024-02-16 | PERA              | W   | 0.087      | -            | -                | -                | -         |     0.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4208 | 2024-02-16 | 500               | L   | 0.086      | -            | -                | -                | -         |    -2.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4427 | 2024-02-04 | Into the Breach   | L   | 0.005      | -            | -                | -                | -         |    -0.15 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,438.51)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.874 | $545.00        | $476.22         |
| 2024-06-09 |      0.846 | $10,000.00     | $8,463.19       |
| 2024-06-02 |      0.800 | $1,306.00      | $1,044.38       |
| 2024-06-02 |      0.799 | $2,000.00      | $1,598.89       |
| 2024-03-17 |      0.287 | $2,984.00      | $855.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
