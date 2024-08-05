### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  973.6<br />
<br />
Final Rank Value (973.6) = Starting Rank Value (1144.7) + Head To Head Adjustments (-171.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.364<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1144.7
- 400 + ( ( 0.364 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1144.7


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
|           80 |       27 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.96 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       63 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       85 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      233 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.28 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      269 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      373 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      448 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.98 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      482 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      565 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.444 (0.193)    | 0 (0.000) |    12.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      695 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.520 (0.226)    | 0 (0.000) |    10.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      764 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      793 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.41 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      806 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.60 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1166 | 2024-06-11 | 3DMAX             | L   | 0.835      | -            | -                | -                | -         |    -2.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1180 | 2024-06-11 | ex-Guild Eagles   | W   | 0.833      | -            | -                | -                | 0 (0.000) |     7.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1194 | 2024-06-10 | Enterprise        | L   | 0.827      | -            | -                | -                | -         |   -16.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1202 | 2024-06-10 | Monte             | L   | 0.827      | -            | -                | -                | -         |   -13.73 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1206 | 2024-06-10 | 9 Pandas          | L   | 0.826      | -            | -                | -                | -         |   -12.87 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1213 | 2024-06-10 | PARIVISION        | W   | 0.826      | -            | -                | -                | -         |    14.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1215 | 2024-06-10 | Rare Atom         | L   | 0.825      | -            | -                | -                | -         |   -20.01 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1245 | 2024-06-09 | SAW               | W   | 0.820      | -            | -                | -                | -         |    16.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1253 | 2024-06-09 | 3DMAX             | W   | 0.820      | 0.143        | 0.508 (0.059)    | -                | -         |    23.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1259 | 2024-06-09 | RUSH B            | L   | 0.820      | -            | -                | -                | -         |   -18.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1268 | 2024-06-09 | Aurora            | W   | 0.819      | 0.143        | 0.422 (0.049)    | -                | -         |    24.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1302 | 2024-06-08 | Sangal            | L   | 0.814      | -            | -                | -                | -         |    -7.09 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1381 | 2024-06-07 | RUBY              | W   | 0.806      | 0.435        | 0.095 (0.033)    | 0.499 (0.175)    | -         |     9.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1424 | 2024-06-06 | KOI               | L   | 0.801      | -            | -                | -                | -         |   -10.96 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1484 | 2024-06-05 | RUSH B            | W   | 0.794      | -            | -                | -                | -         |     7.75 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1493 | 2024-06-05 | EYEBALLERS        | L   | 0.794      | -            | -                | -                | -         |   -17.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1547 | 2024-06-04 | VP.Prodigy        | L   | 0.786      | -            | -                | -                | -         |   -16.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1586 | 2024-06-02 | UNiTY             | L   | 0.773      | -            | -                | -                | -         |   -15.38 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1603 | 2024-06-01 | GUN5              | L   | 0.768      | -            | -                | -                | -         |   -16.24 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1623 | 2024-06-01 | Sampi             | W   | 0.766      | 0.346        | -                | 1.000 (0.265)    | 1 (0.766) |     6.41 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1655 | 2024-05-31 | UNiTY             | L   | 0.760      | -            | -                | -                | -         |   -15.91 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1673 | 2024-05-30 | B8                | W   | 0.754      | 0.435        | 0.165 (0.054)    | 0.947 (0.310)    | -         |    14.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1701 | 2024-05-29 | brazylijski luz   | W   | 0.748      | -            | -                | -                | -         |     4.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1759 | 2024-05-26 | Sampi             | W   | 0.727      | 0.435        | -                | 1.000 (0.316)    | -         |     6.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1793 | 2024-05-24 | GUN5              | W   | 0.715      | 0.435        | 0.073 (0.023)    | 0.569 (0.177)    | -         |     7.29 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1801 | 2024-05-24 | 9 Pandas          | L   | 0.713      | -            | -                | -                | -         |   -12.40 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1812 | 2024-05-23 | UNiTY             | W   | 0.707      | -            | -                | -                | -         |     8.00 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1818 | 2024-05-23 | Passion UA        | L   | 0.706      | -            | -                | -                | -         |   -12.27 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1936 | 2024-05-20 | VP.Prodigy        | W   | 0.686      | -            | -                | -                | -         |     5.55 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1984 | 2024-05-18 | 1WIN              | L   | 0.674      | -            | -                | -                | -         |   -12.92 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2070 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.659      | -            | -                | -                | -         |     7.17 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2162 | 2024-05-14 | Passion UA        | W   | 0.648      | 0.435        | 0.173 (0.049)    | 1.000 (0.282)    | -         |     9.09 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2332 | 2024-05-07 | Nemiga            | L   | 0.599      | -            | -                | -                | -         |    -6.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2367 | 2024-05-05 | Endpoint          | W   | 0.587      | -            | -                | -                | -         |     6.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2430 | 2024-05-02 | Gaimin Gladiators | L   | 0.566      | -            | -                | -                | -         |   -11.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2457 | 2024-05-01 | B8                | L   | 0.559      | -            | -                | -                | -         |   -10.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2489 | 2024-04-29 | 1WIN              | W   | 0.547      | 0.435        | -                | 0.705 (0.167)    | -         |     5.46 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2498 | 2024-04-29 | Sangal            | L   | 0.546      | -            | -                | -                | -         |    -7.68 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2510 | 2024-04-28 | Zero Tenacity     | L   | 0.540      | -            | -                | -                | -         |    -9.37 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2543 | 2024-04-27 | Zero Tenacity     | L   | 0.532      | -            | -                | -                | -         |    -9.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2559 | 2024-04-26 | PARIVISION        | L   | 0.527      | -            | -                | -                | -         |    -9.45 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2609 | 2024-04-24 | Endpoint          | L   | 0.513      | -            | -                | -                | -         |   -12.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2645 | 2024-04-22 | HAVU              | W   | 0.499      | -            | -                | -                | -         |     1.28 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2694 | 2024-04-20 | ENCE Academy      | L   | 0.486      | -            | -                | -                | -         |   -13.99 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2749 | 2024-04-19 | ECLOT             | L   | 0.479      | -            | -                | -                | -         |    -6.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2839 | 2024-04-17 | Gaimin Gladiators | L   | 0.466      | -            | -                | -                | -         |   -10.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2864 | 2024-04-16 | BLEED             | L   | 0.459      | -            | -                | -                | -         |   -10.63 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2894 | 2024-04-14 | Passion UA        | W   | 0.446      | 0.371        | 0.173 (0.029)    | -                | -         |     4.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2983 | 2024-04-10 | 3DMAX             | W   | 0.421      | 0.500        | 0.508 (0.107)    | 1.000 (0.211)    | -         |    12.50 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3010 | 2024-04-10 | UNiTY             | W   | 0.419      | -            | -                | -                | -         |     3.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3036 | 2024-04-09 | 9 Pandas          | W   | 0.415      | 0.500        | 0.081 (0.017)    | -                | -         |     3.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3087 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.406      | -            | -                | -                | -         |     3.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3138 | 2024-04-05 | Nexus             | W   | 0.387      | -            | -                | -                | -         |     2.00 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3230 | 2024-04-03 | Rebels            | W   | 0.372      | -            | -                | -                | -         |     3.55 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3273 | 2024-04-01 | Aurora            | W   | 0.361      | 0.500        | 0.422 (0.076)    | -                | -         |    10.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3296 | 2024-03-29 | ex-Sprout         | W   | 0.341      | -            | -                | -                | -         |     0.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3515 | 2024-03-17 | ECLOT             | L   | 0.261      | -            | -                | -                | -         |    -3.40 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3521 | 2024-03-17 | UNiTY             | W   | 0.260      | -            | -                | -                | 1 (0.260) |     2.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3536 | 2024-03-16 | Sampi             | W   | 0.254      | -            | -                | -                | 1 (0.254) |     1.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3548 | 2024-03-15 | UNiTY             | L   | 0.248      | -            | -                | -                | -         |    -5.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3618 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.235      | -            | -                | -                | -         |     2.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3671 | 2024-03-11 | brazylijski luz   | L   | 0.221      | -            | -                | -                | -         |    -6.09 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3883 | 2024-03-03 | Gaimin Gladiators | L   | 0.168      | -            | -                | -                | -         |    -3.83 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4176 | 2024-02-18 | Monte             | L   | 0.074      | -            | -                | -                | -         |    -1.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4223 | 2024-02-16 | 500               | W   | 0.061      | -            | -                | -                | -         |     0.15 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4226 | 2024-02-16 | PERA              | W   | 0.061      | -            | -                | -                | -         |     0.45 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4231 | 2024-02-16 | 500               | L   | 0.060      | -            | -                | -                | -         |    -1.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,008.28)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.848 | $545.00        | $462.29         |
| 2024-06-09 |      0.821 | $10,000.00     | $8,207.64       |
| 2024-06-02 |      0.774 | $1,306.00      | $1,011.00       |
| 2024-06-02 |      0.774 | $2,000.00      | $1,547.78       |
| 2024-03-17 |      0.261 | $2,984.00      | $779.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
