### Roster Details<br />
Team Name: Sashi<br />
Roster: Cabbi, IceBerg, kwezz, Lucky, MistR<br />
Global Rank: [34](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1176.5<br />
<br />
Final Rank Value (1176.5) = Starting Rank Value (1169.2) + Head To Head Adjustments (7.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.578[<sup>1</sup>](#table2)
- Bounty Collected: 0.462[<sup>2</sup>](#table1)
- Opponent Network: 0.244[<sup>2</sup>](#table1)
- LAN Wins: 0.210[<sup>2</sup>](#table1)

The average of these factors is 0.374<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1169.2
- 400 + ( ( 0.374 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1169.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           99 |       45 | 2024-07-31 | Insilio           | W   | 1.000      | 0.500        | -                | 0.554 (0.277)    | 0 (0.000) |     6.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           98 |       78 | 2024-07-30 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.513 (0.256)    | 0 (0.000) |     3.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           97 |       92 | 2024-07-30 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -18.87 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           96 |      272 | 2024-07-24 | Monte             | W   | 1.000      | 0.500        | 0.081 (0.041)    | 0.614 (0.307)    | 0 (0.000) |     9.86 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           95 |      502 | 2024-07-18 | FURIA             | L   | 1.000      | -            | -                | -                | -         |    -2.97 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           94 |      512 | 2024-07-18 | JiJieHao          | W   | 1.000      | 1.000        | 0.031 (0.031)    | -                | 1 (1.000) |     1.25 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           93 |      582 | 2024-07-17 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           92 |      717 | 2024-07-13 | TSM               | L   | 1.000      | -            | -                | -                | -         |   -22.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           91 |      726 | 2024-07-12 | FLuffy Gangsters  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           90 |      743 | 2024-07-11 | Endpoint          | W   | 1.000      | 0.358        | -                | 0.555 (0.199)    | 0 (0.000) |     5.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           89 |      767 | 2024-07-10 | Johnny Speeds     | L   | 1.000      | -            | -                | -                | -         |   -13.68 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           88 |      770 | 2024-07-10 | 9INE              | W   | 1.000      | 0.358        | -                | 0.521 (0.186)    | 0 (0.000) |     6.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           87 |      963 | 2024-06-14 | 3DMAX             | L   | 0.880      | -            | -                | -                | -         |    -6.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           86 |      998 | 2024-06-13 | Sampi             | W   | 0.874      | -            | -                | -                | 0 (0.000) |     3.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           85 |     1015 | 2024-06-12 | CPH Wolves        | W   | 0.868      | -            | -                | -                | 0 (0.000) |     2.54 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           84 |     1024 | 2024-06-12 | Astralis Talent   | W   | 0.868      | -            | -                | -                | -         |     1.81 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           83 |     1293 | 2024-06-06 | Ninjas in Pyjamas | L   | 0.829      | -            | -                | -                | -         |    -5.59 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           82 |     1330 | 2024-06-06 | HEROIC            | L   | 0.826      | -            | -                | -                | -         |    -3.44 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           81 |     1360 | 2024-06-05 | ENCE              | L   | 0.822      | -            | -                | -                | -         |    -8.93 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           80 |     1381 | 2024-06-05 | Astralis          | W   | 0.820      | 0.715        | 0.359 (0.211)    | 0.385 (0.226)    | 1 (0.820) |    24.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           79 |     1391 | 2024-06-05 | The MongolZ       | L   | 0.819      | -            | -                | -                | -         |    -0.49 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           78 |     1849 | 2024-05-20 | Monte             | L   | 0.713      | -            | -                | -                | -         |   -16.47 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           77 |     1867 | 2024-05-19 | Passion UA        | W   | 0.708      | 0.500        | 0.172 (0.061)    | 1.000 (0.354)    | -         |     5.88 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           76 |     1894 | 2024-05-18 | B8                | L   | 0.701      | -            | -                | -                | -         |   -13.65 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           75 |     1903 | 2024-05-18 | Monte             | W   | 0.700      | -            | -                | -                | -         |     5.58 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           74 |     1912 | 2024-05-18 | ALTERNATE aTTaX   | W   | 0.699      | 0.500        | -                | 0.564 (0.197)    | -         |     3.76 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           73 |     1943 | 2024-05-17 | ex-Guild Eagles   | W   | 0.693      | -            | -                | -                | -         |     2.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           72 |     1983 | 2024-05-16 | Passion UA        | L   | 0.686      | -            | -                | -                | -         |   -16.40 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           71 |     2034 | 2024-05-15 | Endpoint          | W   | 0.679      | -            | -                | -                | -         |     3.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           70 |     2211 | 2024-05-09 | 1WIN              | W   | 0.640      | -            | -                | -                | -         |     3.80 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           69 |     2236 | 2024-05-08 | Grannys Knockers  | W   | 0.633      | -            | -                | -                | -         |     1.95 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           68 |     2254 | 2024-05-07 | 9 Pandas          | W   | 0.627      | -            | -                | -                | -         |     4.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           67 |     2268 | 2024-05-06 | ALTERNATE aTTaX   | W   | 0.621      | -            | -                | -                | -         |     4.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           66 |     2282 | 2024-05-05 | Gaimin Gladiators | L   | 0.615      | -            | -                | -                | -         |   -14.59 | Cabbi, IceBerg, kwezz, Lucky, PR1mE   |
|           65 |     2290 | 2024-05-05 | Come on now dawg  | W   | 0.614      | -            | -                | -                | -         |     0.20 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           64 |     2343 | 2024-05-02 | fnatic            | W   | 0.594      | 0.384        | 0.292 (0.067)    | -                | -         |    12.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           63 |     2379 | 2024-05-01 | 3DMAX             | W   | 0.586      | 0.384        | 0.505 (0.114)    | 1.000 (0.225)    | -         |    16.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           62 |     2397 | 2024-04-30 | OG                | W   | 0.581      | 0.384        | 0.143 (0.032)    | -                | -         |     6.28 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           61 |     2422 | 2024-04-29 | 500               | W   | 0.573      | -            | -                | -                | -         |     1.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           60 |     2450 | 2024-04-27 | 777               | W   | 0.562      | -            | -                | -                | -         |     1.22 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           59 |     2454 | 2024-04-27 | JANO              | W   | 0.561      | -            | -                | -                | -         |     1.15 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           58 |     2521 | 2024-04-25 | Passion UA        | W   | 0.546      | 0.384        | 0.172 (0.036)    | 1.000 (0.210)    | -         |     5.08 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           57 |     2557 | 2024-04-23 | Gaimin Gladiators | W   | 0.534      | -            | -                | -                | -         |     5.64 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           56 |     2562 | 2024-04-23 | BLEED             | W   | 0.533      | -            | -                | -                | -         |     6.13 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           55 |     2617 | 2024-04-20 | Eternal Fire      | W   | 0.515      | 0.143        | 0.757 (0.056)    | -                | -         |    15.60 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           54 |     2624 | 2024-04-20 | Cloud9            | W   | 0.514      | -            | -                | -                | -         |     7.14 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           53 |     2664 | 2024-04-19 | Eternal Fire      | L   | 0.508      | -            | -                | -                | -         |    -0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           52 |     2673 | 2024-04-19 | Cloud9            | W   | 0.507      | -            | -                | -                | -         |     7.04 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           51 |     2700 | 2024-04-18 | ex-Guild Eagles   | W   | 0.502      | -            | -                | -                | -         |     2.73 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           50 |     2704 | 2024-04-18 | RUBY              | W   | 0.501      | -            | -                | -                | -         |     4.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           49 |     2713 | 2024-04-18 | GamerLegion       | W   | 0.501      | -            | -                | -                | -         |     8.16 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           48 |     2758 | 2024-04-17 | Passion UA        | L   | 0.494      | -            | -                | -                | -         |    -9.51 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           47 |     2796 | 2024-04-16 | ex-Guild Eagles   | L   | 0.487      | -            | -                | -                | -         |   -12.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           46 |     2817 | 2024-04-15 | ex-Preasy         | W   | 0.480      | -            | -                | -                | -         |     2.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           45 |     2834 | 2024-04-14 | UNiTY             | W   | 0.472      | -            | -                | -                | -         |     4.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           44 |     2893 | 2024-04-11 | Enterprise        | W   | 0.453      | -            | -                | -                | -         |     3.48 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           43 |     2936 | 2024-04-10 | Passion UA        | L   | 0.446      | -            | -                | -                | -         |    -8.90 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           42 |     3069 | 2024-04-06 | UNiTY             | W   | 0.419      | -            | -                | -                | -         |     3.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           41 |     3127 | 2024-04-04 | UNiTY             | W   | 0.406      | -            | -                | -                | -         |     3.52 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           40 |     3218 | 2024-04-02 | Permitta          | W   | 0.392      | -            | -                | -                | -         |     3.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           39 |     3227 | 2024-04-01 | Nexus             | L   | 0.386      | -            | -                | -                | -         |   -10.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           38 |     3302 | 2024-03-27 | Rebels            | L   | 0.355      | -            | -                | -                | -         |    -7.74 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           37 |     3341 | 2024-03-25 | Nexus             | W   | 0.341      | -            | -                | -                | -         |     1.75 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           36 |     3365 | 2024-03-22 | Nemiga            | W   | 0.322      | 0.372        | 0.324 (0.039)    | -                | -         |     5.38 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           35 |     3430 | 2024-03-19 | RUBY              | W   | 0.302      | -            | -                | -                | -         |     2.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           34 |     3442 | 2024-03-18 | Insilio           | W   | 0.294      | -            | -                | -                | -         |     2.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           33 |     3510 | 2024-03-15 | ECLOT             | W   | 0.273      | -            | -                | -                | -         |     3.82 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           32 |     3588 | 2024-03-13 | BLEED             | L   | 0.259      | -            | -                | -                | -         |    -5.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           31 |     3636 | 2024-03-11 | Nemiga            | L   | 0.247      | -            | -                | -                | -         |    -3.60 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           30 |     3659 | 2024-03-10 | Sampi             | L   | 0.240      | -            | -                | -                | -         |    -6.07 | Cabbi, IceBerg, Kristou, Lucky, MistR |
|           29 |     3684 | 2024-03-09 | Permitta          | W   | 0.233      | -            | -                | -                | -         |     1.88 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           28 |     3705 | 2024-03-08 | ALTERNATE aTTaX   | L   | 0.226      | -            | -                | -                | -         |    -5.07 | Cabbi, IceBerg, larsen, Lucky, MistR  |
|           27 |     3715 | 2024-03-07 | Insilio           | W   | 0.222      | -            | -                | -                | -         |     1.39 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           26 |     3729 | 2024-03-07 | ex-sYnck          | W   | 0.220      | -            | -                | -                | -         |     0.18 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           25 |     3762 | 2024-03-06 | Alliance          | W   | 0.213      | -            | -                | -                | -         |     1.10 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           24 |     3800 | 2024-03-05 | Johnny Speeds     | L   | 0.208      | -            | -                | -                | -         |    -1.92 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           23 |     3809 | 2024-03-05 | ALTERNATE aTTaX   | L   | 0.206      | -            | -                | -                | -         |    -4.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           22 |     3825 | 2024-03-04 | Entropiq          | L   | 0.199      | -            | -                | -                | -         |    -6.07 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           21 |     3870 | 2024-03-02 | brazylijski luz   | W   | 0.187      | -            | -                | -                | -         |     0.72 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           20 |     3905 | 2024-02-29 | JANO              | W   | 0.173      | -            | -                | -                | -         |     0.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           19 |     3916 | 2024-02-28 | Sampi             | W   | 0.167      | -            | -                | -                | -         |     0.98 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           18 |     3931 | 2024-02-27 | V1dar             | L   | 0.161      | -            | -                | -                | -         |    -4.94 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           17 |     3974 | 2024-02-25 | Sangal            | L   | 0.148      | -            | -                | -                | -         |    -2.43 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           16 |     3980 | 2024-02-25 | PGE Turow         | L   | 0.147      | -            | -                | -                | -         |    -4.37 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           15 |     4022 | 2024-02-24 | MOUZ NXT          | L   | 0.139      | -            | -                | -                | -         |    -2.82 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           14 |     4077 | 2024-02-21 | Sampi             | W   | 0.120      | -            | -                | -                | -         |     0.66 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           13 |     4174 | 2024-02-17 | Zero Tenacity     | W   | 0.094      | -            | -                | -                | -         |     1.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           12 |     4332 | 2024-02-11 | ARCRED            | W   | 0.053      | -            | -                | -                | -         |     0.26 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           11 |     4334 | 2024-02-10 | Nemiga            | L   | 0.049      | -            | -                | -                | -         |    -0.78 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|           10 |     4342 | 2024-02-10 | AMKAL             | W   | 0.047      | -            | -                | -                | -         |     0.71 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            9 |     4351 | 2024-02-09 | FORZE             | W   | 0.042      | -            | -                | -                | -         |     0.24 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            8 |     4358 | 2024-02-09 | Insilio           | W   | 0.041      | -            | -                | -                | -         |     0.23 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            7 |     4366 | 2024-02-08 | Nemiga            | L   | 0.035      | -            | -                | -                | -         |    -0.56 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            6 |     4370 | 2024-02-08 | FORZE             | W   | 0.034      | -            | -                | -                | -         |     0.19 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            5 |     4401 | 2024-02-05 | Entropiq          | W   | 0.013      | -            | -                | -                | -         |     0.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            4 |     4418 | 2024-02-04 | TMVG              | L   | 0.007      | -            | -                | -                | -         |    -0.21 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            3 |     4433 | 2024-02-03 | showmakerz        | W   | 0.002      | -            | -                | -                | -         |     0.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            2 |     4437 | 2024-02-03 | Gaimin Gladiators | W   | 0.002      | -            | -                | -                | -         |     0.01 | Cabbi, IceBerg, kwezz, Lucky, MistR   |
|            1 |     4452 | 2024-02-03 | Sampi             | L   | 0.000      | -            | -                | -                | -         |     0.00 | Cabbi, IceBerg, kwezz, Lucky, MistR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61,088.11)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-07-13 |      1.000 | $3,216.00      | $3,216.00       |
| 2024-06-12 |      0.868 | $9,365.00      | $8,129.99       |
| 2024-06-09 |      0.848 | $8,000.00      | $6,780.00       |
| 2024-05-18 |      0.701 | $5,000.00      | $3,506.94       |
| 2024-05-09 |      0.640 | $14,000.00     | $8,960.00       |
| 2024-05-02 |      0.594 | $12,500.00     | $7,430.56       |
| 2024-04-27 |      0.562 | $6,375.00      | $3,582.40       |
| 2024-04-06 |      0.419 | $5,000.00      | $2,094.44       |
| 2024-03-25 |      0.341 | $7,000.00      | $2,387.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
