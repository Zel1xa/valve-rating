### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  955.0<br />
<br />
Final Rank Value (955.0) = Starting Rank Value (1086.7) + Head To Head Adjustments (-131.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.435[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.263[<sup>2</sup>](#table1)

The average of these factors is 0.336<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1086.7
- 400 + ( ( 0.336 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1086.7


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
|           79 |       24 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       46 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -10.72 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      193 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.04 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      226 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      332 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.89 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      406 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      441 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.04 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      524 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    13.05 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      654 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    11.18 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      724 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      750 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -7.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      765 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1125 | 2024-06-11 | 3DMAX             | L   | 0.842      | -            | -                | -                | -         |    -2.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1139 | 2024-06-11 | ex-Guild Eagles   | W   | 0.840      | -            | -                | -                | 0 (0.000) |     8.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1153 | 2024-06-10 | Enterprise        | L   | 0.834      | -            | -                | -                | -         |   -16.12 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1161 | 2024-06-10 | Monte             | L   | 0.833      | -            | -                | -                | -         |   -13.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1165 | 2024-06-10 | 9 Pandas          | L   | 0.833      | -            | -                | -                | -         |   -12.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1172 | 2024-06-10 | PARIVISION        | W   | 0.833      | -            | -                | -                | 0 (0.000) |    15.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1174 | 2024-06-10 | Rare Atom         | L   | 0.832      | -            | -                | -                | -         |   -22.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1204 | 2024-06-09 | SAW               | W   | 0.827      | -            | -                | -                | -         |    17.36 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1212 | 2024-06-09 | 3DMAX             | W   | 0.827      | 0.143        | 0.506 (0.060)    | -                | -         |    24.20 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1218 | 2024-06-09 | RUSH B            | L   | 0.826      | -            | -                | -                | -         |   -17.70 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1227 | 2024-06-09 | Aurora            | W   | 0.826      | 0.143        | 0.423 (0.050)    | -                | -         |    24.36 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1261 | 2024-06-08 | Sangal            | L   | 0.821      | -            | -                | -                | -         |    -6.65 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1340 | 2024-06-07 | RUBY              | W   | 0.813      | 0.435        | 0.095 (0.034)    | 0.502 (0.177)    | -         |     9.98 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1383 | 2024-06-06 | KOI               | L   | 0.808      | -            | -                | -                | -         |   -10.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1443 | 2024-06-05 | RUSH B            | W   | 0.801      | -            | -                | -                | -         |     8.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1452 | 2024-06-05 | EYEBALLERS        | L   | 0.800      | -            | -                | -                | -         |   -16.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1506 | 2024-06-04 | VP.Prodigy        | L   | 0.793      | -            | -                | -                | -         |   -15.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1545 | 2024-06-02 | UNiTY             | L   | 0.780      | -            | -                | -                | -         |   -14.81 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1562 | 2024-06-01 | GUN5              | L   | 0.775      | -            | -                | -                | -         |   -15.59 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1582 | 2024-06-01 | Sampi             | W   | 0.773      | 0.346        | -                | 1.000 (0.267)    | 1 (0.773) |     7.18 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1614 | 2024-05-31 | UNiTY             | L   | 0.767      | -            | -                | -                | -         |   -15.30 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1632 | 2024-05-30 | B8                | W   | 0.761      | 0.435        | 0.165 (0.055)    | 0.912 (0.301)    | -         |    15.33 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1660 | 2024-05-29 | brazylijski luz   | W   | 0.754      | -            | -                | -                | -         |     5.65 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1718 | 2024-05-26 | Sampi             | W   | 0.734      | 0.435        | -                | 1.000 (0.319)    | -         |     7.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1752 | 2024-05-24 | GUN5              | W   | 0.722      | 0.435        | 0.073 (0.023)    | 0.570 (0.179)    | -         |     8.25 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1760 | 2024-05-24 | 9 Pandas          | L   | 0.720      | -            | -                | -                | -         |   -11.48 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1771 | 2024-05-23 | UNiTY             | W   | 0.714      | -            | -                | -                | -         |     8.97 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1777 | 2024-05-23 | Passion UA        | L   | 0.712      | -            | -                | -                | -         |   -11.46 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1895 | 2024-05-20 | VP.Prodigy        | W   | 0.693      | -            | -                | -                | -         |     6.45 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1943 | 2024-05-18 | 1WIN              | L   | 0.681      | -            | -                | -                | -         |   -12.30 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2029 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.665      | -            | -                | -                | -         |     8.23 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2121 | 2024-05-14 | Passion UA        | W   | 0.655      | 0.435        | 0.172 (0.049)    | 1.000 (0.284)    | -         |    10.15 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2291 | 2024-05-07 | Nemiga            | L   | 0.606      | -            | -                | -                | -         |    -6.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2326 | 2024-05-05 | Endpoint          | W   | 0.593      | -            | -                | -                | -         |     7.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2389 | 2024-05-02 | Gaimin Gladiators | L   | 0.573      | -            | -                | -                | -         |   -10.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2416 | 2024-05-01 | B8                | L   | 0.566      | -            | -                | -                | -         |    -9.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2448 | 2024-04-29 | 1WIN              | W   | 0.554      | 0.435        | -                | 0.707 (0.170)    | -         |     6.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2457 | 2024-04-29 | Sangal            | L   | 0.552      | -            | -                | -                | -         |    -6.86 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2469 | 2024-04-28 | Zero Tenacity     | L   | 0.547      | -            | -                | -                | -         |    -8.54 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2502 | 2024-04-27 | Zero Tenacity     | L   | 0.539      | -            | -                | -                | -         |    -8.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2518 | 2024-04-26 | PARIVISION        | L   | 0.534      | -            | -                | -                | -         |    -8.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2568 | 2024-04-24 | Endpoint          | L   | 0.520      | -            | -                | -                | -         |   -12.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2604 | 2024-04-22 | HAVU              | W   | 0.506      | -            | -                | -                | -         |     1.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2653 | 2024-04-20 | ENCE Academy      | L   | 0.493      | -            | -                | -                | -         |   -13.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2708 | 2024-04-19 | ECLOT             | L   | 0.485      | -            | -                | -                | -         |    -5.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2798 | 2024-04-17 | Gaimin Gladiators | L   | 0.472      | -            | -                | -                | -         |    -9.55 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2823 | 2024-04-16 | BLEED             | L   | 0.466      | -            | -                | -                | -         |    -9.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2853 | 2024-04-14 | Passion UA        | W   | 0.453      | 0.371        | 0.172 (0.029)    | -                | -         |     5.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2942 | 2024-04-10 | 3DMAX             | W   | 0.428      | 0.500        | 0.506 (0.108)    | 1.000 (0.214)    | -         |    12.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2969 | 2024-04-10 | UNiTY             | W   | 0.425      | -            | -                | -                | -         |     4.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     2995 | 2024-04-09 | 9 Pandas          | W   | 0.422      | 0.500        | 0.082 (0.017)    | -                | -         |     4.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3046 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.412      | -            | -                | -                | -         |     4.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3097 | 2024-04-05 | Nexus             | W   | 0.394      | -            | -                | -                | -         |     2.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3189 | 2024-04-03 | Rebels            | W   | 0.379      | -            | -                | -                | -         |     4.43 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3232 | 2024-04-01 | Aurora            | W   | 0.368      | 0.500        | 0.423 (0.078)    | -                | -         |    11.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3255 | 2024-03-29 | ex-Sprout         | W   | 0.348      | -            | -                | -                | -         |     0.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3474 | 2024-03-17 | ECLOT             | L   | 0.268      | -            | -                | -                | -         |    -2.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3480 | 2024-03-17 | UNiTY             | W   | 0.267      | -            | -                | -                | 1 (0.267) |     2.91 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3495 | 2024-03-16 | Sampi             | W   | 0.260      | -            | -                | -                | 1 (0.260) |     2.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3507 | 2024-03-15 | UNiTY             | L   | 0.255      | -            | -                | -                | -         |    -5.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3577 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.242      | -            | -                | -                | -         |     2.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3630 | 2024-03-11 | brazylijski luz   | L   | 0.228      | -            | -                | -                | -         |    -5.98 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3842 | 2024-03-03 | Gaimin Gladiators | L   | 0.175      | -            | -                | -                | -         |    -3.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4135 | 2024-02-18 | Monte             | L   | 0.081      | -            | -                | -                | -         |    -1.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4182 | 2024-02-16 | 500               | W   | 0.068      | -            | -                | -                | -         |     0.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4185 | 2024-02-16 | PERA              | W   | 0.068      | -            | -                | -                | -         |     0.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4190 | 2024-02-16 | 500               | L   | 0.067      | -            | -                | -                | -         |    -1.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,122.46)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.855 | $545.00        | $465.99         |
| 2024-06-09 |      0.828 | $10,000.00     | $8,275.46       |
| 2024-06-02 |      0.781 | $1,306.00      | $1,019.86       |
| 2024-06-02 |      0.781 | $2,000.00      | $1,561.34       |
| 2024-03-17 |      0.268 | $2,984.00      | $799.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
