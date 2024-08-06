### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1129.0<br />
<br />
Final Rank Value (1129.0) = Starting Rank Value (1043.4) + Head To Head Adjustments (85.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.448[<sup>2</sup>](#table1)
- Opponent Network: 0.279[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.313<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1043.4
- 400 + ( ( 0.313 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1043.4


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
|          106 |      105 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |      122 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      150 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      154 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.096 (0.036)    | 0.776 (0.288)    | 0 (0.000) |     9.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      190 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | 0 (0.000) |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      194 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.00 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      243 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      283 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      316 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -26.98 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      358 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      362 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      366 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      389 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      394 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      432 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      435 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      465 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.29 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      472 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      475 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      481 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      505 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      525 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.324 (0.124)    | 0.839 (0.322)    | -         |    22.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      532 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      553 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.61 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      566 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      588 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.16 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      591 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      597 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      631 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.05 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      633 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.63 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      643 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.97 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      699 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |     9.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      704 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |    10.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      807 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      812 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.92 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1039 | 2024-06-16 | paiN           | W   | 0.861      | 0.450        | 0.324 (0.125)    | 0.839 (0.325)    | -         |    21.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1067 | 2024-06-15 | inSanitY       | W   | 0.854      | -            | -                | -                | -         |     8.88 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1103 | 2024-06-14 | Sharks         | W   | 0.848      | -            | -                | -                | -         |    11.44 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1313 | 2024-06-08 | KRÜ            | W   | 0.809      | -            | -                | -                | -         |     6.30 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1391 | 2024-06-07 | Bounty Hunters | W   | 0.800      | -            | -                | -                | -         |     6.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1456 | 2024-06-06 | W7M            | W   | 0.794      | -            | -                | -                | -         |     4.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1496 | 2024-06-05 | paiN           | L   | 0.788      | -            | -                | -                | -         |    -4.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1548 | 2024-06-04 | 9z             | L   | 0.782      | -            | -                | -                | -         |    -2.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1871 | 2024-05-22 | BESTIA         | L   | 0.694      | -            | -                | -                | -         |   -12.06 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1874 | 2024-05-22 | BESTIA         | L   | 0.694      | -            | -                | -                | -         |   -12.81 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1945 | 2024-05-20 | RED Canids     | W   | 0.682      | 0.450        | 0.076 (0.023)    | 0.732 (0.225)    | -         |    12.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1948 | 2024-05-20 | RED Canids     | L   | 0.682      | -            | -                | -                | -         |    -9.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     2006 | 2024-05-18 | 9z             | L   | 0.667      | -            | -                | -                | -         |    -2.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2040 | 2024-05-17 | Case           | W   | 0.661      | -            | -                | -                | -         |     5.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2074 | 2024-05-16 | RED Canids     | L   | 0.655      | -            | -                | -                | -         |    -9.94 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2119 | 2024-05-15 | Smoke          | W   | 0.649      | -            | -                | -                | -         |     2.08 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2120 | 2024-05-15 | Smoke          | W   | 0.648      | -            | -                | -                | -         |     2.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2134 | 2024-05-15 | Imperial       | L   | 0.647      | -            | -                | -                | -         |    -5.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2184 | 2024-05-14 | Sharks         | W   | 0.641      | -            | -                | -                | -         |     7.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2197 | 2024-05-14 | ODDIK          | W   | 0.640      | 0.384        | 0.099 (0.024)    | -                | -         |     6.87 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2217 | 2024-05-13 | Hype           | W   | 0.634      | -            | -                | -                | -         |     4.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2244 | 2024-05-12 | Vikings KR     | W   | 0.626      | -            | -                | -                | -         |     3.76 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2304 | 2024-05-09 | paiN           | W   | 0.609      | 0.450        | 0.324 (0.089)    | 0.839 (0.230)    | -         |    16.30 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2309 | 2024-05-09 | paiN           | L   | 0.609      | -            | -                | -                | -         |    -2.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2783 | 2024-04-18 | paiN           | L   | 0.469      | -            | -                | -                | -         |    -2.13 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2790 | 2024-04-18 | Imperial       | L   | 0.468      | -            | -                | -                | -         |    -3.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2837 | 2024-04-17 | ODDIK          | W   | 0.462      | -            | -                | -                | -         |     4.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2845 | 2024-04-17 | Solid          | W   | 0.461      | -            | -                | -                | -         |     3.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2876 | 2024-04-16 | Hype           | W   | 0.456      | -            | -                | -                | -         |     3.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2935 | 2024-04-13 | Galorys        | L   | 0.433      | -            | -                | -                | -         |    -9.74 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     3001 | 2024-04-10 | Imperial       | W   | 0.415      | 0.450        | 0.233 (0.044)    | -                | -         |    10.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     3004 | 2024-04-10 | Imperial       | L   | 0.415      | -            | -                | -                | -         |    -3.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3054 | 2024-04-09 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.52 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3059 | 2024-04-09 | ODDIK          | W   | 0.408      | -            | -                | -                | -         |     4.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3095 | 2024-04-08 | ODDIK          | W   | 0.401      | -            | -                | -                | -         |     4.74 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3145 | 2024-04-06 | BESTIA         | L   | 0.389      | -            | -                | -                | -         |    -7.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3146 | 2024-04-06 | Solid          | W   | 0.388      | -            | -                | -                | -         |     3.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3161 | 2024-04-05 | MIBR           | L   | 0.382      | -            | -                | -                | -         |    -1.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3162 | 2024-04-05 | MIBR           | W   | 0.382      | 0.450        | 0.207 (0.036)    | -                | -         |    10.58 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3189 | 2024-04-04 | Corinthians    | W   | 0.375      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3195 | 2024-04-04 | Corinthians    | W   | 0.375      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3209 | 2024-04-04 | RED Canids     | L   | 0.373      | -            | -                | -                | -         |    -5.22 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3225 | 2024-04-03 | MIBR           | L   | 0.369      | -            | -                | -                | -         |    -1.43 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3236 | 2024-04-03 | BESTIA         | W   | 0.368      | -            | -                | -                | -         |     4.98 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3273 | 2024-04-02 | MIBR           | L   | 0.362      | -            | -                | -                | -         |    -1.39 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3277 | 2024-04-02 | BESTIA         | W   | 0.361      | -            | -                | -                | -         |     4.99 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3361 | 2024-03-27 | Galorys        | L   | 0.322      | -            | -                | -                | -         |    -7.16 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3367 | 2024-03-27 | Galorys        | W   | 0.322      | -            | -                | -                | -         |     3.02 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3636 | 2024-03-13 | Intense        | W   | 0.228      | -            | -                | -                | -         |     1.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3650 | 2024-03-13 | Solid          | L   | 0.227      | -            | -                | -                | -         |    -5.11 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3676 | 2024-03-12 | MIBR           | W   | 0.221      | -            | -                | -                | -         |     6.13 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3708 | 2024-03-11 | Sharks         | W   | 0.213      | -            | -                | -                | -         |     2.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3751 | 2024-03-09 | Corinthians    | W   | 0.199      | -            | -                | -                | -         |     0.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3786 | 2024-03-07 | Case           | L   | 0.188      | -            | -                | -                | -         |    -3.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3811 | 2024-03-06 | Solid          | L   | 0.182      | -            | -                | -                | -         |    -4.08 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3812 | 2024-03-06 | Solid          | W   | 0.182      | -            | -                | -                | -         |     1.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3878 | 2024-03-04 | Case           | W   | 0.169      | -            | -                | -                | -         |     1.83 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3879 | 2024-03-04 | Case           | W   | 0.169      | -            | -                | -                | -         |     1.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     4036 | 2024-02-25 | Imperial       | W   | 0.114      | -            | -                | -                | -         |     2.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4066 | 2024-02-24 | Sharks         | W   | 0.108      | -            | -                | -                | -         |     1.35 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4116 | 2024-02-21 | W7M            | L   | 0.089      | -            | -                | -                | -         |    -2.13 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4121 | 2024-02-21 | W7M            | W   | 0.089      | -            | -                | -                | -         |     0.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4125 | 2024-02-21 | Solid          | W   | 0.087      | -            | -                | -                | -         |     0.84 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4153 | 2024-02-20 | Solid          | L   | 0.081      | -            | -                | -                | -         |    -1.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4250 | 2024-02-16 | 9z             | W   | 0.054      | -            | -                | -                | -         |     1.62 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4277 | 2024-02-15 | Imperial       | L   | 0.048      | -            | -                | -                | -         |    -0.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4279 | 2024-02-15 | W7M            | W   | 0.048      | -            | -                | -                | -         |     0.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4284 | 2024-02-15 | Sharks         | W   | 0.047      | -            | -                | -                | -         |     0.59 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4285 | 2024-02-15 | Sharks         | W   | 0.047      | -            | -                | -                | -         |     0.59 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4308 | 2024-02-14 | Intense        | W   | 0.042      | -            | -                | -                | -         |     0.22 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4373 | 2024-02-12 | Flamengo       | W   | 0.026      | -            | -                | -                | -         |     0.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,327.04)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.861 | $30,000.00     | $25,816.67      |
| 2024-06-09 |      0.815 | $2,000.00      | $1,629.26       |
| 2024-05-19 |      0.674 | $2,000.00      | $1,347.78       |
| 2024-03-14 |      0.234 | $5,000.00      | $1,172.22       |
| 2024-02-25 |      0.114 | $25,000.00     | $2,861.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
