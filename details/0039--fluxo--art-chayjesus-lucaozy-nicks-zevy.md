### Roster Details<br />
Team Name: Fluxo<br />
Roster: arT, chayJESUS, Lucaozy, nicks, zevy<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1132.6<br />
<br />
Final Rank Value (1132.6) = Starting Rank Value (1046.2) + Head To Head Adjustments (86.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.525[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.290[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1046.2
- 400 + ( ( 0.316 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1046.2


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
|          106 |       28 | 2024-08-02 | Legacy         | L   | 1.000      | -            | -                | -                | -         |   -17.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          105 |       45 | 2024-08-02 | MIBR           | L   | 1.000      | -            | -                | -                | -         |    -7.84 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          104 |       73 | 2024-08-01 | Intense        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.09 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          103 |       77 | 2024-08-01 | BESTIA         | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | 0 (0.000) |     9.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          102 |      111 | 2024-07-31 | Hype           | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | 0 (0.000) |     5.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          101 |      115 | 2024-07-31 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.95 | arT, chayJESUS, Lucaozy, nicks, zevy |
|          100 |      164 | 2024-07-30 | Bounty Hunters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           99 |      205 | 2024-07-29 | Vikings KR     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           98 |      237 | 2024-07-28 | Intense        | L   | 1.000      | -            | -                | -                | -         |   -27.04 | arT, Lucaozy, nicks, vsm, zevy       |
|           97 |      279 | 2024-07-26 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -13.90 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           96 |      283 | 2024-07-26 | W7M            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.74 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           95 |      288 | 2024-07-26 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -24.44 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           94 |      310 | 2024-07-25 | Hype           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.18 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           93 |      315 | 2024-07-25 | Imperium Nexus | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           92 |      353 | 2024-07-24 | RED Canids     | L   | 1.000      | -            | -                | -                | -         |   -15.47 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           91 |      356 | 2024-07-24 | Solid          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.41 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           90 |      386 | 2024-07-23 | BESTIA         | W   | 1.000      | -            | -                | -                | -         |     9.25 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           89 |      393 | 2024-07-23 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.40 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           88 |      396 | 2024-07-23 | Case           | L   | 1.000      | -            | -                | -                | -         |   -25.49 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           87 |      403 | 2024-07-23 | Solid          | W   | 1.000      | -            | -                | -                | -         |     5.01 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           86 |      426 | 2024-07-22 | BESTIA         | L   | 1.000      | -            | -                | -                | -         |   -23.70 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           85 |      446 | 2024-07-21 | paiN           | W   | 1.000      | 0.384        | 0.327 (0.126)    | 0.866 (0.333)    | -         |    22.55 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           84 |      453 | 2024-07-21 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           83 |      474 | 2024-07-20 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     7.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           82 |      487 | 2024-07-20 | ODDIK          | W   | 1.000      | -            | -                | -                | -         |     9.17 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           81 |      509 | 2024-07-19 | Vikings KR     | W   | 1.000      | -            | -                | -                | -         |     4.11 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           80 |      512 | 2024-07-19 | paiN           | L   | 1.000      | -            | -                | -                | -         |    -8.77 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           79 |      518 | 2024-07-19 | Case           | W   | 1.000      | -            | -                | -                | -         |     5.61 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           78 |      552 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.01 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           77 |      554 | 2024-07-18 | Sharks         | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.58 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           76 |      567 | 2024-07-18 | Galorys        | W   | 1.000      | -            | -                | -                | -         |     3.90 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           75 |      620 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.360)    | -         |     9.43 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           74 |      625 | 2024-07-17 | BESTIA         | W   | 1.000      | 0.450        | 0.095 (0.043)    | 0.801 (0.360)    | -         |    10.17 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           73 |      728 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.68 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           72 |      733 | 2024-07-15 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     3.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           71 |      960 | 2024-06-16 | paiN           | W   | 0.876      | 0.450        | 0.327 (0.129)    | 0.866 (0.341)    | -         |    21.43 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           70 |      988 | 2024-06-15 | inSanitY       | W   | 0.869      | -            | -                | -                | -         |     9.01 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           69 |     1024 | 2024-06-14 | Sharks         | W   | 0.863      | -            | -                | -                | -         |    11.64 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           68 |     1234 | 2024-06-08 | KRÜ            | W   | 0.824      | -            | -                | -                | -         |     6.36 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           67 |     1312 | 2024-06-07 | Bounty Hunters | W   | 0.815      | -            | -                | -                | -         |     6.76 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           66 |     1377 | 2024-06-06 | W7M            | W   | 0.809      | -            | -                | -                | -         |     4.23 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           65 |     1417 | 2024-06-05 | paiN           | L   | 0.803      | -            | -                | -                | -         |    -4.42 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           64 |     1469 | 2024-06-04 | 9z             | L   | 0.797      | -            | -                | -                | -         |    -2.48 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           63 |     1792 | 2024-05-22 | BESTIA         | L   | 0.709      | -            | -                | -                | -         |   -12.35 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           62 |     1795 | 2024-05-22 | BESTIA         | L   | 0.709      | -            | -                | -                | -         |   -13.14 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           61 |     1866 | 2024-05-20 | RED Canids     | W   | 0.697      | 0.450        | 0.077 (0.024)    | 0.743 (0.233)    | -         |    12.76 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           60 |     1869 | 2024-05-20 | RED Canids     | L   | 0.697      | -            | -                | -                | -         |    -9.29 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           59 |     1927 | 2024-05-18 | 9z             | L   | 0.682      | -            | -                | -                | -         |    -2.28 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           58 |     1961 | 2024-05-17 | Case           | W   | 0.676      | -            | -                | -                | -         |     5.53 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           57 |     1995 | 2024-05-16 | RED Canids     | L   | 0.670      | -            | -                | -                | -         |   -10.15 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           56 |     2040 | 2024-05-15 | Smoke          | W   | 0.664      | -            | -                | -                | -         |     2.07 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           55 |     2041 | 2024-05-15 | Smoke          | W   | 0.663      | -            | -                | -                | -         |     2.12 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           54 |     2055 | 2024-05-15 | Imperial       | L   | 0.662      | -            | -                | -                | -         |    -5.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           53 |     2105 | 2024-05-14 | Sharks         | W   | 0.656      | -            | -                | -                | -         |     7.24 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           52 |     2118 | 2024-05-14 | ODDIK          | W   | 0.655      | 0.384        | 0.098 (0.025)    | -                | -         |     6.96 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           51 |     2138 | 2024-05-13 | Hype           | W   | 0.649      | -            | -                | -                | -         |     4.61 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           50 |     2165 | 2024-05-12 | Vikings KR     | W   | 0.641      | -            | -                | -                | -         |     3.79 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           49 |     2225 | 2024-05-09 | paiN           | W   | 0.624      | 0.450        | 0.327 (0.092)    | 0.866 (0.243)    | -         |    16.75 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           48 |     2230 | 2024-05-09 | paiN           | L   | 0.624      | -            | -                | -                | -         |    -2.82 | arT, chayJESUS, Lucaozy, nicks, zevy |
|           47 |     2704 | 2024-04-18 | paiN           | L   | 0.484      | -            | -                | -                | -         |    -2.16 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           46 |     2711 | 2024-04-18 | Imperial       | L   | 0.483      | -            | -                | -                | -         |    -3.60 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           45 |     2758 | 2024-04-17 | ODDIK          | W   | 0.477      | -            | -                | -                | -         |     5.07 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           44 |     2766 | 2024-04-17 | Solid          | W   | 0.476      | -            | -                | -                | -         |     3.87 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           43 |     2797 | 2024-04-16 | Hype           | W   | 0.471      | -            | -                | -                | -         |     3.79 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           42 |     2856 | 2024-04-13 | Galorys        | L   | 0.448      | -            | -                | -                | -         |   -10.12 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           41 |     2922 | 2024-04-10 | Imperial       | W   | 0.430      | 0.450        | 0.237 (0.046)    | -                | -         |    10.49 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           40 |     2925 | 2024-04-10 | Imperial       | L   | 0.430      | -            | -                | -                | -         |    -3.07 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           39 |     2975 | 2024-04-09 | ODDIK          | W   | 0.424      | -            | -                | -                | -         |     4.64 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           38 |     2980 | 2024-04-09 | ODDIK          | W   | 0.423      | -            | -                | -                | -         |     4.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           37 |     3016 | 2024-04-08 | ODDIK          | W   | 0.416      | -            | -                | -                | -         |     4.88 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           36 |     3066 | 2024-04-06 | BESTIA         | L   | 0.404      | -            | -                | -                | -         |    -7.70 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           35 |     3067 | 2024-04-06 | Solid          | W   | 0.403      | -            | -                | -                | -         |     3.57 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           34 |     3082 | 2024-04-05 | MIBR           | L   | 0.397      | -            | -                | -                | -         |    -1.61 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           33 |     3083 | 2024-04-05 | MIBR           | W   | 0.397      | 0.450        | 0.209 (0.037)    | -                | -         |    11.02 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           32 |     3110 | 2024-04-04 | Corinthians    | W   | 0.390      | -            | -                | -                | -         |     0.56 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           31 |     3116 | 2024-04-04 | Corinthians    | W   | 0.390      | -            | -                | -                | -         |     0.56 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           30 |     3130 | 2024-04-04 | RED Canids     | L   | 0.388      | -            | -                | -                | -         |    -5.41 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           29 |     3146 | 2024-04-03 | MIBR           | L   | 0.384      | -            | -                | -                | -         |    -1.47 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           28 |     3157 | 2024-04-03 | BESTIA         | W   | 0.383      | -            | -                | -                | -         |     5.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           27 |     3194 | 2024-04-02 | MIBR           | L   | 0.377      | -            | -                | -                | -         |    -1.43 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           26 |     3198 | 2024-04-02 | BESTIA         | W   | 0.376      | -            | -                | -                | -         |     5.17 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           25 |     3282 | 2024-03-27 | Galorys        | L   | 0.337      | -            | -                | -                | -         |    -7.53 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           24 |     3288 | 2024-03-27 | Galorys        | W   | 0.337      | -            | -                | -                | -         |     3.13 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           23 |     3557 | 2024-03-13 | Intense        | W   | 0.243      | -            | -                | -                | -         |     1.19 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           22 |     3571 | 2024-03-13 | Solid          | L   | 0.242      | -            | -                | -                | -         |    -5.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           21 |     3597 | 2024-03-12 | MIBR           | W   | 0.236      | -            | -                | -                | -         |     6.56 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           20 |     3629 | 2024-03-11 | Sharks         | W   | 0.228      | -            | -                | -                | -         |     2.85 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           19 |     3672 | 2024-03-09 | Corinthians    | W   | 0.214      | -            | -                | -                | -         |     0.32 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           18 |     3707 | 2024-03-07 | Case           | L   | 0.203      | -            | -                | -                | -         |    -4.29 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           17 |     3732 | 2024-03-06 | Solid          | L   | 0.197      | -            | -                | -                | -         |    -4.42 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           16 |     3733 | 2024-03-06 | Solid          | W   | 0.197      | -            | -                | -                | -         |     1.80 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           15 |     3799 | 2024-03-04 | Case           | W   | 0.184      | -            | -                | -                | -         |     1.98 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           14 |     3800 | 2024-03-04 | Case           | W   | 0.184      | -            | -                | -                | -         |     2.00 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           13 |     3957 | 2024-02-25 | Imperial       | W   | 0.129      | -            | -                | -                | -         |     3.15 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           12 |     3987 | 2024-02-24 | Sharks         | W   | 0.123      | -            | -                | -                | -         |     1.54 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           11 |     4037 | 2024-02-21 | W7M            | L   | 0.104      | -            | -                | -                | -         |    -2.50 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|           10 |     4042 | 2024-02-21 | W7M            | W   | 0.104      | -            | -                | -                | -         |     0.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            9 |     4046 | 2024-02-21 | Solid          | W   | 0.102      | -            | -                | -                | -         |     0.98 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            8 |     4074 | 2024-02-20 | Solid          | L   | 0.096      | -            | -                | -                | -         |    -2.12 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            7 |     4171 | 2024-02-16 | 9z             | W   | 0.069      | -            | -                | -                | -         |     2.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            6 |     4198 | 2024-02-15 | Imperial       | L   | 0.063      | -            | -                | -                | -         |    -0.46 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            5 |     4200 | 2024-02-15 | W7M            | W   | 0.063      | -            | -                | -                | -         |     0.48 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            4 |     4205 | 2024-02-15 | Sharks         | W   | 0.062      | -            | -                | -                | -         |     0.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            3 |     4206 | 2024-02-15 | Sharks         | W   | 0.062      | -            | -                | -                | -         |     0.78 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            2 |     4229 | 2024-02-14 | Intense        | W   | 0.057      | -            | -                | -                | -         |     0.29 | chayJESUS, Lucaozy, PKL, vsm, zevy   |
|            1 |     4294 | 2024-02-12 | Flamengo       | W   | 0.041      | -            | -                | -                | -         |     0.06 | chayJESUS, Lucaozy, PKL, vsm, zevy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,287.04)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-07-22 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-16 |      0.876 | $30,000.00     | $26,266.67      |
| 2024-06-09 |      0.830 | $2,000.00      | $1,659.26       |
| 2024-05-19 |      0.689 | $2,000.00      | $1,377.78       |
| 2024-03-14 |      0.249 | $5,000.00      | $1,247.22       |
| 2024-02-25 |      0.129 | $25,000.00     | $3,236.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
