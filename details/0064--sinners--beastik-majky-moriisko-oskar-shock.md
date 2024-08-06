### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  992.5<br />
<br />
Final Rank Value (992.5) = Starting Rank Value (1150.8) + Head To Head Adjustments (-158.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.433[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1150.8
- 400 + ( ( 0.366 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1150.8


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
|           81 |        8 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.295)    | 0 (0.000) |    16.68 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       42 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.93 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       78 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      100 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.16 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      248 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      284 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.36 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      388 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      463 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      497 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      580 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.437 (0.190)    | 0 (0.000) |    12.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      710 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.513 (0.223)    | 0 (0.000) |    10.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      779 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.96 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      808 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.56 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      821 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1181 | 2024-06-11 | 3DMAX             | L   | 0.829      | -            | -                | -                | -         |    -2.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1195 | 2024-06-11 | ex-Guild Eagles   | W   | 0.827      | -            | -                | -                | -         |     7.49 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1209 | 2024-06-10 | Enterprise        | L   | 0.821      | -            | -                | -                | -         |   -16.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1217 | 2024-06-10 | Monte             | L   | 0.821      | -            | -                | -                | -         |   -13.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1221 | 2024-06-10 | 9 Pandas          | L   | 0.820      | -            | -                | -                | -         |   -12.89 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1228 | 2024-06-10 | PARIVISION        | W   | 0.820      | -            | -                | -                | -         |    14.35 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1230 | 2024-06-10 | Rare Atom         | L   | 0.820      | -            | -                | -                | -         |   -19.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1260 | 2024-06-09 | SAW               | W   | 0.815      | -            | -                | -                | -         |    16.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1268 | 2024-06-09 | 3DMAX             | W   | 0.814      | 0.143        | 0.509 (0.059)    | -                | -         |    23.69 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1274 | 2024-06-09 | RUSH B            | L   | 0.814      | -            | -                | -                | -         |   -18.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1283 | 2024-06-09 | Aurora            | W   | 0.813      | 0.143        | 0.421 (0.049)    | -                | -         |    23.85 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1317 | 2024-06-08 | Sangal            | L   | 0.809      | -            | -                | -                | -         |    -7.10 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1396 | 2024-06-07 | RUBY              | W   | 0.800      | 0.435        | 0.095 (0.033)    | 0.491 (0.171)    | -         |     9.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1439 | 2024-06-06 | KOI               | L   | 0.795      | -            | -                | -                | -         |   -11.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1499 | 2024-06-05 | RUSH B            | W   | 0.789      | -            | -                | -                | -         |     7.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1508 | 2024-06-05 | EYEBALLERS        | L   | 0.788      | -            | -                | -                | -         |   -17.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1562 | 2024-06-04 | VP.Prodigy        | L   | 0.780      | -            | -                | -                | -         |   -16.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1601 | 2024-06-02 | UNiTY             | L   | 0.767      | -            | -                | -                | -         |   -15.36 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1618 | 2024-06-01 | GUN5              | L   | 0.762      | -            | -                | -                | -         |   -16.22 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1638 | 2024-06-01 | Sampi             | W   | 0.761      | 0.346        | -                | 1.000 (0.263)    | 1 (0.761) |     6.29 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1670 | 2024-05-31 | UNiTY             | L   | 0.754      | -            | -                | -                | -         |   -15.88 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1688 | 2024-05-30 | B8                | W   | 0.748      | 0.435        | 0.164 (0.053)    | 0.933 (0.303)    | -         |    14.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1716 | 2024-05-29 | brazylijski luz   | W   | 0.742      | -            | -                | -                | -         |     4.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1774 | 2024-05-26 | Sampi             | W   | 0.721      | 0.435        | -                | 1.000 (0.314)    | -         |     6.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1808 | 2024-05-24 | GUN5              | W   | 0.709      | 0.435        | 0.072 (0.022)    | 0.562 (0.173)    | -         |     7.11 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1816 | 2024-05-24 | 9 Pandas          | L   | 0.707      | -            | -                | -                | -         |   -12.46 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1827 | 2024-05-23 | UNiTY             | W   | 0.701      | -            | -                | -                | -         |     7.82 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1833 | 2024-05-23 | Passion UA        | L   | 0.700      | -            | -                | -                | -         |   -12.19 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1951 | 2024-05-20 | VP.Prodigy        | W   | 0.681      | -            | -                | -                | -         |     5.41 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1999 | 2024-05-18 | 1WIN              | L   | 0.668      | -            | -                | -                | -         |   -12.90 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2085 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.653      | -            | -                | -                | -         |     7.01 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2177 | 2024-05-14 | Passion UA        | W   | 0.642      | 0.435        | 0.173 (0.048)    | 1.000 (0.279)    | -         |     8.99 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2347 | 2024-05-07 | Nemiga            | L   | 0.594      | -            | -                | -                | -         |    -6.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2382 | 2024-05-05 | Endpoint          | W   | 0.581      | -            | -                | -                | -         |     5.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2445 | 2024-05-02 | Gaimin Gladiators | L   | 0.560      | -            | -                | -                | -         |   -11.15 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2472 | 2024-05-01 | B8                | L   | 0.553      | -            | -                | -                | -         |   -10.12 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2504 | 2024-04-29 | 1WIN              | W   | 0.541      | -            | -                | -                | -         |     5.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2513 | 2024-04-29 | Sangal            | L   | 0.540      | -            | -                | -                | -         |    -7.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2525 | 2024-04-28 | Zero Tenacity     | L   | 0.534      | -            | -                | -                | -         |    -9.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2558 | 2024-04-27 | Zero Tenacity     | L   | 0.526      | -            | -                | -                | -         |    -9.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2574 | 2024-04-26 | PARIVISION        | L   | 0.521      | -            | -                | -                | -         |    -9.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2624 | 2024-04-24 | Endpoint          | L   | 0.507      | -            | -                | -                | -         |   -12.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2660 | 2024-04-22 | HAVU              | W   | 0.494      | -            | -                | -                | -         |     1.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2709 | 2024-04-20 | ENCE Academy      | L   | 0.481      | -            | -                | -                | -         |   -13.86 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2764 | 2024-04-19 | ECLOT             | L   | 0.473      | -            | -                | -                | -         |    -6.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2854 | 2024-04-17 | Gaimin Gladiators | L   | 0.460      | -            | -                | -                | -         |   -10.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2879 | 2024-04-16 | BLEED             | L   | 0.453      | -            | -                | -                | -         |   -10.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2909 | 2024-04-14 | Passion UA        | W   | 0.440      | 0.371        | 0.173 (0.028)    | -                | -         |     4.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2998 | 2024-04-10 | 3DMAX             | W   | 0.416      | 0.500        | 0.509 (0.106)    | 1.000 (0.208)    | -         |    12.32 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3025 | 2024-04-10 | UNiTY             | W   | 0.413      | -            | -                | -                | -         |     3.26 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3051 | 2024-04-09 | 9 Pandas          | W   | 0.409      | -            | -                | -                | -         |     3.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3102 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.400      | -            | -                | -                | -         |     3.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3153 | 2024-04-05 | Nexus             | W   | 0.382      | -            | -                | -                | -         |     1.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3245 | 2024-04-03 | Rebels            | W   | 0.367      | -            | -                | -                | -         |     3.42 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3288 | 2024-04-01 | Aurora            | W   | 0.356      | 0.500        | 0.421 (0.075)    | -                | -         |    10.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3311 | 2024-03-29 | ex-Sprout         | W   | 0.335      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3530 | 2024-03-17 | ECLOT             | L   | 0.255      | -            | -                | -                | -         |    -3.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3536 | 2024-03-17 | UNiTY             | W   | 0.254      | -            | -                | -                | 1 (0.254) |     2.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3551 | 2024-03-16 | Sampi             | W   | 0.248      | -            | -                | -                | 1 (0.248) |     1.68 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3563 | 2024-03-15 | UNiTY             | L   | 0.242      | -            | -                | -                | -         |    -5.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3633 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.229      | -            | -                | -                | -         |     2.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3686 | 2024-03-11 | brazylijski luz   | L   | 0.215      | -            | -                | -                | -         |    -5.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3898 | 2024-03-03 | Gaimin Gladiators | L   | 0.162      | -            | -                | -                | -         |    -3.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4191 | 2024-02-18 | Monte             | L   | 0.068      | -            | -                | -                | -         |    -1.53 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4238 | 2024-02-16 | 500               | W   | 0.056      | -            | -                | -                | -         |     0.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4241 | 2024-02-16 | PERA              | W   | 0.055      | -            | -                | -                | -         |     0.40 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4246 | 2024-02-16 | 500               | L   | 0.054      | -            | -                | -                | -         |    -1.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,910.07)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.842 | $545.00        | $459.11         |
| 2024-06-09 |      0.815 | $10,000.00     | $8,149.31       |
| 2024-06-02 |      0.768 | $1,306.00      | $1,003.38       |
| 2024-06-02 |      0.768 | $2,000.00      | $1,536.11       |
| 2024-03-17 |      0.255 | $2,984.00      | $762.16         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
