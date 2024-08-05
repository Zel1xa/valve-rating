### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1135.9<br />
<br />
Final Rank Value (1135.9) = Starting Rank Value (1043.0) + Head To Head Adjustments (92.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.270[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.312<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1043.0
- 400 + ( ( 0.312 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1043.0


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
|          100 |       47 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |       87 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.45 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      120 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -27.11 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      162 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      166 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      170 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.60 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      193 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.09 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      198 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.40 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      236 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.34 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      239 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      269 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.22 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      276 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.27 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      279 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      285 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.89 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      309 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.74 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      329 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.333 (0.128)    | 0.797 (0.306)    | 0 (0.000) |    22.74 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      336 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.27 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      357 | 2024-07-20 | Sharks         | W   | 1.000      | 0.384        | -                | 0.558 (0.215)    | -         |     7.52 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      370 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.04 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      392 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.02 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      395 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.56 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      401 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      435 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     7.95 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      437 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      447 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.74 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      503 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.731 (0.329)    | -         |     9.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      508 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.731 (0.329)    | -         |    10.12 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      611 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.51 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      616 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.63 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |      843 | 2024-06-16 | paiN           | W   | 0.899      | 0.450        | 0.333 (0.135)    | 0.797 (0.322)    | -         |    22.20 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |      871 | 2024-06-15 | inSanitY       | W   | 0.893      | -            | -                | -                | -         |     9.20 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |      907 | 2024-06-14 | Sharks         | W   | 0.887      | 0.450        | -                | 0.558 (0.223)    | -         |    11.97 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1117 | 2024-06-08 | KRÜ            | W   | 0.847      | -            | -                | -                | -         |     6.27 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1195 | 2024-06-07 | Bounty Hunters | W   | 0.839      | -            | -                | -                | -         |     6.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1260 | 2024-06-06 | W7M            | W   | 0.832      | -            | -                | -                | -         |     4.26 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1300 | 2024-06-05 | paiN           | L   | 0.827      | -            | -                | -                | -         |    -4.33 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1352 | 2024-06-04 | 9z             | L   | 0.821      | -            | -                | -                | -         |    -2.40 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1675 | 2024-05-22 | BESTIA         | L   | 0.733      | -            | -                | -                | -         |   -12.74 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1678 | 2024-05-22 | BESTIA         | L   | 0.733      | -            | -                | -                | -         |   -13.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1749 | 2024-05-20 | RED Canids     | W   | 0.721      | 0.450        | 0.079 (0.026)    | 0.738 (0.239)    | -         |    13.35 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1752 | 2024-05-20 | RED Canids     | L   | 0.720      | -            | -                | -                | -         |    -9.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     1810 | 2024-05-18 | 9z             | L   | 0.706      | -            | -                | -                | -         |    -2.20 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     1844 | 2024-05-17 | Case           | W   | 0.700      | -            | -                | -                | -         |     5.68 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     1878 | 2024-05-16 | RED Canids     | L   | 0.694      | -            | -                | -                | -         |   -10.36 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     1923 | 2024-05-15 | Smoke          | W   | 0.687      | -            | -                | -                | -         |     2.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     1924 | 2024-05-15 | Smoke          | W   | 0.687      | -            | -                | -                | -         |     2.18 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     1938 | 2024-05-15 | Imperial       | L   | 0.686      | -            | -                | -                | -         |    -5.55 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     1988 | 2024-05-14 | Sharks         | W   | 0.680      | -            | -                | -                | -         |     7.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2001 | 2024-05-14 | ODDIK          | W   | 0.679      | 0.384        | 0.097 (0.025)    | -                | -         |     7.15 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2021 | 2024-05-13 | Hype           | W   | 0.672      | -            | -                | -                | -         |     4.68 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2048 | 2024-05-12 | Vikings KR     | W   | 0.665      | -            | -                | -                | -         |     3.85 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2108 | 2024-05-09 | paiN           | W   | 0.648      | 0.450        | 0.333 (0.097)    | 0.797 (0.232)    | -         |    17.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2113 | 2024-05-09 | paiN           | L   | 0.648      | -            | -                | -                | -         |    -2.73 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2587 | 2024-04-18 | paiN           | L   | 0.508      | -            | -                | -                | -         |    -2.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2594 | 2024-04-18 | Imperial       | L   | 0.507      | -            | -                | -                | -         |    -3.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2641 | 2024-04-17 | ODDIK          | W   | 0.501      | -            | -                | -                | -         |     5.28 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2649 | 2024-04-17 | Solid          | W   | 0.500      | -            | -                | -                | -         |     4.01 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2680 | 2024-04-16 | Hype           | W   | 0.494      | -            | -                | -                | -         |     3.94 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2739 | 2024-04-13 | Galorys        | L   | 0.472      | -            | -                | -                | -         |   -10.72 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2805 | 2024-04-10 | Imperial       | W   | 0.454      | 0.450        | 0.243 (0.050)    | -                | -         |    11.38 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     2808 | 2024-04-10 | Imperial       | L   | 0.454      | -            | -                | -                | -         |    -2.91 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     2858 | 2024-04-09 | ODDIK          | W   | 0.447      | -            | -                | -                | -         |     4.87 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     2863 | 2024-04-09 | ODDIK          | W   | 0.447      | -            | -                | -                | -         |     5.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     2899 | 2024-04-08 | ODDIK          | W   | 0.440      | -            | -                | -                | -         |     5.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     2949 | 2024-04-06 | BESTIA         | L   | 0.427      | -            | -                | -                | -         |    -8.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     2950 | 2024-04-06 | Solid          | W   | 0.427      | -            | -                | -                | -         |     3.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     2965 | 2024-04-05 | MIBR           | L   | 0.421      | -            | -                | -                | -         |    -1.64 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     2966 | 2024-04-05 | MIBR           | W   | 0.421      | 0.450        | 0.200 (0.038)    | -                | -         |    11.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     2993 | 2024-04-04 | Corinthians    | W   | 0.414      | -            | -                | -                | -         |     0.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     2999 | 2024-04-04 | Corinthians    | W   | 0.414      | -            | -                | -                | -         |     0.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3013 | 2024-04-04 | RED Canids     | L   | 0.412      | -            | -                | -                | -         |    -5.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3029 | 2024-04-03 | MIBR           | L   | 0.408      | -            | -                | -                | -         |    -1.48 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3040 | 2024-04-03 | BESTIA         | W   | 0.406      | -            | -                | -                | -         |     5.49 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3077 | 2024-04-02 | MIBR           | L   | 0.401      | -            | -                | -                | -         |    -1.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3081 | 2024-04-02 | BESTIA         | W   | 0.400      | -            | -                | -                | -         |     5.53 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3165 | 2024-03-27 | Galorys        | L   | 0.361      | -            | -                | -                | -         |    -8.10 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3171 | 2024-03-27 | Galorys        | W   | 0.361      | -            | -                | -                | -         |     3.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3440 | 2024-03-13 | Intense        | W   | 0.267      | -            | -                | -                | -         |     1.31 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3454 | 2024-03-13 | Solid          | L   | 0.266      | -            | -                | -                | -         |    -6.02 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3480 | 2024-03-12 | MIBR           | W   | 0.260      | 0.435        | 0.200 (0.023)    | -                | -         |     7.27 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3512 | 2024-03-11 | Sharks         | W   | 0.252      | -            | -                | -                | -         |     3.17 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3555 | 2024-03-09 | Corinthians    | W   | 0.238      | -            | -                | -                | -         |     0.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3590 | 2024-03-07 | Case           | L   | 0.227      | -            | -                | -                | -         |    -4.76 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3615 | 2024-03-06 | Solid          | L   | 0.221      | -            | -                | -                | -         |    -4.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3616 | 2024-03-06 | Solid          | W   | 0.221      | -            | -                | -                | -         |     2.01 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3682 | 2024-03-04 | Case           | W   | 0.208      | -            | -                | -                | -         |     2.27 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3683 | 2024-03-04 | Case           | W   | 0.207      | -            | -                | -                | -         |     2.31 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     3840 | 2024-02-25 | Imperial       | W   | 0.153      | -            | -                | -                | -         |     3.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     3870 | 2024-02-24 | Sharks         | W   | 0.147      | -            | -                | -                | -         |     1.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     3920 | 2024-02-21 | W7M            | L   | 0.128      | -            | -                | -                | -         |    -3.07 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     3925 | 2024-02-21 | W7M            | W   | 0.127      | -            | -                | -                | -         |     0.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     3929 | 2024-02-21 | Solid          | W   | 0.126      | -            | -                | -                | -         |     1.22 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     3957 | 2024-02-20 | Solid          | L   | 0.120      | -            | -                | -                | -         |    -2.65 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4054 | 2024-02-16 | 9z             | W   | 0.093      | -            | -                | -                | -         |     2.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4081 | 2024-02-15 | Imperial       | L   | 0.087      | -            | -                | -                | -         |    -0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4083 | 2024-02-15 | W7M            | W   | 0.087      | -            | -                | -                | -         |     0.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4088 | 2024-02-15 | Sharks         | W   | 0.086      | -            | -                | -                | -         |     1.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4089 | 2024-02-15 | Sharks         | W   | 0.086      | -            | -                | -                | -         |     1.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4112 | 2024-02-14 | Intense        | W   | 0.081      | -            | -                | -                | -         |     0.42 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4177 | 2024-02-12 | Flamengo       | W   | 0.065      | -            | -                | -                | -         |     0.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,809.11)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.899 | $30,000.00     | $26,980.14      |
| 2024-06-09 |      0.853 | $2,000.00      | $1,706.82       |
| 2024-05-19 |      0.713 | $2,000.00      | $1,425.34       |
| 2024-03-14 |      0.273 | $5,000.00      | $1,366.13       |
| 2024-02-25 |      0.153 | $25,000.00     | $3,830.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
