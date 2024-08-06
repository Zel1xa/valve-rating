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
|          106 |      103 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |      120 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      148 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      152 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.776 (0.287)    | 0 (0.000) |     9.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      188 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | 0 (0.000) |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      192 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.00 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      241 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      281 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.57 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      314 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -26.98 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      356 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      360 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      364 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      387 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      392 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      430 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      433 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      463 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.29 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      470 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      473 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      479 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      503 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      523 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.324 (0.124)    | 0.839 (0.322)    | -         |    22.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      530 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      551 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.61 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      564 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      586 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.16 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      589 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      595 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      629 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.05 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      631 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.63 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      641 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.97 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      697 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |     9.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      702 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.776 (0.349)    | -         |    10.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      805 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      810 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.92 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1037 | 2024-06-16 | paiN           | W   | 0.861      | 0.450        | 0.324 (0.125)    | 0.839 (0.325)    | -         |    21.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1065 | 2024-06-15 | inSanitY       | W   | 0.855      | -            | -                | -                | -         |     8.88 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1101 | 2024-06-14 | Sharks         | W   | 0.848      | -            | -                | -                | -         |    11.45 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1311 | 2024-06-08 | KRÜ            | W   | 0.809      | -            | -                | -                | -         |     6.30 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1389 | 2024-06-07 | Bounty Hunters | W   | 0.801      | -            | -                | -                | -         |     6.69 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1454 | 2024-06-06 | W7M            | W   | 0.794      | -            | -                | -                | -         |     4.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1494 | 2024-06-05 | paiN           | L   | 0.789      | -            | -                | -                | -         |    -4.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1546 | 2024-06-04 | 9z             | L   | 0.782      | -            | -                | -                | -         |    -2.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1869 | 2024-05-22 | BESTIA         | L   | 0.695      | -            | -                | -                | -         |   -12.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1872 | 2024-05-22 | BESTIA         | L   | 0.694      | -            | -                | -                | -         |   -12.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1943 | 2024-05-20 | RED Canids     | W   | 0.682      | 0.450        | 0.076 (0.023)    | 0.732 (0.225)    | -         |    12.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1946 | 2024-05-20 | RED Canids     | L   | 0.682      | -            | -                | -                | -         |    -9.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     2004 | 2024-05-18 | 9z             | L   | 0.667      | -            | -                | -                | -         |    -2.19 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2038 | 2024-05-17 | Case           | W   | 0.662      | -            | -                | -                | -         |     5.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2072 | 2024-05-16 | RED Canids     | L   | 0.655      | -            | -                | -                | -         |    -9.94 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2117 | 2024-05-15 | Smoke          | W   | 0.649      | -            | -                | -                | -         |     2.08 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2118 | 2024-05-15 | Smoke          | W   | 0.649      | -            | -                | -                | -         |     2.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2132 | 2024-05-15 | Imperial       | L   | 0.647      | -            | -                | -                | -         |    -5.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2182 | 2024-05-14 | Sharks         | W   | 0.641      | -            | -                | -                | -         |     7.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2195 | 2024-05-14 | ODDIK          | W   | 0.640      | 0.384        | 0.099 (0.024)    | -                | -         |     6.87 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2215 | 2024-05-13 | Hype           | W   | 0.634      | -            | -                | -                | -         |     4.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2242 | 2024-05-12 | Vikings KR     | W   | 0.627      | -            | -                | -                | -         |     3.76 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2302 | 2024-05-09 | paiN           | W   | 0.609      | 0.450        | 0.324 (0.089)    | 0.839 (0.230)    | -         |    16.31 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2307 | 2024-05-09 | paiN           | L   | 0.609      | -            | -                | -                | -         |    -2.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2781 | 2024-04-18 | paiN           | L   | 0.470      | -            | -                | -                | -         |    -2.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2788 | 2024-04-18 | Imperial       | L   | 0.468      | -            | -                | -                | -         |    -3.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2835 | 2024-04-17 | ODDIK          | W   | 0.462      | -            | -                | -                | -         |     4.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2843 | 2024-04-17 | Solid          | W   | 0.462      | -            | -                | -                | -         |     3.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2874 | 2024-04-16 | Hype           | W   | 0.456      | -            | -                | -                | -         |     3.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2933 | 2024-04-13 | Galorys        | L   | 0.433      | -            | -                | -                | -         |    -9.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2999 | 2024-04-10 | Imperial       | W   | 0.416      | 0.450        | 0.233 (0.044)    | -                | -         |    10.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     3002 | 2024-04-10 | Imperial       | L   | 0.415      | -            | -                | -                | -         |    -3.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3052 | 2024-04-09 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.52 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3057 | 2024-04-09 | ODDIK          | W   | 0.409      | -            | -                | -                | -         |     4.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3093 | 2024-04-08 | ODDIK          | W   | 0.401      | -            | -                | -                | -         |     4.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3143 | 2024-04-06 | BESTIA         | L   | 0.389      | -            | -                | -                | -         |    -7.38 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3144 | 2024-04-06 | Solid          | W   | 0.388      | -            | -                | -                | -         |     3.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3159 | 2024-04-05 | MIBR           | L   | 0.383      | -            | -                | -                | -         |    -1.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3160 | 2024-04-05 | MIBR           | W   | 0.382      | 0.450        | 0.208 (0.036)    | -                | -         |    10.59 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3187 | 2024-04-04 | Corinthians    | W   | 0.376      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3193 | 2024-04-04 | Corinthians    | W   | 0.375      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3207 | 2024-04-04 | RED Canids     | L   | 0.373      | -            | -                | -                | -         |    -5.23 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3223 | 2024-04-03 | MIBR           | L   | 0.369      | -            | -                | -                | -         |    -1.43 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3234 | 2024-04-03 | BESTIA         | W   | 0.368      | -            | -                | -                | -         |     4.98 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3271 | 2024-04-02 | MIBR           | L   | 0.362      | -            | -                | -                | -         |    -1.39 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3275 | 2024-04-02 | BESTIA         | W   | 0.361      | -            | -                | -                | -         |     4.99 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3359 | 2024-03-27 | Galorys        | L   | 0.323      | -            | -                | -                | -         |    -7.17 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3365 | 2024-03-27 | Galorys        | W   | 0.322      | -            | -                | -                | -         |     3.02 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3634 | 2024-03-13 | Intense        | W   | 0.228      | -            | -                | -                | -         |     1.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3648 | 2024-03-13 | Solid          | L   | 0.227      | -            | -                | -                | -         |    -5.12 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3674 | 2024-03-12 | MIBR           | W   | 0.221      | -            | -                | -                | -         |     6.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3706 | 2024-03-11 | Sharks         | W   | 0.213      | -            | -                | -                | -         |     2.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3749 | 2024-03-09 | Corinthians    | W   | 0.200      | -            | -                | -                | -         |     0.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3784 | 2024-03-07 | Case           | L   | 0.188      | -            | -                | -                | -         |    -3.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3809 | 2024-03-06 | Solid          | L   | 0.183      | -            | -                | -                | -         |    -4.08 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3810 | 2024-03-06 | Solid          | W   | 0.182      | -            | -                | -                | -         |     1.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3876 | 2024-03-04 | Case           | W   | 0.169      | -            | -                | -                | -         |     1.83 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3877 | 2024-03-04 | Case           | W   | 0.169      | -            | -                | -                | -         |     1.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     4034 | 2024-02-25 | Imperial       | W   | 0.115      | -            | -                | -                | -         |     2.77 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4064 | 2024-02-24 | Sharks         | W   | 0.108      | -            | -                | -                | -         |     1.35 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4114 | 2024-02-21 | W7M            | L   | 0.089      | -            | -                | -                | -         |    -2.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4119 | 2024-02-21 | W7M            | W   | 0.089      | -            | -                | -                | -         |     0.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4123 | 2024-02-21 | Solid          | W   | 0.087      | -            | -                | -                | -         |     0.84 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4151 | 2024-02-20 | Solid          | L   | 0.082      | -            | -                | -                | -         |    -1.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4248 | 2024-02-16 | 9z             | W   | 0.055      | -            | -                | -                | -         |     1.63 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4275 | 2024-02-15 | Imperial       | L   | 0.049      | -            | -                | -                | -         |    -0.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4277 | 2024-02-15 | W7M            | W   | 0.048      | -            | -                | -                | -         |     0.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4282 | 2024-02-15 | Sharks         | W   | 0.048      | -            | -                | -                | -         |     0.59 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4283 | 2024-02-15 | Sharks         | W   | 0.047      | -            | -                | -                | -         |     0.59 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4306 | 2024-02-14 | Intense        | W   | 0.043      | -            | -                | -                | -         |     0.22 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4371 | 2024-02-12 | Flamengo       | W   | 0.026      | -            | -                | -                | -         |     0.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,344.81)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.861 | $30,000.00     | $25,825.00      |
| 2024-06-09 |      0.815 | $2,000.00      | $1,629.81       |
| 2024-05-19 |      0.674 | $2,000.00      | $1,348.33       |
| 2024-03-14 |      0.235 | $5,000.00      | $1,173.61       |
| 2024-02-25 |      0.115 | $25,000.00     | $2,868.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
