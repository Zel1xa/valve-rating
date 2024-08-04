### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [71](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  948.7<br />
<br />
Final Rank Value (948.7) = Starting Rank Value (1086.7) + Head To Head Adjustments (-138.0)<br />

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
|           79 |       16 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       38 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -10.53 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      185 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      218 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      324 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.68 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      398 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      433 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      516 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    13.36 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      646 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    11.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      716 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      742 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -7.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      757 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1117 | 2024-06-11 | 3DMAX             | L   | 0.842      | -            | -                | -                | -         |    -2.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1131 | 2024-06-11 | ex-Guild Eagles   | W   | 0.840      | -            | -                | -                | 0 (0.000) |     8.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1145 | 2024-06-10 | Enterprise        | L   | 0.835      | -            | -                | -                | -         |   -16.10 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1153 | 2024-06-10 | Monte             | L   | 0.834      | -            | -                | -                | -         |   -13.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1157 | 2024-06-10 | 9 Pandas          | L   | 0.834      | -            | -                | -                | -         |   -12.26 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1164 | 2024-06-10 | PARIVISION        | W   | 0.833      | -            | -                | -                | 0 (0.000) |    15.26 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1166 | 2024-06-10 | Rare Atom         | L   | 0.833      | -            | -                | -                | -         |   -22.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1196 | 2024-06-09 | SAW               | W   | 0.828      | -            | -                | -                | -         |    17.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1204 | 2024-06-09 | 3DMAX             | W   | 0.828      | 0.143        | 0.506 (0.060)    | -                | -         |    24.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1210 | 2024-06-09 | RUSH B            | L   | 0.827      | -            | -                | -                | -         |   -18.01 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1219 | 2024-06-09 | Aurora            | W   | 0.827      | 0.143        | 0.424 (0.050)    | -                | -         |    24.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1253 | 2024-06-08 | Sangal            | L   | 0.822      | -            | -                | -                | -         |    -6.65 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1332 | 2024-06-07 | RUBY              | W   | 0.814      | 0.435        | 0.095 (0.034)    | 0.502 (0.177)    | -         |    10.02 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1375 | 2024-06-06 | KOI               | L   | 0.809      | -            | -                | -                | -         |   -10.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1435 | 2024-06-05 | RUSH B            | W   | 0.802      | -            | -                | -                | -         |     8.23 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1444 | 2024-06-05 | EYEBALLERS        | L   | 0.801      | -            | -                | -                | -         |   -16.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1498 | 2024-06-04 | VP.Prodigy        | L   | 0.794      | -            | -                | -                | -         |   -15.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1537 | 2024-06-02 | UNiTY             | L   | 0.781      | -            | -                | -                | -         |   -14.80 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1554 | 2024-06-01 | GUN5              | L   | 0.776      | -            | -                | -                | -         |   -15.57 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1574 | 2024-06-01 | Sampi             | W   | 0.774      | 0.346        | -                | 1.000 (0.268)    | 1 (0.774) |     7.20 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1606 | 2024-05-31 | UNiTY             | L   | 0.767      | -            | -                | -                | -         |   -15.29 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1624 | 2024-05-30 | B8                | W   | 0.761      | 0.435        | 0.165 (0.055)    | 0.912 (0.302)    | -         |    15.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1652 | 2024-05-29 | brazylijski luz   | W   | 0.755      | -            | -                | -                | -         |     5.65 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1710 | 2024-05-26 | Sampi             | W   | 0.735      | 0.435        | -                | 1.000 (0.319)    | -         |     7.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1744 | 2024-05-24 | GUN5              | W   | 0.722      | 0.435        | 0.073 (0.023)    | 0.570 (0.179)    | -         |     8.29 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1752 | 2024-05-24 | 9 Pandas          | L   | 0.720      | -            | -                | -                | -         |   -11.49 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1763 | 2024-05-23 | UNiTY             | W   | 0.715      | -            | -                | -                | -         |     9.01 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1769 | 2024-05-23 | Passion UA        | L   | 0.713      | -            | -                | -                | -         |   -11.46 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1887 | 2024-05-20 | VP.Prodigy        | W   | 0.694      | -            | -                | -                | -         |     6.48 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1935 | 2024-05-18 | 1WIN              | L   | 0.681      | -            | -                | -                | -         |   -12.78 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2021 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.666      | -            | -                | -                | -         |     8.24 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2113 | 2024-05-14 | Passion UA        | W   | 0.655      | 0.435        | 0.172 (0.049)    | 1.000 (0.285)    | -         |    10.15 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2283 | 2024-05-07 | Nemiga            | L   | 0.607      | -            | -                | -                | -         |    -6.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2318 | 2024-05-05 | Endpoint          | W   | 0.594      | -            | -                | -                | -         |     7.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2381 | 2024-05-02 | Gaimin Gladiators | L   | 0.574      | -            | -                | -                | -         |   -10.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2408 | 2024-05-01 | B8                | L   | 0.566      | -            | -                | -                | -         |    -9.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2440 | 2024-04-29 | 1WIN              | W   | 0.554      | -            | -                | -                | -         |     5.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2449 | 2024-04-29 | Sangal            | L   | 0.553      | -            | -                | -                | -         |    -6.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2461 | 2024-04-28 | Zero Tenacity     | L   | 0.547      | -            | -                | -                | -         |    -8.55 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2494 | 2024-04-27 | Zero Tenacity     | L   | 0.540      | -            | -                | -                | -         |    -8.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2510 | 2024-04-26 | PARIVISION        | L   | 0.535      | -            | -                | -                | -         |    -8.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2560 | 2024-04-24 | Endpoint          | L   | 0.521      | -            | -                | -                | -         |   -12.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2596 | 2024-04-22 | HAVU              | W   | 0.507      | -            | -                | -                | -         |     1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2645 | 2024-04-20 | ENCE Academy      | L   | 0.494      | -            | -                | -                | -         |   -13.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2700 | 2024-04-19 | ECLOT             | L   | 0.486      | -            | -                | -                | -         |    -5.97 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2790 | 2024-04-17 | Gaimin Gladiators | L   | 0.473      | -            | -                | -                | -         |    -9.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2815 | 2024-04-16 | BLEED             | L   | 0.466      | -            | -                | -                | -         |    -9.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2845 | 2024-04-14 | Passion UA        | W   | 0.454      | 0.371        | 0.172 (0.029)    | 1.000 (0.168)    | -         |     5.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2934 | 2024-04-10 | 3DMAX             | W   | 0.429      | 0.500        | 0.506 (0.108)    | 1.000 (0.214)    | -         |    12.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2961 | 2024-04-10 | UNiTY             | W   | 0.426      | -            | -                | -                | -         |     4.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     2987 | 2024-04-09 | 9 Pandas          | W   | 0.422      | 0.500        | 0.082 (0.017)    | -                | -         |     4.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3038 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.413      | -            | -                | -                | -         |     4.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3089 | 2024-04-05 | Nexus             | W   | 0.395      | -            | -                | -                | -         |     2.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3181 | 2024-04-03 | Rebels            | W   | 0.380      | -            | -                | -                | -         |     4.44 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3224 | 2024-04-01 | Aurora            | W   | 0.369      | 0.500        | 0.424 (0.078)    | -                | -         |    11.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3247 | 2024-03-29 | ex-Sprout         | W   | 0.349      | -            | -                | -                | -         |     0.25 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3466 | 2024-03-17 | ECLOT             | L   | 0.269      | -            | -                | -                | -         |    -2.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3472 | 2024-03-17 | UNiTY             | W   | 0.268      | -            | -                | -                | 1 (0.268) |     2.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3487 | 2024-03-16 | Sampi             | W   | 0.261      | -            | -                | -                | 1 (0.261) |     2.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3499 | 2024-03-15 | UNiTY             | L   | 0.256      | -            | -                | -                | -         |    -5.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3569 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.242      | -            | -                | -                | -         |     2.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3622 | 2024-03-11 | brazylijski luz   | L   | 0.229      | -            | -                | -                | -         |    -6.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3834 | 2024-03-03 | Gaimin Gladiators | L   | 0.175      | -            | -                | -                | -         |    -3.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4127 | 2024-02-18 | Monte             | L   | 0.082      | -            | -                | -                | -         |    -1.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4174 | 2024-02-16 | 500               | W   | 0.069      | -            | -                | -                | -         |     0.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4177 | 2024-02-16 | PERA              | W   | 0.069      | -            | -                | -                | -         |     0.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4182 | 2024-02-16 | 500               | L   | 0.068      | -            | -                | -                | -         |    -1.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,134.54)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.856 | $545.00        | $466.38         |
| 2024-06-09 |      0.828 | $10,000.00     | $8,282.64       |
| 2024-06-02 |      0.782 | $1,306.00      | $1,020.80       |
| 2024-06-02 |      0.781 | $2,000.00      | $1,562.78       |
| 2024-03-17 |      0.269 | $2,984.00      | $801.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
