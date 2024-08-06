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
Final Rank Value (1129.0) = Starting Rank Value (1043.4) + Head To Head Adjustments (85.6)<br />

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
|          106 |      102 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |      119 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      147 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      151 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.776 (0.287)    | 0 (0.000) |     9.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      187 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | 0 (0.000) |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      191 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.00 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      240 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      280 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      313 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -26.98 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      355 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      359 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      363 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      386 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      391 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      429 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      432 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      462 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.29 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      469 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      472 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      478 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      502 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      522 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.324 (0.124)    | 0.839 (0.322)    | -         |    22.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      529 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      550 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.61 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      563 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      585 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.16 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      588 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      594 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      628 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.05 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      630 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      640 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.97 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      696 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |     9.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      701 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |    10.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      804 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      809 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.92 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1036 | 2024-06-16 | paiN           | W   | 0.861      | 0.450        | 0.324 (0.125)    | 0.839 (0.325)    | -         |    21.08 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1064 | 2024-06-15 | inSanitY       | W   | 0.855      | -            | -                | -                | -         |     8.88 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1100 | 2024-06-14 | Sharks         | W   | 0.848      | -            | -                | -                | -         |    11.45 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1310 | 2024-06-08 | KRÜ            | W   | 0.809      | -            | -                | -                | -         |     6.30 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1388 | 2024-06-07 | Bounty Hunters | W   | 0.801      | -            | -                | -                | -         |     6.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1453 | 2024-06-06 | W7M            | W   | 0.794      | -            | -                | -                | -         |     4.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1493 | 2024-06-05 | paiN           | L   | 0.789      | -            | -                | -                | -         |    -4.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1545 | 2024-06-04 | 9z             | L   | 0.782      | -            | -                | -                | -         |    -2.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1868 | 2024-05-22 | BESTIA         | L   | 0.695      | -            | -                | -                | -         |   -12.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1871 | 2024-05-22 | BESTIA         | L   | 0.695      | -            | -                | -                | -         |   -12.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1942 | 2024-05-20 | RED Canids     | W   | 0.682      | 0.450        | 0.076 (0.023)    | 0.732 (0.225)    | -         |    12.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1945 | 2024-05-20 | RED Canids     | L   | 0.682      | -            | -                | -                | -         |    -9.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     2003 | 2024-05-18 | 9z             | L   | 0.668      | -            | -                | -                | -         |    -2.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2037 | 2024-05-17 | Case           | W   | 0.662      | -            | -                | -                | -         |     5.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2071 | 2024-05-16 | RED Canids     | L   | 0.655      | -            | -                | -                | -         |    -9.94 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2116 | 2024-05-15 | Smoke          | W   | 0.649      | -            | -                | -                | -         |     2.08 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2117 | 2024-05-15 | Smoke          | W   | 0.649      | -            | -                | -                | -         |     2.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2131 | 2024-05-15 | Imperial       | L   | 0.647      | -            | -                | -                | -         |    -5.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2181 | 2024-05-14 | Sharks         | W   | 0.641      | -            | -                | -                | -         |     7.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2194 | 2024-05-14 | ODDIK          | W   | 0.640      | 0.384        | 0.099 (0.024)    | -                | -         |     6.87 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2214 | 2024-05-13 | Hype           | W   | 0.634      | -            | -                | -                | -         |     4.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2241 | 2024-05-12 | Vikings KR     | W   | 0.627      | -            | -                | -                | -         |     3.76 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2301 | 2024-05-09 | paiN           | W   | 0.610      | 0.450        | 0.324 (0.089)    | 0.839 (0.230)    | -         |    16.32 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2306 | 2024-05-09 | paiN           | L   | 0.609      | -            | -                | -                | -         |    -2.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2780 | 2024-04-18 | paiN           | L   | 0.470      | -            | -                | -                | -         |    -2.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2787 | 2024-04-18 | Imperial       | L   | 0.468      | -            | -                | -                | -         |    -3.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2834 | 2024-04-17 | ODDIK          | W   | 0.462      | -            | -                | -                | -         |     4.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2842 | 2024-04-17 | Solid          | W   | 0.462      | -            | -                | -                | -         |     3.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2873 | 2024-04-16 | Hype           | W   | 0.456      | -            | -                | -                | -         |     3.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2932 | 2024-04-13 | Galorys        | L   | 0.433      | -            | -                | -                | -         |    -9.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2998 | 2024-04-10 | Imperial       | W   | 0.416      | 0.450        | 0.233 (0.044)    | -                | -         |    10.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     3001 | 2024-04-10 | Imperial       | L   | 0.415      | -            | -                | -                | -         |    -3.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3051 | 2024-04-09 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.52 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3056 | 2024-04-09 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3092 | 2024-04-08 | ODDIK          | W   | 0.402      | -            | -                | -                | -         |     4.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3142 | 2024-04-06 | BESTIA         | L   | 0.389      | -            | -                | -                | -         |    -7.38 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3143 | 2024-04-06 | Solid          | W   | 0.388      | -            | -                | -                | -         |     3.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3158 | 2024-04-05 | MIBR           | L   | 0.383      | -            | -                | -                | -         |    -1.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3159 | 2024-04-05 | MIBR           | W   | 0.382      | 0.450        | 0.208 (0.036)    | -                | -         |    10.59 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3186 | 2024-04-04 | Corinthians    | W   | 0.376      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3192 | 2024-04-04 | Corinthians    | W   | 0.375      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3206 | 2024-04-04 | RED Canids     | L   | 0.374      | -            | -                | -                | -         |    -5.23 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3222 | 2024-04-03 | MIBR           | L   | 0.369      | -            | -                | -                | -         |    -1.43 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3233 | 2024-04-03 | BESTIA         | W   | 0.368      | -            | -                | -                | -         |     4.99 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3270 | 2024-04-02 | MIBR           | L   | 0.363      | -            | -                | -                | -         |    -1.39 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3274 | 2024-04-02 | BESTIA         | W   | 0.361      | -            | -                | -                | -         |     5.00 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3358 | 2024-03-27 | Galorys        | L   | 0.323      | -            | -                | -                | -         |    -7.17 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3364 | 2024-03-27 | Galorys        | W   | 0.322      | -            | -                | -                | -         |     3.02 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3633 | 2024-03-13 | Intense        | W   | 0.229      | -            | -                | -                | -         |     1.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3647 | 2024-03-13 | Solid          | L   | 0.227      | -            | -                | -                | -         |    -5.12 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3673 | 2024-03-12 | MIBR           | W   | 0.222      | -            | -                | -                | -         |     6.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3705 | 2024-03-11 | Sharks         | W   | 0.213      | -            | -                | -                | -         |     2.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3748 | 2024-03-09 | Corinthians    | W   | 0.200      | -            | -                | -                | -         |     0.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3783 | 2024-03-07 | Case           | L   | 0.188      | -            | -                | -                | -         |    -3.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3808 | 2024-03-06 | Solid          | L   | 0.183      | -            | -                | -                | -         |    -4.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3809 | 2024-03-06 | Solid          | W   | 0.182      | -            | -                | -                | -         |     1.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3875 | 2024-03-04 | Case           | W   | 0.169      | -            | -                | -                | -         |     1.83 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3876 | 2024-03-04 | Case           | W   | 0.169      | -            | -                | -                | -         |     1.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     4033 | 2024-02-25 | Imperial       | W   | 0.115      | -            | -                | -                | -         |     2.77 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4063 | 2024-02-24 | Sharks         | W   | 0.108      | -            | -                | -                | -         |     1.35 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4113 | 2024-02-21 | W7M            | L   | 0.089      | -            | -                | -                | -         |    -2.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4118 | 2024-02-21 | W7M            | W   | 0.089      | -            | -                | -                | -         |     0.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4122 | 2024-02-21 | Solid          | W   | 0.087      | -            | -                | -                | -         |     0.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4150 | 2024-02-20 | Solid          | L   | 0.082      | -            | -                | -                | -         |    -1.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4247 | 2024-02-16 | 9z             | W   | 0.055      | -            | -                | -                | -         |     1.63 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4274 | 2024-02-15 | Imperial       | L   | 0.049      | -            | -                | -                | -         |    -0.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4276 | 2024-02-15 | W7M            | W   | 0.049      | -            | -                | -                | -         |     0.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4281 | 2024-02-15 | Sharks         | W   | 0.048      | -            | -                | -                | -         |     0.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4282 | 2024-02-15 | Sharks         | W   | 0.047      | -            | -                | -                | -         |     0.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4305 | 2024-02-14 | Intense        | W   | 0.043      | -            | -                | -                | -         |     0.22 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4370 | 2024-02-12 | Flamengo       | W   | 0.027      | -            | -                | -                | -         |     0.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,356.67)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.861 | $30,000.00     | $25,830.56      |
| 2024-06-09 |      0.815 | $2,000.00      | $1,630.19       |
| 2024-05-19 |      0.674 | $2,000.00      | $1,348.70       |
| 2024-03-14 |      0.235 | $5,000.00      | $1,174.54       |
| 2024-02-25 |      0.115 | $25,000.00     | $2,872.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
