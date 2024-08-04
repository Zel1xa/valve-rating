### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1317.0<br />
<br />
Final Rank Value (1317.0) = Starting Rank Value (1421.9) + Head To Head Adjustments (-104.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.596[<sup>1</sup>](#table2)
- Bounty Collected: 0.488[<sup>2</sup>](#table1)
- Opponent Network: 0.307[<sup>2</sup>](#table1)
- LAN Wins: 0.609[<sup>2</sup>](#table1)

The average of these factors is 0.500<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1421.9
- 400 + ( ( 0.500 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1421.9


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
|           81 |       29 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.96 | brnz4n, drop, exit, insani, saffee |
|           80 |       31 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.98 | brnz4n, drop, exit, insani, saffee |
|           79 |       45 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.723 (0.268)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |       72 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.831 (0.308)    | -         |     4.99 | brnz4n, drop, exit, insani, saffee |
|           77 |      117 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.62 | brnz4n, drop, exit, insani, saffee |
|           76 |      120 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |     5.46 | brnz4n, drop, exit, insani, saffee |
|           75 |      126 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |     5.75 | brnz4n, drop, exit, insani, saffee |
|           74 |      156 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.05 | brnz4n, drop, exit, insani, saffee |
|           73 |      159 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           72 |      165 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      201 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.61 | brnz4n, drop, exit, insani, saffee |
|           70 |      226 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.40 | brnz4n, drop, exit, insani, saffee |
|           69 |      232 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.63 | brnz4n, drop, exit, insani, saffee |
|           68 |      322 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.22 | brnz4n, drop, exit, insani, saffee |
|           67 |      323 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           66 |      586 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.32 | brnz4n, drop, exit, insani, saffee |
|           65 |      641 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.45 | brnz4n, drop, exit, insani, saffee |
|           64 |     1008 | 2024-06-15 | Complexity     | L   | 0.867      | -            | -                | -                | -         |    -6.97 | brnz4n, drop, exit, insani, saffee |
|           63 |     1034 | 2024-06-14 | Alliance       | W   | 0.862      | -            | -                | -                | 1 (0.862) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1047 | 2024-06-14 | ENCE           | L   | 0.861      | -            | -                | -                | -         |   -16.19 | brnz4n, drop, exit, insani, saffee |
|           61 |     1289 | 2024-06-07 | Bounty Hunters | L   | 0.817      | -            | -                | -                | -         |   -24.45 | brnz4n, drop, exit, insani, saffee |
|           60 |     1350 | 2024-06-06 | 9z             | L   | 0.810      | -            | -                | -                | -         |   -12.26 | brnz4n, drop, exit, insani, saffee |
|           59 |     1418 | 2024-06-05 | BESTIA         | W   | 0.803      | 0.450        | -                | 0.801 (0.289)    | -         |     2.56 | brnz4n, drop, exit, insani, saffee |
|           58 |     1472 | 2024-06-04 | Galorys        | W   | 0.797      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1796 | 2024-05-22 | paiN           | W   | 0.709      | 0.450        | 0.327 (0.104)    | 0.866 (0.276)    | -         |     8.53 | brnz4n, drop, exit, insani, saffee |
|           56 |     1800 | 2024-05-22 | paiN           | W   | 0.709      | 0.450        | 0.327 (0.104)    | 0.866 (0.276)    | -         |     9.06 | brnz4n, drop, exit, insani, saffee |
|           55 |     1874 | 2024-05-20 | BetBoom        | L   | 0.696      | -            | -                | -                | -         |   -12.92 | brnz4n, drop, exit, insani, saffee |
|           54 |     1885 | 2024-05-20 | BIG            | W   | 0.694      | 0.769        | 0.155 (0.083)    | -                | -         |     6.79 | brnz4n, drop, exit, insani, saffee |
|           53 |     1894 | 2024-05-20 | BetBoom        | L   | 0.693      | -            | -                | -                | -         |   -13.36 | brnz4n, drop, exit, insani, saffee |
|           52 |     1971 | 2024-05-17 | HEROIC         | L   | 0.675      | -            | -                | -                | -         |    -7.81 | brnz4n, drop, exit, insani, saffee |
|           51 |     2004 | 2024-05-16 | Aurora         | W   | 0.669      | 0.769        | 0.424 (0.218)    | 0.793 (0.408)    | 1 (0.669) |    13.46 | brnz4n, drop, exit, insani, saffee |
|           50 |     2062 | 2024-05-15 | HEROIC         | L   | 0.661      | -            | -                | -                | -         |    -7.63 | brnz4n, drop, exit, insani, saffee |
|           49 |     2468 | 2024-04-28 | Aurora         | W   | 0.546      | 0.500        | 0.424 (0.116)    | -                | 1 (0.546) |    12.25 | brnz4n, drop, exit, insani, saffee |
|           48 |     2471 | 2024-04-27 | Apeks          | W   | 0.545      | -            | -                | -                | 1 (0.545) |     1.10 | brnz4n, drop, exit, insani, saffee |
|           47 |     2497 | 2024-04-26 | Rooster        | W   | 0.539      | -            | -                | -                | 1 (0.539) |     0.45 | brnz4n, drop, exit, insani, saffee |
|           46 |     2520 | 2024-04-26 | Rebels         | L   | 0.533      | -            | -                | -                | -         |   -15.58 | brnz4n, drop, exit, insani, saffee |
|           45 |     2523 | 2024-04-25 | KZG            | W   | 0.531      | -            | -                | -                | 1 (0.531) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2633 | 2024-04-20 | paiN           | L   | 0.495      | -            | -                | -                | -         |    -9.09 | brnz4n, drop, exit, insani, saffee |
|           43 |     2642 | 2024-04-20 | OG             | W   | 0.494      | -            | -                | -                | 1 (0.494) |     1.57 | brnz4n, drop, exit, insani, saffee |
|           42 |     2655 | 2024-04-19 | paiN           | W   | 0.491      | -            | -                | -                | -         |     6.82 | brnz4n, drop, exit, insani, saffee |
|           41 |     2662 | 2024-04-19 | FURIA          | W   | 0.490      | 0.589        | 0.284 (0.082)    | -                | 1 (0.490) |    11.95 | brnz4n, drop, exit, insani, saffee |
|           40 |     2681 | 2024-04-19 | paiN           | L   | 0.489      | -            | -                | -                | -         |    -8.67 | brnz4n, drop, exit, insani, saffee |
|           39 |     2703 | 2024-04-18 | Imperial       | W   | 0.484      | -            | -                | -                | -         |     4.72 | brnz4n, drop, exit, insani, saffee |
|           38 |     2708 | 2024-04-18 | paiN           | W   | 0.483      | -            | -                | -                | -         |     6.83 | brnz4n, drop, exit, insani, saffee |
|           37 |     2712 | 2024-04-18 | OG             | W   | 0.483      | -            | -                | -                | 1 (0.483) |     1.56 | brnz4n, drop, exit, insani, saffee |
|           36 |     2757 | 2024-04-17 | RED Canids     | W   | 0.477      | -            | -                | -                | -         |     1.92 | brnz4n, drop, exit, insani, saffee |
|           35 |     2763 | 2024-04-17 | Case           | W   | 0.476      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2802 | 2024-04-16 | Bounty Hunters | W   | 0.470      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2823 | 2024-04-15 | Imperial       | W   | 0.463      | 0.435        | 0.237 (0.048)    | -                | -         |     4.57 | brnz4n, drop, exit, insani, saffee |
|           32 |     2837 | 2024-04-14 | Galorys        | W   | 0.456      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2851 | 2024-04-13 | Case           | W   | 0.449      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2882 | 2024-04-11 | paiN           | W   | 0.437      | -            | -                | -                | -         |     6.80 | brnz4n, drop, exit, insani, saffee |
|           29 |     2920 | 2024-04-10 | Galorys        | W   | 0.430      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2924 | 2024-04-10 | Galorys        | W   | 0.430      | -            | -                | -                | -         |     0.72 | brnz4n, drop, exit, insani, saffee |
|           27 |     2941 | 2024-04-10 | Imperial       | W   | 0.428      | -            | -                | -                | -         |     4.51 | brnz4n, drop, exit, insani, saffee |
|           26 |     2972 | 2024-04-09 | adalYamigos    | W   | 0.424      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     2977 | 2024-04-09 | adalYamigos    | W   | 0.423      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     2984 | 2024-04-09 | RED Canids     | W   | 0.422      | -            | -                | -                | -         |     1.86 | brnz4n, drop, exit, insani, saffee |
|           23 |     3014 | 2024-04-08 | W7M            | W   | 0.417      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           22 |     3048 | 2024-04-07 | paiN           | W   | 0.411      | -            | -                | -                | -         |     6.79 | brnz4n, drop, exit, insani, saffee |
|           21 |     3065 | 2024-04-06 | Bounty Hunters | W   | 0.404      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           20 |     3082 | 2024-04-05 | Fluxo          | W   | 0.397      | -            | -                | -                | -         |     1.61 | brnz4n, drop, exit, insani, saffee |
|           19 |     3083 | 2024-04-05 | Fluxo          | L   | 0.397      | -            | -                | -                | -         |   -11.02 | brnz4n, drop, exit, insani, saffee |
|           18 |     3086 | 2024-04-05 | ODDIK          | W   | 0.396      | -            | -                | -                | -         |     0.99 | brnz4n, drop, exit, insani, saffee |
|           17 |     3107 | 2024-04-04 | Solid          | W   | 0.390      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3113 | 2024-04-04 | Solid          | W   | 0.390      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           15 |     3146 | 2024-04-03 | Fluxo          | W   | 0.384      | -            | -                | -                | -         |     1.47 | brnz4n, drop, exit, insani, saffee |
|           14 |     3194 | 2024-04-02 | Fluxo          | W   | 0.377      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           13 |     3197 | 2024-04-02 | Sharks         | W   | 0.376      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3283 | 2024-03-27 | Case           | W   | 0.337      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3289 | 2024-03-27 | Case           | W   | 0.337      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           10 |     3329 | 2024-03-26 | ODDIK          | W   | 0.331      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|            9 |     3331 | 2024-03-26 | ODDIK          | W   | 0.330      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|            8 |     3523 | 2024-03-14 | Sharks         | W   | 0.251      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|            7 |     3525 | 2024-03-14 | Sharks         | W   | 0.250      | -            | -                | -                | -         |     0.66 | brnz4n, drop, exit, insani, saffee |
|            6 |     3597 | 2024-03-12 | Fluxo          | L   | 0.236      | -            | -                | -                | -         |    -6.56 | brnz4n, drop, exit, insani, saffee |
|            5 |     3636 | 2024-03-10 | Galorys        | W   | 0.223      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|            4 |     3684 | 2024-03-08 | LA RUGONETA    | W   | 0.209      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3815 | 2024-03-03 | Legacy         | L   | 0.176      | -            | -                | -                | -         |    -5.04 | brnz4n, drop, exit, insani, saffee |
|            2 |     3847 | 2024-03-02 | NRG            | W   | 0.169      | -            | -                | -                | 1 (0.169) |     0.22 | brnz4n, drop, exit, insani, saffee |
|            1 |     3869 | 2024-03-01 | BOSS           | L   | 0.163      | -            | -                | -                | -         |    -4.97 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,929.35)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.874 | $3,000.00      | $2,623.33       |
| 2024-06-09 |      0.830 | $3,000.00      | $2,488.89       |
| 2024-04-28 |      0.546 | $50,000.00     | $27,321.76      |
| 2024-04-20 |      0.496 | $20,000.00     | $9,925.93       |
| 2024-04-15 |      0.463 | $25,000.00     | $11,569.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
