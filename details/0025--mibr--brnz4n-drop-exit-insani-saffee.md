### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1315.6<br />
<br />
Final Rank Value (1315.6) = Starting Rank Value (1417.6) + Head To Head Adjustments (-102.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.486[<sup>2</sup>](#table1)
- Opponent Network: 0.302[<sup>2</sup>](#table1)
- LAN Wins: 0.603[<sup>2</sup>](#table1)

The average of these factors is 0.496<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1417.6
- 400 + ( ( 0.496 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1417.6


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
|           81 |       84 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.98 | brnz4n, drop, exit, insani, saffee |
|           80 |       86 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.98 | brnz4n, drop, exit, insani, saffee |
|           79 |      100 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.716 (0.265)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      127 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.822 (0.305)    | -         |     5.00 | brnz4n, drop, exit, insani, saffee |
|           77 |      174 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.62 | brnz4n, drop, exit, insani, saffee |
|           76 |      177 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |     5.47 | brnz4n, drop, exit, insani, saffee |
|           75 |      183 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |     5.76 | brnz4n, drop, exit, insani, saffee |
|           74 |      213 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.04 | brnz4n, drop, exit, insani, saffee |
|           73 |      216 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.26 | brnz4n, drop, exit, insani, saffee |
|           72 |      222 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      258 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.66 | brnz4n, drop, exit, insani, saffee |
|           70 |      283 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.38 | brnz4n, drop, exit, insani, saffee |
|           69 |      289 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.67 | brnz4n, drop, exit, insani, saffee |
|           68 |      379 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.22 | brnz4n, drop, exit, insani, saffee |
|           67 |      380 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.24 | brnz4n, drop, exit, insani, saffee |
|           66 |      643 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.18 | brnz4n, drop, exit, insani, saffee |
|           65 |      695 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.43 | brnz4n, drop, exit, insani, saffee |
|           64 |     1065 | 2024-06-15 | Complexity     | L   | 0.858      | -            | -                | -                | -         |    -6.59 | brnz4n, drop, exit, insani, saffee |
|           63 |     1091 | 2024-06-14 | Alliance       | W   | 0.853      | -            | -                | -                | 1 (0.853) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1104 | 2024-06-14 | ENCE           | L   | 0.852      | -            | -                | -                | -         |   -15.49 | brnz4n, drop, exit, insani, saffee |
|           61 |     1346 | 2024-06-07 | Bounty Hunters | L   | 0.808      | -            | -                | -                | -         |   -24.18 | brnz4n, drop, exit, insani, saffee |
|           60 |     1407 | 2024-06-06 | 9z             | L   | 0.801      | -            | -                | -                | -         |   -11.96 | brnz4n, drop, exit, insani, saffee |
|           59 |     1475 | 2024-06-05 | BESTIA         | W   | 0.795      | 0.450        | -                | 0.792 (0.283)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1529 | 2024-06-04 | Galorys        | W   | 0.788      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1853 | 2024-05-22 | paiN           | W   | 0.701      | 0.450        | 0.325 (0.103)    | 0.856 (0.270)    | -         |     8.42 | brnz4n, drop, exit, insani, saffee |
|           56 |     1857 | 2024-05-22 | paiN           | W   | 0.700      | 0.450        | 0.325 (0.102)    | 0.856 (0.270)    | -         |     8.93 | brnz4n, drop, exit, insani, saffee |
|           55 |     1931 | 2024-05-20 | BetBoom        | L   | 0.687      | -            | -                | -                | -         |   -12.72 | brnz4n, drop, exit, insani, saffee |
|           54 |     1942 | 2024-05-20 | BIG            | W   | 0.685      | 0.769        | 0.154 (0.081)    | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           53 |     1951 | 2024-05-20 | BetBoom        | L   | 0.684      | -            | -                | -                | -         |   -13.16 | brnz4n, drop, exit, insani, saffee |
|           52 |     2028 | 2024-05-17 | HEROIC         | L   | 0.666      | -            | -                | -                | -         |    -7.56 | brnz4n, drop, exit, insani, saffee |
|           51 |     2061 | 2024-05-16 | Aurora         | W   | 0.660      | 0.769        | 0.422 (0.214)    | 0.779 (0.395)    | 1 (0.660) |    13.57 | brnz4n, drop, exit, insani, saffee |
|           50 |     2119 | 2024-05-15 | HEROIC         | L   | 0.652      | -            | -                | -                | -         |    -7.37 | brnz4n, drop, exit, insani, saffee |
|           49 |     2525 | 2024-04-28 | Aurora         | W   | 0.538      | 0.500        | 0.422 (0.113)    | -                | 1 (0.538) |    12.27 | brnz4n, drop, exit, insani, saffee |
|           48 |     2528 | 2024-04-27 | Apeks          | W   | 0.536      | -            | -                | -                | 1 (0.536) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2554 | 2024-04-26 | Rooster        | W   | 0.530      | -            | -                | -                | 1 (0.530) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2577 | 2024-04-26 | Rebels         | L   | 0.524      | -            | -                | -                | -         |   -15.31 | brnz4n, drop, exit, insani, saffee |
|           45 |     2580 | 2024-04-25 | KZG            | W   | 0.523      | -            | -                | -                | 1 (0.523) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2690 | 2024-04-20 | paiN           | L   | 0.487      | -            | -                | -                | -         |    -8.94 | brnz4n, drop, exit, insani, saffee |
|           43 |     2699 | 2024-04-20 | OG             | W   | 0.486      | -            | -                | -                | 1 (0.486) |     1.56 | brnz4n, drop, exit, insani, saffee |
|           42 |     2712 | 2024-04-19 | paiN           | W   | 0.482      | -            | -                | -                | -         |     6.70 | brnz4n, drop, exit, insani, saffee |
|           41 |     2719 | 2024-04-19 | FURIA          | W   | 0.482      | 0.589        | 0.284 (0.081)    | -                | 1 (0.482) |    11.85 | brnz4n, drop, exit, insani, saffee |
|           40 |     2738 | 2024-04-19 | paiN           | L   | 0.480      | -            | -                | -                | -         |    -8.52 | brnz4n, drop, exit, insani, saffee |
|           39 |     2760 | 2024-04-18 | Imperial       | W   | 0.476      | -            | -                | -                | -         |     4.61 | brnz4n, drop, exit, insani, saffee |
|           38 |     2765 | 2024-04-18 | paiN           | W   | 0.475      | -            | -                | -                | -         |     6.70 | brnz4n, drop, exit, insani, saffee |
|           37 |     2769 | 2024-04-18 | OG             | W   | 0.474      | -            | -                | -                | 1 (0.474) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           36 |     2814 | 2024-04-17 | RED Canids     | W   | 0.468      | -            | -                | -                | -         |     1.90 | brnz4n, drop, exit, insani, saffee |
|           35 |     2820 | 2024-04-17 | Case           | W   | 0.468      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2859 | 2024-04-16 | Bounty Hunters | W   | 0.462      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2880 | 2024-04-15 | Imperial       | W   | 0.454      | 0.435        | 0.235 (0.046)    | -                | -         |     4.46 | brnz4n, drop, exit, insani, saffee |
|           32 |     2894 | 2024-04-14 | Galorys        | W   | 0.448      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2908 | 2024-04-13 | Case           | W   | 0.440      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2939 | 2024-04-11 | paiN           | W   | 0.428      | -            | -                | -                | -         |     6.64 | brnz4n, drop, exit, insani, saffee |
|           29 |     2977 | 2024-04-10 | Galorys        | W   | 0.422      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2981 | 2024-04-10 | Galorys        | W   | 0.421      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     2998 | 2024-04-10 | Imperial       | W   | 0.420      | -            | -                | -                | -         |     4.38 | brnz4n, drop, exit, insani, saffee |
|           26 |     3029 | 2024-04-09 | adalYamigos    | W   | 0.415      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3034 | 2024-04-09 | adalYamigos    | W   | 0.415      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3041 | 2024-04-09 | RED Canids     | W   | 0.414      | -            | -                | -                | -         |     1.83 | brnz4n, drop, exit, insani, saffee |
|           23 |     3071 | 2024-04-08 | W7M            | W   | 0.408      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3105 | 2024-04-07 | paiN           | W   | 0.402      | -            | -                | -                | -         |     6.61 | brnz4n, drop, exit, insani, saffee |
|           21 |     3122 | 2024-04-06 | Bounty Hunters | W   | 0.395      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3139 | 2024-04-05 | Fluxo          | W   | 0.389      | -            | -                | -                | -         |     1.59 | brnz4n, drop, exit, insani, saffee |
|           19 |     3140 | 2024-04-05 | Fluxo          | L   | 0.388      | -            | -                | -                | -         |   -10.77 | brnz4n, drop, exit, insani, saffee |
|           18 |     3143 | 2024-04-05 | ODDIK          | W   | 0.387      | -            | -                | -                | -         |     0.98 | brnz4n, drop, exit, insani, saffee |
|           17 |     3164 | 2024-04-04 | Solid          | W   | 0.382      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3170 | 2024-04-04 | Solid          | W   | 0.381      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3203 | 2024-04-03 | Fluxo          | W   | 0.375      | -            | -                | -                | -         |     1.45 | brnz4n, drop, exit, insani, saffee |
|           14 |     3251 | 2024-04-02 | Fluxo          | W   | 0.368      | -            | -                | -                | -         |     1.41 | brnz4n, drop, exit, insani, saffee |
|           13 |     3254 | 2024-04-02 | Sharks         | W   | 0.367      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3340 | 2024-03-27 | Case           | W   | 0.329      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3346 | 2024-03-27 | Case           | W   | 0.328      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3386 | 2024-03-26 | ODDIK          | W   | 0.322      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            9 |     3388 | 2024-03-26 | ODDIK          | W   | 0.322      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|            8 |     3580 | 2024-03-14 | Sharks         | W   | 0.242      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            7 |     3582 | 2024-03-14 | Sharks         | W   | 0.242      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            6 |     3654 | 2024-03-12 | Fluxo          | L   | 0.228      | -            | -                | -                | -         |    -6.31 | brnz4n, drop, exit, insani, saffee |
|            5 |     3693 | 2024-03-10 | Galorys        | W   | 0.215      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3741 | 2024-03-08 | LA RUGONETA    | W   | 0.201      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3872 | 2024-03-03 | Legacy         | L   | 0.168      | -            | -                | -                | -         |    -4.78 | brnz4n, drop, exit, insani, saffee |
|            2 |     3904 | 2024-03-02 | NRG            | W   | 0.160      | -            | -                | -                | 1 (0.160) |     0.21 | brnz4n, drop, exit, insani, saffee |
|            1 |     3926 | 2024-03-01 | BOSS           | L   | 0.154      | -            | -                | -                | -         |    -4.70 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,059.63)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.866 | $3,000.00      | $2,597.50       |
| 2024-06-09 |      0.821 | $3,000.00      | $2,463.06       |
| 2024-04-28 |      0.538 | $50,000.00     | $26,891.20      |
| 2024-04-20 |      0.488 | $20,000.00     | $9,753.70       |
| 2024-04-15 |      0.454 | $25,000.00     | $11,354.17      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
