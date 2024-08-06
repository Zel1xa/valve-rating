### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1313.5<br />
<br />
Final Rank Value (1313.5) = Starting Rank Value (1414.1) + Head To Head Adjustments (-100.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.485[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.599[<sup>2</sup>](#table1)

The average of these factors is 0.493<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1414.1
- 400 + ( ( 0.493 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1414.1


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
|           81 |       93 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.99 | brnz4n, drop, exit, insani, saffee |
|           80 |       95 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.96 | brnz4n, drop, exit, insani, saffee |
|           79 |      109 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.701 (0.260)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      136 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.805 (0.298)    | -         |     5.02 | brnz4n, drop, exit, insani, saffee |
|           77 |      183 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.63 | brnz4n, drop, exit, insani, saffee |
|           76 |      186 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.49 | brnz4n, drop, exit, insani, saffee |
|           75 |      192 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.78 | brnz4n, drop, exit, insani, saffee |
|           74 |      222 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      225 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      231 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|           71 |      267 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.67 | brnz4n, drop, exit, insani, saffee |
|           70 |      292 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      298 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      388 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      389 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           66 |      652 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.15 | brnz4n, drop, exit, insani, saffee |
|           65 |      704 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.42 | brnz4n, drop, exit, insani, saffee |
|           64 |     1074 | 2024-06-15 | Complexity     | L   | 0.853      | -            | -                | -                | -         |    -6.51 | brnz4n, drop, exit, insani, saffee |
|           63 |     1100 | 2024-06-14 | Alliance       | W   | 0.848      | -            | -                | -                | 1 (0.848) |     1.26 | brnz4n, drop, exit, insani, saffee |
|           62 |     1113 | 2024-06-14 | ENCE           | L   | 0.846      | -            | -                | -                | -         |   -15.24 | brnz4n, drop, exit, insani, saffee |
|           61 |     1355 | 2024-06-07 | Bounty Hunters | L   | 0.803      | -            | -                | -                | -         |   -24.00 | brnz4n, drop, exit, insani, saffee |
|           60 |     1416 | 2024-06-06 | 9z             | L   | 0.796      | -            | -                | -                | -         |   -11.82 | brnz4n, drop, exit, insani, saffee |
|           59 |     1484 | 2024-06-05 | BESTIA         | W   | 0.789      | 0.450        | -                | 0.776 (0.276)    | -         |     2.54 | brnz4n, drop, exit, insani, saffee |
|           58 |     1538 | 2024-06-04 | Galorys        | W   | 0.783      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1862 | 2024-05-22 | paiN           | W   | 0.695      | 0.450        | 0.324 (0.101)    | 0.839 (0.262)    | -         |     8.35 | brnz4n, drop, exit, insani, saffee |
|           56 |     1866 | 2024-05-22 | paiN           | W   | 0.695      | 0.450        | 0.324 (0.101)    | 0.839 (0.262)    | -         |     8.85 | brnz4n, drop, exit, insani, saffee |
|           55 |     1940 | 2024-05-20 | BetBoom        | L   | 0.682      | -            | -                | -                | -         |   -12.56 | brnz4n, drop, exit, insani, saffee |
|           54 |     1951 | 2024-05-20 | BIG            | W   | 0.680      | 0.769        | 0.154 (0.080)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1960 | 2024-05-20 | BetBoom        | L   | 0.679      | -            | -                | -                | -         |   -12.98 | brnz4n, drop, exit, insani, saffee |
|           52 |     2037 | 2024-05-17 | HEROIC         | L   | 0.661      | -            | -                | -                | -         |    -7.48 | brnz4n, drop, exit, insani, saffee |
|           51 |     2070 | 2024-05-16 | Aurora         | W   | 0.654      | 0.769        | 0.420 (0.211)    | 0.759 (0.382)    | 1 (0.654) |    13.66 | brnz4n, drop, exit, insani, saffee |
|           50 |     2128 | 2024-05-15 | HEROIC         | L   | 0.647      | -            | -                | -                | -         |    -7.29 | brnz4n, drop, exit, insani, saffee |
|           49 |     2534 | 2024-04-28 | Aurora         | W   | 0.532      | 0.500        | 0.420 (0.112)    | -                | 1 (0.532) |    12.28 | brnz4n, drop, exit, insani, saffee |
|           48 |     2537 | 2024-04-27 | Apeks          | W   | 0.530      | -            | -                | -                | 1 (0.530) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2563 | 2024-04-26 | Rooster        | W   | 0.524      | -            | -                | -                | 1 (0.524) |     0.45 | brnz4n, drop, exit, insani, saffee |
|           46 |     2586 | 2024-04-26 | Rebels         | L   | 0.518      | -            | -                | -                | -         |   -15.12 | brnz4n, drop, exit, insani, saffee |
|           45 |     2589 | 2024-04-25 | KZG            | W   | 0.517      | -            | -                | -                | 1 (0.517) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2699 | 2024-04-20 | paiN           | L   | 0.481      | -            | -                | -                | -         |    -8.84 | brnz4n, drop, exit, insani, saffee |
|           43 |     2708 | 2024-04-20 | OG             | W   | 0.480      | -            | -                | -                | 1 (0.480) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           42 |     2721 | 2024-04-19 | paiN           | W   | 0.477      | -            | -                | -                | -         |     6.61 | brnz4n, drop, exit, insani, saffee |
|           41 |     2728 | 2024-04-19 | FURIA          | W   | 0.476      | 0.589        | 0.284 (0.080)    | -                | 1 (0.476) |    11.75 | brnz4n, drop, exit, insani, saffee |
|           40 |     2747 | 2024-04-19 | paiN           | L   | 0.474      | -            | -                | -                | -         |    -8.43 | brnz4n, drop, exit, insani, saffee |
|           39 |     2769 | 2024-04-18 | Imperial       | W   | 0.470      | -            | -                | -                | -         |     4.55 | brnz4n, drop, exit, insani, saffee |
|           38 |     2774 | 2024-04-18 | paiN           | W   | 0.469      | -            | -                | -                | -         |     6.61 | brnz4n, drop, exit, insani, saffee |
|           37 |     2778 | 2024-04-18 | OG             | W   | 0.469      | -            | -                | -                | 1 (0.469) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           36 |     2823 | 2024-04-17 | RED Canids     | W   | 0.463      | -            | -                | -                | -         |     1.88 | brnz4n, drop, exit, insani, saffee |
|           35 |     2829 | 2024-04-17 | Case           | W   | 0.462      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2868 | 2024-04-16 | Bounty Hunters | W   | 0.456      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2889 | 2024-04-15 | Imperial       | W   | 0.449      | 0.435        | 0.233 (0.045)    | -                | -         |     4.39 | brnz4n, drop, exit, insani, saffee |
|           32 |     2903 | 2024-04-14 | Galorys        | W   | 0.442      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           31 |     2917 | 2024-04-13 | Case           | W   | 0.434      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2948 | 2024-04-11 | paiN           | W   | 0.423      | -            | -                | -                | -         |     6.54 | brnz4n, drop, exit, insani, saffee |
|           29 |     2986 | 2024-04-10 | Galorys        | W   | 0.416      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2990 | 2024-04-10 | Galorys        | W   | 0.416      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     3007 | 2024-04-10 | Imperial       | W   | 0.414      | -            | -                | -                | -         |     4.31 | brnz4n, drop, exit, insani, saffee |
|           26 |     3038 | 2024-04-09 | adalYamigos    | W   | 0.409      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3043 | 2024-04-09 | adalYamigos    | W   | 0.409      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3050 | 2024-04-09 | RED Canids     | W   | 0.408      | -            | -                | -                | -         |     1.81 | brnz4n, drop, exit, insani, saffee |
|           23 |     3080 | 2024-04-08 | W7M            | W   | 0.403      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3114 | 2024-04-07 | paiN           | W   | 0.396      | -            | -                | -                | -         |     6.50 | brnz4n, drop, exit, insani, saffee |
|           21 |     3131 | 2024-04-06 | Bounty Hunters | W   | 0.389      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3148 | 2024-04-05 | Fluxo          | W   | 0.383      | -            | -                | -                | -         |     1.57 | brnz4n, drop, exit, insani, saffee |
|           19 |     3149 | 2024-04-05 | Fluxo          | L   | 0.383      | -            | -                | -                | -         |   -10.60 | brnz4n, drop, exit, insani, saffee |
|           18 |     3152 | 2024-04-05 | ODDIK          | W   | 0.381      | -            | -                | -                | -         |     0.97 | brnz4n, drop, exit, insani, saffee |
|           17 |     3173 | 2024-04-04 | Solid          | W   | 0.376      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           16 |     3179 | 2024-04-04 | Solid          | W   | 0.376      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3212 | 2024-04-03 | Fluxo          | W   | 0.369      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           14 |     3260 | 2024-04-02 | Fluxo          | W   | 0.363      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           13 |     3263 | 2024-04-02 | Sharks         | W   | 0.362      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3349 | 2024-03-27 | Case           | W   | 0.323      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|           11 |     3355 | 2024-03-27 | Case           | W   | 0.323      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3395 | 2024-03-26 | ODDIK          | W   | 0.316      | -            | -                | -                | -         |     0.89 | brnz4n, drop, exit, insani, saffee |
|            9 |     3397 | 2024-03-26 | ODDIK          | W   | 0.316      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            8 |     3589 | 2024-03-14 | Sharks         | W   | 0.236      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            7 |     3591 | 2024-03-14 | Sharks         | W   | 0.236      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            6 |     3663 | 2024-03-12 | Fluxo          | L   | 0.222      | -            | -                | -                | -         |    -6.15 | brnz4n, drop, exit, insani, saffee |
|            5 |     3702 | 2024-03-10 | Galorys        | W   | 0.209      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3750 | 2024-03-08 | LA RUGONETA    | W   | 0.195      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3881 | 2024-03-03 | Legacy         | L   | 0.162      | -            | -                | -                | -         |    -4.62 | brnz4n, drop, exit, insani, saffee |
|            2 |     3913 | 2024-03-02 | NRG            | W   | 0.155      | -            | -                | -                | 1 (0.155) |     0.20 | brnz4n, drop, exit, insani, saffee |
|            1 |     3935 | 2024-03-01 | BOSS           | L   | 0.149      | -            | -                | -                | -         |    -4.53 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,489.17)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.860 | $3,000.00      | $2,580.56       |
| 2024-06-09 |      0.815 | $3,000.00      | $2,446.11       |
| 2024-04-28 |      0.532 | $50,000.00     | $26,608.80      |
| 2024-04-20 |      0.482 | $20,000.00     | $9,640.74       |
| 2024-04-15 |      0.449 | $25,000.00     | $11,212.96      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
