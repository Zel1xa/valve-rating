### Roster Details<br />
Team Name: Sangal<br />
Roster: Chill, LNZ, SaMey, xfl0ud, yxngstxr<br />
Global Rank: [27](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1282.2<br />
<br />
Final Rank Value (1282.2) = Starting Rank Value (1159.3) + Head To Head Adjustments (122.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.603[<sup>1</sup>](#table2)
- Bounty Collected: 0.501[<sup>2</sup>](#table1)
- Opponent Network: 0.380[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.371<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1159.3
- 400 + ( ( 0.371 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1159.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |        8 | 2024-08-05 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.73 | Chill, LNZ, SaMey, xfl0ud, yxngstxr     |
|           67 |       64 | 2024-08-03 | Passion UA        | W   | 1.000      | 0.435        | 0.173 (0.075)    | 1.000 (0.435)    | 0 (0.000) |     8.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      233 | 2024-07-30 | SINNERS           | W   | 1.000      | 0.500        | -                | 0.794 (0.397)    | 0 (0.000) |     5.28 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      287 | 2024-07-28 | fnatic            | W   | 1.000      | 0.435        | 0.371 (0.161)    | 0.706 (0.307)    | 0 (0.000) |    23.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |      303 | 2024-07-28 | Monte             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      325 | 2024-07-27 | B8                | W   | 1.000      | 0.435        | 0.165 (0.072)    | 0.947 (0.412)    | 0 (0.000) |    12.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      339 | 2024-07-26 | Permitta          | W   | 1.000      | 0.435        | -                | 0.873 (0.379)    | 0 (0.000) |     4.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      454 | 2024-07-23 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      554 | 2024-07-20 | fnatic            | L   | 1.000      | -            | -                | -                | -         |    -6.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      683 | 2024-07-17 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -17.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |      697 | 2024-07-17 | B8                | W   | 1.000      | 0.500        | 0.165 (0.082)    | 0.947 (0.474)    | 0 (0.000) |    13.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |      791 | 2024-07-15 | RUSH B            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.33 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |      808 | 2024-07-15 | Rebels            | W   | 1.000      | -            | -                | -                | -         |     7.90 | imoRR, jottAAA, SaMey, xfl0ud, yxngstxr |
|           55 |     1236 | 2024-06-09 | KOI               | W   | 0.821      | -            | -                | -                | -         |     8.45 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1302 | 2024-06-08 | SINNERS           | W   | 0.814      | 0.500        | -                | 0.794 (0.323)    | -         |     7.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1355 | 2024-06-07 | Aurora            | W   | 0.808      | 0.500        | 0.422 (0.170)    | 0.788 (0.319)    | -         |    22.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1422 | 2024-06-06 | 3DMAX             | W   | 0.801      | 0.500        | 0.508 (0.203)    | 1.000 (0.401)    | -         |    22.18 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1482 | 2024-06-05 | SAW               | W   | 0.794      | 0.500        | 0.105 (0.042)    | -                | -         |    13.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1533 | 2024-06-04 | 9 Pandas          | W   | 0.788      | -            | -                | -                | -         |    10.24 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     1646 | 2024-05-31 | SAW               | L   | 0.761      | -            | -                | -                | -         |    -9.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     1649 | 2024-05-31 | FAVBET            | W   | 0.761      | -            | -                | -                | -         |     3.02 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     1653 | 2024-05-31 | fnatic            | L   | 0.760      | -            | -                | -                | -         |    -3.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     1681 | 2024-05-30 | MOUZ NXT          | L   | 0.752      | -            | -                | -                | -         |   -13.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     1853 | 2024-05-22 | Zero Tenacity     | W   | 0.701      | 0.500        | 0.137 (0.048)    | 1.000 (0.350)    | -         |    10.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     1900 | 2024-05-21 | Monte             | W   | 0.693      | -            | -                | -                | -         |     8.06 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     1935 | 2024-05-20 | PARIVISION        | W   | 0.687      | -            | -                | -                | -         |     9.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     1950 | 2024-05-19 | Ninjas in Pyjamas | W   | 0.682      | 0.500        | 0.254 (0.087)    | -                | -         |    19.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     1957 | 2024-05-19 | Endpoint          | W   | 0.680      | -            | -                | -                | -         |     6.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     1992 | 2024-05-18 | Rare Atom         | W   | 0.673      | -            | -                | -                | -         |     4.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2034 | 2024-05-17 | Permitta          | W   | 0.665      | -            | -                | -                | -         |     5.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2047 | 2024-05-16 | Ninjas in Pyjamas | L   | 0.661      | -            | -                | -                | -         |    -1.13 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2114 | 2024-05-15 | Verdant           | L   | 0.653      | -            | -                | -                | -         |   -15.08 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2177 | 2024-05-14 | DMS               | L   | 0.645      | -            | -                | -                | -         |   -15.32 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2423 | 2024-05-02 | Metizport         | L   | 0.567      | -            | -                | -                | -         |   -14.16 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     2456 | 2024-05-01 | ALTERNATE aTTaX   | L   | 0.559      | -            | -                | -                | -         |   -12.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |     2466 | 2024-04-30 | Zero Tenacity     | W   | 0.554      | -            | -                | -                | -         |     7.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |     2498 | 2024-04-29 | SINNERS           | W   | 0.546      | -            | -                | -                | -         |     7.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |     2505 | 2024-04-28 | 1WIN              | W   | 0.541      | -            | -                | -                | -         |     4.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |     2529 | 2024-04-27 | PARIVISION        | L   | 0.534      | -            | -                | -                | -         |    -9.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     2563 | 2024-04-26 | Nemiga            | W   | 0.526      | 0.435        | 0.316 (0.072)    | -                | -         |     9.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2635 | 2024-04-23 | Grannys Knockers  | W   | 0.505      | -            | -                | -                | -         |     1.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           27 |     2640 | 2024-04-22 | BLEED             | L   | 0.501      | -            | -                | -                | -         |    -9.56 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           26 |     2651 | 2024-04-22 | ex-Guild Eagles   | L   | 0.499      | -            | -                | -                | -         |   -13.24 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           25 |     2666 | 2024-04-21 | Alliance          | W   | 0.492      | -            | -                | -                | -         |     2.69 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           24 |     2685 | 2024-04-20 | brazylijski luz   | W   | 0.487      | -            | -                | -                | -         |     2.31 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           23 |     2701 | 2024-04-20 | JANO              | W   | 0.485      | -            | -                | -                | -         |     1.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           22 |     2720 | 2024-04-19 | TSM               | W   | 0.481      | -            | -                | -                | -         |     1.09 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           21 |     2732 | 2024-04-19 | Nemiga            | L   | 0.481      | -            | -                | -                | -         |    -7.04 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           20 |     2840 | 2024-04-17 | 9 Pandas          | W   | 0.466      | -            | -                | -                | -         |     4.43 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           19 |     2852 | 2024-04-16 | Zero Tenacity     | W   | 0.461      | -            | -                | -                | -         |     5.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           18 |     2873 | 2024-04-15 | B8                | W   | 0.455      | -            | -                | -                | -         |     5.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           17 |     2877 | 2024-04-15 | Aurora Young Blud | W   | 0.454      | -            | -                | -                | -         |     2.40 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           16 |     2918 | 2024-04-12 | Monte             | L   | 0.434      | -            | -                | -                | -         |    -9.49 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           15 |     3171 | 2024-04-04 | EYEBALLERS        | W   | 0.381      | -            | -                | -                | -         |     2.55 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           14 |     3254 | 2024-04-02 | 9 Pandas          | L   | 0.368      | -            | -                | -                | -         |    -7.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           13 |     3611 | 2024-03-13 | KOI               | L   | 0.235      | -            | -                | -                | -         |    -4.34 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     3720 | 2024-03-09 | Zero Tenacity     | L   | 0.207      | -            | -                | -                | -         |    -3.70 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     3769 | 2024-03-07 | 500               | L   | 0.194      | -            | -                | -                | -         |    -5.62 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     3789 | 2024-03-06 | TSM               | W   | 0.188      | -            | -                | -                | -         |     0.38 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     3859 | 2024-03-04 | Sampi             | W   | 0.173      | -            | -                | -                | -         |     0.99 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     3885 | 2024-03-03 | Rebels            | L   | 0.168      | -            | -                | -                | -         |    -3.75 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     3912 | 2024-03-02 | HAVU              | W   | 0.159      | -            | -                | -                | -         |     0.37 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     3933 | 2024-02-29 | Rebels            | L   | 0.147      | -            | -                | -                | -         |    -3.33 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     3954 | 2024-02-28 | Alliance          | L   | 0.139      | -            | -                | -                | -         |    -3.73 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     3961 | 2024-02-27 | 9INE              | W   | 0.135      | -            | -                | -                | -         |     0.12 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     4007 | 2024-02-25 | Sashi             | W   | 0.122      | -            | -                | -                | -         |     1.90 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     4183 | 2024-02-18 | 500               | W   | 0.072      | -            | -                | -                | -         |     0.16 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     4386 | 2024-02-08 | AURA              | L   | 0.007      | -            | -                | -                | -         |    -0.22 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($70,570.38)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-06-09 |      0.821 | $16,500.00     | $13,542.60      |
| 2024-05-22 |      0.701 | $50,000.00     | $35,027.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
