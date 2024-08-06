### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1313.6<br />
<br />
Final Rank Value (1313.6) = Starting Rank Value (1414.4) + Head To Head Adjustments (-100.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.485[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.599[<sup>2</sup>](#table1)

The average of these factors is 0.493<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.4
- 400 + ( ( 0.493 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1414.4


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
|           81 |       95 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.99 | brnz4n, drop, exit, insani, saffee |
|           80 |       97 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.96 | brnz4n, drop, exit, insani, saffee |
|           79 |      111 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.701 (0.260)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      138 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.805 (0.298)    | -         |     5.01 | brnz4n, drop, exit, insani, saffee |
|           77 |      185 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.62 | brnz4n, drop, exit, insani, saffee |
|           76 |      188 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.48 | brnz4n, drop, exit, insani, saffee |
|           75 |      194 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.78 | brnz4n, drop, exit, insani, saffee |
|           74 |      224 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      227 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      233 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|           71 |      269 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.67 | brnz4n, drop, exit, insani, saffee |
|           70 |      294 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.38 | brnz4n, drop, exit, insani, saffee |
|           69 |      300 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      390 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      391 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           66 |      654 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.15 | brnz4n, drop, exit, insani, saffee |
|           65 |      706 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.42 | brnz4n, drop, exit, insani, saffee |
|           64 |     1076 | 2024-06-15 | Complexity     | L   | 0.853      | -            | -                | -                | -         |    -6.51 | brnz4n, drop, exit, insani, saffee |
|           63 |     1102 | 2024-06-14 | Alliance       | W   | 0.848      | -            | -                | -                | 1 (0.848) |     1.26 | brnz4n, drop, exit, insani, saffee |
|           62 |     1115 | 2024-06-14 | ENCE           | L   | 0.847      | -            | -                | -                | -         |   -15.26 | brnz4n, drop, exit, insani, saffee |
|           61 |     1357 | 2024-06-07 | Bounty Hunters | L   | 0.803      | -            | -                | -                | -         |   -24.02 | brnz4n, drop, exit, insani, saffee |
|           60 |     1418 | 2024-06-06 | 9z             | L   | 0.796      | -            | -                | -                | -         |   -11.84 | brnz4n, drop, exit, insani, saffee |
|           59 |     1486 | 2024-06-05 | BESTIA         | W   | 0.790      | 0.450        | -                | 0.775 (0.276)    | -         |     2.54 | brnz4n, drop, exit, insani, saffee |
|           58 |     1540 | 2024-06-04 | Galorys        | W   | 0.783      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1864 | 2024-05-22 | paiN           | W   | 0.696      | 0.450        | 0.324 (0.101)    | 0.838 (0.262)    | -         |     8.36 | brnz4n, drop, exit, insani, saffee |
|           56 |     1868 | 2024-05-22 | paiN           | W   | 0.695      | 0.450        | 0.324 (0.101)    | 0.838 (0.262)    | -         |     8.86 | brnz4n, drop, exit, insani, saffee |
|           55 |     1942 | 2024-05-20 | BetBoom        | L   | 0.682      | -            | -                | -                | -         |   -12.57 | brnz4n, drop, exit, insani, saffee |
|           54 |     1953 | 2024-05-20 | BIG            | W   | 0.680      | 0.769        | 0.154 (0.081)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1962 | 2024-05-20 | BetBoom        | L   | 0.679      | -            | -                | -                | -         |   -13.00 | brnz4n, drop, exit, insani, saffee |
|           52 |     2039 | 2024-05-17 | HEROIC         | L   | 0.661      | -            | -                | -                | -         |    -7.49 | brnz4n, drop, exit, insani, saffee |
|           51 |     2072 | 2024-05-16 | Aurora         | W   | 0.655      | 0.769        | 0.421 (0.212)    | 0.759 (0.382)    | 1 (0.655) |    13.66 | brnz4n, drop, exit, insani, saffee |
|           50 |     2130 | 2024-05-15 | HEROIC         | L   | 0.647      | -            | -                | -                | -         |    -7.29 | brnz4n, drop, exit, insani, saffee |
|           49 |     2536 | 2024-04-28 | Aurora         | W   | 0.533      | 0.500        | 0.421 (0.112)    | -                | 1 (0.533) |    12.29 | brnz4n, drop, exit, insani, saffee |
|           48 |     2539 | 2024-04-27 | Apeks          | W   | 0.531      | -            | -                | -                | 1 (0.531) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2565 | 2024-04-26 | Rooster        | W   | 0.525      | -            | -                | -                | 1 (0.525) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2588 | 2024-04-26 | Rebels         | L   | 0.519      | -            | -                | -                | -         |   -15.13 | brnz4n, drop, exit, insani, saffee |
|           45 |     2591 | 2024-04-25 | KZG            | W   | 0.518      | -            | -                | -                | 1 (0.518) |     0.22 | brnz4n, drop, exit, insani, saffee |
|           44 |     2701 | 2024-04-20 | paiN           | L   | 0.482      | -            | -                | -                | -         |    -8.86 | brnz4n, drop, exit, insani, saffee |
|           43 |     2710 | 2024-04-20 | OG             | W   | 0.481      | -            | -                | -                | 1 (0.481) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           42 |     2723 | 2024-04-19 | paiN           | W   | 0.477      | -            | -                | -                | -         |     6.62 | brnz4n, drop, exit, insani, saffee |
|           41 |     2730 | 2024-04-19 | FURIA          | W   | 0.477      | 0.589        | 0.284 (0.080)    | -                | 1 (0.477) |    11.77 | brnz4n, drop, exit, insani, saffee |
|           40 |     2749 | 2024-04-19 | paiN           | L   | 0.475      | -            | -                | -                | -         |    -8.44 | brnz4n, drop, exit, insani, saffee |
|           39 |     2771 | 2024-04-18 | Imperial       | W   | 0.471      | -            | -                | -                | -         |     4.55 | brnz4n, drop, exit, insani, saffee |
|           38 |     2776 | 2024-04-18 | paiN           | W   | 0.470      | -            | -                | -                | -         |     6.62 | brnz4n, drop, exit, insani, saffee |
|           37 |     2780 | 2024-04-18 | OG             | W   | 0.469      | -            | -                | -                | 1 (0.469) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           36 |     2825 | 2024-04-17 | RED Canids     | W   | 0.463      | -            | -                | -                | -         |     1.88 | brnz4n, drop, exit, insani, saffee |
|           35 |     2831 | 2024-04-17 | Case           | W   | 0.463      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2870 | 2024-04-16 | Bounty Hunters | W   | 0.457      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2891 | 2024-04-15 | Imperial       | W   | 0.449      | 0.435        | 0.233 (0.046)    | -                | -         |     4.40 | brnz4n, drop, exit, insani, saffee |
|           32 |     2905 | 2024-04-14 | Galorys        | W   | 0.443      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           31 |     2919 | 2024-04-13 | Case           | W   | 0.435      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2950 | 2024-04-11 | paiN           | W   | 0.423      | -            | -                | -                | -         |     6.55 | brnz4n, drop, exit, insani, saffee |
|           29 |     2988 | 2024-04-10 | Galorys        | W   | 0.417      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2992 | 2024-04-10 | Galorys        | W   | 0.416      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     3009 | 2024-04-10 | Imperial       | W   | 0.415      | -            | -                | -                | -         |     4.32 | brnz4n, drop, exit, insani, saffee |
|           26 |     3040 | 2024-04-09 | adalYamigos    | W   | 0.410      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3045 | 2024-04-09 | adalYamigos    | W   | 0.410      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3052 | 2024-04-09 | RED Canids     | W   | 0.409      | -            | -                | -                | -         |     1.82 | brnz4n, drop, exit, insani, saffee |
|           23 |     3082 | 2024-04-08 | W7M            | W   | 0.403      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3116 | 2024-04-07 | paiN           | W   | 0.397      | -            | -                | -                | -         |     6.51 | brnz4n, drop, exit, insani, saffee |
|           21 |     3133 | 2024-04-06 | Bounty Hunters | W   | 0.390      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3150 | 2024-04-05 | Fluxo          | W   | 0.384      | -            | -                | -                | -         |     1.57 | brnz4n, drop, exit, insani, saffee |
|           19 |     3151 | 2024-04-05 | Fluxo          | L   | 0.383      | -            | -                | -                | -         |   -10.62 | brnz4n, drop, exit, insani, saffee |
|           18 |     3154 | 2024-04-05 | ODDIK          | W   | 0.382      | -            | -                | -                | -         |     0.97 | brnz4n, drop, exit, insani, saffee |
|           17 |     3175 | 2024-04-04 | Solid          | W   | 0.377      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           16 |     3181 | 2024-04-04 | Solid          | W   | 0.376      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3214 | 2024-04-03 | Fluxo          | W   | 0.370      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           14 |     3262 | 2024-04-02 | Fluxo          | W   | 0.363      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           13 |     3265 | 2024-04-02 | Sharks         | W   | 0.362      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3351 | 2024-03-27 | Case           | W   | 0.324      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|           11 |     3357 | 2024-03-27 | Case           | W   | 0.323      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3397 | 2024-03-26 | ODDIK          | W   | 0.317      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            9 |     3399 | 2024-03-26 | ODDIK          | W   | 0.317      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            8 |     3591 | 2024-03-14 | Sharks         | W   | 0.237      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            7 |     3593 | 2024-03-14 | Sharks         | W   | 0.237      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            6 |     3665 | 2024-03-12 | Fluxo          | L   | 0.223      | -            | -                | -                | -         |    -6.17 | brnz4n, drop, exit, insani, saffee |
|            5 |     3704 | 2024-03-10 | Galorys        | W   | 0.210      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3752 | 2024-03-08 | LA RUGONETA    | W   | 0.196      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3883 | 2024-03-03 | Legacy         | L   | 0.163      | -            | -                | -                | -         |    -4.64 | brnz4n, drop, exit, insani, saffee |
|            2 |     3915 | 2024-03-02 | NRG            | W   | 0.155      | -            | -                | -                | 1 (0.155) |     0.21 | brnz4n, drop, exit, insani, saffee |
|            1 |     3937 | 2024-03-01 | BOSS           | L   | 0.149      | -            | -                | -                | -         |    -4.55 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,554.63)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.861 | $3,000.00      | $2,582.50       |
| 2024-06-09 |      0.816 | $3,000.00      | $2,448.06       |
| 2024-04-28 |      0.533 | $50,000.00     | $26,641.20      |
| 2024-04-20 |      0.483 | $20,000.00     | $9,653.70       |
| 2024-04-15 |      0.449 | $25,000.00     | $11,229.17      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
