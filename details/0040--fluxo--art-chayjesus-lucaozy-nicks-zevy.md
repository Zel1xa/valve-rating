### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1132.6<br />
<br />
Final Rank Value (1132.6) = Starting Rank Value (1046.4) + Head To Head Adjustments (86.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.524[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.290[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.4
- 400 + ( ( 0.316 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1046.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          106 |       58 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |       75 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      103 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.09 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      107 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | 0 (0.000) |     9.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      143 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.489 (0.220)    | 0 (0.000) |     5.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      147 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.95 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      196 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      236 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      269 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -27.04 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      311 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.90 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      315 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      319 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.44 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      342 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      347 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      385 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      388 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      418 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.26 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      425 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.40 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      428 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      434 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.01 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      458 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      478 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.327 (0.126)    | 0.867 (0.333)    | -         |    22.55 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      485 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      506 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      519 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.18 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      541 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      544 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      550 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      584 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.02 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      586 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      596 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.90 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      652 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.361)    | -         |     9.44 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      657 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.361)    | -         |    10.18 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      760 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      765 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |      992 | 2024-06-16 | paiN           | W   | 0.874      | 0.450        | 0.327 (0.128)    | 0.867 (0.341)    | -         |    21.40 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1020 | 2024-06-15 | inSanitY       | W   | 0.868      | -            | -                | -                | -         |     8.98 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1056 | 2024-06-14 | Sharks         | W   | 0.861      | -            | -                | -                | -         |    11.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1266 | 2024-06-08 | KRÜ            | W   | 0.822      | -            | -                | -                | -         |     6.35 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1344 | 2024-06-07 | Bounty Hunters | W   | 0.813      | -            | -                | -                | -         |     6.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1409 | 2024-06-06 | W7M            | W   | 0.807      | -            | -                | -                | -         |     4.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1449 | 2024-06-05 | paiN           | L   | 0.802      | -            | -                | -                | -         |    -4.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1501 | 2024-06-04 | 9z             | L   | 0.795      | -            | -                | -                | -         |    -2.44 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1824 | 2024-05-22 | BESTIA         | L   | 0.708      | -            | -                | -                | -         |   -12.32 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1827 | 2024-05-22 | BESTIA         | L   | 0.707      | -            | -                | -                | -         |   -13.10 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1898 | 2024-05-20 | RED Canids     | W   | 0.695      | 0.450        | 0.077 (0.024)    | 0.758 (0.237)    | -         |    12.71 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1901 | 2024-05-20 | RED Canids     | L   | 0.695      | -            | -                | -                | -         |    -9.28 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     1959 | 2024-05-18 | 9z             | L   | 0.680      | -            | -                | -                | -         |    -2.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     1993 | 2024-05-17 | Case           | W   | 0.675      | -            | -                | -                | -         |     5.52 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2027 | 2024-05-16 | RED Canids     | L   | 0.668      | -            | -                | -                | -         |   -10.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2072 | 2024-05-15 | Smoke          | W   | 0.662      | -            | -                | -                | -         |     2.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2073 | 2024-05-15 | Smoke          | W   | 0.662      | -            | -                | -                | -         |     2.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2087 | 2024-05-15 | Imperial       | L   | 0.660      | -            | -                | -                | -         |    -5.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2137 | 2024-05-14 | Sharks         | W   | 0.654      | -            | -                | -                | -         |     7.23 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2150 | 2024-05-14 | ODDIK          | W   | 0.653      | 0.384        | 0.099 (0.025)    | -                | -         |     6.95 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2170 | 2024-05-13 | Hype           | W   | 0.647      | -            | -                | -                | -         |     4.60 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2197 | 2024-05-12 | Vikings KR     | W   | 0.640      | -            | -                | -                | -         |     3.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2257 | 2024-05-09 | paiN           | W   | 0.622      | 0.450        | 0.327 (0.092)    | 0.867 (0.243)    | -         |    16.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2262 | 2024-05-09 | paiN           | L   | 0.622      | -            | -                | -                | -         |    -2.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2736 | 2024-04-18 | paiN           | L   | 0.483      | -            | -                | -                | -         |    -2.16 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2743 | 2024-04-18 | Imperial       | L   | 0.481      | -            | -                | -                | -         |    -3.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2790 | 2024-04-17 | ODDIK          | W   | 0.475      | -            | -                | -                | -         |     5.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2798 | 2024-04-17 | Solid          | W   | 0.475      | -            | -                | -                | -         |     3.86 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2829 | 2024-04-16 | Hype           | W   | 0.469      | -            | -                | -                | -         |     3.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2888 | 2024-04-13 | Galorys        | L   | 0.446      | -            | -                | -                | -         |   -10.08 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2954 | 2024-04-10 | Imperial       | W   | 0.428      | 0.450        | 0.236 (0.046)    | -                | -         |    10.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     2957 | 2024-04-10 | Imperial       | L   | 0.428      | -            | -                | -                | -         |    -3.07 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3007 | 2024-04-09 | ODDIK          | W   | 0.422      | -            | -                | -                | -         |     4.63 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3012 | 2024-04-09 | ODDIK          | W   | 0.422      | -            | -                | -                | -         |     4.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3048 | 2024-04-08 | ODDIK          | W   | 0.414      | -            | -                | -                | -         |     4.87 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3098 | 2024-04-06 | BESTIA         | L   | 0.402      | -            | -                | -                | -         |    -7.66 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3099 | 2024-04-06 | Solid          | W   | 0.401      | -            | -                | -                | -         |     3.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3114 | 2024-04-05 | MIBR           | L   | 0.395      | -            | -                | -                | -         |    -1.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3115 | 2024-04-05 | MIBR           | W   | 0.395      | 0.450        | 0.209 (0.037)    | -                | -         |    10.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3142 | 2024-04-04 | Corinthians    | W   | 0.388      | -            | -                | -                | -         |     0.56 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3148 | 2024-04-04 | Corinthians    | W   | 0.388      | -            | -                | -                | -         |     0.56 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3162 | 2024-04-04 | RED Canids     | L   | 0.386      | -            | -                | -                | -         |    -5.39 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3178 | 2024-04-03 | MIBR           | L   | 0.382      | -            | -                | -                | -         |    -1.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3189 | 2024-04-03 | BESTIA         | W   | 0.381      | -            | -                | -                | -         |     5.13 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3226 | 2024-04-02 | MIBR           | L   | 0.375      | -            | -                | -                | -         |    -1.42 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3230 | 2024-04-02 | BESTIA         | W   | 0.374      | -            | -                | -                | -         |     5.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3314 | 2024-03-27 | Galorys        | L   | 0.336      | -            | -                | -                | -         |    -7.49 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3320 | 2024-03-27 | Galorys        | W   | 0.335      | -            | -                | -                | -         |     3.11 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3589 | 2024-03-13 | Intense        | W   | 0.241      | -            | -                | -                | -         |     1.18 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3603 | 2024-03-13 | Solid          | L   | 0.240      | -            | -                | -                | -         |    -5.42 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3629 | 2024-03-12 | MIBR           | W   | 0.234      | -            | -                | -                | -         |     6.50 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3661 | 2024-03-11 | Sharks         | W   | 0.226      | -            | -                | -                | -         |     2.83 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3704 | 2024-03-09 | Corinthians    | W   | 0.213      | -            | -                | -                | -         |     0.31 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3739 | 2024-03-07 | Case           | L   | 0.201      | -            | -                | -                | -         |    -4.25 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3764 | 2024-03-06 | Solid          | L   | 0.195      | -            | -                | -                | -         |    -4.38 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3765 | 2024-03-06 | Solid          | W   | 0.195      | -            | -                | -                | -         |     1.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3831 | 2024-03-04 | Case           | W   | 0.182      | -            | -                | -                | -         |     1.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3832 | 2024-03-04 | Case           | W   | 0.182      | -            | -                | -                | -         |     1.98 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     3989 | 2024-02-25 | Imperial       | W   | 0.128      | -            | -                | -                | -         |     3.10 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4019 | 2024-02-24 | Sharks         | W   | 0.121      | -            | -                | -                | -         |     1.52 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4069 | 2024-02-21 | W7M            | L   | 0.102      | -            | -                | -                | -         |    -2.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4074 | 2024-02-21 | W7M            | W   | 0.102      | -            | -                | -                | -         |     0.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4078 | 2024-02-21 | Solid          | W   | 0.100      | -            | -                | -                | -         |     0.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4106 | 2024-02-20 | Solid          | L   | 0.095      | -            | -                | -                | -         |    -2.08 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4203 | 2024-02-16 | 9z             | W   | 0.068      | -            | -                | -                | -         |     2.01 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4230 | 2024-02-15 | Imperial       | L   | 0.062      | -            | -                | -                | -         |    -0.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4232 | 2024-02-15 | W7M            | W   | 0.061      | -            | -                | -                | -         |     0.47 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4237 | 2024-02-15 | Sharks         | W   | 0.060      | -            | -                | -                | -         |     0.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4238 | 2024-02-15 | Sharks         | W   | 0.060      | -            | -                | -                | -         |     0.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4261 | 2024-02-14 | Intense        | W   | 0.055      | -            | -                | -                | -         |     0.28 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4326 | 2024-02-12 | Flamengo       | W   | 0.039      | -            | -                | -                | -         |     0.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,172.96)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.874 | $30,000.00     | $26,213.19      |
| 2024-06-09 |      0.828 | $2,000.00      | $1,655.69       |
| 2024-05-19 |      0.687 | $2,000.00      | $1,374.21       |
| 2024-03-14 |      0.248 | $5,000.00      | $1,238.31       |
| 2024-02-25 |      0.128 | $25,000.00     | $3,191.55       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
