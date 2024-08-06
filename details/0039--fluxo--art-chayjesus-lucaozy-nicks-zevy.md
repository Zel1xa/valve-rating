### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1130.4<br />
<br />
Final Rank Value (1130.4) = Starting Rank Value (1045.2) + Head To Head Adjustments (85.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.524[<sup>1</sup>](#table2)
- Bounty Collected: 0.448[<sup>2</sup>](#table1)
- Opponent Network: 0.286[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1045.2
- 400 + ( ( 0.314 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1045.2


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
|          106 |       90 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |      107 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.85 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |      135 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.12 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |      139 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.793 (0.294)    | 0 (0.000) |     9.85 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      175 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.486 (0.219)    | 0 (0.000) |     5.68 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      179 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.99 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      228 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.50 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      268 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.56 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      301 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -26.99 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      343 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      347 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.79 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      351 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.39 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      374 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.23 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      379 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      417 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      420 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.46 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      450 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.29 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      457 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.45 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      460 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.43 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      466 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.06 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      490 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.66 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      510 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.324 (0.124)    | 0.857 (0.329)    | -         |    22.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      517 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      538 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.61 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      551 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.23 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      573 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.15 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      576 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.79 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      582 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.68 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      616 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.05 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      618 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.62 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      628 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      684 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.793 (0.357)    | -         |     9.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      689 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.793 (0.357)    | -         |    10.23 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      792 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      797 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.90 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |     1024 | 2024-06-16 | paiN           | W   | 0.862      | 0.450        | 0.324 (0.126)    | 0.857 (0.333)    | -         |    21.10 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |     1052 | 2024-06-15 | inSanitY       | W   | 0.856      | -            | -                | -                | -         |     8.89 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1088 | 2024-06-14 | Sharks         | W   | 0.849      | -            | -                | -                | -         |    11.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1298 | 2024-06-08 | KRÜ            | W   | 0.810      | -            | -                | -                | -         |     6.31 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1376 | 2024-06-07 | Bounty Hunters | W   | 0.802      | -            | -                | -                | -         |     6.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1441 | 2024-06-06 | W7M            | W   | 0.795      | -            | -                | -                | -         |     4.21 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1481 | 2024-06-05 | paiN           | L   | 0.790      | -            | -                | -                | -         |    -4.39 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1533 | 2024-06-04 | 9z             | L   | 0.783      | -            | -                | -                | -         |    -2.39 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1856 | 2024-05-22 | BESTIA         | L   | 0.696      | -            | -                | -                | -         |   -12.10 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1859 | 2024-05-22 | BESTIA         | L   | 0.696      | -            | -                | -                | -         |   -12.85 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1930 | 2024-05-20 | RED Canids     | W   | 0.684      | 0.450        | 0.076 (0.024)    | 0.748 (0.230)    | -         |    12.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1933 | 2024-05-20 | RED Canids     | L   | 0.683      | -            | -                | -                | -         |    -9.15 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     1991 | 2024-05-18 | 9z             | L   | 0.669      | -            | -                | -                | -         |    -2.21 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     2025 | 2024-05-17 | Case           | W   | 0.663      | -            | -                | -                | -         |     5.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     2059 | 2024-05-16 | RED Canids     | L   | 0.656      | -            | -                | -                | -         |    -9.97 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2104 | 2024-05-15 | Smoke          | W   | 0.650      | -            | -                | -                | -         |     2.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2105 | 2024-05-15 | Smoke          | W   | 0.650      | -            | -                | -                | -         |     2.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2119 | 2024-05-15 | Imperial       | L   | 0.649      | -            | -                | -                | -         |    -5.72 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2169 | 2024-05-14 | Sharks         | W   | 0.643      | -            | -                | -                | -         |     7.13 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2182 | 2024-05-14 | ODDIK          | W   | 0.641      | 0.384        | 0.099 (0.024)    | -                | -         |     6.87 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2202 | 2024-05-13 | Hype           | W   | 0.635      | -            | -                | -                | -         |     4.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2229 | 2024-05-12 | Vikings KR     | W   | 0.628      | -            | -                | -                | -         |     3.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2289 | 2024-05-09 | paiN           | W   | 0.611      | 0.450        | 0.324 (0.089)    | 0.857 (0.236)    | -         |    16.35 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2294 | 2024-05-09 | paiN           | L   | 0.611      | -            | -                | -                | -         |    -2.81 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2768 | 2024-04-18 | paiN           | L   | 0.471      | -            | -                | -                | -         |    -2.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2775 | 2024-04-18 | Imperial       | L   | 0.470      | -            | -                | -                | -         |    -3.58 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2822 | 2024-04-17 | ODDIK          | W   | 0.463      | -            | -                | -                | -         |     4.97 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2830 | 2024-04-17 | Solid          | W   | 0.463      | -            | -                | -                | -         |     3.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2861 | 2024-04-16 | Hype           | W   | 0.457      | -            | -                | -                | -         |     3.73 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2920 | 2024-04-13 | Galorys        | L   | 0.434      | -            | -                | -                | -         |    -9.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2986 | 2024-04-10 | Imperial       | W   | 0.417      | 0.450        | 0.233 (0.044)    | -                | -         |    10.09 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     2989 | 2024-04-10 | Imperial       | L   | 0.417      | -            | -                | -                | -         |    -3.05 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     3039 | 2024-04-09 | ODDIK          | W   | 0.410      | -            | -                | -                | -         |     4.53 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     3044 | 2024-04-09 | ODDIK          | W   | 0.410      | -            | -                | -                | -         |     4.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3080 | 2024-04-08 | ODDIK          | W   | 0.403      | -            | -                | -                | -         |     4.75 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3130 | 2024-04-06 | BESTIA         | L   | 0.390      | -            | -                | -                | -         |    -7.41 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3131 | 2024-04-06 | Solid          | W   | 0.389      | -            | -                | -                | -         |     3.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3146 | 2024-04-05 | MIBR           | L   | 0.384      | -            | -                | -                | -         |    -1.58 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3147 | 2024-04-05 | MIBR           | W   | 0.383      | 0.450        | 0.208 (0.036)    | -                | -         |    10.63 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3174 | 2024-04-04 | Corinthians    | W   | 0.377      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3180 | 2024-04-04 | Corinthians    | W   | 0.377      | -            | -                | -                | -         |     0.55 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3194 | 2024-04-04 | RED Canids     | L   | 0.375      | -            | -                | -                | -         |    -5.25 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3210 | 2024-04-03 | MIBR           | L   | 0.370      | -            | -                | -                | -         |    -1.44 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3221 | 2024-04-03 | BESTIA         | W   | 0.369      | -            | -                | -                | -         |     5.00 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3258 | 2024-04-02 | MIBR           | L   | 0.364      | -            | -                | -                | -         |    -1.40 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3262 | 2024-04-02 | BESTIA         | W   | 0.363      | -            | -                | -                | -         |     5.01 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3346 | 2024-03-27 | Galorys        | L   | 0.324      | -            | -                | -                | -         |    -7.21 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3352 | 2024-03-27 | Galorys        | W   | 0.324      | -            | -                | -                | -         |     3.03 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3621 | 2024-03-13 | Intense        | W   | 0.230      | -            | -                | -                | -         |     1.14 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3635 | 2024-03-13 | Solid          | L   | 0.229      | -            | -                | -                | -         |    -5.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3661 | 2024-03-12 | MIBR           | W   | 0.223      | -            | -                | -                | -         |     6.17 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3693 | 2024-03-11 | Sharks         | W   | 0.214      | -            | -                | -                | -         |     2.69 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3736 | 2024-03-09 | Corinthians    | W   | 0.201      | -            | -                | -                | -         |     0.30 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3771 | 2024-03-07 | Case           | L   | 0.189      | -            | -                | -                | -         |    -4.00 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3796 | 2024-03-06 | Solid          | L   | 0.184      | -            | -                | -                | -         |    -4.12 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3797 | 2024-03-06 | Solid          | W   | 0.184      | -            | -                | -                | -         |     1.69 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3863 | 2024-03-04 | Case           | W   | 0.171      | -            | -                | -                | -         |     1.84 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3864 | 2024-03-04 | Case           | W   | 0.170      | -            | -                | -                | -         |     1.86 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     4021 | 2024-02-25 | Imperial       | W   | 0.116      | -            | -                | -                | -         |     2.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     4051 | 2024-02-24 | Sharks         | W   | 0.109      | -            | -                | -                | -         |     1.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4101 | 2024-02-21 | W7M            | L   | 0.091      | -            | -                | -                | -         |    -2.18 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4106 | 2024-02-21 | W7M            | W   | 0.090      | -            | -                | -                | -         |     0.68 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4110 | 2024-02-21 | Solid          | W   | 0.089      | -            | -                | -                | -         |     0.86 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4138 | 2024-02-20 | Solid          | L   | 0.083      | -            | -                | -                | -         |    -1.82 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4235 | 2024-02-16 | 9z             | W   | 0.056      | -            | -                | -                | -         |     1.67 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4262 | 2024-02-15 | Imperial       | L   | 0.050      | -            | -                | -                | -         |    -0.37 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4264 | 2024-02-15 | W7M            | W   | 0.050      | -            | -                | -                | -         |     0.38 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4269 | 2024-02-15 | Sharks         | W   | 0.049      | -            | -                | -                | -         |     0.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4270 | 2024-02-15 | Sharks         | W   | 0.049      | -            | -                | -                | -         |     0.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4293 | 2024-02-14 | Intense        | W   | 0.044      | -            | -                | -                | -         |     0.23 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4358 | 2024-02-12 | Flamengo       | W   | 0.028      | -            | -                | -                | -         |     0.04 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39,433.70)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.862 | $30,000.00     | $25,866.67      |
| 2024-06-09 |      0.816 | $2,000.00      | $1,632.59       |
| 2024-05-19 |      0.676 | $2,000.00      | $1,351.11       |
| 2024-03-14 |      0.236 | $5,000.00      | $1,180.56       |
| 2024-02-25 |      0.116 | $25,000.00     | $2,902.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
