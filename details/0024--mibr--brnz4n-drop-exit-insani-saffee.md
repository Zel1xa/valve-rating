### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1303.2<br />
<br />
Final Rank Value (1303.2) = Starting Rank Value (1427.7) + Head To Head Adjustments (-124.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.596[<sup>1</sup>](#table2)
- Bounty Collected: 0.488[<sup>2</sup>](#table1)
- Opponent Network: 0.313[<sup>2</sup>](#table1)
- LAN Wins: 0.613[<sup>2</sup>](#table1)

The average of these factors is 0.502<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1427.7
- 400 + ( ( 0.502 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1427.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           81 |       22 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -12.24 | brnz4n, drop, exit, insani, saffee |
|           80 |       23 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -26.28 | brnz4n, drop, exit, insani, saffee |
|           79 |       35 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.125 (0.046)    | 0.746 (0.276)    | -         |     7.74 | brnz4n, drop, exit, insani, saffee |
|           78 |       50 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.857 (0.318)    | -         |     4.70 | brnz4n, drop, exit, insani, saffee |
|           77 |       92 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.55 | brnz4n, drop, exit, insani, saffee |
|           76 |       95 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.857 (0.386)    | -         |     5.12 | brnz4n, drop, exit, insani, saffee |
|           75 |      101 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.857 (0.386)    | -         |     5.38 | brnz4n, drop, exit, insani, saffee |
|           74 |      130 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      133 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      139 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.29 | brnz4n, drop, exit, insani, saffee |
|           71 |      175 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.79 | brnz4n, drop, exit, insani, saffee |
|           70 |      200 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     6.38 | brnz4n, drop, exit, insani, saffee |
|           69 |      206 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.84 | brnz4n, drop, exit, insani, saffee |
|           68 |      296 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.571 (0.257)    | -         |     1.20 | brnz4n, drop, exit, insani, saffee |
|           67 |      297 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.571 (0.257)    | -         |     1.22 | brnz4n, drop, exit, insani, saffee |
|           66 |      560 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.12 | brnz4n, drop, exit, insani, saffee |
|           65 |      612 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.33 | brnz4n, drop, exit, insani, saffee |
|           64 |      961 | 2024-06-15 | Complexity     | L   | 0.872      | -            | -                | -                | -         |    -6.71 | brnz4n, drop, exit, insani, saffee |
|           63 |      982 | 2024-06-14 | Alliance       | W   | 0.867      | -            | -                | -                | 1 (0.867) |     1.34 | brnz4n, drop, exit, insani, saffee |
|           62 |      993 | 2024-06-14 | ENCE           | L   | 0.865      | -            | -                | -                | -         |   -16.25 | brnz4n, drop, exit, insani, saffee |
|           61 |     1225 | 2024-06-07 | Bounty Hunters | L   | 0.822      | -            | -                | -                | -         |   -24.56 | brnz4n, drop, exit, insani, saffee |
|           60 |     1286 | 2024-06-06 | 9z             | L   | 0.815      | -            | -                | -                | -         |   -19.14 | brnz4n, drop, exit, insani, saffee |
|           59 |     1354 | 2024-06-05 | BESTIA         | W   | 0.808      | 0.450        | -                | 0.756 (0.275)    | -         |     2.41 | brnz4n, drop, exit, insani, saffee |
|           58 |     1408 | 2024-06-04 | Galorys        | W   | 0.802      | -            | -                | -                | -         |     1.02 | brnz4n, drop, exit, insani, saffee |
|           57 |     1728 | 2024-05-22 | paiN           | W   | 0.714      | 0.450        | 0.324 (0.104)    | 0.859 (0.276)    | -         |     7.59 | brnz4n, drop, exit, insani, saffee |
|           56 |     1732 | 2024-05-22 | paiN           | W   | 0.714      | 0.450        | 0.324 (0.104)    | 0.859 (0.276)    | -         |     8.04 | brnz4n, drop, exit, insani, saffee |
|           55 |     1806 | 2024-05-20 | BetBoom        | L   | 0.701      | -            | -                | -                | -         |   -12.95 | brnz4n, drop, exit, insani, saffee |
|           54 |     1818 | 2024-05-20 | BIG            | W   | 0.699      | 0.769        | 0.156 (0.084)    | -                | -         |     7.01 | brnz4n, drop, exit, insani, saffee |
|           53 |     1826 | 2024-05-20 | BetBoom        | L   | 0.698      | -            | -                | -                | -         |   -13.39 | brnz4n, drop, exit, insani, saffee |
|           52 |     1902 | 2024-05-17 | HEROIC         | L   | 0.680      | -            | -                | -                | -         |    -7.89 | brnz4n, drop, exit, insani, saffee |
|           51 |     1935 | 2024-05-16 | Aurora         | W   | 0.673      | 0.769        | 0.425 (0.220)    | 0.809 (0.419)    | 1 (0.673) |    13.69 | brnz4n, drop, exit, insani, saffee |
|           50 |     1993 | 2024-05-15 | HEROIC         | L   | 0.666      | -            | -                | -                | -         |    -7.71 | brnz4n, drop, exit, insani, saffee |
|           49 |     2398 | 2024-04-28 | Aurora         | W   | 0.551      | 0.500        | 0.425 (0.117)    | -                | 1 (0.551) |    12.47 | brnz4n, drop, exit, insani, saffee |
|           48 |     2401 | 2024-04-27 | Apeks          | W   | 0.549      | -            | -                | -                | 1 (0.549) |     1.12 | brnz4n, drop, exit, insani, saffee |
|           47 |     2427 | 2024-04-26 | Rooster        | W   | 0.543      | -            | -                | -                | 1 (0.543) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2449 | 2024-04-26 | Rebels         | L   | 0.537      | -            | -                | -                | -         |   -15.72 | brnz4n, drop, exit, insani, saffee |
|           45 |     2452 | 2024-04-25 | KZG            | W   | 0.536      | -            | -                | -                | 1 (0.536) |     0.19 | brnz4n, drop, exit, insani, saffee |
|           44 |     2562 | 2024-04-20 | paiN           | L   | 0.500      | -            | -                | -                | -         |    -9.91 | brnz4n, drop, exit, insani, saffee |
|           43 |     2571 | 2024-04-20 | OG             | W   | 0.499      | -            | -                | -                | 1 (0.499) |     1.53 | brnz4n, drop, exit, insani, saffee |
|           42 |     2584 | 2024-04-19 | paiN           | W   | 0.496      | -            | -                | -                | -         |     6.12 | brnz4n, drop, exit, insani, saffee |
|           41 |     2591 | 2024-04-19 | FURIA          | W   | 0.495      | 0.589        | 0.284 (0.083)    | -                | 1 (0.495) |    12.02 | brnz4n, drop, exit, insani, saffee |
|           40 |     2610 | 2024-04-19 | paiN           | L   | 0.493      | -            | -                | -                | -         |    -9.55 | brnz4n, drop, exit, insani, saffee |
|           39 |     2632 | 2024-04-18 | Imperial       | W   | 0.489      | -            | -                | -                | -         |     4.23 | brnz4n, drop, exit, insani, saffee |
|           38 |     2637 | 2024-04-18 | paiN           | W   | 0.488      | -            | -                | -                | -         |     6.05 | brnz4n, drop, exit, insani, saffee |
|           37 |     2641 | 2024-04-18 | OG             | W   | 0.488      | -            | -                | -                | 1 (0.488) |     1.52 | brnz4n, drop, exit, insani, saffee |
|           36 |     2686 | 2024-04-17 | RED Canids     | W   | 0.482      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           35 |     2692 | 2024-04-17 | Case           | W   | 0.481      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           34 |     2731 | 2024-04-16 | Bounty Hunters | W   | 0.475      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2752 | 2024-04-15 | Imperial       | W   | 0.468      | 0.435        | 0.234 (0.048)    | -                | -         |     4.14 | brnz4n, drop, exit, insani, saffee |
|           32 |     2766 | 2024-04-14 | Galorys        | W   | 0.461      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           31 |     2780 | 2024-04-13 | Case           | W   | 0.453      | -            | -                | -                | -         |     0.72 | brnz4n, drop, exit, insani, saffee |
|           30 |     2811 | 2024-04-11 | paiN           | W   | 0.442      | -            | -                | -                | -         |     6.02 | brnz4n, drop, exit, insani, saffee |
|           29 |     2849 | 2024-04-10 | Galorys        | W   | 0.435      | -            | -                | -                | -         |     0.66 | brnz4n, drop, exit, insani, saffee |
|           28 |     2853 | 2024-04-10 | Galorys        | W   | 0.435      | -            | -                | -                | -         |     0.67 | brnz4n, drop, exit, insani, saffee |
|           27 |     2870 | 2024-04-10 | Imperial       | W   | 0.433      | -            | -                | -                | -         |     4.08 | brnz4n, drop, exit, insani, saffee |
|           26 |     2901 | 2024-04-09 | adalYamigos    | W   | 0.429      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     2906 | 2024-04-09 | adalYamigos    | W   | 0.428      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     2913 | 2024-04-09 | RED Canids     | W   | 0.427      | -            | -                | -                | -         |     1.31 | brnz4n, drop, exit, insani, saffee |
|           23 |     2943 | 2024-04-08 | W7M            | W   | 0.422      | -            | -                | -                | -         |     0.50 | brnz4n, drop, exit, insani, saffee |
|           22 |     2977 | 2024-04-07 | paiN           | W   | 0.415      | -            | -                | -                | -         |     5.99 | brnz4n, drop, exit, insani, saffee |
|           21 |     2994 | 2024-04-06 | Bounty Hunters | W   | 0.408      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3011 | 2024-04-05 | Fluxo          | W   | 0.402      | -            | -                | -                | -         |     1.57 | brnz4n, drop, exit, insani, saffee |
|           19 |     3012 | 2024-04-05 | Fluxo          | L   | 0.402      | -            | -                | -                | -         |   -11.21 | brnz4n, drop, exit, insani, saffee |
|           18 |     3015 | 2024-04-05 | ODDIK          | W   | 0.400      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|           17 |     3036 | 2024-04-04 | Solid          | W   | 0.395      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3042 | 2024-04-04 | Solid          | W   | 0.395      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3075 | 2024-04-03 | Fluxo          | W   | 0.389      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           14 |     3123 | 2024-04-02 | Fluxo          | W   | 0.382      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           13 |     3126 | 2024-04-02 | Sharks         | W   | 0.381      | -            | -                | -                | -         |     0.29 | brnz4n, drop, exit, insani, saffee |
|           12 |     3212 | 2024-03-27 | Case           | W   | 0.342      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3218 | 2024-03-27 | Case           | W   | 0.342      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3255 | 2024-03-26 | ODDIK          | W   | 0.335      | -            | -                | -                | -         |     0.87 | brnz4n, drop, exit, insani, saffee |
|            9 |     3257 | 2024-03-26 | ODDIK          | W   | 0.335      | -            | -                | -                | -         |     0.88 | brnz4n, drop, exit, insani, saffee |
|            8 |     3446 | 2024-03-14 | Sharks         | W   | 0.255      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            7 |     3448 | 2024-03-14 | Sharks         | W   | 0.255      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|            6 |     3519 | 2024-03-12 | Fluxo          | L   | 0.241      | -            | -                | -                | -         |    -6.72 | brnz4n, drop, exit, insani, saffee |
|            5 |     3557 | 2024-03-10 | Galorys        | W   | 0.228      | -            | -                | -                | -         |     0.34 | brnz4n, drop, exit, insani, saffee |
|            4 |     3605 | 2024-03-08 | LA RUGONETA    | W   | 0.214      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3736 | 2024-03-03 | Legacy         | L   | 0.181      | -            | -                | -                | -         |    -5.19 | brnz4n, drop, exit, insani, saffee |
|            2 |     3768 | 2024-03-02 | NRG            | W   | 0.174      | -            | -                | -                | 1 (0.174) |     0.22 | brnz4n, drop, exit, insani, saffee |
|            1 |     3790 | 2024-03-01 | BOSS           | L   | 0.168      | -            | -                | -                | -         |    -5.12 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($68,410.97)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.879 | $3,000.00      | $2,637.64       |
| 2024-06-09 |      0.834 | $3,000.00      | $2,503.19       |
| 2024-04-28 |      0.551 | $50,000.00     | $27,560.19      |
| 2024-04-20 |      0.501 | $20,000.00     | $10,021.30      |
| 2024-04-15 |      0.468 | $25,000.00     | $11,688.66      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
