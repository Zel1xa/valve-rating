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
|          106 |       92 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |      109 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      137 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      141 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.776 (0.287)    | 0 (0.000) |     9.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      177 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | 0 (0.000) |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      181 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.00 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      230 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      270 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      303 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -26.98 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      345 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      349 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      353 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      376 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      381 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      419 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      422 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      452 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.29 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      459 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      462 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      468 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      492 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      512 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.324 (0.124)    | 0.839 (0.322)    | -         |    22.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      519 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      540 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.61 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      553 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      575 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.16 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      578 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      584 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      618 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.05 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      620 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      630 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      686 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |     9.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      691 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |    10.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      794 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      799 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.92 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1026 | 2024-06-16 | paiN           | W   | 0.861      | 0.450        | 0.324 (0.125)    | 0.839 (0.325)    | -         |    21.09 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1054 | 2024-06-15 | inSanitY       | W   | 0.855      | -            | -                | -                | -         |     8.89 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1090 | 2024-06-14 | Sharks         | W   | 0.849      | -            | -                | -                | -         |    11.45 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1300 | 2024-06-08 | KRÜ            | W   | 0.809      | -            | -                | -                | -         |     6.30 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1378 | 2024-06-07 | Bounty Hunters | W   | 0.801      | -            | -                | -                | -         |     6.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1443 | 2024-06-06 | W7M            | W   | 0.794      | -            | -                | -                | -         |     4.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1483 | 2024-06-05 | paiN           | L   | 0.789      | -            | -                | -                | -         |    -4.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1535 | 2024-06-04 | 9z             | L   | 0.783      | -            | -                | -                | -         |    -2.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1858 | 2024-05-22 | BESTIA         | L   | 0.695      | -            | -                | -                | -         |   -12.08 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1861 | 2024-05-22 | BESTIA         | L   | 0.695      | -            | -                | -                | -         |   -12.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1932 | 2024-05-20 | RED Canids     | W   | 0.683      | 0.450        | 0.076 (0.023)    | 0.732 (0.225)    | -         |    12.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1935 | 2024-05-20 | RED Canids     | L   | 0.682      | -            | -                | -                | -         |    -9.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     1993 | 2024-05-18 | 9z             | L   | 0.668      | -            | -                | -                | -         |    -2.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2027 | 2024-05-17 | Case           | W   | 0.662      | -            | -                | -                | -         |     5.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2061 | 2024-05-16 | RED Canids     | L   | 0.655      | -            | -                | -                | -         |    -9.95 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2106 | 2024-05-15 | Smoke          | W   | 0.649      | -            | -                | -                | -         |     2.08 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2107 | 2024-05-15 | Smoke          | W   | 0.649      | -            | -                | -                | -         |     2.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2121 | 2024-05-15 | Imperial       | L   | 0.648      | -            | -                | -                | -         |    -5.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2171 | 2024-05-14 | Sharks         | W   | 0.642      | -            | -                | -                | -         |     7.12 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2184 | 2024-05-14 | ODDIK          | W   | 0.640      | 0.384        | 0.099 (0.024)    | -                | -         |     6.88 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2204 | 2024-05-13 | Hype           | W   | 0.634      | -            | -                | -                | -         |     4.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2231 | 2024-05-12 | Vikings KR     | W   | 0.627      | -            | -                | -                | -         |     3.76 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2291 | 2024-05-09 | paiN           | W   | 0.610      | 0.450        | 0.324 (0.089)    | 0.839 (0.230)    | -         |    16.33 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2296 | 2024-05-09 | paiN           | L   | 0.610      | -            | -                | -                | -         |    -2.81 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2770 | 2024-04-18 | paiN           | L   | 0.470      | -            | -                | -                | -         |    -2.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2777 | 2024-04-18 | Imperial       | L   | 0.469      | -            | -                | -                | -         |    -3.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2824 | 2024-04-17 | ODDIK          | W   | 0.462      | -            | -                | -                | -         |     4.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2832 | 2024-04-17 | Solid          | W   | 0.462      | -            | -                | -                | -         |     3.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2863 | 2024-04-16 | Hype           | W   | 0.456      | -            | -                | -                | -         |     3.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2922 | 2024-04-13 | Galorys        | L   | 0.434      | -            | -                | -                | -         |    -9.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2988 | 2024-04-10 | Imperial       | W   | 0.416      | 0.450        | 0.233 (0.044)    | -                | -         |    10.07 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     2991 | 2024-04-10 | Imperial       | L   | 0.416      | -            | -                | -                | -         |    -3.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3041 | 2024-04-09 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.53 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3046 | 2024-04-09 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3082 | 2024-04-08 | ODDIK          | W   | 0.402      | -            | -                | -                | -         |     4.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3132 | 2024-04-06 | BESTIA         | L   | 0.389      | -            | -                | -                | -         |    -7.39 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3133 | 2024-04-06 | Solid          | W   | 0.389      | -            | -                | -                | -         |     3.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3148 | 2024-04-05 | MIBR           | L   | 0.383      | -            | -                | -                | -         |    -1.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3149 | 2024-04-05 | MIBR           | W   | 0.383      | 0.450        | 0.208 (0.036)    | -                | -         |    10.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3176 | 2024-04-04 | Corinthians    | W   | 0.376      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3182 | 2024-04-04 | Corinthians    | W   | 0.376      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3196 | 2024-04-04 | RED Canids     | L   | 0.374      | -            | -                | -                | -         |    -5.23 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3212 | 2024-04-03 | MIBR           | L   | 0.369      | -            | -                | -                | -         |    -1.43 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3223 | 2024-04-03 | BESTIA         | W   | 0.368      | -            | -                | -                | -         |     4.99 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3260 | 2024-04-02 | MIBR           | L   | 0.363      | -            | -                | -                | -         |    -1.39 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3264 | 2024-04-02 | BESTIA         | W   | 0.362      | -            | -                | -                | -         |     5.00 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3348 | 2024-03-27 | Galorys        | L   | 0.323      | -            | -                | -                | -         |    -7.18 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3354 | 2024-03-27 | Galorys        | W   | 0.323      | -            | -                | -                | -         |     3.03 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3623 | 2024-03-13 | Intense        | W   | 0.229      | -            | -                | -                | -         |     1.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3637 | 2024-03-13 | Solid          | L   | 0.228      | -            | -                | -                | -         |    -5.13 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3663 | 2024-03-12 | MIBR           | W   | 0.222      | -            | -                | -                | -         |     6.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3695 | 2024-03-11 | Sharks         | W   | 0.214      | -            | -                | -                | -         |     2.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3738 | 2024-03-09 | Corinthians    | W   | 0.200      | -            | -                | -                | -         |     0.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3773 | 2024-03-07 | Case           | L   | 0.189      | -            | -                | -                | -         |    -3.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3798 | 2024-03-06 | Solid          | L   | 0.183      | -            | -                | -                | -         |    -4.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3799 | 2024-03-06 | Solid          | W   | 0.183      | -            | -                | -                | -         |     1.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3865 | 2024-03-04 | Case           | W   | 0.170      | -            | -                | -                | -         |     1.83 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3866 | 2024-03-04 | Case           | W   | 0.169      | -            | -                | -                | -         |     1.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     4023 | 2024-02-25 | Imperial       | W   | 0.115      | -            | -                | -                | -         |     2.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4053 | 2024-02-24 | Sharks         | W   | 0.109      | -            | -                | -                | -         |     1.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4103 | 2024-02-21 | W7M            | L   | 0.090      | -            | -                | -                | -         |    -2.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4108 | 2024-02-21 | W7M            | W   | 0.089      | -            | -                | -                | -         |     0.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4112 | 2024-02-21 | Solid          | W   | 0.088      | -            | -                | -                | -         |     0.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4140 | 2024-02-20 | Solid          | L   | 0.082      | -            | -                | -                | -         |    -1.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4237 | 2024-02-16 | 9z             | W   | 0.055      | -            | -                | -                | -         |     1.64 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4264 | 2024-02-15 | Imperial       | L   | 0.049      | -            | -                | -                | -         |    -0.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4266 | 2024-02-15 | W7M            | W   | 0.049      | -            | -                | -                | -         |     0.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4271 | 2024-02-15 | Sharks         | W   | 0.048      | -            | -                | -                | -         |     0.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4272 | 2024-02-15 | Sharks         | W   | 0.048      | -            | -                | -                | -         |     0.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4295 | 2024-02-14 | Intense        | W   | 0.043      | -            | -                | -                | -         |     0.22 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4360 | 2024-02-12 | Flamengo       | W   | 0.027      | -            | -                | -                | -         |     0.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,374.44)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.861 | $30,000.00     | $25,838.89      |
| 2024-06-09 |      0.815 | $2,000.00      | $1,630.74       |
| 2024-05-19 |      0.675 | $2,000.00      | $1,349.26       |
| 2024-03-14 |      0.235 | $5,000.00      | $1,175.93       |
| 2024-02-25 |      0.115 | $25,000.00     | $2,879.63       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
