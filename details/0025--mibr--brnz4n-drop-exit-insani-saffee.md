### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Global Rank: [25](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1315.1<br />
<br />
Final Rank Value (1315.1) = Starting Rank Value (1416.7) + Head To Head Adjustments (-101.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.486[<sup>2</sup>](#table1)
- Opponent Network: 0.301[<sup>2</sup>](#table1)
- LAN Wins: 0.601[<sup>2</sup>](#table1)

The average of these factors is 0.496<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1416.7
- 400 + ( ( 0.496 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1416.7


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
|           81 |       87 | 2024-08-02 | paiN           | L   | 1.000      | -            | -                | -                | -         |   -11.98 | brnz4n, drop, exit, insani, saffee |
|           80 |       89 | 2024-08-02 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |   -25.97 | brnz4n, drop, exit, insani, saffee |
|           79 |      103 | 2024-08-02 | Fluxo          | W   | 1.000      | 0.371        | 0.123 (0.046)    | 0.716 (0.265)    | -         |     7.84 | brnz4n, drop, exit, insani, saffee |
|           78 |      130 | 2024-08-01 | ODDIK          | W   | 1.000      | 0.371        | -                | 0.822 (0.305)    | -         |     5.01 | brnz4n, drop, exit, insani, saffee |
|           77 |      177 | 2024-07-31 | Sharks         | W   | 1.000      | -            | -                | -                | -         |     4.63 | brnz4n, drop, exit, insani, saffee |
|           76 |      180 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |     5.48 | brnz4n, drop, exit, insani, saffee |
|           75 |      186 | 2024-07-31 | ODDIK          | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |     5.77 | brnz4n, drop, exit, insani, saffee |
|           74 |      216 | 2024-07-30 | Dusty Roots    | L   | 1.000      | -            | -                | -                | -         |   -30.04 | brnz4n, drop, exit, insani, saffee |
|           73 |      219 | 2024-07-30 | Dusty Roots    | W   | 1.000      | -            | -                | -                | -         |     1.27 | brnz4n, drop, exit, insani, saffee |
|           72 |      225 | 2024-07-30 | 9z Academy     | W   | 1.000      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           71 |      261 | 2024-07-29 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -21.66 | brnz4n, drop, exit, insani, saffee |
|           70 |      286 | 2024-07-28 | RED Canids     | W   | 1.000      | -            | -                | -                | -         |     7.39 | brnz4n, drop, exit, insani, saffee |
|           69 |      292 | 2024-07-28 | Imperial       | L   | 1.000      | -            | -                | -                | -         |   -22.68 | brnz4n, drop, exit, insani, saffee |
|           68 |      382 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.23 | brnz4n, drop, exit, insani, saffee |
|           67 |      383 | 2024-07-25 | Galorys        | W   | 1.000      | 0.450        | -                | 0.543 (0.244)    | -         |     1.25 | brnz4n, drop, exit, insani, saffee |
|           66 |      646 | 2024-07-18 | The MongolZ    | L   | 1.000      | -            | -                | -                | -         |    -3.17 | brnz4n, drop, exit, insani, saffee |
|           65 |      698 | 2024-07-17 | Spirit         | L   | 1.000      | -            | -                | -                | -         |    -1.43 | brnz4n, drop, exit, insani, saffee |
|           64 |     1068 | 2024-06-15 | Complexity     | L   | 0.856      | -            | -                | -                | -         |    -6.57 | brnz4n, drop, exit, insani, saffee |
|           63 |     1094 | 2024-06-14 | Alliance       | W   | 0.851      | -            | -                | -                | 1 (0.851) |     1.24 | brnz4n, drop, exit, insani, saffee |
|           62 |     1107 | 2024-06-14 | ENCE           | L   | 0.850      | -            | -                | -                | -         |   -15.43 | brnz4n, drop, exit, insani, saffee |
|           61 |     1349 | 2024-06-07 | Bounty Hunters | L   | 0.806      | -            | -                | -                | -         |   -24.11 | brnz4n, drop, exit, insani, saffee |
|           60 |     1410 | 2024-06-06 | 9z             | L   | 0.799      | -            | -                | -                | -         |   -11.91 | brnz4n, drop, exit, insani, saffee |
|           59 |     1478 | 2024-06-05 | BESTIA         | W   | 0.793      | 0.450        | -                | 0.792 (0.283)    | -         |     2.55 | brnz4n, drop, exit, insani, saffee |
|           58 |     1532 | 2024-06-04 | Galorys        | W   | 0.786      | -            | -                | -                | -         |     1.00 | brnz4n, drop, exit, insani, saffee |
|           57 |     1856 | 2024-05-22 | paiN           | W   | 0.698      | 0.450        | 0.325 (0.102)    | 0.857 (0.269)    | -         |     8.39 | brnz4n, drop, exit, insani, saffee |
|           56 |     1860 | 2024-05-22 | paiN           | W   | 0.698      | 0.450        | 0.325 (0.102)    | 0.857 (0.269)    | -         |     8.90 | brnz4n, drop, exit, insani, saffee |
|           55 |     1934 | 2024-05-20 | BetBoom        | L   | 0.685      | -            | -                | -                | -         |   -12.67 | brnz4n, drop, exit, insani, saffee |
|           54 |     1945 | 2024-05-20 | BIG            | W   | 0.683      | 0.769        | 0.154 (0.081)    | -                | -         |     6.76 | brnz4n, drop, exit, insani, saffee |
|           53 |     1954 | 2024-05-20 | BetBoom        | L   | 0.682      | -            | -                | -                | -         |   -13.11 | brnz4n, drop, exit, insani, saffee |
|           52 |     2031 | 2024-05-17 | HEROIC         | L   | 0.664      | -            | -                | -                | -         |    -7.53 | brnz4n, drop, exit, insani, saffee |
|           51 |     2064 | 2024-05-16 | Aurora         | W   | 0.658      | 0.769        | 0.421 (0.213)    | 0.777 (0.393)    | 1 (0.658) |    13.56 | brnz4n, drop, exit, insani, saffee |
|           50 |     2122 | 2024-05-15 | HEROIC         | L   | 0.650      | -            | -                | -                | -         |    -7.34 | brnz4n, drop, exit, insani, saffee |
|           49 |     2528 | 2024-04-28 | Aurora         | W   | 0.536      | 0.500        | 0.421 (0.113)    | -                | 1 (0.536) |    12.24 | brnz4n, drop, exit, insani, saffee |
|           48 |     2531 | 2024-04-27 | Apeks          | W   | 0.534      | -            | -                | -                | 1 (0.534) |     1.08 | brnz4n, drop, exit, insani, saffee |
|           47 |     2557 | 2024-04-26 | Rooster        | W   | 0.528      | -            | -                | -                | 1 (0.528) |     0.46 | brnz4n, drop, exit, insani, saffee |
|           46 |     2580 | 2024-04-26 | Rebels         | L   | 0.522      | -            | -                | -                | -         |   -15.24 | brnz4n, drop, exit, insani, saffee |
|           45 |     2583 | 2024-04-25 | KZG            | W   | 0.521      | -            | -                | -                | 1 (0.521) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           44 |     2693 | 2024-04-20 | paiN           | L   | 0.485      | -            | -                | -                | -         |    -8.90 | brnz4n, drop, exit, insani, saffee |
|           43 |     2702 | 2024-04-20 | OG             | W   | 0.483      | -            | -                | -                | 1 (0.483) |     1.55 | brnz4n, drop, exit, insani, saffee |
|           42 |     2715 | 2024-04-19 | paiN           | W   | 0.480      | -            | -                | -                | -         |     6.66 | brnz4n, drop, exit, insani, saffee |
|           41 |     2722 | 2024-04-19 | FURIA          | W   | 0.479      | 0.589        | 0.284 (0.080)    | -                | 1 (0.479) |    11.81 | brnz4n, drop, exit, insani, saffee |
|           40 |     2741 | 2024-04-19 | paiN           | L   | 0.478      | -            | -                | -                | -         |    -8.49 | brnz4n, drop, exit, insani, saffee |
|           39 |     2763 | 2024-04-18 | Imperial       | W   | 0.474      | -            | -                | -                | -         |     4.58 | brnz4n, drop, exit, insani, saffee |
|           38 |     2768 | 2024-04-18 | paiN           | W   | 0.472      | -            | -                | -                | -         |     6.67 | brnz4n, drop, exit, insani, saffee |
|           37 |     2772 | 2024-04-18 | OG             | W   | 0.472      | -            | -                | -                | 1 (0.472) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           36 |     2817 | 2024-04-17 | RED Canids     | W   | 0.466      | -            | -                | -                | -         |     1.89 | brnz4n, drop, exit, insani, saffee |
|           35 |     2823 | 2024-04-17 | Case           | W   | 0.466      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           34 |     2862 | 2024-04-16 | Bounty Hunters | W   | 0.460      | -            | -                | -                | -         |     0.69 | brnz4n, drop, exit, insani, saffee |
|           33 |     2883 | 2024-04-15 | Imperial       | W   | 0.452      | 0.435        | 0.234 (0.046)    | -                | -         |     4.43 | brnz4n, drop, exit, insani, saffee |
|           32 |     2897 | 2024-04-14 | Galorys        | W   | 0.445      | -            | -                | -                | -         |     0.78 | brnz4n, drop, exit, insani, saffee |
|           31 |     2911 | 2024-04-13 | Case           | W   | 0.438      | -            | -                | -                | -         |     0.73 | brnz4n, drop, exit, insani, saffee |
|           30 |     2942 | 2024-04-11 | paiN           | W   | 0.426      | -            | -                | -                | -         |     6.60 | brnz4n, drop, exit, insani, saffee |
|           29 |     2980 | 2024-04-10 | Galorys        | W   | 0.420      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           28 |     2984 | 2024-04-10 | Galorys        | W   | 0.419      | -            | -                | -                | -         |     0.71 | brnz4n, drop, exit, insani, saffee |
|           27 |     3001 | 2024-04-10 | Imperial       | W   | 0.417      | -            | -                | -                | -         |     4.35 | brnz4n, drop, exit, insani, saffee |
|           26 |     3032 | 2024-04-09 | adalYamigos    | W   | 0.413      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           25 |     3037 | 2024-04-09 | adalYamigos    | W   | 0.412      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           24 |     3044 | 2024-04-09 | RED Canids     | W   | 0.412      | -            | -                | -                | -         |     1.83 | brnz4n, drop, exit, insani, saffee |
|           23 |     3074 | 2024-04-08 | W7M            | W   | 0.406      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           22 |     3108 | 2024-04-07 | paiN           | W   | 0.400      | -            | -                | -                | -         |     6.57 | brnz4n, drop, exit, insani, saffee |
|           21 |     3125 | 2024-04-06 | Bounty Hunters | W   | 0.393      | -            | -                | -                | -         |     0.70 | brnz4n, drop, exit, insani, saffee |
|           20 |     3142 | 2024-04-05 | Fluxo          | W   | 0.386      | -            | -                | -                | -         |     1.58 | brnz4n, drop, exit, insani, saffee |
|           19 |     3143 | 2024-04-05 | Fluxo          | L   | 0.386      | -            | -                | -                | -         |   -10.70 | brnz4n, drop, exit, insani, saffee |
|           18 |     3146 | 2024-04-05 | ODDIK          | W   | 0.385      | -            | -                | -                | -         |     0.98 | brnz4n, drop, exit, insani, saffee |
|           17 |     3167 | 2024-04-04 | Solid          | W   | 0.380      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           16 |     3173 | 2024-04-04 | Solid          | W   | 0.379      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|           15 |     3206 | 2024-04-03 | Fluxo          | W   | 0.373      | -            | -                | -                | -         |     1.44 | brnz4n, drop, exit, insani, saffee |
|           14 |     3254 | 2024-04-02 | Fluxo          | W   | 0.366      | -            | -                | -                | -         |     1.40 | brnz4n, drop, exit, insani, saffee |
|           13 |     3257 | 2024-04-02 | Sharks         | W   | 0.365      | -            | -                | -                | -         |     0.30 | brnz4n, drop, exit, insani, saffee |
|           12 |     3343 | 2024-03-27 | Case           | W   | 0.326      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           11 |     3349 | 2024-03-27 | Case           | W   | 0.326      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|           10 |     3389 | 2024-03-26 | ODDIK          | W   | 0.320      | -            | -                | -                | -         |     0.90 | brnz4n, drop, exit, insani, saffee |
|            9 |     3391 | 2024-03-26 | ODDIK          | W   | 0.319      | -            | -                | -                | -         |     0.91 | brnz4n, drop, exit, insani, saffee |
|            8 |     3583 | 2024-03-14 | Sharks         | W   | 0.240      | -            | -                | -                | -         |     0.63 | brnz4n, drop, exit, insani, saffee |
|            7 |     3585 | 2024-03-14 | Sharks         | W   | 0.240      | -            | -                | -                | -         |     0.64 | brnz4n, drop, exit, insani, saffee |
|            6 |     3657 | 2024-03-12 | Fluxo          | L   | 0.225      | -            | -                | -                | -         |    -6.25 | brnz4n, drop, exit, insani, saffee |
|            5 |     3696 | 2024-03-10 | Galorys        | W   | 0.212      | -            | -                | -                | -         |     0.36 | brnz4n, drop, exit, insani, saffee |
|            4 |     3744 | 2024-03-08 | LA RUGONETA    | W   | 0.199      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            3 |     3875 | 2024-03-03 | Legacy         | L   | 0.166      | -            | -                | -                | -         |    -4.72 | brnz4n, drop, exit, insani, saffee |
|            2 |     3907 | 2024-03-02 | NRG            | W   | 0.158      | -            | -                | -                | 1 (0.158) |     0.21 | brnz4n, drop, exit, insani, saffee |
|            1 |     3929 | 2024-03-01 | BOSS           | L   | 0.152      | -            | -                | -                | -         |    -4.63 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66,835.19)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-16 |      0.864 | $3,000.00      | $2,590.83       |
| 2024-06-09 |      0.819 | $3,000.00      | $2,456.39       |
| 2024-04-28 |      0.536 | $50,000.00     | $26,780.09      |
| 2024-04-20 |      0.485 | $20,000.00     | $9,709.26       |
| 2024-04-15 |      0.452 | $25,000.00     | $11,298.61      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
