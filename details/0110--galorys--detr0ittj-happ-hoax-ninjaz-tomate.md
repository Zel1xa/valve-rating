### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Global Rank: [110](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
<br />
Final Rank Value:  840.2<br />
<br />
Final Rank Value (840.2) = Starting Rank Value (907.1) + Head To Head Adjustments (-66.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.246<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 907.1
- 400 + ( ( 0.246 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 907.1


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
|           98 |       75 | 2024-07-30 | BESTIA            | W   | 1.000      | 0.450        | 0.089 (0.040)    | 0.738 (0.332)    | 0 (0.000) |    23.37 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           97 |       81 | 2024-07-30 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |    -7.63 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           96 |      178 | 2024-07-27 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -7.15 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           95 |      196 | 2024-07-26 | Case              | W   | 1.000      | 0.365        | 0.030 (0.011)    | 0.722 (0.263)    | 0 (0.000) |    19.51 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           94 |      240 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.58 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           93 |      241 | 2024-07-25 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -1.61 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           92 |      313 | 2024-07-23 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.43 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           91 |      364 | 2024-07-21 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           90 |      406 | 2024-07-20 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -14.14 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           89 |      491 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -3.96 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           88 |      542 | 2024-07-17 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -17.07 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           87 |      546 | 2024-07-17 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.31 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           86 |      558 | 2024-07-17 | FURIA Academy     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.13 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           85 |      610 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.18 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           84 |      617 | 2024-07-16 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.23 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           83 |      633 | 2024-07-16 | Intense           | L   | 1.000      | -            | -                | -                | -         |   -22.54 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           82 |      662 | 2024-07-15 | inSanitY          | L   | 1.000      | -            | -                | -                | -         |    -8.31 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           81 |      668 | 2024-07-15 | inSanitY          | W   | 1.000      | 0.450        | 0.049 (0.022)    | 0.421 (0.189)    | 0 (0.000) |    23.73 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           80 |      746 | 2024-07-11 | Case              | L   | 1.000      | -            | -                | -                | -         |   -14.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           79 |      765 | 2024-07-10 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.49 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           78 |      807 | 2024-07-08 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.46 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           77 |      838 | 2024-06-30 | Vikings KR        | L   | 0.986      | -            | -                | -                | -         |   -16.72 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           76 |      845 | 2024-06-29 | inSanitY          | L   | 0.980      | -            | -                | -                | -         |    -9.33 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           75 |      856 | 2024-06-27 | Sharks            | L   | 0.968      | -            | -                | -                | -         |    -9.29 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           74 |      858 | 2024-06-27 | KRÜ               | W   | 0.967      | 0.333        | -                | 0.516 (0.166)    | 0 (0.000) |    16.81 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           73 |      881 | 2024-06-18 | inSanitY          | L   | 0.908      | -            | -                | -                | -         |    -9.99 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           72 |     1098 | 2024-06-09 | ODDIK             | L   | 0.848      | -            | -                | -                | -         |   -10.17 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           71 |     1194 | 2024-06-08 | Case              | W   | 0.839      | 0.450        | 0.030 (0.011)    | 0.722 (0.273)    | 0 (0.000) |    12.80 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           70 |     1229 | 2024-06-07 | Imperial          | L   | 0.834      | -            | -                | -                | -         |    -2.53 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           69 |     1258 | 2024-06-07 | W7M               | L   | 0.832      | -            | -                | -                | -         |   -14.21 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           68 |     1277 | 2024-06-06 | paiN              | L   | 0.829      | -            | -                | -                | -         |    -3.14 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           67 |     1291 | 2024-06-06 | ex-Corinthians    | W   | 0.828      | -            | -                | -                | -         |     5.73 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           66 |     1412 | 2024-06-04 | MIBR              | L   | 0.815      | -            | -                | -                | -         |    -1.38 | detr0ittJ, happ, hoax, ninjaZ, piriajr |
|           65 |     1451 | 2024-06-03 | Intense           | L   | 0.807      | -            | -                | -                | -         |   -20.48 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           64 |     1500 | 2024-06-01 | Hype              | L   | 0.793      | -            | -                | -                | -         |   -12.87 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           63 |     1553 | 2024-05-30 | Hawks             | W   | 0.781      | -            | -                | -                | -         |     2.89 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           62 |     1639 | 2024-05-27 | Dusty Roots       | W   | 0.759      | -            | -                | -                | -         |    10.11 | detr0ittJ, happ, hoax, ninjaZ, Tomate  |
|           61 |     1838 | 2024-05-20 | Case              | L   | 0.713      | -            | -                | -                | -         |   -11.06 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           60 |     1871 | 2024-05-19 | Solid             | W   | 0.707      | 0.303        | -                | 0.844 (0.181)    | -         |    10.47 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           59 |     1897 | 2024-05-18 | ODDIK             | L   | 0.700      | -            | -                | -                | -         |    -9.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           58 |     2014 | 2024-05-15 | Hype              | W   | 0.681      | -            | -                | -                | -         |    10.77 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           57 |     2023 | 2024-05-15 | Case              | L   | 0.680      | -            | -                | -                | -         |   -11.61 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           56 |     2070 | 2024-05-14 | Case              | L   | 0.675      | -            | -                | -                | -         |   -12.23 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           55 |     2075 | 2024-05-14 | Case              | W   | 0.674      | 0.450        | -                | 0.722 (0.219)    | -         |     9.13 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           54 |     2087 | 2024-05-14 | 9z                | L   | 0.673      | -            | -                | -                | -         |    -3.83 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           53 |     2107 | 2024-05-13 | 9z                | L   | 0.668      | -            | -                | -                | -         |    -3.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           52 |     2113 | 2024-05-13 | Yawara            | W   | 0.667      | -            | -                | -                | -         |     1.90 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           51 |     2134 | 2024-05-12 | KRÜ               | W   | 0.660      | -            | -                | -                | -         |    10.85 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           50 |     2173 | 2024-05-11 | Case              | W   | 0.652      | 0.384        | -                | 0.722 (0.181)    | -         |    10.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           49 |     2234 | 2024-05-08 | paiN              | L   | 0.634      | -            | -                | -                | -         |    -1.34 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           48 |     2237 | 2024-05-08 | paiN              | L   | 0.633      | -            | -                | -                | -         |    -1.36 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           47 |     2259 | 2024-05-07 | KRÜ               | L   | 0.626      | -            | -                | -                | -         |    -9.75 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           46 |     2294 | 2024-05-05 | W7M               | L   | 0.612      | -            | -                | -                | -         |   -11.68 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           45 |     2610 | 2024-04-20 | Solid             | W   | 0.515      | 0.450        | -                | 0.844 (0.195)    | -         |     7.38 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           44 |     2612 | 2024-04-20 | Solid             | L   | 0.514      | -            | -                | -                | -         |    -9.05 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           43 |     2791 | 2024-04-16 | Case              | L   | 0.488      | -            | -                | -                | -         |    -8.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           42 |     2830 | 2024-04-14 | MIBR              | L   | 0.474      | -            | -                | -                | -         |    -0.92 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           41 |     2849 | 2024-04-13 | Fluxo             | W   | 0.466      | 0.435        | 0.122 (0.025)    | -                | -         |    10.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           40 |     2858 | 2024-04-12 | Sharks            | W   | 0.461      | -            | -                | -                | -         |     4.55 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           39 |     2879 | 2024-04-11 | Vikings KR        | L   | 0.454      | -            | -                | -                | -         |    -9.09 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           38 |     2886 | 2024-04-11 | BESTIA            | W   | 0.453      | 0.435        | 0.089 (0.018)    | -                | -         |     8.08 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           37 |     2914 | 2024-04-10 | MIBR              | L   | 0.448      | -            | -                | -                | -         |    -0.85 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           36 |     2918 | 2024-04-10 | MIBR              | L   | 0.448      | -            | -                | -                | -         |    -0.85 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           35 |     2968 | 2024-04-09 | BESTIA            | W   | 0.441      | 0.450        | 0.089 (0.018)    | 0.738 (0.147)    | -         |     8.15 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           34 |     2973 | 2024-04-09 | BESTIA            | L   | 0.441      | -            | -                | -                | -         |    -5.86 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           33 |     3046 | 2024-04-07 | paiN              | L   | 0.427      | -            | -                | -                | -         |    -0.97 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           32 |     3166 | 2024-04-03 | 9z                | W   | 0.399      | 0.450        | 0.138 (0.025)    | -                | -         |    10.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           31 |     3167 | 2024-04-03 | 9z                | W   | 0.399      | 0.450        | 0.138 (0.025)    | -                | -         |    10.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           30 |     3284 | 2024-03-27 | Fluxo             | W   | 0.355      | 0.450        | 0.122 (0.020)    | -                | -         |     8.02 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           29 |     3291 | 2024-03-27 | Fluxo             | L   | 0.355      | -            | -                | -                | -         |    -3.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           28 |     3331 | 2024-03-26 | 2GAME             | W   | 0.348      | -            | -                | -                | -         |     2.64 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           27 |     3335 | 2024-03-26 | 2GAME             | W   | 0.348      | -            | -                | -                | -         |     2.70 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           26 |     3532 | 2024-03-14 | W7M               | W   | 0.268      | -            | -                | -                | -         |     3.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           25 |     3535 | 2024-03-14 | W7M               | W   | 0.268      | -            | -                | -                | -         |     3.88 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           24 |     3581 | 2024-03-13 | RED Canids        | L   | 0.260      | -            | -                | -                | -         |    -2.55 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           23 |     3626 | 2024-03-11 | LA RUGONETA       | L   | 0.247      | -            | -                | -                | -         |    -6.87 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           22 |     3648 | 2024-03-10 | MIBR              | L   | 0.241      | -            | -                | -                | -         |    -0.41 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           21 |     3707 | 2024-03-08 | ODDIK             | W   | 0.226      | -            | -                | -                | -         |     4.73 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           20 |     3997 | 2024-02-24 | Sharks            | L   | 0.142      | -            | -                | -                | -         |    -1.76 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           19 |     4005 | 2024-02-24 | Sharks            | L   | 0.141      | -            | -                | -                | -         |    -1.78 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           18 |     4030 | 2024-02-23 | Corinthians       | L   | 0.135      | -            | -                | -                | -         |    -3.79 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           17 |     4031 | 2024-02-23 | Corinthians       | W   | 0.134      | -            | -                | -                | -         |     0.46 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           16 |     4051 | 2024-02-22 | MIBR Academy      | W   | 0.128      | -            | -                | -                | -         |     0.42 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           15 |     4066 | 2024-02-21 | adalYamigos       | L   | 0.122      | -            | -                | -                | -         |    -3.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           14 |     4070 | 2024-02-21 | adalYamigos       | L   | 0.121      | -            | -                | -                | -         |    -3.20 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           13 |     4078 | 2024-02-21 | Sharks            | L   | 0.119      | -            | -                | -                | -         |    -1.55 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           12 |     4146 | 2024-02-18 | Sharks            | L   | 0.102      | -            | -                | -                | -         |    -1.33 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           11 |     4148 | 2024-02-18 | Case              | W   | 0.100      | -            | -                | -                | -         |     1.80 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|           10 |     4173 | 2024-02-17 | Sharks            | W   | 0.094      | -            | -                | -                | -         |     1.75 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            9 |     4176 | 2024-02-17 | Corinthians       | W   | 0.093      | -            | -                | -                | -         |     0.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            8 |     4198 | 2024-02-16 | Flamengo          | W   | 0.088      | -            | -                | -                | -         |     0.26 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            7 |     4201 | 2024-02-16 | Imperial          | L   | 0.087      | -            | -                | -                | -         |    -0.31 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            6 |     4206 | 2024-02-16 | Imperial          | L   | 0.086      | -            | -                | -                | -         |    -0.30 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            5 |     4232 | 2024-02-15 | 9z Academy        | W   | 0.080      | -            | -                | -                | -         |     0.25 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            4 |     4259 | 2024-02-14 | Solid             | L   | 0.075      | -            | -                | -                | -         |    -1.19 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            3 |     4273 | 2024-02-14 | Sharks            | L   | 0.073      | -            | -                | -                | -         |    -0.94 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            2 |     4316 | 2024-02-13 | Case              | L   | 0.067      | -            | -                | -                | -         |    -0.92 | detr0ittJ, happ, hoax, koala, ninjaZ   |
|            1 |     4326 | 2024-02-12 | inSanitY          | W   | 0.061      | -            | -                | -                | -         |     0.11 | detr0ittJ, happ, hoax, koala, ninjaZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,885.18)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $4,600.00      | $4,600.00       |
| 2024-06-19 |      0.914 | $1,075.00      | $982.43         |
| 2024-06-09 |      0.847 | $1,500.00      | $1,271.11       |
| 2024-04-15 |      0.481 | $5,000.00      | $2,402.78       |
| 2024-04-11 |      0.454 | $592.00        | $269.03         |
| 2024-02-22 |      0.128 | $1,417.00      | $180.67         |
| 2024-02-21 |      0.119 | $1,500.00      | $179.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
