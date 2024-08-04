### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [24](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1317.3<br />
<br />
Final Rank Value (1317.3) = Starting Rank Value (1421.6) + Head To Head Adjustments (-104.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.487[<sup>2</sup>](#table1)
- Opponent Network: 0.307[<sup>2</sup>](#table1)
- LAN Wins: 0.609[<sup>2</sup>](#table1)

The average of these factors is 0.500<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1421.6
- 400 + ( ( 0.500 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1421.6


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
|           81 |       37 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.96 | brnz4n, drop, exit, insani, saffee |
|           80 |       39 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.99 | brnz4n, drop, exit, insani, saffee |
|           79 |       53 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.124 (0.046)    | 0.723 (0.268)    | -         |     7.83 | brnz4n, drop, exit, insani, saffee |
|           78 |       80 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.831 (0.308)    | -         |     4.99 | brnz4n, drop, exit, insani, saffee |
|           77 |      125 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.61 | brnz4n, drop, exit, insani, saffee |
|           76 |      128 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |     5.45 | brnz4n, drop, exit, insani, saffee |
|           75 |      134 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |     5.74 | brnz4n, drop, exit, insani, saffee |
|           74 |      164 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.06 | brnz4n, drop, exit, insani, saffee |
|           73 |      167 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           72 |      173 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      209 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.63 | brnz4n, drop, exit, insani, saffee |
|           70 |      234 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      240 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.64 | brnz4n, drop, exit, insani, saffee |
|           68 |      330 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.22 | brnz4n, drop, exit, insani, saffee |
|           67 |      331 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.552 (0.248)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           66 |      594 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.25 | brnz4n, drop, exit, insani, saffee |
|           65 |      649 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.45 | brnz4n, drop, exit, insani, saffee |
|           64 |     1016 | 2024-06-15 | Complexity     | L   | 0.866      | -            | -                | -                | -         |    -6.89 | brnz4n, drop, exit, insani, saffee |
|           63 |     1042 | 2024-06-14 | Alliance       | W   | 0.861      | -            | -                | -                | 1 (0.861) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1055 | 2024-06-14 | ENCE           | L   | 0.860      | -            | -                | -                | -         |   -16.04 | brnz4n, drop, exit, insani, saffee |
|           61 |     1297 | 2024-06-07 | Bounty Hunters | L   | 0.816      | -            | -                | -                | -         |   -24.43 | brnz4n, drop, exit, insani, saffee |
|           60 |     1358 | 2024-06-06 | 9z             | L   | 0.809      | -            | -                | -                | -         |   -12.14 | brnz4n, drop, exit, insani, saffee |
|           59 |     1426 | 2024-06-05 | BESTIA         | W   | 0.803      | 0.450        | -                | 0.801 (0.289)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1480 | 2024-06-04 | Galorys        | W   | 0.796      | -            | -                | -                | -         |     0.99 | brnz4n, drop, exit, insani, saffee |
|           57 |     1804 | 2024-05-22 | paiN           | W   | 0.708      | 0.450        | 0.327 (0.104)    | 0.866 (0.276)    | -         |     8.52 | brnz4n, drop, exit, insani, saffee |
|           56 |     1808 | 2024-05-22 | paiN           | W   | 0.708      | 0.450        | 0.327 (0.104)    | 0.866 (0.276)    | -         |     9.04 | brnz4n, drop, exit, insani, saffee |
|           55 |     1882 | 2024-05-20 | BetBoom        | L   | 0.695      | -            | -                | -                | -         |   -12.89 | brnz4n, drop, exit, insani, saffee |
|           54 |     1893 | 2024-05-20 | BIG            | W   | 0.693      | 0.769        | 0.155 (0.083)    | -                | -         |     6.79 | brnz4n, drop, exit, insani, saffee |
|           53 |     1902 | 2024-05-20 | BetBoom        | L   | 0.692      | -            | -                | -                | -         |   -13.34 | brnz4n, drop, exit, insani, saffee |
|           52 |     1979 | 2024-05-17 | HEROIC         | L   | 0.674      | -            | -                | -                | -         |    -7.73 | brnz4n, drop, exit, insani, saffee |
|           51 |     2012 | 2024-05-16 | Aurora         | W   | 0.668      | 0.769        | 0.423 (0.217)    | 0.793 (0.407)    | 1 (0.668) |    13.46 | brnz4n, drop, exit, insani, saffee |
|           50 |     2070 | 2024-05-15 | HEROIC         | L   | 0.660      | -            | -                | -                | -         |    -7.55 | brnz4n, drop, exit, insani, saffee |
|           49 |     2476 | 2024-04-28 | Aurora         | W   | 0.546      | 0.500        | 0.423 (0.116)    | -                | 1 (0.546) |    12.25 | brnz4n, drop, exit, insani, saffee |
|           48 |     2479 | 2024-04-27 | Apeks          | W   | 0.544      | -            | -                | -                | 1 (0.544) |     1.10 | brnz4n, drop, exit, insani, saffee |
|           47 |     2505 | 2024-04-26 | Rooster        | W   | 0.538      | -            | -                | -                | 1 (0.538) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2528 | 2024-04-26 | Rebels         | L   | 0.532      | -            | -                | -                | -         |   -15.56 | brnz4n, drop, exit, insani, saffee |
|           45 |     2531 | 2024-04-25 | KZG            | W   | 0.531      | -            | -                | -                | 1 (0.531) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2641 | 2024-04-20 | paiN           | L   | 0.495      | -            | -                | -                | -         |    -9.08 | brnz4n, drop, exit, insani, saffee |
|           43 |     2650 | 2024-04-20 | OG             | W   | 0.494      | -            | -                | -                | 1 (0.494) |     1.57 | brnz4n, drop, exit, insani, saffee |
|           42 |     2663 | 2024-04-19 | paiN           | W   | 0.490      | -            | -                | -                | -         |     6.81 | brnz4n, drop, exit, insani, saffee |
|           41 |     2670 | 2024-04-19 | FURIA          | W   | 0.489      | 0.589        | 0.284 (0.082)    | -                | 1 (0.489) |    11.95 | brnz4n, drop, exit, insani, saffee |
|           40 |     2689 | 2024-04-19 | paiN           | L   | 0.488      | -            | -                | -                | -         |    -8.65 | brnz4n, drop, exit, insani, saffee |
|           39 |     2711 | 2024-04-18 | Imperial       | W   | 0.484      | -            | -                | -                | -         |     4.71 | brnz4n, drop, exit, insani, saffee |
|           38 |     2716 | 2024-04-18 | paiN           | W   | 0.483      | -            | -                | -                | -         |     6.82 | brnz4n, drop, exit, insani, saffee |
|           37 |     2720 | 2024-04-18 | OG             | W   | 0.482      | -            | -                | -                | 1 (0.482) |     1.56 | brnz4n, drop, exit, insani, saffee |
|           36 |     2765 | 2024-04-17 | RED Canids     | W   | 0.476      | -            | -                | -                | -         |     1.92 | brnz4n, drop, exit, insani, saffee |
|           35 |     2771 | 2024-04-17 | Case           | W   | 0.476      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2810 | 2024-04-16 | Bounty Hunters | W   | 0.470      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2831 | 2024-04-15 | Imperial       | W   | 0.462      | 0.435        | 0.237 (0.048)    | -                | -         |     4.56 | brnz4n, drop, exit, insani, saffee |
|           32 |     2845 | 2024-04-14 | Galorys        | W   | 0.455      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2859 | 2024-04-13 | Case           | W   | 0.448      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2890 | 2024-04-11 | paiN           | W   | 0.436      | -            | -                | -                | -         |     6.78 | brnz4n, drop, exit, insani, saffee |
|           29 |     2928 | 2024-04-10 | Galorys        | W   | 0.430      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2932 | 2024-04-10 | Galorys        | W   | 0.429      | -            | -                | -                | -         |     0.72 | brnz4n, drop, exit, insani, saffee |
|           27 |     2949 | 2024-04-10 | Imperial       | W   | 0.427      | -            | -                | -                | -         |     4.50 | brnz4n, drop, exit, insani, saffee |
|           26 |     2980 | 2024-04-09 | adalYamigos    | W   | 0.423      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     2985 | 2024-04-09 | adalYamigos    | W   | 0.423      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     2992 | 2024-04-09 | RED Canids     | W   | 0.422      | -            | -                | -                | -         |     1.86 | brnz4n, drop, exit, insani, saffee |
|           23 |     3022 | 2024-04-08 | W7M            | W   | 0.416      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           22 |     3056 | 2024-04-07 | paiN           | W   | 0.410      | -            | -                | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           21 |     3073 | 2024-04-06 | Bounty Hunters | W   | 0.403      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           20 |     3090 | 2024-04-05 | Fluxo          | W   | 0.397      | -            | -                | -                | -         |     1.61 | brnz4n, drop, exit, insani, saffee |
|           19 |     3091 | 2024-04-05 | Fluxo          | L   | 0.396      | -            | -                | -                | -         |   -11.00 | brnz4n, drop, exit, insani, saffee |
|           18 |     3094 | 2024-04-05 | ODDIK          | W   | 0.395      | -            | -                | -                | -         |     0.99 | brnz4n, drop, exit, insani, saffee |
|           17 |     3115 | 2024-04-04 | Solid          | W   | 0.390      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3121 | 2024-04-04 | Solid          | W   | 0.389      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|           15 |     3154 | 2024-04-03 | Fluxo          | W   | 0.383      | -            | -                | -                | -         |     1.47 | brnz4n, drop, exit, insani, saffee |
|           14 |     3202 | 2024-04-02 | Fluxo          | W   | 0.376      | -            | -                | -                | -         |     1.42 | brnz4n, drop, exit, insani, saffee |
|           13 |     3205 | 2024-04-02 | Sharks         | W   | 0.375      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3291 | 2024-03-27 | Case           | W   | 0.337      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3297 | 2024-03-27 | Case           | W   | 0.336      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           10 |     3337 | 2024-03-26 | ODDIK          | W   | 0.330      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|            9 |     3339 | 2024-03-26 | ODDIK          | W   | 0.330      | -            | -                | -                | -         |     0.92 | brnz4n, drop, exit, insani, saffee |
|            8 |     3531 | 2024-03-14 | Sharks         | W   | 0.250      | -            | -                | -                | -         |     0.65 | brnz4n, drop, exit, insani, saffee |
|            7 |     3533 | 2024-03-14 | Sharks         | W   | 0.250      | -            | -                | -                | -         |     0.66 | brnz4n, drop, exit, insani, saffee |
|            6 |     3605 | 2024-03-12 | Fluxo          | L   | 0.235      | -            | -                | -                | -         |    -6.54 | brnz4n, drop, exit, insani, saffee |
|            5 |     3644 | 2024-03-10 | Galorys        | W   | 0.223      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|            4 |     3692 | 2024-03-08 | LA RUGONETA    | W   | 0.209      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3823 | 2024-03-03 | Legacy         | L   | 0.176      | -            | -                | -                | -         |    -5.01 | brnz4n, drop, exit, insani, saffee |
|            2 |     3855 | 2024-03-02 | NRG            | W   | 0.168      | -            | -                | -                | 1 (0.168) |     0.22 | brnz4n, drop, exit, insani, saffee |
|            1 |     3877 | 2024-03-01 | BOSS           | L   | 0.162      | -            | -                | -                | -         |    -4.95 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,856.88)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.874 | $3,000.00      | $2,621.18       |
| 2024-06-09 |      0.829 | $3,000.00      | $2,486.74       |
| 2024-04-28 |      0.546 | $50,000.00     | $27,285.88      |
| 2024-04-20 |      0.496 | $20,000.00     | $9,911.57       |
| 2024-04-15 |      0.462 | $25,000.00     | $11,551.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
