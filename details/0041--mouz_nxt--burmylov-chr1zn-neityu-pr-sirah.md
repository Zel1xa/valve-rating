### Roster Details<br />
Team Name: MOUZ NXT<br />
Roster: Burmylov, Chr1zN, Neityu, PR, sirah<br />
Global Rank: [41](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1119.9<br />
<br />
Final Rank Value (1119.9) = Starting Rank Value (1063.9) + Head To Head Adjustments (56.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.540[<sup>1</sup>](#table2)
- Bounty Collected: 0.465[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.323<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1063.9
- 400 + ( ( 0.323 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1063.9


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
|           97 |      123 | 2024-07-29 | CYBERSHOKE        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           96 |      126 | 2024-07-29 | Monte Gen         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           95 |      182 | 2024-07-27 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           94 |      257 | 2024-07-25 | Aurora Young Blud | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           93 |      379 | 2024-07-21 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.18 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           92 |      420 | 2024-07-20 | BLEED             | W   | 1.000      | 0.500        | 0.128 (0.064)    | 0.513 (0.257)    | 0 (0.000) |    24.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           91 |      435 | 2024-07-19 | Rhyno             | W   | 1.000      | 0.500        | 0.072 (0.036)    | 0.403 (0.202)    | 0 (0.000) |    12.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           90 |      492 | 2024-07-18 | Ninjas in Pyjamas | L   | 1.000      | -            | -                | -                | -         |    -2.68 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           89 |      635 | 2024-07-16 | Rhyno             | W   | 1.000      | 0.500        | 0.072 (0.036)    | -                | 0 (0.000) |    12.48 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           88 |     1011 | 2024-06-13 | B8                | L   | 0.871      | -            | -                | -                | -         |   -12.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           87 |     1074 | 2024-06-10 | Endpoint          | L   | 0.852      | -            | -                | -                | -         |   -20.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           86 |     1110 | 2024-06-09 | GhoulsW           | W   | 0.846      | -            | -                | -                | 0 (0.000) |     1.09 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           85 |     1129 | 2024-06-09 | BLEED             | L   | 0.845      | -            | -                | -                | -         |    -4.88 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           84 |     1188 | 2024-06-08 | Sampi             | W   | 0.839      | 0.435        | -                | 1.000 (0.365)    | 0 (0.000) |     6.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           83 |     1201 | 2024-06-08 | ECLOT             | L   | 0.839      | -            | -                | -                | -         |   -14.17 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           82 |     1235 | 2024-06-07 | GamerLegion       | L   | 0.834      | -            | -                | -                | -         |   -10.92 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           81 |     1302 | 2024-06-06 | Rhyno             | W   | 0.827      | -            | -                | -                | 0 (0.000) |     8.64 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           80 |     1332 | 2024-06-06 | Entropiq          | W   | 0.825      | -            | -                | -                | 0 (0.000) |     0.46 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           79 |     1370 | 2024-06-05 | Passion UA        | W   | 0.820      | 0.435        | 0.173 (0.061)    | 1.000 (0.356)    | -         |    10.80 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           78 |     1432 | 2024-06-04 | NAVI Junior       | W   | 0.812      | -            | -                | -                | -         |     1.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           77 |     1439 | 2024-06-04 | Aurora Young Blud | W   | 0.811      | -            | -                | -                | -         |     4.76 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           76 |     1478 | 2024-06-02 | FURIA             | L   | 0.799      | -            | -                | -                | -         |    -1.43 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           75 |     1512 | 2024-06-01 | AMKAL             | W   | 0.792      | 0.435        | 0.132 (0.045)    | -                | -         |    15.94 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           74 |     1571 | 2024-05-30 | Sangal            | W   | 0.778      | 0.435        | 0.221 (0.075)    | 0.823 (0.278)    | -         |    13.58 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           73 |     1612 | 2024-05-28 | RUBY              | W   | 0.766      | -            | -                | -                | -         |     8.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           72 |     1640 | 2024-05-27 | Nexus             | W   | 0.758      | -            | -                | -                | -         |     4.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           71 |     1649 | 2024-05-26 | 9 Pandas          | L   | 0.753      | -            | -                | -                | -         |   -11.82 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           70 |     1657 | 2024-05-26 | B8                | W   | 0.751      | 0.435        | 0.168 (0.055)    | 0.878 (0.287)    | -         |    15.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           69 |     1682 | 2024-05-25 | 3DMAX             | W   | 0.744      | 0.435        | 0.505 (0.163)    | 1.000 (0.323)    | -         |    22.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           68 |     1695 | 2024-05-24 | Illuminar         | W   | 0.738      | -            | -                | -                | -         |     7.39 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           67 |     1708 | 2024-05-23 | Rare Atom         | W   | 0.732      | -            | -                | -                | -         |     2.50 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           66 |     1758 | 2024-05-22 | Rhyno             | L   | 0.725      | -            | -                | -                | -         |   -12.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           65 |     1805 | 2024-05-21 | DMS               | L   | 0.719      | -            | -                | -                | -         |   -15.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           64 |     1884 | 2024-05-19 | BLEED             | L   | 0.704      | -            | -                | -                | -         |    -2.97 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           63 |     1909 | 2024-05-18 | B8                | W   | 0.699      | 0.435        | 0.168 (0.051)    | 0.878 (0.266)    | -         |    13.60 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           62 |     1951 | 2024-05-17 | DMS               | W   | 0.691      | -            | -                | -                | -         |     7.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           61 |     1976 | 2024-05-16 | Sampi             | W   | 0.686      | 0.435        | -                | 1.000 (0.298)    | -         |     7.47 | Chr1zN, Neityu, PR, sirah, TOBIZ       |
|           60 |     2043 | 2024-05-15 | BLEED             | L   | 0.678      | -            | -                | -                | -         |    -2.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           59 |     2099 | 2024-05-14 | B8                | L   | 0.671      | -            | -                | -                | -         |    -8.73 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           58 |     2125 | 2024-05-13 | Space             | W   | 0.664      | -            | -                | -                | -         |     5.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           57 |     2147 | 2024-05-12 | B8                | L   | 0.658      | -            | -                | -                | -         |    -9.44 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           56 |     2161 | 2024-05-11 | Endpoint          | W   | 0.654      | -            | -                | -                | -         |     8.27 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           55 |     2187 | 2024-05-10 | Aurora            | W   | 0.647      | 0.435        | 0.431 (0.121)    | 0.798 (0.224)    | -         |    19.61 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           54 |     2259 | 2024-05-07 | RUSH B            | W   | 0.626      | -            | -                | -                | -         |     5.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           53 |     2302 | 2024-05-05 | GL Academy        | W   | 0.611      | -            | -                | -                | -         |     3.98 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           52 |     2304 | 2024-05-04 | Enterprise        | L   | 0.607      | -            | -                | -                | -         |   -13.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           51 |     2323 | 2024-05-03 | Nemiga            | L   | 0.599      | -            | -                | -                | -         |    -5.83 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           50 |     2343 | 2024-05-02 | Endpoint          | L   | 0.594      | -            | -                | -                | -         |   -11.54 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           49 |     2345 | 2024-05-02 | 500               | L   | 0.593      | -            | -                | -                | -         |   -15.65 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           48 |     2357 | 2024-05-02 | ALTERNATE aTTaX   | W   | 0.592      | -            | -                | -                | -         |     7.40 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           47 |     2363 | 2024-05-02 | 9 Pandas          | L   | 0.591      | -            | -                | -                | -         |   -11.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           46 |     2364 | 2024-05-01 | Soda              | L   | 0.588      | -            | -                | -                | -         |   -17.45 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           45 |     2379 | 2024-05-01 | BLEED             | W   | 0.585      | -            | -                | -                | -         |     9.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           44 |     2392 | 2024-04-30 | ECLOT             | W   | 0.580      | -            | -                | -                | -         |    10.41 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           43 |     2403 | 2024-04-30 | V1dar             | W   | 0.579      | -            | -                | -                | -         |     0.99 | Burmylov, Chr1zN, PR, sirah, TOBIZ     |
|           42 |     2415 | 2024-04-29 | Nemiga            | L   | 0.574      | -            | -                | -                | -         |    -6.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           41 |     2428 | 2024-04-29 | Grannys Knockers  | W   | 0.571      | -            | -                | -                | -         |     3.26 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           40 |     2456 | 2024-04-27 | ECLOT             | W   | 0.560      | -            | -                | -                | -         |    10.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           39 |     2466 | 2024-04-27 | Permitta          | W   | 0.559      | -            | -                | -                | -         |     6.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           38 |     2528 | 2024-04-25 | Insilio           | L   | 0.544      | -            | -                | -                | -         |   -11.49 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           37 |     2539 | 2024-04-24 | PARIVISION        | L   | 0.539      | -            | -                | -                | -         |    -8.38 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           36 |     2551 | 2024-04-23 | BLEED             | W   | 0.534      | -            | -                | -                | -         |     8.78 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           35 |     2576 | 2024-04-22 | EYEBALLERS        | W   | 0.526      | -            | -                | -                | -         |     4.89 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           34 |     2584 | 2024-04-22 | Nemiga            | L   | 0.524      | -            | -                | -                | -         |    -5.96 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           33 |     2586 | 2024-04-22 | Permitta          | L   | 0.524      | -            | -                | -                | -         |   -10.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           32 |     2594 | 2024-04-21 | ALTERNATE aTTaX   | W   | 0.519      | -            | -                | -                | -         |     5.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           31 |     2601 | 2024-04-21 | ECLOT             | L   | 0.518      | -            | -                | -                | -         |    -7.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           30 |     2624 | 2024-04-20 | BLEED             | L   | 0.513      | -            | -                | -                | -         |    -8.95 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           29 |     2724 | 2024-04-18 | Enterprise        | W   | 0.499      | -            | -                | -                | -         |     4.84 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           28 |     2734 | 2024-04-18 | ENCE Academy      | W   | 0.498      | -            | -                | -                | -         |     2.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           27 |     2784 | 2024-04-17 | JANO              | W   | 0.491      | -            | -                | -                | -         |     1.74 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           26 |     2799 | 2024-04-16 | GamerLegion       | L   | 0.486      | -            | -                | -                | -         |    -6.32 | Anlelele, Burmylov, Neityu, PR, sirah  |
|           25 |     2824 | 2024-04-15 | Alliance          | W   | 0.478      | -            | -                | -                | -         |     3.63 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           24 |     2865 | 2024-04-12 | Permitta          | L   | 0.458      | -            | -                | -                | -         |    -9.47 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           23 |     2992 | 2024-04-09 | Zero Tenacity     | W   | 0.439      | -            | -                | -                | -         |     7.13 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           22 |     3027 | 2024-04-08 | B8                | W   | 0.432      | -            | -                | -                | -         |     7.23 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           21 |     3153 | 2024-04-03 | PARIVISION        | W   | 0.400      | -            | -                | -                | -         |     7.10 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           20 |     3495 | 2024-03-16 | Sampi             | L   | 0.278      | -            | -                | -                | -         |    -6.11 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           19 |     3513 | 2024-03-15 | Entropiq          | W   | 0.272      | -            | -                | -                | -         |     0.53 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           18 |     3569 | 2024-03-13 | Permitta          | L   | 0.261      | -            | -                | -                | -         |    -5.25 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           17 |     3586 | 2024-03-13 | Alliance          | W   | 0.258      | -            | -                | -                | -         |     2.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           16 |     3614 | 2024-03-12 | AURA              | W   | 0.253      | -            | -                | -                | -         |     0.34 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           15 |     3621 | 2024-03-12 | Sampi             | L   | 0.251      | -            | -                | -                | -         |    -5.66 | Burmylov, Chr1zN, Neityu, sirah, xReal |
|           14 |     3641 | 2024-03-11 | Passion UA        | W   | 0.245      | -            | -                | -                | -         |     4.12 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           13 |     3643 | 2024-03-11 | NOM               | W   | 0.244      | -            | -                | -                | -         |     0.33 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           12 |     3649 | 2024-03-10 | V1dar             | W   | 0.240      | -            | -                | -                | -         |     0.37 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           11 |     3661 | 2024-03-10 | Passion UA        | L   | 0.239      | -            | -                | -                | -         |    -3.56 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|           10 |     3665 | 2024-03-10 | ALTERNATE aTTaX   | W   | 0.238      | -            | -                | -                | -         |     3.01 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            9 |     3703 | 2024-03-08 | Fraud5            | W   | 0.226      | -            | -                | -                | -         |     0.67 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            8 |     3720 | 2024-03-07 | INGLORIOUS        | L   | 0.220      | -            | -                | -                | -         |    -6.59 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            7 |     3859 | 2024-03-03 | ex-Preasy         | W   | 0.191      | -            | -                | -                | -         |     1.07 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            6 |     3872 | 2024-03-02 | kONO              | W   | 0.186      | -            | -                | -                | -         |     1.19 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            5 |     3944 | 2024-02-27 | ECLOT             | L   | 0.159      | -            | -                | -                | -         |    -2.21 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            4 |     3959 | 2024-02-26 | BLEED             | W   | 0.152      | -            | -                | -                | -         |     1.75 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            3 |     3961 | 2024-02-26 | Permitta          | L   | 0.152      | -            | -                | -                | -         |    -3.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            2 |     4026 | 2024-02-24 | Sashi             | W   | 0.138      | -            | -                | -                | -         |     2.79 | Burmylov, Chr1zN, Neityu, PR, sirah    |
|            1 |     4092 | 2024-02-21 | Entropiq          | W   | 0.118      | -            | -                | -                | -         |     0.20 | Burmylov, Chr1zN, Neityu, PR, sirah    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,059.79)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-02 |      0.799 | $5,000.00      | $3,997.22       |
| 2024-05-26 |      0.753 | $10,000.00     | $7,530.56       |
| 2024-05-18 |      0.700 | $500.00        | $350.00         |
| 2024-05-12 |      0.660 | $5,000.00      | $3,299.65       |
| 2024-05-03 |      0.599 | $25,000.00     | $14,986.11      |
| 2024-03-18 |      0.291 | $1,000.00      | $291.11         |
| 2024-03-11 |      0.245 | $3,500.00      | $858.47         |
| 2024-02-28 |      0.164 | $1,500.00      | $246.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
