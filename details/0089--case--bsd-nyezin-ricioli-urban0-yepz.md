### Roster Details<br />
Team Name: Case<br />
Roster: bsd, nyezin, RICIOLI, urban0, yepz<br />
Global Rank: [89](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [23]( ../standings_americas.md)<br />
<br />
Final Rank Value:  896.0<br />
<br />
Final Rank Value (896.0) = Starting Rank Value (940.8) + Head To Head Adjustments (-44.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.395[<sup>1</sup>](#table2)
- Bounty Collected: 0.410[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 940.8
- 400 + ( ( 0.265 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 940.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          124 |       27 | 2024-08-02 | BESTIA            | L   | 1.000      | -            | -                | -                | -         |   -11.65 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          123 |       29 | 2024-08-02 | inSanitY          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    19.30 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          122 |       59 | 2024-08-01 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -9.41 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          121 |       66 | 2024-08-01 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.17 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          120 |      109 | 2024-07-31 | Legacy            | L   | 1.000      | -            | -                | -                | -         |    -8.03 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          119 |      113 | 2024-07-31 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -16.54 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          118 |      115 | 2024-07-31 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -18.05 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          117 |      125 | 2024-07-31 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.62 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          116 |      174 | 2024-07-30 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.24 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          115 |      240 | 2024-07-28 | Solid             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.16 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          114 |      261 | 2024-07-27 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.41 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          113 |      275 | 2024-07-26 | Galorys           | L   | 1.000      | -            | -                | -                | -         |   -19.43 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          112 |      391 | 2024-07-23 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -18.32 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          111 |      393 | 2024-07-23 | Fluxo             | W   | 1.000      | 0.143        | 0.124 (0.018)    | -                | 0 (0.000) |    25.51 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          110 |      401 | 2024-07-23 | Sharks Youngsters | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.97 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          109 |      422 | 2024-07-22 | Intense           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.83 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          108 |      479 | 2024-07-20 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -5.24 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          107 |      507 | 2024-07-19 | Dusty Roots       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.65 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          106 |      511 | 2024-07-19 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -18.58 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          105 |      515 | 2024-07-19 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -5.59 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          104 |      544 | 2024-07-18 | Smoke             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.10 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          103 |      547 | 2024-07-18 | Smoke             | W   | 1.000      | -            | -                | -                | -         |     8.68 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          102 |      555 | 2024-07-18 | ODDIK             | W   | 1.000      | 0.384        | 0.098 (0.038)    | 0.829 (0.319)    | -         |    22.08 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          101 |      568 | 2024-07-18 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -15.11 | bsd, nyezin, RICIOLI, urban0, yepz     |
|          100 |      618 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.31 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           99 |      621 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -2.37 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           98 |      646 | 2024-07-17 | Vikings KR        | L   | 1.000      | -            | -                | -                | -         |   -18.48 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           97 |      678 | 2024-07-16 | Solid             | L   | 1.000      | -            | -                | -                | -         |   -19.20 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           96 |      684 | 2024-07-16 | Solid             | W   | 1.000      | 0.450        | 0.025 (0.011)    | 0.835 (0.376)    | -         |    12.00 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           95 |      731 | 2024-07-15 | 9z Academy        | W   | 1.000      | -            | -                | -                | -         |     2.62 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           94 |      735 | 2024-07-15 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -10.50 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           93 |      736 | 2024-07-15 | Imperial          | W   | 1.000      | 0.450        | 0.238 (0.107)    | 0.685 (0.308)    | -         |    26.82 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           92 |      742 | 2024-07-15 | Imperial          | W   | 1.000      | 0.450        | 0.238 (0.107)    | 0.685 (0.308)    | -         |    27.92 | bsd, nyezin, RICIOLI, urban0, yepz     |
|           91 |      780 | 2024-07-13 | Dusty Roots       | W   | 1.000      | -            | -                | -                | -         |    12.40 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           90 |      801 | 2024-07-11 | W7M               | L   | 1.000      | -            | -                | -                | -         |   -18.13 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           89 |      806 | 2024-07-11 | Hawks             | W   | 1.000      | -            | -                | -                | -         |     4.11 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           88 |      807 | 2024-07-11 | Galorys           | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.552 (0.205)    | -         |    13.88 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           87 |      825 | 2024-07-10 | Legacy            | L   | 1.000      | -            | -                | -                | -         |    -7.58 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           86 |      850 | 2024-07-09 | W7M               | W   | 1.000      | 0.371        | -                | 0.536 (0.199)    | -         |    11.69 | nyezin, paqueta, RICIOLI, urban0, yepz |
|           85 |      940 | 2024-06-19 | inSanitY          | L   | 0.899      | -            | -                | -                | -         |    -9.04 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           84 |      942 | 2024-06-18 | Solid             | W   | 0.892      | 0.337        | -                | 0.835 (0.251)    | -         |    14.28 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           83 |     1262 | 2024-06-08 | Galorys           | L   | 0.824      | -            | -                | -                | -         |   -12.72 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           82 |     1307 | 2024-06-07 | Vikings KR        | L   | 0.818      | -            | -                | -                | -         |   -15.98 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           81 |     1341 | 2024-06-06 | Bounty Hunters    | L   | 0.814      | -            | -                | -                | -         |   -12.64 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           80 |     1381 | 2024-06-06 | Bounty Hunters    | L   | 0.811      | -            | -                | -                | -         |   -13.54 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           79 |     1502 | 2024-06-03 | Solid             | L   | 0.793      | -            | -                | -                | -         |   -13.07 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           78 |     1547 | 2024-06-01 | Smoke             | W   | 0.779      | -            | -                | -                | -         |     5.97 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           77 |     1635 | 2024-05-29 | Dusty Roots       | W   | 0.759      | -            | -                | -                | -         |     9.48 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           76 |     1689 | 2024-05-27 | Hawks             | L   | 0.745      | -            | -                | -                | -         |   -20.92 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           75 |     1780 | 2024-05-22 | BESTIA            | L   | 0.713      | -            | -                | -                | -         |    -7.04 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           74 |     1786 | 2024-05-22 | BESTIA            | L   | 0.713      | -            | -                | -                | -         |    -7.44 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           73 |     1824 | 2024-05-21 | Sharks            | W   | 0.707      | 0.450        | -                | 0.564 (0.179)    | -         |    13.70 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           72 |     1825 | 2024-05-21 | Sharks            | L   | 0.707      | -            | -                | -                | -         |    -8.61 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           71 |     1837 | 2024-05-21 | ODDIK             | W   | 0.705      | 0.303        | 0.098 (0.021)    | 0.829 (0.177)    | -         |    12.30 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           70 |     1874 | 2024-05-20 | Galorys           | W   | 0.699      | -            | -                | -                | -         |    10.60 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           69 |     1894 | 2024-05-19 | ODDIK             | L   | 0.693      | -            | -                | -                | -         |    -9.53 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           68 |     1920 | 2024-05-18 | Solid             | W   | 0.686      | -            | -                | -                | -         |    10.22 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           67 |     1957 | 2024-05-17 | Fluxo             | L   | 0.679      | -            | -                | -                | -         |    -5.54 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           66 |     1963 | 2024-05-17 | Hype              | W   | 0.679      | -            | -                | -                | -         |     9.82 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           65 |     1997 | 2024-05-16 | KRÜ               | W   | 0.672      | -            | -                | -                | -         |    10.94 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           64 |     2004 | 2024-05-16 | Yawara            | W   | 0.671      | -            | -                | -                | -         |     2.21 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           63 |     2040 | 2024-05-15 | Corinthians       | W   | 0.666      | -            | -                | -                | -         |     2.14 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           62 |     2043 | 2024-05-15 | Corinthians       | W   | 0.666      | -            | -                | -                | -         |     2.18 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           61 |     2050 | 2024-05-15 | Galorys           | W   | 0.665      | -            | -                | -                | -         |    11.05 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           60 |     2091 | 2024-05-14 | Galorys           | W   | 0.660      | -            | -                | -                | -         |    11.63 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           59 |     2096 | 2024-05-14 | Galorys           | L   | 0.660      | -            | -                | -                | -         |    -9.30 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           58 |     2112 | 2024-05-14 | Hype              | L   | 0.658      | -            | -                | -                | -         |   -10.61 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           57 |     2131 | 2024-05-13 | Intense           | W   | 0.652      | -            | -                | -                | -         |     6.42 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           56 |     2158 | 2024-05-12 | Solid             | L   | 0.645      | -            | -                | -                | -         |   -10.02 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           55 |     2191 | 2024-05-11 | Galorys           | L   | 0.638      | -            | -                | -                | -         |   -10.27 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           54 |     2270 | 2024-05-07 | inSanitY          | L   | 0.612      | -            | -                | -                | -         |    -9.33 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           53 |     2299 | 2024-05-05 | ODDIK             | L   | 0.600      | -            | -                | -                | -         |    -7.84 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           52 |     2357 | 2024-05-02 | ODDIK             | W   | 0.580      | 0.450        | 0.098 (0.026)    | 0.829 (0.217)    | -         |    10.96 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           51 |     2358 | 2024-05-02 | ODDIK             | L   | 0.580      | -            | -                | -                | -         |    -7.41 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           50 |     2381 | 2024-05-01 | 9z                | L   | 0.573      | -            | -                | -                | -         |    -0.57 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           49 |     2382 | 2024-05-01 | 9z                | L   | 0.572      | -            | -                | -                | -         |    -0.58 | nyezin, RCF, RICIOLI, urban0, yepz     |
|           48 |     2758 | 2024-04-17 | MIBR              | L   | 0.479      | -            | -                | -                | -         |    -0.78 | RCF, RICIOLI, snow, urban0, yepz       |
|           47 |     2794 | 2024-04-16 | Galorys           | W   | 0.474      | -            | -                | -                | -         |     7.56 | RCF, RICIOLI, snow, urban0, yepz       |
|           46 |     2846 | 2024-04-13 | MIBR              | L   | 0.452      | -            | -                | -                | -         |    -0.73 | pr1sma, RCF, RICIOLI, urban0, yepz     |
|           45 |     2859 | 2024-04-12 | adalYamigos       | W   | 0.447      | -            | -                | -                | -         |     2.46 | RCF, RICIOLI, snow, urban0, yepz       |
|           44 |     2894 | 2024-04-11 | FURIA Academy     | W   | 0.438      | -            | -                | -                | -         |     1.43 | RCF, RICIOLI, snow, urban0, yepz       |
|           43 |     2968 | 2024-04-09 | paiN              | L   | 0.427      | -            | -                | -                | -         |    -0.74 | RCF, RICIOLI, snow, urban0, yepz       |
|           42 |     2973 | 2024-04-09 | paiN              | L   | 0.426      | -            | -                | -                | -         |    -0.75 | RCF, RICIOLI, snow, urban0, yepz       |
|           41 |     3044 | 2024-04-07 | adalYamigos       | L   | 0.413      | -            | -                | -                | -         |   -10.91 | RCF, RICIOLI, snow, urban0, yepz       |
|           40 |     3104 | 2024-04-04 | RED Canids        | W   | 0.393      | 0.450        | 0.077 (0.014)    | -                | -         |     9.24 | RCF, RICIOLI, snow, urban0, yepz       |
|           39 |     3109 | 2024-04-04 | RED Canids        | L   | 0.393      | -            | -                | -                | -         |    -3.17 | RCF, RICIOLI, snow, urban0, yepz       |
|           38 |     3144 | 2024-04-03 | Imperial          | L   | 0.387      | -            | -                | -                | -         |    -1.43 | RCF, RICIOLI, snow, urban0, yepz       |
|           37 |     3147 | 2024-04-03 | Imperial          | L   | 0.386      | -            | -                | -                | -         |    -1.45 | RCF, RICIOLI, snow, urban0, yepz       |
|           36 |     3278 | 2024-03-27 | MIBR              | L   | 0.340      | -            | -                | -                | -         |    -0.63 | RCF, RICIOLI, snow, urban0, yepz       |
|           35 |     3284 | 2024-03-27 | MIBR              | L   | 0.340      | -            | -                | -                | -         |    -0.64 | RCF, RICIOLI, snow, urban0, yepz       |
|           34 |     3458 | 2024-03-17 | ODDIK             | L   | 0.272      | -            | -                | -                | -         |    -3.43 | RCF, RICIOLI, snow, urban0, yepz       |
|           33 |     3478 | 2024-03-16 | MIBR Academy      | W   | 0.265      | -            | -                | -                | -         |     0.78 | RCF, RICIOLI, snow, urban0, yepz       |
|           32 |     3493 | 2024-03-15 | RED Canids        | L   | 0.259      | -            | -                | -                | -         |    -2.39 | RCF, RICIOLI, snow, urban0, yepz       |
|           31 |     3532 | 2024-03-14 | FURIA Academy     | W   | 0.252      | -            | -                | -                | -         |     0.77 | RCF, RICIOLI, snow, urban0, yepz       |
|           30 |     3553 | 2024-03-13 | RED Canids        | L   | 0.246      | -            | -                | -                | -         |    -2.25 | RCF, RICIOLI, snow, urban0, yepz       |
|           29 |     3559 | 2024-03-13 | Yawara            | L   | 0.246      | -            | -                | -                | -         |    -7.04 | RCF, RICIOLI, snow, urban0, yepz       |
|           28 |     3567 | 2024-03-13 | ODDIK             | L   | 0.245      | -            | -                | -                | -         |    -3.22 | RCF, RICIOLI, snow, urban0, yepz       |
|           27 |     3601 | 2024-03-12 | LA RUGONETA       | W   | 0.237      | -            | -                | -                | -         |     0.78 | RCF, RICIOLI, snow, urban0, yepz       |
|           26 |     3631 | 2024-03-10 | FURIA Academy     | W   | 0.226      | -            | -                | -                | -         |     0.63 | RCF, RICIOLI, snow, urban0, yepz       |
|           25 |     3651 | 2024-03-09 | Sharks            | W   | 0.219      | -            | -                | -                | -         |     3.94 | RCF, RICIOLI, snow, urban0, yepz       |
|           24 |     3701 | 2024-03-07 | Fluxo             | W   | 0.206      | 0.435        | 0.124 (0.011)    | -                | -         |     4.36 | RCF, RICIOLI, snow, urban0, yepz       |
|           23 |     3763 | 2024-03-05 | adalYamigos       | L   | 0.194      | -            | -                | -                | -         |    -5.28 | RCF, RICIOLI, snow, urban0, yepz       |
|           22 |     3765 | 2024-03-05 | adalYamigos       | L   | 0.193      | -            | -                | -                | -         |    -5.31 | RCF, RICIOLI, snow, urban0, yepz       |
|           21 |     3793 | 2024-03-04 | Fluxo             | L   | 0.187      | -            | -                | -                | -         |    -2.01 | RCF, RICIOLI, snow, urban0, yepz       |
|           20 |     3794 | 2024-03-04 | Fluxo             | L   | 0.187      | -            | -                | -                | -         |    -2.04 | RCF, RICIOLI, snow, urban0, yepz       |
|           19 |     3970 | 2024-02-24 | 2GAME             | W   | 0.127      | -            | -                | -                | -         |     0.76 | RCF, RICIOLI, snow, urban0, yepz       |
|           18 |     3975 | 2024-02-24 | 2GAME             | L   | 0.127      | -            | -                | -                | -         |    -3.25 | RCF, RICIOLI, snow, urban0, yepz       |
|           17 |     4030 | 2024-02-21 | Solid             | W   | 0.107      | -            | -                | -                | -         |     1.52 | RCF, RICIOLI, snow, urban0, yepz       |
|           16 |     4032 | 2024-02-21 | Solid             | L   | 0.107      | -            | -                | -                | -         |    -1.87 | RCF, RICIOLI, snow, urban0, yepz       |
|           15 |     4039 | 2024-02-21 | Sharks            | L   | 0.106      | -            | -                | -                | -         |    -1.54 | RCF, RICIOLI, snow, urban0, yepz       |
|           14 |     4067 | 2024-02-20 | 9z                | L   | 0.100      | -            | -                | -                | -         |    -0.10 | RCF, RICIOLI, snow, urban0, yepz       |
|           13 |     4070 | 2024-02-20 | W7M               | W   | 0.099      | -            | -                | -                | -         |     1.14 | RCF, RICIOLI, snow, urban0, yepz       |
|           12 |     4074 | 2024-02-20 | Sharks            | L   | 0.098      | -            | -                | -                | -         |    -1.42 | RCF, RICIOLI, snow, urban0, yepz       |
|           11 |     4114 | 2024-02-18 | Galorys           | L   | 0.086      | -            | -                | -                | -         |    -1.50 | RCF, RICIOLI, snow, urban0, yepz       |
|           10 |     4135 | 2024-02-17 | Solid             | W   | 0.080      | -            | -                | -                | -         |     1.11 | RCF, RICIOLI, snow, urban0, yepz       |
|            9 |     4162 | 2024-02-16 | BESTIA            | W   | 0.073      | -            | -                | -                | -         |     1.41 | RCF, RICIOLI, snow, urban0, yepz       |
|            8 |     4190 | 2024-02-15 | 9z                | L   | 0.066      | -            | -                | -                | -         |    -0.07 | RCF, RICIOLI, snow, urban0, yepz       |
|            7 |     4192 | 2024-02-15 | Sharks            | W   | 0.066      | -            | -                | -                | -         |     1.13 | RCF, RICIOLI, snow, urban0, yepz       |
|            6 |     4202 | 2024-02-15 | Flamengo          | W   | 0.065      | -            | -                | -                | -         |     0.16 | RCF, RICIOLI, snow, urban0, yepz       |
|            5 |     4220 | 2024-02-14 | O PLANO C         | W   | 0.060      | -            | -                | -                | -         |     0.09 | RCF, RICIOLI, snow, urban0, yepz       |
|            4 |     4263 | 2024-02-13 | W7M               | W   | 0.054      | -            | -                | -                | -         |     0.62 | RCF, RICIOLI, snow, urban0, yepz       |
|            3 |     4268 | 2024-02-13 | W7M               | L   | 0.053      | -            | -                | -                | -         |    -1.07 | RCF, RICIOLI, snow, urban0, yepz       |
|            2 |     4273 | 2024-02-13 | Galorys           | W   | 0.052      | -            | -                | -                | -         |     0.74 | RCF, RICIOLI, snow, urban0, yepz       |
|            1 |     4286 | 2024-02-12 | Dusty Roots       | W   | 0.045      | -            | -                | -                | -         |     0.53 | RCF, RICIOLI, snow, urban0, yepz       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,555.74)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $2,700.00      | $2,700.00       |
| 2024-06-19 |      0.899 | $2,150.00      | $1,933.21       |
| 2024-06-09 |      0.833 | $600.00        | $499.61         |
| 2024-05-21 |      0.705 | $3,500.00      | $2,468.47       |
| 2024-05-19 |      0.692 | $1,000.00      | $691.94         |
| 2024-03-14 |      0.253 | $5,000.00      | $1,262.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
