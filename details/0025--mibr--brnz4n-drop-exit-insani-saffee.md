### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1313.3<br />
<br />
Final Rank Value (1313.3) = Starting Rank Value (1413.8) + Head To Head Adjustments (-100.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.594[<sup>1</sup>](#table2)
- Bounty Collected: 0.485[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.598[<sup>2</sup>](#table1)

The average of these factors is 0.493<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1413.8
- 400 + ( ( 0.493 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1413.8


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
|           81 |      106 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.99 | brnz4n, drop, exit, insani, saffee |
|           80 |      108 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.96 | brnz4n, drop, exit, insani, saffee |
|           79 |      122 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.701 (0.260)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      149 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.805 (0.298)    | -         |     5.02 | brnz4n, drop, exit, insani, saffee |
|           77 |      196 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.63 | brnz4n, drop, exit, insani, saffee |
|           76 |      199 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.49 | brnz4n, drop, exit, insani, saffee |
|           75 |      205 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |     5.78 | brnz4n, drop, exit, insani, saffee |
|           74 |      235 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.03 | brnz4n, drop, exit, insani, saffee |
|           73 |      238 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      244 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|           71 |      280 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.67 | brnz4n, drop, exit, insani, saffee |
|           70 |      305 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      311 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      401 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      402 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.530 (0.239)    | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           66 |      665 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.14 | brnz4n, drop, exit, insani, saffee |
|           65 |      717 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.42 | brnz4n, drop, exit, insani, saffee |
|           64 |     1087 | 2024-06-15 | Complexity     | L   | 0.852      | -            | -                | -                | -         |    -6.50 | brnz4n, drop, exit, insani, saffee |
|           63 |     1113 | 2024-06-14 | Alliance       | W   | 0.847      | -            | -                | -                | 1 (0.847) |     1.26 | brnz4n, drop, exit, insani, saffee |
|           62 |     1126 | 2024-06-14 | ENCE           | L   | 0.846      | -            | -                | -                | -         |   -15.22 | brnz4n, drop, exit, insani, saffee |
|           61 |     1368 | 2024-06-07 | Bounty Hunters | L   | 0.802      | -            | -                | -                | -         |   -23.98 | brnz4n, drop, exit, insani, saffee |
|           60 |     1429 | 2024-06-06 | 9z             | L   | 0.795      | -            | -                | -                | -         |   -11.81 | brnz4n, drop, exit, insani, saffee |
|           59 |     1497 | 2024-06-05 | BESTIA         | W   | 0.788      | 0.450        | -                | 0.776 (0.275)    | -         |     2.54 | brnz4n, drop, exit, insani, saffee |
|           58 |     1551 | 2024-06-04 | Galorys        | W   | 0.782      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1875 | 2024-05-22 | paiN           | W   | 0.694      | 0.450        | 0.324 (0.101)    | 0.839 (0.262)    | -         |     8.34 | brnz4n, drop, exit, insani, saffee |
|           56 |     1879 | 2024-05-22 | paiN           | W   | 0.694      | 0.450        | 0.324 (0.101)    | 0.839 (0.262)    | -         |     8.84 | brnz4n, drop, exit, insani, saffee |
|           55 |     1953 | 2024-05-20 | BetBoom        | L   | 0.681      | -            | -                | -                | -         |   -12.54 | brnz4n, drop, exit, insani, saffee |
|           54 |     1964 | 2024-05-20 | BIG            | W   | 0.679      | 0.769        | 0.154 (0.080)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1973 | 2024-05-20 | BetBoom        | L   | 0.678      | -            | -                | -                | -         |   -12.96 | brnz4n, drop, exit, insani, saffee |
|           52 |     2050 | 2024-05-17 | HEROIC         | L   | 0.660      | -            | -                | -                | -         |    -7.47 | brnz4n, drop, exit, insani, saffee |
|           51 |     2083 | 2024-05-16 | Aurora         | W   | 0.654      | 0.769        | 0.420 (0.211)    | 0.758 (0.381)    | 1 (0.654) |    13.66 | brnz4n, drop, exit, insani, saffee |
|           50 |     2141 | 2024-05-15 | HEROIC         | L   | 0.646      | -            | -                | -                | -         |    -7.28 | brnz4n, drop, exit, insani, saffee |
|           49 |     2547 | 2024-04-28 | Aurora         | W   | 0.531      | 0.500        | 0.420 (0.112)    | -                | 1 (0.531) |    12.28 | brnz4n, drop, exit, insani, saffee |
|           48 |     2550 | 2024-04-27 | Apeks          | W   | 0.530      | -            | -                | -                | 1 (0.530) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2576 | 2024-04-26 | Rooster        | W   | 0.524      | -            | -                | -                | 1 (0.524) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2599 | 2024-04-26 | Rebels         | L   | 0.518      | -            | -                | -                | -         |   -15.09 | brnz4n, drop, exit, insani, saffee |
|           45 |     2602 | 2024-04-25 | KZG            | W   | 0.516      | -            | -                | -                | 1 (0.516) |     0.22 | brnz4n, drop, exit, insani, saffee |
|           44 |     2712 | 2024-04-20 | paiN           | L   | 0.480      | -            | -                | -                | -         |    -8.83 | brnz4n, drop, exit, insani, saffee |
|           43 |     2721 | 2024-04-20 | OG             | W   | 0.479      | -            | -                | -                | 1 (0.479) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           42 |     2734 | 2024-04-19 | paiN           | W   | 0.476      | -            | -                | -                | -         |     6.60 | brnz4n, drop, exit, insani, saffee |
|           41 |     2741 | 2024-04-19 | FURIA          | W   | 0.475      | 0.589        | 0.284 (0.079)    | -                | 1 (0.475) |    11.74 | brnz4n, drop, exit, insani, saffee |
|           40 |     2760 | 2024-04-19 | paiN           | L   | 0.474      | -            | -                | -                | -         |    -8.42 | brnz4n, drop, exit, insani, saffee |
|           39 |     2782 | 2024-04-18 | Imperial       | W   | 0.469      | -            | -                | -                | -         |     4.54 | brnz4n, drop, exit, insani, saffee |
|           38 |     2787 | 2024-04-18 | paiN           | W   | 0.468      | -            | -                | -                | -         |     6.60 | brnz4n, drop, exit, insani, saffee |
|           37 |     2791 | 2024-04-18 | OG             | W   | 0.468      | -            | -                | -                | 1 (0.468) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           36 |     2836 | 2024-04-17 | RED Canids     | W   | 0.462      | -            | -                | -                | -         |     1.88 | brnz4n, drop, exit, insani, saffee |
|           35 |     2842 | 2024-04-17 | Case           | W   | 0.461      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2881 | 2024-04-16 | Bounty Hunters | W   | 0.455      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2902 | 2024-04-15 | Imperial       | W   | 0.448      | 0.435        | 0.233 (0.045)    | -                | -         |     4.38 | brnz4n, drop, exit, insani, saffee |
|           32 |     2916 | 2024-04-14 | Galorys        | W   | 0.441      | -            | -                | -                | -         |     0.77 | brnz4n, drop, exit, insani, saffee |
|           31 |     2930 | 2024-04-13 | Case           | W   | 0.434      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2961 | 2024-04-11 | paiN           | W   | 0.422      | -            | -                | -                | -         |     6.52 | brnz4n, drop, exit, insani, saffee |
|           29 |     2999 | 2024-04-10 | Galorys        | W   | 0.415      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     3003 | 2024-04-10 | Galorys        | W   | 0.415      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     3020 | 2024-04-10 | Imperial       | W   | 0.413      | -            | -                | -                | -         |     4.29 | brnz4n, drop, exit, insani, saffee |
|           26 |     3051 | 2024-04-09 | adalYamigos    | W   | 0.409      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3056 | 2024-04-09 | adalYamigos    | W   | 0.408      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3063 | 2024-04-09 | RED Canids     | W   | 0.407      | -            | -                | -                | -         |     1.81 | brnz4n, drop, exit, insani, saffee |
|           23 |     3093 | 2024-04-08 | W7M            | W   | 0.402      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3127 | 2024-04-07 | paiN           | W   | 0.396      | -            | -                | -                | -         |     6.48 | brnz4n, drop, exit, insani, saffee |
|           21 |     3144 | 2024-04-06 | Bounty Hunters | W   | 0.389      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3161 | 2024-04-05 | Fluxo          | W   | 0.382      | -            | -                | -                | -         |     1.57 | brnz4n, drop, exit, insani, saffee |
|           19 |     3162 | 2024-04-05 | Fluxo          | L   | 0.382      | -            | -                | -                | -         |   -10.58 | brnz4n, drop, exit, insani, saffee |
|           18 |     3165 | 2024-04-05 | ODDIK          | W   | 0.381      | -            | -                | -                | -         |     0.97 | brnz4n, drop, exit, insani, saffee |
|           17 |     3186 | 2024-04-04 | Solid          | W   | 0.375      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           16 |     3192 | 2024-04-04 | Solid          | W   | 0.375      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3225 | 2024-04-03 | Fluxo          | W   | 0.369      | -            | -                | -                | -         |     1.43 | brnz4n, drop, exit, insani, saffee |
|           14 |     3273 | 2024-04-02 | Fluxo          | W   | 0.362      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           13 |     3276 | 2024-04-02 | Sharks         | W   | 0.361      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3362 | 2024-03-27 | Case           | W   | 0.322      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|           11 |     3368 | 2024-03-27 | Case           | W   | 0.322      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3408 | 2024-03-26 | ODDIK          | W   | 0.316      | -            | -                | -                | -         |     0.89 | brnz4n, drop, exit, insani, saffee |
|            9 |     3410 | 2024-03-26 | ODDIK          | W   | 0.315      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            8 |     3602 | 2024-03-14 | Sharks         | W   | 0.236      | -            | -                | -                | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|            7 |     3604 | 2024-03-14 | Sharks         | W   | 0.235      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            6 |     3676 | 2024-03-12 | Fluxo          | L   | 0.221      | -            | -                | -                | -         |    -6.13 | brnz4n, drop, exit, insani, saffee |
|            5 |     3715 | 2024-03-10 | Galorys        | W   | 0.208      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3763 | 2024-03-08 | LA RUGONETA    | W   | 0.194      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3894 | 2024-03-03 | Legacy         | L   | 0.161      | -            | -                | -                | -         |    -4.60 | brnz4n, drop, exit, insani, saffee |
|            2 |     3926 | 2024-03-02 | NRG            | W   | 0.154      | -            | -                | -                | 1 (0.154) |     0.20 | brnz4n, drop, exit, insani, saffee |
|            1 |     3948 | 2024-03-01 | BOSS           | L   | 0.148      | -            | -                | -                | -         |    -4.50 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,414.35)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.859 | $3,000.00      | $2,578.33       |
| 2024-06-09 |      0.815 | $3,000.00      | $2,443.89       |
| 2024-04-28 |      0.531 | $50,000.00     | $26,571.76      |
| 2024-04-20 |      0.481 | $20,000.00     | $9,625.93       |
| 2024-04-15 |      0.448 | $25,000.00     | $11,194.44      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
