### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1131.8<br />
<br />
Final Rank Value (1131.8) = Starting Rank Value (1046.3) + Head To Head Adjustments (85.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.524[<sup>1</sup>](#table2)
- Bounty Collected: 0.449[<sup>2</sup>](#table1)
- Opponent Network: 0.289[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.3
- 400 + ( ( 0.316 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1046.3


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
|          106 |       75 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |       92 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      120 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.10 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      124 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.801 (0.297)    | 0 (0.000) |     9.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      160 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.490 (0.221)    | 0 (0.000) |     5.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      164 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.97 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      213 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      253 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.54 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      286 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -27.02 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      328 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.94 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      332 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      336 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      359 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.21 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      364 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      402 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      405 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.44 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      435 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.27 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      442 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      445 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      451 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.04 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      475 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.68 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      495 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.325 (0.125)    | 0.867 (0.333)    | -         |    22.54 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      502 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      523 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      536 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.20 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      558 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      561 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      567 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      601 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.03 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      603 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.60 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      613 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.93 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      669 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.801 (0.361)    | -         |     9.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      674 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.801 (0.361)    | -         |    10.20 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      777 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.72 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      782 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1009 | 2024-06-16 | paiN           | W   | 0.868      | 0.450        | 0.325 (0.127)    | 0.867 (0.339)    | -         |    21.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1037 | 2024-06-15 | inSanitY       | W   | 0.862      | -            | -                | -                | -         |     8.94 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1073 | 2024-06-14 | Sharks         | W   | 0.855      | -            | -                | -                | -         |    11.54 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1283 | 2024-06-08 | KRÜ            | W   | 0.816      | -            | -                | -                | -         |     6.33 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1361 | 2024-06-07 | Bounty Hunters | W   | 0.808      | -            | -                | -                | -         |     6.72 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1426 | 2024-06-06 | W7M            | W   | 0.801      | -            | -                | -                | -         |     4.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1466 | 2024-06-05 | paiN           | L   | 0.796      | -            | -                | -                | -         |    -4.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1518 | 2024-06-04 | 9z             | L   | 0.789      | -            | -                | -                | -         |    -2.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1841 | 2024-05-22 | BESTIA         | L   | 0.702      | -            | -                | -                | -         |   -12.21 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1844 | 2024-05-22 | BESTIA         | L   | 0.702      | -            | -                | -                | -         |   -12.98 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1915 | 2024-05-20 | RED Canids     | W   | 0.689      | 0.450        | 0.077 (0.024)    | 0.757 (0.235)    | -         |    12.60 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1918 | 2024-05-20 | RED Canids     | L   | 0.689      | -            | -                | -                | -         |    -9.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     1976 | 2024-05-18 | 9z             | L   | 0.675      | -            | -                | -                | -         |    -2.23 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2010 | 2024-05-17 | Case           | W   | 0.669      | -            | -                | -                | -         |     5.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2044 | 2024-05-16 | RED Canids     | L   | 0.662      | -            | -                | -                | -         |   -10.05 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2089 | 2024-05-15 | Smoke          | W   | 0.656      | -            | -                | -                | -         |     2.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2090 | 2024-05-15 | Smoke          | W   | 0.656      | -            | -                | -                | -         |     2.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2104 | 2024-05-15 | Imperial       | L   | 0.654      | -            | -                | -                | -         |    -5.74 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2154 | 2024-05-14 | Sharks         | W   | 0.648      | -            | -                | -                | -         |     7.18 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2167 | 2024-05-14 | ODDIK          | W   | 0.647      | 0.384        | 0.099 (0.025)    | -                | -         |     6.91 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2187 | 2024-05-13 | Hype           | W   | 0.641      | -            | -                | -                | -         |     4.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2214 | 2024-05-12 | Vikings KR     | W   | 0.634      | -            | -                | -                | -         |     3.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2274 | 2024-05-09 | paiN           | W   | 0.617      | 0.450        | 0.325 (0.090)    | 0.867 (0.240)    | -         |    16.52 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2279 | 2024-05-09 | paiN           | L   | 0.616      | -            | -                | -                | -         |    -2.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2753 | 2024-04-18 | paiN           | L   | 0.477      | -            | -                | -                | -         |    -2.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2760 | 2024-04-18 | Imperial       | L   | 0.475      | -            | -                | -                | -         |    -3.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2807 | 2024-04-17 | ODDIK          | W   | 0.469      | -            | -                | -                | -         |     5.01 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2815 | 2024-04-17 | Solid          | W   | 0.469      | -            | -                | -                | -         |     3.82 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2846 | 2024-04-16 | Hype           | W   | 0.463      | -            | -                | -                | -         |     3.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2905 | 2024-04-13 | Galorys        | L   | 0.440      | -            | -                | -                | -         |    -9.93 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2971 | 2024-04-10 | Imperial       | W   | 0.423      | 0.450        | 0.235 (0.045)    | -                | -         |    10.26 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     2974 | 2024-04-10 | Imperial       | L   | 0.422      | -            | -                | -                | -         |    -3.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3024 | 2024-04-09 | ODDIK          | W   | 0.416      | -            | -                | -                | -         |     4.58 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3029 | 2024-04-09 | ODDIK          | W   | 0.416      | -            | -                | -                | -         |     4.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3065 | 2024-04-08 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.81 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3115 | 2024-04-06 | BESTIA         | L   | 0.396      | -            | -                | -                | -         |    -7.54 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3116 | 2024-04-06 | Solid          | W   | 0.395      | -            | -                | -                | -         |     3.51 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3131 | 2024-04-05 | MIBR           | L   | 0.390      | -            | -                | -                | -         |    -1.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3132 | 2024-04-05 | MIBR           | W   | 0.389      | 0.450        | 0.208 (0.037)    | -                | -         |    10.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3159 | 2024-04-04 | Corinthians    | W   | 0.383      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3165 | 2024-04-04 | Corinthians    | W   | 0.383      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3179 | 2024-04-04 | RED Canids     | L   | 0.381      | -            | -                | -                | -         |    -5.32 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3195 | 2024-04-03 | MIBR           | L   | 0.376      | -            | -                | -                | -         |    -1.45 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3206 | 2024-04-03 | BESTIA         | W   | 0.375      | -            | -                | -                | -         |     5.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3243 | 2024-04-02 | MIBR           | L   | 0.370      | -            | -                | -                | -         |    -1.41 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3247 | 2024-04-02 | BESTIA         | W   | 0.368      | -            | -                | -                | -         |     5.08 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3331 | 2024-03-27 | Galorys        | L   | 0.330      | -            | -                | -                | -         |    -7.35 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3337 | 2024-03-27 | Galorys        | W   | 0.329      | -            | -                | -                | -         |     3.07 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3606 | 2024-03-13 | Intense        | W   | 0.236      | -            | -                | -                | -         |     1.16 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3620 | 2024-03-13 | Solid          | L   | 0.234      | -            | -                | -                | -         |    -5.29 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3646 | 2024-03-12 | MIBR           | W   | 0.229      | -            | -                | -                | -         |     6.34 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3678 | 2024-03-11 | Sharks         | W   | 0.220      | -            | -                | -                | -         |     2.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3721 | 2024-03-09 | Corinthians    | W   | 0.207      | -            | -                | -                | -         |     0.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3756 | 2024-03-07 | Case           | L   | 0.195      | -            | -                | -                | -         |    -4.13 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3781 | 2024-03-06 | Solid          | L   | 0.190      | -            | -                | -                | -         |    -4.25 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3782 | 2024-03-06 | Solid          | W   | 0.189      | -            | -                | -                | -         |     1.74 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3848 | 2024-03-04 | Case           | W   | 0.176      | -            | -                | -                | -         |     1.90 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3849 | 2024-03-04 | Case           | W   | 0.176      | -            | -                | -                | -         |     1.93 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     4006 | 2024-02-25 | Imperial       | W   | 0.122      | -            | -                | -                | -         |     2.95 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4036 | 2024-02-24 | Sharks         | W   | 0.115      | -            | -                | -                | -         |     1.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4086 | 2024-02-21 | W7M            | L   | 0.097      | -            | -                | -                | -         |    -2.32 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4091 | 2024-02-21 | W7M            | W   | 0.096      | -            | -                | -                | -         |     0.72 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4095 | 2024-02-21 | Solid          | W   | 0.094      | -            | -                | -                | -         |     0.91 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4123 | 2024-02-20 | Solid          | L   | 0.089      | -            | -                | -                | -         |    -1.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4220 | 2024-02-16 | 9z             | W   | 0.062      | -            | -                | -                | -         |     1.84 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4247 | 2024-02-15 | Imperial       | L   | 0.056      | -            | -                | -                | -         |    -0.41 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4249 | 2024-02-15 | W7M            | W   | 0.056      | -            | -                | -                | -         |     0.42 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4254 | 2024-02-15 | Sharks         | W   | 0.055      | -            | -                | -                | -         |     0.69 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4255 | 2024-02-15 | Sharks         | W   | 0.054      | -            | -                | -                | -         |     0.69 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4278 | 2024-02-14 | Intense        | W   | 0.050      | -            | -                | -                | -         |     0.25 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4343 | 2024-02-12 | Flamengo       | W   | 0.034      | -            | -                | -                | -         |     0.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,807.04)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.868 | $30,000.00     | $26,041.67      |
| 2024-06-09 |      0.822 | $2,000.00      | $1,644.26       |
| 2024-05-19 |      0.681 | $2,000.00      | $1,362.78       |
| 2024-03-14 |      0.242 | $5,000.00      | $1,209.72       |
| 2024-02-25 |      0.122 | $25,000.00     | $3,048.61       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
