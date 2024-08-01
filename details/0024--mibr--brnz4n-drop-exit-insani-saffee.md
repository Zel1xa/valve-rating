### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1299.2<br />
<br />
Final Rank Value (1299.2) = Starting Rank Value (1429.8) + Head To Head Adjustments (-130.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.589[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 0.636[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1429.8
- 400 + ( ( 0.501 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1429.8


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
|           87 |       32 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     5.61 | brnz4n, drop, exit, insani, saffee |
|           86 |       38 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |     6.76 | brnz4n, drop, exit, insani, saffee |
|           85 |       43 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |     7.18 | brnz4n, drop, exit, insani, saffee |
|           84 |       71 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -29.51 | brnz4n, drop, exit, insani, saffee |
|           83 |       76 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.74 | brnz4n, drop, exit, insani, saffee |
|           82 |       80 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.35 | brnz4n, drop, exit, insani, saffee |
|           81 |       93 | 2024-07-30 | Galorys        | W   | 1.000      | 0.371        | -                | 0.568 (0.210)    | -         |     1.98 | brnz4n, drop, exit, insani, saffee |
|           80 |      117 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -20.62 | brnz4n, drop, exit, insani, saffee |
|           79 |      142 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     8.67 | brnz4n, drop, exit, insani, saffee |
|           78 |      148 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.52 | brnz4n, drop, exit, insani, saffee |
|           77 |      238 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     1.58 | brnz4n, drop, exit, insani, saffee |
|           76 |      239 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     1.61 | brnz4n, drop, exit, insani, saffee |
|           75 |      511 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -2.52 | brnz4n, drop, exit, insani, saffee |
|           74 |      566 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.04 | brnz4n, drop, exit, insani, saffee |
|           73 |      936 | 2024-06-15 | Complexity     | L   | 0.885      | -            | -                | -                | -         |    -5.74 | brnz4n, drop, exit, insani, saffee |
|           72 |      957 | 2024-06-14 | Alliance       | W   | 0.880      | -            | -                | -                | 1 (0.880) |     1.75 | brnz4n, drop, exit, insani, saffee |
|           71 |      969 | 2024-06-14 | ENCE           | L   | 0.879      | -            | -                | -                | -         |   -14.57 | brnz4n, drop, exit, insani, saffee |
|           70 |     1218 | 2024-06-07 | Bounty Hunters | L   | 0.835      | -            | -                | -                | -         |   -24.54 | brnz4n, drop, exit, insani, saffee |
|           69 |     1284 | 2024-06-06 | 9z             | L   | 0.828      | -            | -                | -                | -         |   -18.56 | brnz4n, drop, exit, insani, saffee |
|           68 |     1355 | 2024-06-05 | BESTIA         | W   | 0.821      | 0.450        | -                | 0.738 (0.273)    | -         |     3.37 | brnz4n, drop, exit, insani, saffee |
|           67 |     1410 | 2024-06-04 | Galorys        | W   | 0.815      | -            | -                | -                | -         |     1.38 | brnz4n, drop, exit, insani, saffee |
|           66 |     1737 | 2024-05-22 | paiN           | W   | 0.727      | 0.450        | 0.300 (0.098)    | 0.801 (0.262)    | -         |     7.32 | brnz4n, drop, exit, insani, saffee |
|           65 |     1741 | 2024-05-22 | paiN           | W   | 0.727      | 0.450        | 0.300 (0.098)    | 0.801 (0.262)    | -         |     7.75 | brnz4n, drop, exit, insani, saffee |
|           64 |     1750 | 2024-05-22 | W7M            | L   | 0.726      | -            | -                | -                | -         |   -21.85 | brnz4n, drop, exit, insani, saffee |
|           63 |     1751 | 2024-05-22 | W7M            | L   | 0.726      | -            | -                | -                | -         |   -22.06 | brnz4n, drop, exit, insani, saffee |
|           62 |     1832 | 2024-05-20 | BetBoom        | L   | 0.714      | -            | -                | -                | -         |   -12.84 | brnz4n, drop, exit, insani, saffee |
|           61 |     1847 | 2024-05-20 | BIG            | W   | 0.712      | 0.769        | 0.132 (0.072)    | -                | -         |     5.49 | brnz4n, drop, exit, insani, saffee |
|           60 |     1855 | 2024-05-20 | BetBoom        | L   | 0.711      | -            | -                | -                | -         |   -13.34 | brnz4n, drop, exit, insani, saffee |
|           59 |     1938 | 2024-05-17 | HEROIC         | L   | 0.693      | -            | -                | -                | -         |    -7.84 | brnz4n, drop, exit, insani, saffee |
|           58 |     1971 | 2024-05-16 | Aurora         | W   | 0.687      | 0.769        | 0.431 (0.228)    | 0.798 (0.421)    | 1 (0.687) |    14.13 | brnz4n, drop, exit, insani, saffee |
|           57 |     2033 | 2024-05-15 | HEROIC         | L   | 0.679      | -            | -                | -                | -         |    -7.65 | brnz4n, drop, exit, insani, saffee |
|           56 |     2449 | 2024-04-28 | Aurora         | W   | 0.564      | 0.500        | 0.431 (0.122)    | 0.798 (0.225)    | 1 (0.564) |    12.93 | brnz4n, drop, exit, insani, saffee |
|           55 |     2452 | 2024-04-27 | Apeks          | W   | 0.563      | -            | -                | -                | 1 (0.563) |     1.26 | brnz4n, drop, exit, insani, saffee |
|           54 |     2479 | 2024-04-26 | Rooster        | W   | 0.557      | -            | -                | -                | 1 (0.557) |     0.51 | brnz4n, drop, exit, insani, saffee |
|           53 |     2501 | 2024-04-26 | Rebels         | L   | 0.551      | -            | -                | -                | -         |   -16.01 | brnz4n, drop, exit, insani, saffee |
|           52 |     2504 | 2024-04-25 | KZG            | W   | 0.549      | -            | -                | -                | 1 (0.549) |     0.23 | brnz4n, drop, exit, insani, saffee |
|           51 |     2620 | 2024-04-20 | paiN           | L   | 0.513      | -            | -                | -                | -         |   -10.06 | brnz4n, drop, exit, insani, saffee |
|           50 |     2629 | 2024-04-20 | OG             | W   | 0.512      | 0.589        | 0.143 (0.043)    | -                | 1 (0.512) |     1.67 | brnz4n, drop, exit, insani, saffee |
|           49 |     2642 | 2024-04-19 | paiN           | W   | 0.509      | -            | -                | -                | -         |     6.39 | brnz4n, drop, exit, insani, saffee |
|           48 |     2649 | 2024-04-19 | FURIA          | W   | 0.508      | 0.589        | 0.286 (0.086)    | -                | 1 (0.508) |    12.62 | brnz4n, drop, exit, insani, saffee |
|           47 |     2669 | 2024-04-19 | paiN           | L   | 0.507      | -            | -                | -                | -         |    -9.70 | brnz4n, drop, exit, insani, saffee |
|           46 |     2691 | 2024-04-18 | Imperial       | W   | 0.503      | -            | -                | -                | -         |     5.00 | brnz4n, drop, exit, insani, saffee |
|           45 |     2696 | 2024-04-18 | paiN           | W   | 0.501      | -            | -                | -                | -         |     6.34 | brnz4n, drop, exit, insani, saffee |
|           44 |     2701 | 2024-04-18 | OG             | W   | 0.501      | -            | -                | -                | 1 (0.501) |     1.69 | brnz4n, drop, exit, insani, saffee |
|           43 |     2746 | 2024-04-17 | RED Canids     | W   | 0.495      | -            | -                | -                | -         |     1.71 | brnz4n, drop, exit, insani, saffee |
|           42 |     2753 | 2024-04-17 | Case           | W   | 0.494      | -            | -                | -                | -         |     0.85 | brnz4n, drop, exit, insani, saffee |
|           41 |     2792 | 2024-04-16 | Bounty Hunters | W   | 0.488      | -            | -                | -                | -         |     0.74 | brnz4n, drop, exit, insani, saffee |
|           40 |     2814 | 2024-04-15 | Imperial       | W   | 0.481      | 0.435        | 0.239 (0.050)    | -                | -         |     4.99 | brnz4n, drop, exit, insani, saffee |
|           39 |     2828 | 2024-04-14 | Galorys        | W   | 0.474      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|           38 |     2842 | 2024-04-13 | Case           | W   | 0.467      | -            | -                | -                | -         |     0.80 | brnz4n, drop, exit, insani, saffee |
|           37 |     2874 | 2024-04-11 | paiN           | W   | 0.455      | -            | -                | -                | -         |     6.35 | brnz4n, drop, exit, insani, saffee |
|           36 |     2912 | 2024-04-10 | Galorys        | W   | 0.448      | -            | -                | -                | -         |     0.85 | brnz4n, drop, exit, insani, saffee |
|           35 |     2916 | 2024-04-10 | Galorys        | W   | 0.448      | -            | -                | -                | -         |     0.85 | brnz4n, drop, exit, insani, saffee |
|           34 |     2933 | 2024-04-10 | Imperial       | W   | 0.446      | -            | -                | -                | -         |     4.99 | brnz4n, drop, exit, insani, saffee |
|           33 |     2964 | 2024-04-09 | adalYamigos    | W   | 0.442      | -            | -                | -                | -         |     0.23 | brnz4n, drop, exit, insani, saffee |
|           32 |     2969 | 2024-04-09 | adalYamigos    | W   | 0.441      | -            | -                | -                | -         |     0.23 | brnz4n, drop, exit, insani, saffee |
|           31 |     2976 | 2024-04-09 | RED Canids     | W   | 0.440      | -            | -                | -                | -         |     1.64 | brnz4n, drop, exit, insani, saffee |
|           30 |     3006 | 2024-04-08 | W7M            | W   | 0.435      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           29 |     3040 | 2024-04-07 | paiN           | W   | 0.429      | -            | -                | -                | -         |     6.33 | brnz4n, drop, exit, insani, saffee |
|           28 |     3057 | 2024-04-06 | Bounty Hunters | W   | 0.422      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           27 |     3074 | 2024-04-05 | Fluxo          | W   | 0.415      | -            | -                | -                | -         |     1.79 | brnz4n, drop, exit, insani, saffee |
|           26 |     3075 | 2024-04-05 | Fluxo          | L   | 0.415      | -            | -                | -                | -         |   -11.42 | brnz4n, drop, exit, insani, saffee |
|           25 |     3078 | 2024-04-05 | ODDIK          | W   | 0.414      | -            | -                | -                | -         |     1.18 | brnz4n, drop, exit, insani, saffee |
|           24 |     3099 | 2024-04-04 | Solid          | W   | 0.408      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           23 |     3105 | 2024-04-04 | Solid          | W   | 0.408      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           22 |     3139 | 2024-04-03 | Fluxo          | W   | 0.402      | -            | -                | -                | -         |     1.64 | brnz4n, drop, exit, insani, saffee |
|           21 |     3194 | 2024-04-02 | Fluxo          | W   | 0.395      | -            | -                | -                | -         |     1.60 | brnz4n, drop, exit, insani, saffee |
|           20 |     3197 | 2024-04-02 | Sharks         | W   | 0.394      | -            | -                | -                | -         |     0.33 | brnz4n, drop, exit, insani, saffee |
|           19 |     3283 | 2024-03-27 | Case           | W   | 0.355      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           18 |     3290 | 2024-03-27 | Case           | W   | 0.355      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           17 |     3331 | 2024-03-26 | ODDIK          | W   | 0.349      | -            | -                | -                | -         |     1.13 | brnz4n, drop, exit, insani, saffee |
|           16 |     3334 | 2024-03-26 | ODDIK          | W   | 0.348      | -            | -                | -                | -         |     1.14 | brnz4n, drop, exit, insani, saffee |
|           15 |     3528 | 2024-03-14 | Sharks         | W   | 0.269      | -            | -                | -                | -         |     0.75 | brnz4n, drop, exit, insani, saffee |
|           14 |     3531 | 2024-03-14 | Sharks         | W   | 0.268      | -            | -                | -                | -         |     0.76 | brnz4n, drop, exit, insani, saffee |
|           13 |     3607 | 2024-03-12 | Fluxo          | L   | 0.254      | -            | -                | -                | -         |    -7.01 | brnz4n, drop, exit, insani, saffee |
|           12 |     3646 | 2024-03-10 | Galorys        | W   | 0.241      | -            | -                | -                | -         |     0.41 | brnz4n, drop, exit, insani, saffee |
|           11 |     3695 | 2024-03-08 | LA RUGONETA    | W   | 0.228      | -            | -                | -                | -         |     0.06 | brnz4n, drop, exit, insani, saffee |
|           10 |     3831 | 2024-03-03 | Legacy         | L   | 0.195      | -            | -                | -                | -         |    -5.51 | brnz4n, drop, exit, insani, saffee |
|            9 |     3863 | 2024-03-02 | NRG            | W   | 0.187      | -            | -                | -                | 1 (0.187) |     0.25 | brnz4n, drop, exit, insani, saffee |
|            8 |     3886 | 2024-03-01 | BOSS           | L   | 0.181      | -            | -                | -                | -         |    -5.50 | brnz4n, drop, exit, insani, saffee |
|            7 |     4013 | 2024-02-24 | Imperial       | L   | 0.139      | -            | -                | -                | -         |    -3.07 | brnz4n, drop, exit, insani, saffee |
|            6 |     4014 | 2024-02-24 | Imperial       | L   | 0.139      | -            | -                | -                | -         |    -3.04 | brnz4n, drop, exit, insani, saffee |
|            5 |     4302 | 2024-02-13 | BESTIA         | L   | 0.068      | -            | -                | -                | -         |    -1.95 | brnz4n, drop, exit, insani, saffee |
|            4 |     4303 | 2024-02-13 | BESTIA         | L   | 0.068      | -            | -                | -                | -         |    -1.95 | brnz4n, drop, exit, insani, saffee |
|            3 |     4306 | 2024-02-13 | 9z             | L   | 0.068      | -            | -                | -                | -         |    -1.62 | brnz4n, drop, exit, insani, saffee |
|            2 |     4307 | 2024-02-13 | 9z             | L   | 0.068      | -            | -                | -                | -         |    -1.63 | brnz4n, drop, exit, insani, saffee |
|            1 |     4433 | 2024-02-03 | Imperial       | L   | 0.001      | -            | -                | -                | -         |    -0.03 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($65,752.96)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.20) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.892 | $3,000.00      | $2,677.50       |
| 2024-06-09 |      0.848 | $3,000.00      | $2,543.06       |
| 2024-04-28 |      0.564 | $50,000.00     | $28,224.54      |
| 2024-04-20 |      0.514 | $20,000.00     | $10,287.04      |
| 2024-04-15 |      0.481 | $25,000.00     | $12,020.83      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
