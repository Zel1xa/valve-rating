### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  949.1<br />
<br />
Final Rank Value (949.1) = Starting Rank Value (1087.4) + Head To Head Adjustments (-138.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.435[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.264[<sup>2</sup>](#table1)

The average of these factors is 0.336<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1087.4
- 400 + ( ( 0.336 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1087.4


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
|           79 |       13 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       35 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -10.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      182 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.91 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      215 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.28 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      321 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      395 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      430 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      513 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    13.35 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      643 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    11.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      713 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -25.77 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      739 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -7.81 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      754 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.09 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1113 | 2024-06-11 | 3DMAX             | L   | 0.845      | -            | -                | -                | -         |    -2.35 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1127 | 2024-06-11 | ex-Guild Eagles   | W   | 0.843      | -            | -                | -                | 0 (0.000) |     8.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1141 | 2024-06-10 | Enterprise        | L   | 0.838      | -            | -                | -                | -         |   -16.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1149 | 2024-06-10 | Monte             | L   | 0.837      | -            | -                | -                | -         |   -13.19 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1153 | 2024-06-10 | 9 Pandas          | L   | 0.837      | -            | -                | -                | -         |   -12.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1160 | 2024-06-10 | PARIVISION        | W   | 0.836      | -            | -                | -                | 0 (0.000) |    15.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1162 | 2024-06-10 | Rare Atom         | L   | 0.836      | -            | -                | -                | -         |   -22.57 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1192 | 2024-06-09 | SAW               | W   | 0.831      | -            | -                | -                | -         |    17.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1200 | 2024-06-09 | 3DMAX             | W   | 0.831      | 0.143        | 0.505 (0.060)    | -                | -         |    24.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1206 | 2024-06-09 | RUSH B            | L   | 0.830      | -            | -                | -                | -         |   -18.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1215 | 2024-06-09 | Aurora            | W   | 0.830      | 0.143        | 0.424 (0.050)    | -                | -         |    24.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1249 | 2024-06-08 | Sangal            | L   | 0.825      | -            | -                | -                | -         |    -6.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1328 | 2024-06-07 | RUBY              | W   | 0.817      | 0.435        | 0.095 (0.034)    | 0.502 (0.178)    | -         |    10.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1371 | 2024-06-06 | KOI               | L   | 0.812      | -            | -                | -                | -         |   -10.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1431 | 2024-06-05 | RUSH B            | W   | 0.805      | -            | -                | -                | -         |     8.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1440 | 2024-06-05 | EYEBALLERS        | L   | 0.804      | -            | -                | -                | -         |   -16.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1494 | 2024-06-04 | VP.Prodigy        | L   | 0.797      | -            | -                | -                | -         |   -15.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1533 | 2024-06-02 | UNiTY             | L   | 0.784      | -            | -                | -                | -         |   -14.85 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1550 | 2024-06-01 | GUN5              | L   | 0.779      | -            | -                | -                | -         |   -15.63 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1570 | 2024-06-01 | Sampi             | W   | 0.777      | 0.346        | -                | 1.000 (0.269)    | 1 (0.777) |     7.23 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1602 | 2024-05-31 | UNiTY             | L   | 0.771      | -            | -                | -                | -         |   -15.34 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1620 | 2024-05-30 | B8                | W   | 0.764      | 0.435        | 0.165 (0.055)    | 0.913 (0.303)    | -         |    15.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1648 | 2024-05-29 | brazylijski luz   | W   | 0.758      | -            | -                | -                | -         |     5.68 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1706 | 2024-05-26 | Sampi             | W   | 0.738      | 0.435        | -                | 1.000 (0.321)    | -         |     7.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1740 | 2024-05-24 | GUN5              | W   | 0.725      | 0.435        | 0.073 (0.023)    | 0.569 (0.179)    | -         |     8.33 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1748 | 2024-05-24 | 9 Pandas          | L   | 0.723      | -            | -                | -                | -         |   -11.35 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1759 | 2024-05-23 | UNiTY             | W   | 0.718      | -            | -                | -                | -         |     9.06 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1765 | 2024-05-23 | Passion UA        | L   | 0.716      | -            | -                | -                | -         |   -11.67 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1883 | 2024-05-20 | VP.Prodigy        | W   | 0.697      | -            | -                | -                | -         |     6.51 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1931 | 2024-05-18 | 1WIN              | L   | 0.684      | -            | -                | -                | -         |   -12.82 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2017 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.669      | -            | -                | -                | -         |     8.28 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2109 | 2024-05-14 | Passion UA        | W   | 0.658      | 0.435        | 0.172 (0.049)    | 1.000 (0.286)    | -         |    10.00 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2279 | 2024-05-07 | Nemiga            | L   | 0.610      | -            | -                | -                | -         |    -6.05 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2314 | 2024-05-05 | Endpoint          | W   | 0.597      | -            | -                | -                | -         |     7.07 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2377 | 2024-05-02 | Gaimin Gladiators | L   | 0.577      | -            | -                | -                | -         |   -10.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2404 | 2024-05-01 | B8                | L   | 0.569      | -            | -                | -                | -         |    -9.27 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2436 | 2024-04-29 | 1WIN              | W   | 0.557      | -            | -                | -                | -         |     5.79 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2445 | 2024-04-29 | Sangal            | L   | 0.556      | -            | -                | -                | -         |    -6.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2457 | 2024-04-28 | Zero Tenacity     | L   | 0.551      | -            | -                | -                | -         |    -8.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2490 | 2024-04-27 | Zero Tenacity     | L   | 0.543      | -            | -                | -                | -         |    -8.97 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2505 | 2024-04-26 | PARIVISION        | L   | 0.538      | -            | -                | -                | -         |    -8.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2555 | 2024-04-24 | Endpoint          | L   | 0.524      | -            | -                | -                | -         |   -12.28 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2591 | 2024-04-22 | HAVU              | W   | 0.510      | -            | -                | -                | -         |     1.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2640 | 2024-04-20 | ENCE Academy      | L   | 0.497      | -            | -                | -                | -         |   -13.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2695 | 2024-04-19 | ECLOT             | L   | 0.489      | -            | -                | -                | -         |    -6.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2785 | 2024-04-17 | Gaimin Gladiators | L   | 0.476      | -            | -                | -                | -         |    -9.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2810 | 2024-04-16 | BLEED             | L   | 0.469      | -            | -                | -                | -         |   -10.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2840 | 2024-04-14 | Passion UA        | W   | 0.457      | 0.371        | 0.172 (0.029)    | 1.000 (0.169)    | -         |     5.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2929 | 2024-04-10 | 3DMAX             | W   | 0.432      | 0.500        | 0.505 (0.109)    | 1.000 (0.216)    | -         |    12.98 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2956 | 2024-04-10 | UNiTY             | W   | 0.429      | -            | -                | -                | -         |     4.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     2982 | 2024-04-09 | 9 Pandas          | W   | 0.425      | 0.500        | 0.082 (0.017)    | -                | -         |     4.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3033 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.416      | -            | -                | -                | -         |     4.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3084 | 2024-04-05 | Nexus             | W   | 0.398      | -            | -                | -                | -         |     2.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3176 | 2024-04-03 | Rebels            | W   | 0.383      | -            | -                | -                | -         |     4.47 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3219 | 2024-04-01 | Aurora            | W   | 0.372      | 0.500        | 0.424 (0.079)    | -                | -         |    11.29 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3242 | 2024-03-29 | ex-Sprout         | W   | 0.352      | -            | -                | -                | -         |     0.25 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3461 | 2024-03-17 | ECLOT             | L   | 0.272      | -            | -                | -                | -         |    -2.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3467 | 2024-03-17 | UNiTY             | W   | 0.271      | -            | -                | -                | 1 (0.271) |     2.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3482 | 2024-03-16 | Sampi             | W   | 0.264      | -            | -                | -                | 1 (0.264) |     2.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3494 | 2024-03-15 | UNiTY             | L   | 0.259      | -            | -                | -                | -         |    -5.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3563 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.245      | -            | -                | -                | -         |     2.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3616 | 2024-03-11 | brazylijski luz   | L   | 0.232      | -            | -                | -                | -         |    -6.09 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3828 | 2024-03-03 | Gaimin Gladiators | L   | 0.178      | -            | -                | -                | -         |    -3.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4121 | 2024-02-18 | Monte             | L   | 0.085      | -            | -                | -                | -         |    -1.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4167 | 2024-02-16 | 500               | W   | 0.072      | -            | -                | -                | -         |     0.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4170 | 2024-02-16 | PERA              | W   | 0.072      | -            | -                | -                | -         |     0.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4175 | 2024-02-16 | 500               | L   | 0.071      | -            | -                | -                | -         |    -2.00 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,185.98)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.859 | $545.00        | $468.04         |
| 2024-06-09 |      0.831 | $10,000.00     | $8,313.19       |
| 2024-06-02 |      0.785 | $1,306.00      | $1,024.79       |
| 2024-06-02 |      0.784 | $2,000.00      | $1,568.89       |
| 2024-03-17 |      0.272 | $2,984.00      | $811.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
