### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  829.2<br />
<br />
Final Rank Value (829.2) = Starting Rank Value (816.4) + Head To Head Adjustments (12.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 816.4
- 400 + ( ( 0.204 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 816.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |       39 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |       47 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -18.18 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      122 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.90 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      169 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.60 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      255 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      284 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      305 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      375 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.57 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      490 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.364 (0.158)    | 0 (0.000) |    12.47 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      566 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    16.23 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      749 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.876 (0.381)    | 0 (0.000) |    18.11 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1042 | 2024-06-14 | BIG             | L   | 0.861      | -            | -                | -                | -         |    -2.26 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1127 | 2024-06-11 | Rare Atom       | W   | 0.841      | 0.435        | -                | 0.480 (0.175)    | 0 (0.000) |     7.79 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1148 | 2024-06-10 | Passion UA      | L   | 0.835      | -            | -                | -                | -         |    -7.09 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1255 | 2024-06-08 | Permitta        | L   | 0.822      | -            | -                | -                | -         |   -11.29 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1376 | 2024-06-06 | VP.Prodigy      | W   | 0.809      | 0.435        | 0.026 (0.009)    | 0.401 (0.141)    | 0 (0.000) |    14.38 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1513 | 2024-06-03 | EYEBALLERS      | W   | 0.789      | 0.435        | 0.006 (0.002)    | 0.510 (0.175)    | 0 (0.000) |    12.06 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1726 | 2024-05-25 | 9 Pandas        | L   | 0.729      | -            | -                | -                | -         |    -6.48 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1770 | 2024-05-23 | Metizport       | W   | 0.713      | 0.435        | 0.037 (0.011)    | -                | 0 (0.000) |    14.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1842 | 2024-05-21 | System5         | W   | 0.702      | -            | -                | -                | 0 (0.000) |     6.01 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1904 | 2024-05-19 | DMS             | W   | 0.688      | 0.435        | -                | 0.446 (0.133)    | 0 (0.000) |    12.92 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1952 | 2024-05-18 | Verdant         | W   | 0.679      | 0.435        | 0.015 (0.004)    | -                | 0 (0.000) |    13.18 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1983 | 2024-05-17 | 777             | L   | 0.673      | -            | -                | -                | -         |   -13.96 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2002 | 2024-05-16 | GUN5            | L   | 0.669      | -            | -                | -                | -         |    -7.92 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2058 | 2024-05-15 | Rounds          | W   | 0.661      | -            | -                | -                | -         |     1.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2076 | 2024-05-15 | Nexus           | W   | 0.659      | 0.435        | 0.014 (0.004)    | -                | -         |     9.14 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2108 | 2024-05-14 | EYEBALLERS      | W   | 0.656      | 0.500        | 0.006 (0.002)    | 0.510 (0.167)    | -         |    12.14 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2149 | 2024-05-13 | MOUZ NXT        | L   | 0.646      | -            | -                | -                | -         |    -4.65 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2201 | 2024-05-11 | Viperio         | W   | 0.634      | -            | -                | -                | -         |     4.61 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2627 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.496      | 0.500        | 0.031 (0.008)    | 0.560 (0.139)    | -         |    10.75 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3132 | 2024-04-04 | 3DMAX           | L   | 0.388      | -            | -                | -                | -         |    -0.11 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3171 | 2024-04-03 | PARIVISION      | L   | 0.381      | -            | -                | -                | -         |    -2.08 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3249 | 2024-03-29 | B8              | W   | 0.348      | 0.500        | 0.165 (0.029)    | 0.912 (0.159)    | -         |     9.11 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3265 | 2024-03-28 | GUN5            | L   | 0.342      | -            | -                | -                | -         |    -3.71 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3718 | 2024-03-07 | Apeks           | L   | 0.202      | -            | -                | -                | -         |    -2.40 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,884.13)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $500.00        | $414.13         |
| 2024-05-26 |      0.735 | $2,000.00      | $1,470.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
