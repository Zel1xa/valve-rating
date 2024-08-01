### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1136.9<br />
<br />
Final Rank Value (1136.9) = Starting Rank Value (1038.5) + Head To Head Adjustments (98.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.523[<sup>1</sup>](#table2)
- Bounty Collected: 0.444[<sup>2</sup>](#table1)
- Opponent Network: 0.275[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.310<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1038.5
- 400 + ( ( 0.310 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1038.5


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
|          107 |       32 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.512 (0.231)    | 0 (0.000) |     6.27 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          106 |       33 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |       82 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      122 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      155 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -28.54 | arT, Lucaozy, nicks, vsm, zevy       |
|          102 |      197 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -14.59 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      201 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      205 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.02 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      228 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.86 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      233 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           97 |      271 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      274 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.87 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      304 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.30 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      311 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      314 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.34 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      320 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      345 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      365 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.300 (0.115)    | 0.801 (0.308)    | -         |    20.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      373 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -10.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      395 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      408 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |    10.14 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      431 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.37 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      434 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -10.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      440 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      477 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.572 (0.258)    | -         |     8.10 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      479 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.572 (0.258)    | -         |     8.67 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      491 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      548 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.089 (0.040)    | 0.738 (0.332)    | -         |     9.14 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      552 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.089 (0.040)    | 0.738 (0.332)    | -         |     9.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      661 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     4.20 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      667 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     4.38 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      894 | 2024-06-16 | paiN           | W   | 0.893      | 0.450        | 0.300 (0.120)    | 0.801 (0.322)    | -         |    20.04 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      919 | 2024-06-15 | inSanitY       | W   | 0.887      | -            | -                | -                | -         |     8.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      950 | 2024-06-14 | Sharks         | W   | 0.881      | -            | -                | -                | -         |    11.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |     1162 | 2024-06-08 | KRÜ            | W   | 0.841      | -            | -                | -                | -         |     7.63 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |     1247 | 2024-06-07 | Bounty Hunters | W   | 0.833      | -            | -                | -                | -         |     7.03 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1314 | 2024-06-06 | W7M            | W   | 0.826      | 0.450        | -                | 0.626 (0.233)    | -         |     5.83 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1356 | 2024-06-05 | paiN           | L   | 0.821      | -            | -                | -                | -         |    -6.71 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1409 | 2024-06-04 | 9z             | L   | 0.815      | -            | -                | -                | -         |    -7.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1735 | 2024-05-22 | BESTIA         | L   | 0.727      | -            | -                | -                | -         |   -12.65 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1738 | 2024-05-22 | BESTIA         | L   | 0.727      | -            | -                | -                | -         |   -13.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1825 | 2024-05-20 | RED Canids     | W   | 0.715      | 0.450        | 0.075 (0.024)    | 0.754 (0.243)    | -         |    11.80 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1829 | 2024-05-20 | RED Canids     | L   | 0.714      | -            | -                | -                | -         |   -10.89 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1895 | 2024-05-18 | 9z             | L   | 0.700      | -            | -                | -                | -         |    -8.45 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1930 | 2024-05-17 | Case           | W   | 0.694      | -            | -                | -                | -         |     5.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1964 | 2024-05-16 | RED Canids     | L   | 0.688      | -            | -                | -                | -         |   -11.93 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     2009 | 2024-05-15 | Smoke          | W   | 0.681      | -            | -                | -                | -         |     2.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     2010 | 2024-05-15 | Smoke          | W   | 0.681      | -            | -                | -                | -         |     3.04 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     2024 | 2024-05-15 | Imperial       | L   | 0.680      | -            | -                | -                | -         |    -5.52 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2080 | 2024-05-14 | Sharks         | W   | 0.674      | -            | -                | -                | -         |     7.31 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2093 | 2024-05-14 | ODDIK          | W   | 0.672      | 0.384        | 0.096 (0.025)    | -                | -         |     7.32 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2116 | 2024-05-13 | Hype           | W   | 0.666      | -            | -                | -                | -         |     4.78 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2142 | 2024-05-12 | Vikings KR     | W   | 0.659      | -            | -                | -                | -         |     3.73 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2203 | 2024-05-09 | paiN           | W   | 0.642      | 0.450        | 0.300 (0.087)    | 0.801 (0.232)    | -         |    16.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2208 | 2024-05-09 | paiN           | L   | 0.642      | -            | -                | -                | -         |    -3.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2694 | 2024-04-18 | paiN           | L   | 0.502      | -            | -                | -                | -         |    -2.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           51 |     2702 | 2024-04-18 | Imperial       | L   | 0.501      | -            | -                | -                | -         |    -3.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           50 |     2749 | 2024-04-17 | ODDIK          | W   | 0.495      | -            | -                | -                | -         |     5.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           49 |     2758 | 2024-04-17 | Solid          | W   | 0.494      | -            | -                | -                | -         |     3.88 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           48 |     2789 | 2024-04-16 | Hype           | W   | 0.488      | -            | -                | -                | -         |     3.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           47 |     2849 | 2024-04-13 | Galorys        | L   | 0.466      | -            | -                | -                | -         |   -10.33 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2916 | 2024-04-10 | Imperial       | W   | 0.448      | 0.450        | 0.239 (0.048)    | -                | -         |    10.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2919 | 2024-04-10 | Imperial       | L   | 0.448      | -            | -                | -                | -         |    -3.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2969 | 2024-04-09 | ODDIK          | W   | 0.441      | -            | -                | -                | -         |     5.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2974 | 2024-04-09 | ODDIK          | W   | 0.441      | -            | -                | -                | -         |     5.23 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     3010 | 2024-04-08 | ODDIK          | W   | 0.434      | -            | -                | -                | -         |     5.33 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     3060 | 2024-04-06 | BESTIA         | L   | 0.421      | -            | -                | -                | -         |    -8.16 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     3061 | 2024-04-06 | Solid          | W   | 0.421      | -            | -                | -                | -         |     3.62 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3076 | 2024-04-05 | MIBR           | L   | 0.415      | -            | -                | -                | -         |    -1.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3077 | 2024-04-05 | MIBR           | W   | 0.415      | 0.450        | 0.201 (0.038)    | -                | -         |    11.41 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3104 | 2024-04-04 | Corinthians    | W   | 0.408      | -            | -                | -                | -         |     0.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3110 | 2024-04-04 | Corinthians    | W   | 0.408      | -            | -                | -                | -         |     0.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3125 | 2024-04-04 | RED Canids     | L   | 0.406      | -            | -                | -                | -         |    -6.58 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3141 | 2024-04-03 | MIBR           | L   | 0.402      | -            | -                | -                | -         |    -1.64 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3153 | 2024-04-03 | BESTIA         | W   | 0.400      | -            | -                | -                | -         |     5.25 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3196 | 2024-04-02 | MIBR           | L   | 0.395      | -            | -                | -                | -         |    -1.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3200 | 2024-04-02 | BESTIA         | W   | 0.394      | -            | -                | -                | -         |     5.27 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3284 | 2024-03-27 | Galorys        | L   | 0.355      | -            | -                | -                | -         |    -8.02 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3291 | 2024-03-27 | Galorys        | W   | 0.355      | -            | -                | -                | -         |     3.19 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3531 | 2024-03-14 | adalYamigos    | W   | 0.268      | -            | -                | -                | -         |     0.72 | arT, chayJESUS, Lucaozy, PKL, zevy   |
|           27 |     3534 | 2024-03-14 | adalYamigos    | W   | 0.268      | -            | -                | -                | -         |     0.72 | arT, chayJESUS, Lucaozy, PKL, zevy   |
|           26 |     3565 | 2024-03-13 | RED Canids     | W   | 0.261      | -            | -                | -                | -         |     3.86 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3569 | 2024-03-13 | Intense        | W   | 0.261      | -            | -                | -                | -         |     0.63 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3582 | 2024-03-13 | Solid          | L   | 0.260      | -            | -                | -                | -         |    -5.87 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3609 | 2024-03-12 | MIBR           | W   | 0.254      | 0.435        | 0.201 (0.022)    | -                | -         |     7.00 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3641 | 2024-03-11 | Sharks         | W   | 0.246      | -            | -                | -                | -         |     3.12 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3685 | 2024-03-09 | Corinthians    | W   | 0.232      | -            | -                | -                | -         |     0.36 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3720 | 2024-03-07 | Case           | L   | 0.221      | -            | -                | -                | -         |    -4.64 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3745 | 2024-03-06 | Solid          | L   | 0.215      | -            | -                | -                | -         |    -4.83 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3746 | 2024-03-06 | Solid          | W   | 0.215      | -            | -                | -                | -         |     1.96 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3795 | 2024-03-05 | 9z             | W   | 0.207      | -            | -                | -                | -         |     4.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3796 | 2024-03-05 | 9z             | W   | 0.207      | -            | -                | -                | -         |     4.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3817 | 2024-03-04 | Case           | W   | 0.202      | -            | -                | -                | -         |     2.28 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3818 | 2024-03-04 | Case           | W   | 0.201      | -            | -                | -                | -         |     2.32 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     3979 | 2024-02-25 | Imperial       | W   | 0.147      | -            | -                | -                | -         |     3.66 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4009 | 2024-02-24 | Sharks         | W   | 0.141      | -            | -                | -                | -         |     1.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4064 | 2024-02-21 | W7M            | L   | 0.122      | -            | -                | -                | -         |    -2.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4069 | 2024-02-21 | W7M            | W   | 0.121      | -            | -                | -                | -         |     1.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4074 | 2024-02-21 | Solid          | W   | 0.120      | -            | -                | -                | -         |     1.21 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4102 | 2024-02-20 | Solid          | L   | 0.114      | -            | -                | -                | -         |    -2.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4199 | 2024-02-16 | 9z             | W   | 0.087      | -            | -                | -                | -         |     2.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4226 | 2024-02-15 | Imperial       | L   | 0.081      | -            | -                | -                | -         |    -0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4228 | 2024-02-15 | W7M            | W   | 0.081      | -            | -                | -                | -         |     0.71 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4233 | 2024-02-15 | Sharks         | W   | 0.080      | -            | -                | -                | -         |     1.03 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4234 | 2024-02-15 | Sharks         | W   | 0.080      | -            | -                | -                | -         |     1.03 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4257 | 2024-02-14 | Intense        | W   | 0.075      | -            | -                | -                | -         |     0.20 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4330 | 2024-02-12 | Flamengo       | W   | 0.059      | -            | -                | -                | -         |     0.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,924.81)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.893 | $30,000.00     | $26,800.00      |
| 2024-06-09 |      0.847 | $2,000.00      | $1,694.81       |
| 2024-05-19 |      0.707 | $2,000.00      | $1,413.33       |
| 2024-03-14 |      0.267 | $5,000.00      | $1,336.11       |
| 2024-02-25 |      0.147 | $25,000.00     | $3,680.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
