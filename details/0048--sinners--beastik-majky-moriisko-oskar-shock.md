### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1042.6<br />
<br />
Final Rank Value (1042.6) = Starting Rank Value (1140.8) + Head To Head Adjustments (-98.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.478[<sup>1</sup>](#table2)
- Bounty Collected: 0.465[<sup>2</sup>](#table1)
- Opponent Network: 0.325[<sup>2</sup>](#table1)
- LAN Wins: 0.263[<sup>2</sup>](#table1)

The average of these factors is 0.383<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1140.8
- 400 + ( ( 0.383 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1140.8


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
|          110 |        5 | 2024-09-08 | Insilio           | L   | 1.000      | -            | -                | -                | -         |   -21.94 | beastik, majky, MoriiSko, oskar, SHOCK |
|          109 |       69 | 2024-09-05 | B8                | L   | 1.000      | -            | -                | -                | -         |   -13.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|          108 |       97 | 2024-09-05 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -17.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|          107 |      131 | 2024-09-04 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -18.88 | beastik, majky, MoriiSko, oskar, SHOCK |
|          106 |      163 | 2024-09-03 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |   -23.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|          105 |      186 | 2024-09-02 | Revenant          | W   | 1.000      | 0.435        | -                | 0.666 (0.289)    | 0 (0.000) |     7.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|          104 |      215 | 2024-08-31 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |   -25.12 | beastik, majky, MoriiSko, oskar, SHOCK |
|          103 |      241 | 2024-08-30 | HOTU              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.60 | beastik, majky, MoriiSko, oskar, SHOCK |
|          102 |      293 | 2024-08-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.97 | beastik, majky, MoriiSko, oskar, SHOCK |
|          101 |      321 | 2024-08-28 | B8                | L   | 1.000      | -            | -                | -                | -         |   -17.34 | beastik, majky, MoriiSko, oskar, SHOCK |
|          100 |      343 | 2024-08-28 | DMS               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.68 | beastik, majky, MoriiSko, oskar, SHOCK |
|           99 |      386 | 2024-08-27 | Zero Tenacity     | W   | 1.000      | 0.435        | 0.163 (0.071)    | 1.000 (0.435)    | 0 (0.000) |     8.80 | beastik, majky, MoriiSko, oskar, SHOCK |
|           98 |      462 | 2024-08-26 | GamerLegion       | W   | 1.000      | 0.384        | 0.162 (0.062)    | 0.601 (0.231)    | -         |    13.25 | beastik, majky, MoriiSko, oskar, SHOCK |
|           97 |      485 | 2024-08-26 | DMS               | W   | 1.000      | -            | -                | -                | -         |     5.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           96 |      504 | 2024-08-25 | Young Ninjas      | W   | 1.000      | -            | -                | -                | -         |     6.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           95 |      589 | 2024-08-22 | KOI               | W   | 1.000      | -            | -                | -                | -         |     9.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           94 |      627 | 2024-08-21 | PARIVISION        | W   | 1.000      | -            | -                | -                | -         |    16.25 | beastik, majky, MoriiSko, oskar, SHOCK |
|           93 |      660 | 2024-08-21 | B8                | W   | 1.000      | -            | -                | -                | -         |    17.34 | beastik, majky, MoriiSko, oskar, SHOCK |
|           92 |      685 | 2024-08-20 | ARCRED            | W   | 1.000      | -            | -                | -                | -         |    10.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           91 |      691 | 2024-08-20 | EYEBALLERS        | W   | 1.000      | -            | -                | -                | -         |     3.77 | beastik, majky, MoriiSko, oskar, SHOCK |
|           90 |      740 | 2024-08-18 | BetBoom           | L   | 1.000      | -            | -                | -                | -         |    -7.26 | beastik, majky, MoriiSko, oskar, SHOCK |
|           89 |      747 | 2024-08-18 | GamerLegion       | W   | 1.000      | 0.435        | 0.162 (0.070)    | 0.601 (0.261)    | -         |    17.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           88 |      761 | 2024-08-17 | GamerLegion       | L   | 1.000      | -            | -                | -                | -         |   -13.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           87 |      771 | 2024-08-17 | BLEED             | W   | 1.000      | -            | -                | -                | -         |    18.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           86 |      777 | 2024-08-17 | CYBERSHOKE        | W   | 1.000      | 0.435        | -                | 0.702 (0.305)    | -         |    13.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           85 |      795 | 2024-08-16 | 3DMAX             | W   | 1.000      | 0.435        | 0.509 (0.221)    | 0.951 (0.413)    | -         |    28.49 | beastik, majky, MoriiSko, oskar, SHOCK |
|           84 |      872 | 2024-08-13 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           83 |      880 | 2024-08-13 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | -         |     3.88 | beastik, majky, MoriiSko, oskar, SHOCK |
|           82 |      888 | 2024-08-13 | Illuminar         | W   | 1.000      | -            | -                | -                | -         |     8.61 | beastik, majky, MoriiSko, oskar, SHOCK |
|           81 |      920 | 2024-08-12 | B8                | W   | 1.000      | 0.500        | 0.176 (0.088)    | 1.000 (0.500)    | -         |    19.35 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |      931 | 2024-08-12 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -17.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |     1002 | 2024-08-09 | The Suspect       | W   | 1.000      | -            | -                | -                | -         |     8.68 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |     1065 | 2024-08-07 | Project G         | W   | 0.988      | -            | -                | -                | -         |     2.27 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |     1082 | 2024-08-07 | PARIVISION        | L   | 0.986      | -            | -                | -                | -         |   -11.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |     1119 | 2024-08-06 | Apogee            | W   | 0.981      | -            | -                | -                | -         |     6.80 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |     1140 | 2024-08-05 | Rebels            | W   | 0.974      | 0.500        | -                | 0.656 (0.319)    | -         |    13.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |     1174 | 2024-08-04 | AVEZ              | W   | 0.967      | -            | -                | -                | 1 (0.967) |     4.78 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |     1210 | 2024-08-03 | SINNERS Academy   | W   | 0.960      | -            | -                | -                | 1 (0.960) |     2.12 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |     1232 | 2024-08-02 | ECLOT             | L   | 0.955      | -            | -                | -                | -         |   -14.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |     1381 | 2024-07-30 | Sangal            | L   | 0.933      | -            | -                | -                | -         |    -4.12 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |     1415 | 2024-07-29 | Alliance          | W   | 0.926      | -            | -                | -                | -         |     8.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |     1520 | 2024-07-25 | B8                | L   | 0.902      | -            | -                | -                | -         |    -9.95 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |     1595 | 2024-07-23 | RUSH B            | L   | 0.888      | -            | -                | -                | -         |   -18.70 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1629 | 2024-07-22 | CPH Wolves        | W   | 0.880      | -            | -                | -                | -         |     7.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1712 | 2024-07-19 | DMS               | W   | 0.861      | -            | -                | -                | -         |     8.77 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1842 | 2024-07-17 | Endpoint          | W   | 0.847      | 0.435        | -                | 0.723 (0.266)    | -         |     9.89 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1911 | 2024-07-16 | BC.Game           | L   | 0.839      | -            | -                | -                | -         |   -17.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1943 | 2024-07-15 | SAW               | L   | 0.835      | -            | -                | -                | -         |    -2.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1956 | 2024-07-15 | Nexus             | L   | 0.833      | -            | -                | -                | -         |   -22.03 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     2316 | 2024-06-11 | 3DMAX             | L   | 0.608      | -            | -                | -                | -         |    -1.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     2330 | 2024-06-11 | ex-Guild Eagles   | W   | 0.606      | -            | -                | -                | -         |     3.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     2344 | 2024-06-10 | Enterprise        | L   | 0.601      | -            | -                | -                | -         |   -13.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     2352 | 2024-06-10 | Monte             | L   | 0.600      | -            | -                | -                | -         |   -11.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     2356 | 2024-06-10 | 9 Pandas          | L   | 0.600      | -            | -                | -                | -         |    -9.77 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     2363 | 2024-06-10 | PARIVISION        | W   | 0.599      | -            | -                | -                | -         |     9.88 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     2365 | 2024-06-10 | Rare Atom         | L   | 0.599      | -            | -                | -                | -         |   -15.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     2395 | 2024-06-09 | SAW               | W   | 0.594      | 0.143        | 0.330 (0.028)    | -                | -         |    16.57 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     2403 | 2024-06-09 | 3DMAX             | W   | 0.593      | 0.143        | 0.509 (0.043)    | -                | -         |    17.81 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     2409 | 2024-06-09 | RUSH B            | L   | 0.593      | -            | -                | -                | -         |   -14.01 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     2418 | 2024-06-09 | Aurora            | W   | 0.593      | -            | -                | -                | -         |    15.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     2452 | 2024-06-08 | Sangal            | L   | 0.588      | -            | -                | -                | -         |    -3.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           49 |     2531 | 2024-06-07 | RUBY              | W   | 0.579      | -            | -                | -                | -         |     5.26 | beastik, majky, MoriiSko, oskar, SHOCK |
|           48 |     2574 | 2024-06-06 | KOI               | L   | 0.574      | -            | -                | -                | -         |   -11.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|           47 |     2634 | 2024-06-05 | RUSH B            | W   | 0.568      | -            | -                | -                | -         |     4.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           46 |     2643 | 2024-06-05 | EYEBALLERS        | L   | 0.567      | -            | -                | -                | -         |   -14.19 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     2697 | 2024-06-04 | VP.Prodigy        | L   | 0.559      | -            | -                | -                | -         |   -13.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     2736 | 2024-06-02 | UNiTY             | L   | 0.547      | -            | -                | -                | -         |   -12.64 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           43 |     2753 | 2024-06-01 | GUN5              | L   | 0.542      | -            | -                | -                | -         |   -11.19 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           42 |     2773 | 2024-06-01 | Sampi             | W   | 0.540      | -            | -                | -                | 1 (0.540) |     4.07 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           41 |     2805 | 2024-05-31 | UNiTY             | L   | 0.533      | -            | -                | -                | -         |   -12.72 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           40 |     2823 | 2024-05-30 | B8                | W   | 0.527      | 0.435        | 0.176 (0.040)    | 1.000 (0.229)    | -         |     8.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           39 |     2851 | 2024-05-29 | Apogee            | W   | 0.521      | -            | -                | -                | -         |     2.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           38 |     2909 | 2024-05-26 | Sampi             | W   | 0.501      | -            | -                | -                | -         |     3.97 | beastik, majky, MoriiSko, oskar, SHOCK |
|           37 |     2943 | 2024-05-24 | GUN5              | W   | 0.488      | -            | -                | -                | -         |     5.30 | AJTT, beastik, majky, MoriiSko, oskar  |
|           36 |     2951 | 2024-05-24 | 9 Pandas          | L   | 0.486      | -            | -                | -                | -         |    -8.88 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2962 | 2024-05-23 | UNiTY             | W   | 0.481      | -            | -                | -                | -         |     3.84 | AJTT, beastik, majky, MoriiSko, oskar  |
|           34 |     2968 | 2024-05-23 | Passion UA        | L   | 0.479      | -            | -                | -                | -         |    -9.18 | AJTT, beastik, majky, MoriiSko, oskar  |
|           33 |     3086 | 2024-05-20 | VP.Prodigy        | W   | 0.460      | -            | -                | -                | -         |     2.69 | AJTT, beastik, majky, MoriiSko, oskar  |
|           32 |     3134 | 2024-05-18 | 1WIN              | L   | 0.447      | -            | -                | -                | -         |   -10.34 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           31 |     3220 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.432      | -            | -                | -                | -         |     5.22 | AJTT, beastik, majky, oskar, SHOCK     |
|           30 |     3312 | 2024-05-14 | Passion UA        | W   | 0.421      | 0.435        | 0.164 (0.030)    | -                | -         |     5.13 | AJTT, beastik, majky, oskar, SHOCK     |
|           29 |     3482 | 2024-05-07 | Nemiga            | L   | 0.373      | -            | -                | -                | -         |    -4.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     3517 | 2024-05-05 | Endpoint          | W   | 0.360      | -            | -                | -                | -         |     4.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     3580 | 2024-05-02 | Gaimin Gladiators | L   | 0.339      | -            | -                | -                | -         |    -8.11 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     3607 | 2024-05-01 | B8                | L   | 0.332      | -            | -                | -                | -         |    -6.36 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     3639 | 2024-04-29 | 1WIN              | W   | 0.320      | -            | -                | -                | -         |     2.28 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     3648 | 2024-04-29 | Sangal            | L   | 0.319      | -            | -                | -                | -         |    -2.71 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     3660 | 2024-04-28 | Zero Tenacity     | L   | 0.313      | -            | -                | -                | -         |    -5.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     3693 | 2024-04-27 | Zero Tenacity     | L   | 0.306      | -            | -                | -                | -         |    -5.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     3709 | 2024-04-26 | PARIVISION        | L   | 0.300      | -            | -                | -                | -         |    -5.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     3759 | 2024-04-24 | Endpoint          | L   | 0.287      | -            | -                | -                | -         |    -6.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     3795 | 2024-04-22 | HAVU              | W   | 0.273      | -            | -                | -                | -         |     0.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3844 | 2024-04-20 | ENCE Academy      | L   | 0.260      | -            | -                | -                | -         |    -7.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3899 | 2024-04-19 | ECLOT             | L   | 0.252      | -            | -                | -                | -         |    -4.80 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3989 | 2024-04-17 | Gaimin Gladiators | L   | 0.239      | -            | -                | -                | -         |    -6.04 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     4014 | 2024-04-16 | BLEED             | L   | 0.232      | -            | -                | -                | -         |    -6.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     4044 | 2024-04-14 | Passion UA        | W   | 0.220      | -            | -                | -                | -         |     2.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     4133 | 2024-04-10 | 3DMAX             | W   | 0.195      | 0.500        | 0.509 (0.050)    | -                | -         |     5.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     4160 | 2024-04-10 | UNiTY             | W   | 0.192      | -            | -                | -                | -         |     1.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     4186 | 2024-04-09 | 9 Pandas          | W   | 0.188      | -            | -                | -                | -         |     1.98 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     4237 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.179      | -            | -                | -                | -         |     2.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     4288 | 2024-04-05 | Nexus             | W   | 0.161      | -            | -                | -                | -         |     0.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     4380 | 2024-04-03 | Rebels            | W   | 0.146      | -            | -                | -                | -         |     1.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     4423 | 2024-04-01 | Aurora            | W   | 0.135      | -            | -                | -                | -         |     3.49 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     4446 | 2024-03-29 | ex-Sprout         | W   | 0.114      | -            | -                | -                | -         |     0.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     4665 | 2024-03-17 | ECLOT             | L   | 0.035      | -            | -                | -                | -         |    -0.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4671 | 2024-03-17 | UNiTY             | W   | 0.034      | -            | -                | -                | 1 (0.034) |     0.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4686 | 2024-03-16 | Sampi             | W   | 0.027      | -            | -                | -                | 1 (0.027) |     0.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4698 | 2024-03-15 | UNiTY             | L   | 0.021      | -            | -                | -                | -         |    -0.54 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4768 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.008      | -            | -                | -                | -         |     0.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,692.35)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-06 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-08-28 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-08-18 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-13 |      0.622 | $545.00        | $338.76         |
| 2024-06-09 |      0.594 | $10,000.00     | $5,940.97       |
| 2024-06-02 |      0.547 | $1,306.00      | $714.97         |
| 2024-06-02 |      0.547 | $2,000.00      | $1,094.44       |
| 2024-03-17 |      0.035 | $2,984.00      | $103.20         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
