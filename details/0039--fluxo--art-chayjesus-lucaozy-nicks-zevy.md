### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1137.8<br />
<br />
Final Rank Value (1137.8) = Starting Rank Value (1039.3) + Head To Head Adjustments (98.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.444[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.310<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1039.3
- 400 + ( ( 0.310 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1039.3


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
|          107 |       25 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.511 (0.230)    | 0 (0.000) |     6.27 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          106 |       26 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |       75 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      117 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      149 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -28.55 | arT, Lucaozy, nicks, vsm, zevy       |
|          102 |      191 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -14.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      195 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.81 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      199 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.03 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      222 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      227 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           97 |      265 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      268 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      298 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.30 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      305 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.81 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      308 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.35 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      314 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.52 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      339 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      359 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.300 (0.115)    | 0.801 (0.308)    | -         |    20.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      367 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -10.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      389 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      402 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |    10.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      425 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.37 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      428 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -10.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      434 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      471 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.572 (0.257)    | -         |     8.09 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      473 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.572 (0.257)    | -         |     8.67 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      487 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.95 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      542 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.089 (0.040)    | 0.738 (0.332)    | -         |     9.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      546 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.089 (0.040)    | 0.738 (0.332)    | -         |     9.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      655 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     4.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      661 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     4.36 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      888 | 2024-06-16 | paiN           | W   | 0.895      | 0.450        | 0.300 (0.121)    | 0.801 (0.323)    | -         |    20.08 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      913 | 2024-06-15 | inSanitY       | W   | 0.889      | -            | -                | -                | -         |     8.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      944 | 2024-06-14 | Sharks         | W   | 0.882      | -            | -                | -                | -         |    11.85 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |     1156 | 2024-06-08 | KRÜ            | W   | 0.843      | -            | -                | -                | -         |     7.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |     1241 | 2024-06-07 | Bounty Hunters | W   | 0.835      | -            | -                | -                | -         |     7.03 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1308 | 2024-06-06 | W7M            | W   | 0.828      | 0.450        | -                | 0.625 (0.233)    | -         |     5.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1350 | 2024-06-05 | paiN           | L   | 0.823      | -            | -                | -                | -         |    -6.71 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1403 | 2024-06-04 | 9z             | L   | 0.816      | -            | -                | -                | -         |    -7.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1729 | 2024-05-22 | BESTIA         | L   | 0.729      | -            | -                | -                | -         |   -12.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1732 | 2024-05-22 | BESTIA         | L   | 0.729      | -            | -                | -                | -         |   -13.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1819 | 2024-05-20 | RED Canids     | W   | 0.716      | 0.450        | 0.075 (0.024)    | 0.753 (0.243)    | -         |    11.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1823 | 2024-05-20 | RED Canids     | L   | 0.716      | -            | -                | -                | -         |   -10.91 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1889 | 2024-05-18 | 9z             | L   | 0.702      | -            | -                | -                | -         |    -8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1924 | 2024-05-17 | Case           | W   | 0.696      | -            | -                | -                | -         |     5.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1958 | 2024-05-16 | RED Canids     | L   | 0.689      | -            | -                | -                | -         |   -11.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     2003 | 2024-05-15 | Smoke          | W   | 0.683      | -            | -                | -                | -         |     2.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     2004 | 2024-05-15 | Smoke          | W   | 0.683      | -            | -                | -                | -         |     3.04 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     2018 | 2024-05-15 | Imperial       | L   | 0.681      | -            | -                | -                | -         |    -5.52 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2074 | 2024-05-14 | Sharks         | W   | 0.675      | -            | -                | -                | -         |     7.32 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2087 | 2024-05-14 | ODDIK          | W   | 0.674      | 0.384        | 0.096 (0.025)    | -                | -         |     7.33 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2110 | 2024-05-13 | Hype           | W   | 0.668      | -            | -                | -                | -         |     4.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2136 | 2024-05-12 | Vikings KR     | W   | 0.661      | -            | -                | -                | -         |     3.73 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2197 | 2024-05-09 | paiN           | W   | 0.644      | 0.450        | 0.300 (0.087)    | 0.801 (0.232)    | -         |    16.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2202 | 2024-05-09 | paiN           | L   | 0.643      | -            | -                | -                | -         |    -3.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2688 | 2024-04-18 | paiN           | L   | 0.504      | -            | -                | -                | -         |    -2.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           51 |     2696 | 2024-04-18 | Imperial       | L   | 0.502      | -            | -                | -                | -         |    -3.74 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           50 |     2743 | 2024-04-17 | ODDIK          | W   | 0.496      | -            | -                | -                | -         |     5.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           49 |     2752 | 2024-04-17 | Solid          | W   | 0.496      | -            | -                | -                | -         |     3.89 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           48 |     2783 | 2024-04-16 | Hype           | W   | 0.490      | -            | -                | -                | -         |     3.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           47 |     2843 | 2024-04-13 | Galorys        | L   | 0.467      | -            | -                | -                | -         |   -10.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2910 | 2024-04-10 | Imperial       | W   | 0.450      | 0.450        | 0.240 (0.048)    | -                | -         |    11.01 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2913 | 2024-04-10 | Imperial       | L   | 0.449      | -            | -                | -                | -         |    -3.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2963 | 2024-04-09 | ODDIK          | W   | 0.443      | -            | -                | -                | -         |     5.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2968 | 2024-04-09 | ODDIK          | W   | 0.443      | -            | -                | -                | -         |     5.24 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     3004 | 2024-04-08 | ODDIK          | W   | 0.436      | -            | -                | -                | -         |     5.35 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     3054 | 2024-04-06 | BESTIA         | L   | 0.423      | -            | -                | -                | -         |    -8.20 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     3055 | 2024-04-06 | Solid          | W   | 0.422      | -            | -                | -                | -         |     3.63 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3070 | 2024-04-05 | MIBR           | L   | 0.417      | -            | -                | -                | -         |    -1.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3071 | 2024-04-05 | MIBR           | W   | 0.416      | 0.450        | 0.201 (0.038)    | -                | -         |    11.47 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3098 | 2024-04-04 | Corinthians    | W   | 0.410      | -            | -                | -                | -         |     0.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3104 | 2024-04-04 | Corinthians    | W   | 0.409      | -            | -                | -                | -         |     0.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3119 | 2024-04-04 | RED Canids     | L   | 0.407      | -            | -                | -                | -         |    -6.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3135 | 2024-04-03 | MIBR           | L   | 0.403      | -            | -                | -                | -         |    -1.64 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3147 | 2024-04-03 | BESTIA         | W   | 0.402      | -            | -                | -                | -         |     5.26 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3190 | 2024-04-02 | MIBR           | L   | 0.397      | -            | -                | -                | -         |    -1.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3194 | 2024-04-02 | BESTIA         | W   | 0.395      | -            | -                | -                | -         |     5.29 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3278 | 2024-03-27 | Galorys        | L   | 0.357      | -            | -                | -                | -         |    -8.07 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3285 | 2024-03-27 | Galorys        | W   | 0.356      | -            | -                | -                | -         |     3.20 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3525 | 2024-03-14 | adalYamigos    | W   | 0.270      | -            | -                | -                | -         |     0.72 | arT, chayJESUS, Lucaozy, PKL, zevy   |
|           27 |     3528 | 2024-03-14 | adalYamigos    | W   | 0.270      | -            | -                | -                | -         |     0.73 | arT, chayJESUS, Lucaozy, PKL, zevy   |
|           26 |     3559 | 2024-03-13 | RED Canids     | W   | 0.263      | -            | -                | -                | -         |     3.89 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3563 | 2024-03-13 | Intense        | W   | 0.263      | -            | -                | -                | -         |     0.63 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3576 | 2024-03-13 | Solid          | L   | 0.261      | -            | -                | -                | -         |    -5.91 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3603 | 2024-03-12 | MIBR           | W   | 0.256      | 0.435        | 0.201 (0.022)    | -                | -         |     7.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3635 | 2024-03-11 | Sharks         | W   | 0.247      | -            | -                | -                | -         |     3.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3679 | 2024-03-09 | Corinthians    | W   | 0.234      | -            | -                | -                | -         |     0.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3714 | 2024-03-07 | Case           | L   | 0.222      | -            | -                | -                | -         |    -4.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3739 | 2024-03-06 | Solid          | L   | 0.217      | -            | -                | -                | -         |    -4.87 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3740 | 2024-03-06 | Solid          | W   | 0.216      | -            | -                | -                | -         |     1.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3789 | 2024-03-05 | 9z             | W   | 0.208      | -            | -                | -                | -         |     4.77 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3790 | 2024-03-05 | 9z             | W   | 0.208      | -            | -                | -                | -         |     4.84 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3811 | 2024-03-04 | Case           | W   | 0.203      | -            | -                | -                | -         |     2.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3812 | 2024-03-04 | Case           | W   | 0.203      | -            | -                | -                | -         |     2.33 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     3973 | 2024-02-25 | Imperial       | W   | 0.149      | -            | -                | -                | -         |     3.71 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4003 | 2024-02-24 | Sharks         | W   | 0.142      | -            | -                | -                | -         |     1.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4058 | 2024-02-21 | W7M            | L   | 0.123      | -            | -                | -                | -         |    -2.83 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4063 | 2024-02-21 | W7M            | W   | 0.123      | -            | -                | -                | -         |     1.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4068 | 2024-02-21 | Solid          | W   | 0.121      | -            | -                | -                | -         |     1.22 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4096 | 2024-02-20 | Solid          | L   | 0.116      | -            | -                | -                | -         |    -2.50 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4193 | 2024-02-16 | 9z             | W   | 0.089      | -            | -                | -                | -         |     2.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4220 | 2024-02-15 | Imperial       | L   | 0.083      | -            | -                | -                | -         |    -0.56 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4222 | 2024-02-15 | W7M            | W   | 0.083      | -            | -                | -                | -         |     0.72 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4227 | 2024-02-15 | Sharks         | W   | 0.082      | -            | -                | -                | -         |     1.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4228 | 2024-02-15 | Sharks         | W   | 0.081      | -            | -                | -                | -         |     1.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4251 | 2024-02-14 | Intense        | W   | 0.077      | -            | -                | -                | -         |     0.20 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4324 | 2024-02-12 | Flamengo       | W   | 0.061      | -            | -                | -                | -         |     0.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,031.48)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.895 | $30,000.00     | $26,850.00      |
| 2024-06-09 |      0.849 | $2,000.00      | $1,698.15       |
| 2024-05-19 |      0.708 | $2,000.00      | $1,416.67       |
| 2024-03-14 |      0.269 | $5,000.00      | $1,344.44       |
| 2024-02-25 |      0.149 | $25,000.00     | $3,722.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
