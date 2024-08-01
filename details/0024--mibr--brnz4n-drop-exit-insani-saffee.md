### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1300.1<br />
<br />
Final Rank Value (1300.1) = Starting Rank Value (1431.8) + Head To Head Adjustments (-131.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.590[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 0.637[<sup>2</sup>](#table1)

The average of these factors is 0.501<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1431.8
- 400 + ( ( 0.501 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1431.8


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
|           87 |       28 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     5.61 | brnz4n, drop, exit, insani, saffee |
|           86 |       34 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |     6.76 | brnz4n, drop, exit, insani, saffee |
|           85 |       39 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |     7.18 | brnz4n, drop, exit, insani, saffee |
|           84 |       67 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -29.52 | brnz4n, drop, exit, insani, saffee |
|           83 |       72 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.73 | brnz4n, drop, exit, insani, saffee |
|           82 |       76 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.35 | brnz4n, drop, exit, insani, saffee |
|           81 |       89 | 2024-07-30 | Galorys        | W   | 1.000      | 0.371        | -                | 0.568 (0.210)    | -         |     1.98 | brnz4n, drop, exit, insani, saffee |
|           80 |      113 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -20.61 | brnz4n, drop, exit, insani, saffee |
|           79 |      138 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     8.67 | brnz4n, drop, exit, insani, saffee |
|           78 |      144 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.51 | brnz4n, drop, exit, insani, saffee |
|           77 |      234 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     1.58 | brnz4n, drop, exit, insani, saffee |
|           76 |      235 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.568 (0.256)    | -         |     1.61 | brnz4n, drop, exit, insani, saffee |
|           75 |      507 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -2.55 | brnz4n, drop, exit, insani, saffee |
|           74 |      562 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      932 | 2024-06-15 | Complexity     | L   | 0.886      | -            | -                | -                | -         |    -5.78 | brnz4n, drop, exit, insani, saffee |
|           72 |      953 | 2024-06-14 | Alliance       | W   | 0.881      | -            | -                | -                | 1 (0.881) |     1.75 | brnz4n, drop, exit, insani, saffee |
|           71 |      965 | 2024-06-14 | ENCE           | L   | 0.880      | -            | -                | -                | -         |   -14.70 | brnz4n, drop, exit, insani, saffee |
|           70 |     1214 | 2024-06-07 | Bounty Hunters | L   | 0.836      | -            | -                | -                | -         |   -24.59 | brnz4n, drop, exit, insani, saffee |
|           69 |     1280 | 2024-06-06 | 9z             | L   | 0.829      | -            | -                | -                | -         |   -18.63 | brnz4n, drop, exit, insani, saffee |
|           68 |     1351 | 2024-06-05 | BESTIA         | W   | 0.823      | 0.450        | -                | 0.738 (0.273)    | -         |     3.37 | brnz4n, drop, exit, insani, saffee |
|           67 |     1406 | 2024-06-04 | Galorys        | W   | 0.816      | -            | -                | -                | -         |     1.38 | brnz4n, drop, exit, insani, saffee |
|           66 |     1733 | 2024-05-22 | paiN           | W   | 0.729      | 0.450        | 0.300 (0.098)    | 0.801 (0.263)    | -         |     7.33 | brnz4n, drop, exit, insani, saffee |
|           65 |     1737 | 2024-05-22 | paiN           | W   | 0.728      | 0.450        | 0.300 (0.098)    | 0.801 (0.263)    | -         |     7.76 | brnz4n, drop, exit, insani, saffee |
|           64 |     1746 | 2024-05-22 | W7M            | L   | 0.727      | -            | -                | -                | -         |   -21.89 | brnz4n, drop, exit, insani, saffee |
|           63 |     1747 | 2024-05-22 | W7M            | L   | 0.727      | -            | -                | -                | -         |   -22.11 | brnz4n, drop, exit, insani, saffee |
|           62 |     1828 | 2024-05-20 | BetBoom        | L   | 0.715      | -            | -                | -                | -         |   -12.88 | brnz4n, drop, exit, insani, saffee |
|           61 |     1843 | 2024-05-20 | BIG            | W   | 0.713      | 0.769        | 0.132 (0.073)    | -                | -         |     5.50 | brnz4n, drop, exit, insani, saffee |
|           60 |     1851 | 2024-05-20 | BetBoom        | L   | 0.713      | -            | -                | -                | -         |   -13.38 | brnz4n, drop, exit, insani, saffee |
|           59 |     1934 | 2024-05-17 | HEROIC         | L   | 0.694      | -            | -                | -                | -         |    -7.96 | brnz4n, drop, exit, insani, saffee |
|           58 |     1967 | 2024-05-16 | Aurora         | W   | 0.688      | 0.769        | 0.432 (0.228)    | 0.798 (0.422)    | 1 (0.688) |    14.11 | brnz4n, drop, exit, insani, saffee |
|           57 |     2029 | 2024-05-15 | HEROIC         | L   | 0.680      | -            | -                | -                | -         |    -7.77 | brnz4n, drop, exit, insani, saffee |
|           56 |     2445 | 2024-04-28 | Aurora         | W   | 0.566      | 0.500        | 0.432 (0.122)    | 0.798 (0.226)    | 1 (0.566) |    12.93 | brnz4n, drop, exit, insani, saffee |
|           55 |     2448 | 2024-04-27 | Apeks          | W   | 0.564      | -            | -                | -                | 1 (0.564) |     1.26 | brnz4n, drop, exit, insani, saffee |
|           54 |     2475 | 2024-04-26 | Rooster        | W   | 0.558      | -            | -                | -                | 1 (0.558) |     0.51 | brnz4n, drop, exit, insani, saffee |
|           53 |     2497 | 2024-04-26 | Rebels         | L   | 0.552      | -            | -                | -                | -         |   -16.05 | brnz4n, drop, exit, insani, saffee |
|           52 |     2500 | 2024-04-25 | KZG            | W   | 0.551      | -            | -                | -                | 1 (0.551) |     0.23 | brnz4n, drop, exit, insani, saffee |
|           51 |     2616 | 2024-04-20 | paiN           | L   | 0.515      | -            | -                | -                | -         |   -10.09 | brnz4n, drop, exit, insani, saffee |
|           50 |     2625 | 2024-04-20 | OG             | W   | 0.514      | 0.589        | 0.143 (0.043)    | -                | 1 (0.514) |     1.66 | brnz4n, drop, exit, insani, saffee |
|           49 |     2638 | 2024-04-19 | paiN           | W   | 0.511      | -            | -                | -                | -         |     6.42 | brnz4n, drop, exit, insani, saffee |
|           48 |     2645 | 2024-04-19 | FURIA          | W   | 0.510      | 0.589        | 0.286 (0.086)    | -                | 1 (0.510) |    12.65 | brnz4n, drop, exit, insani, saffee |
|           47 |     2665 | 2024-04-19 | paiN           | L   | 0.508      | -            | -                | -                | -         |    -9.72 | brnz4n, drop, exit, insani, saffee |
|           46 |     2687 | 2024-04-18 | Imperial       | W   | 0.504      | -            | -                | -                | -         |     5.02 | brnz4n, drop, exit, insani, saffee |
|           45 |     2692 | 2024-04-18 | paiN           | W   | 0.503      | -            | -                | -                | -         |     6.36 | brnz4n, drop, exit, insani, saffee |
|           44 |     2697 | 2024-04-18 | OG             | W   | 0.502      | -            | -                | -                | 1 (0.502) |     1.68 | brnz4n, drop, exit, insani, saffee |
|           43 |     2742 | 2024-04-17 | RED Canids     | W   | 0.496      | -            | -                | -                | -         |     1.71 | brnz4n, drop, exit, insani, saffee |
|           42 |     2749 | 2024-04-17 | Case           | W   | 0.496      | -            | -                | -                | -         |     0.85 | brnz4n, drop, exit, insani, saffee |
|           41 |     2788 | 2024-04-16 | Bounty Hunters | W   | 0.490      | -            | -                | -                | -         |     0.74 | brnz4n, drop, exit, insani, saffee |
|           40 |     2810 | 2024-04-15 | Imperial       | W   | 0.482      | 0.435        | 0.240 (0.050)    | -                | -         |     5.00 | brnz4n, drop, exit, insani, saffee |
|           39 |     2824 | 2024-04-14 | Galorys        | W   | 0.476      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|           38 |     2838 | 2024-04-13 | Case           | W   | 0.468      | -            | -                | -                | -         |     0.80 | brnz4n, drop, exit, insani, saffee |
|           37 |     2870 | 2024-04-11 | paiN           | W   | 0.457      | -            | -                | -                | -         |     6.37 | brnz4n, drop, exit, insani, saffee |
|           36 |     2908 | 2024-04-10 | Galorys        | W   | 0.450      | -            | -                | -                | -         |     0.85 | brnz4n, drop, exit, insani, saffee |
|           35 |     2912 | 2024-04-10 | Galorys        | W   | 0.449      | -            | -                | -                | -         |     0.85 | brnz4n, drop, exit, insani, saffee |
|           34 |     2929 | 2024-04-10 | Imperial       | W   | 0.448      | -            | -                | -                | -         |     5.01 | brnz4n, drop, exit, insani, saffee |
|           33 |     2960 | 2024-04-09 | adalYamigos    | W   | 0.443      | -            | -                | -                | -         |     0.23 | brnz4n, drop, exit, insani, saffee |
|           32 |     2965 | 2024-04-09 | adalYamigos    | W   | 0.443      | -            | -                | -                | -         |     0.23 | brnz4n, drop, exit, insani, saffee |
|           31 |     2972 | 2024-04-09 | RED Canids     | W   | 0.442      | -            | -                | -                | -         |     1.64 | brnz4n, drop, exit, insani, saffee |
|           30 |     3002 | 2024-04-08 | W7M            | W   | 0.436      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           29 |     3036 | 2024-04-07 | paiN           | W   | 0.430      | -            | -                | -                | -         |     6.36 | brnz4n, drop, exit, insani, saffee |
|           28 |     3053 | 2024-04-06 | Bounty Hunters | W   | 0.423      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           27 |     3070 | 2024-04-05 | Fluxo          | W   | 0.417      | -            | -                | -                | -         |     1.79 | brnz4n, drop, exit, insani, saffee |
|           26 |     3071 | 2024-04-05 | Fluxo          | L   | 0.416      | -            | -                | -                | -         |   -11.47 | brnz4n, drop, exit, insani, saffee |
|           25 |     3074 | 2024-04-05 | ODDIK          | W   | 0.415      | -            | -                | -                | -         |     1.18 | brnz4n, drop, exit, insani, saffee |
|           24 |     3095 | 2024-04-04 | Solid          | W   | 0.410      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           23 |     3101 | 2024-04-04 | Solid          | W   | 0.409      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           22 |     3135 | 2024-04-03 | Fluxo          | W   | 0.403      | -            | -                | -                | -         |     1.64 | brnz4n, drop, exit, insani, saffee |
|           21 |     3190 | 2024-04-02 | Fluxo          | W   | 0.397      | -            | -                | -                | -         |     1.60 | brnz4n, drop, exit, insani, saffee |
|           20 |     3193 | 2024-04-02 | Sharks         | W   | 0.395      | -            | -                | -                | -         |     0.33 | brnz4n, drop, exit, insani, saffee |
|           19 |     3279 | 2024-03-27 | Case           | W   | 0.357      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           18 |     3286 | 2024-03-27 | Case           | W   | 0.356      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           17 |     3327 | 2024-03-26 | ODDIK          | W   | 0.350      | -            | -                | -                | -         |     1.13 | brnz4n, drop, exit, insani, saffee |
|           16 |     3330 | 2024-03-26 | ODDIK          | W   | 0.350      | -            | -                | -                | -         |     1.14 | brnz4n, drop, exit, insani, saffee |
|           15 |     3524 | 2024-03-14 | Sharks         | W   | 0.270      | -            | -                | -                | -         |     0.75 | brnz4n, drop, exit, insani, saffee |
|           14 |     3527 | 2024-03-14 | Sharks         | W   | 0.270      | -            | -                | -                | -         |     0.76 | brnz4n, drop, exit, insani, saffee |
|           13 |     3603 | 2024-03-12 | Fluxo          | L   | 0.256      | -            | -                | -                | -         |    -7.05 | brnz4n, drop, exit, insani, saffee |
|           12 |     3642 | 2024-03-10 | Galorys        | W   | 0.243      | -            | -                | -                | -         |     0.41 | brnz4n, drop, exit, insani, saffee |
|           11 |     3691 | 2024-03-08 | LA RUGONETA    | W   | 0.229      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|           10 |     3827 | 2024-03-03 | Legacy         | L   | 0.196      | -            | -                | -                | -         |    -5.55 | brnz4n, drop, exit, insani, saffee |
|            9 |     3859 | 2024-03-02 | NRG            | W   | 0.188      | -            | -                | -                | 1 (0.188) |     0.25 | brnz4n, drop, exit, insani, saffee |
|            8 |     3882 | 2024-03-01 | BOSS           | L   | 0.182      | -            | -                | -                | -         |    -5.55 | brnz4n, drop, exit, insani, saffee |
|            7 |     4009 | 2024-02-24 | Imperial       | L   | 0.141      | -            | -                | -                | -         |    -3.10 | brnz4n, drop, exit, insani, saffee |
|            6 |     4010 | 2024-02-24 | Imperial       | L   | 0.141      | -            | -                | -                | -         |    -3.07 | brnz4n, drop, exit, insani, saffee |
|            5 |     4298 | 2024-02-13 | BESTIA         | L   | 0.070      | -            | -                | -                | -         |    -1.99 | brnz4n, drop, exit, insani, saffee |
|            4 |     4299 | 2024-02-13 | BESTIA         | L   | 0.070      | -            | -                | -                | -         |    -1.99 | brnz4n, drop, exit, insani, saffee |
|            3 |     4302 | 2024-02-13 | 9z             | L   | 0.070      | -            | -                | -                | -         |    -1.65 | brnz4n, drop, exit, insani, saffee |
|            2 |     4303 | 2024-02-13 | 9z             | L   | 0.070      | -            | -                | -                | -         |    -1.66 | brnz4n, drop, exit, insani, saffee |
|            1 |     4429 | 2024-02-03 | Imperial       | L   | 0.003      | -            | -                | -                | -         |    -0.06 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($65,893.24)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.20) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.894 | $3,000.00      | $2,681.67       |
| 2024-06-09 |      0.849 | $3,000.00      | $2,547.22       |
| 2024-04-28 |      0.566 | $50,000.00     | $28,293.98      |
| 2024-04-20 |      0.516 | $20,000.00     | $10,314.81      |
| 2024-04-15 |      0.482 | $25,000.00     | $12,055.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
