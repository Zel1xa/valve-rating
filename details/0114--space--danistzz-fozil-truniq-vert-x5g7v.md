### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  835.1<br />
<br />
Final Rank Value (835.1) = Starting Rank Value (816.3) + Head To Head Adjustments (18.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 816.3
- 400 + ( ( 0.204 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 816.3


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
|           35 |       47 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.33 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |       55 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.47 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      130 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.88 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      177 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      263 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.64 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      292 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.52 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      313 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.43 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      383 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.56 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      498 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.364 (0.158)    | 0 (0.000) |    12.47 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      574 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    16.24 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      757 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.876 (0.381)    | 0 (0.000) |    18.14 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1050 | 2024-06-14 | BIG             | L   | 0.860      | -            | -                | -                | -         |    -2.25 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1135 | 2024-06-11 | Rare Atom       | W   | 0.841      | 0.435        | -                | 0.480 (0.175)    | 0 (0.000) |     7.82 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1156 | 2024-06-10 | Passion UA      | L   | 0.834      | -            | -                | -                | -         |    -7.05 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1263 | 2024-06-08 | Permitta        | L   | 0.821      | -            | -                | -                | -         |   -11.25 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1384 | 2024-06-06 | VP.Prodigy      | W   | 0.808      | 0.435        | 0.025 (0.009)    | 0.401 (0.141)    | 0 (0.000) |    14.38 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1521 | 2024-06-03 | EYEBALLERS      | W   | 0.788      | 0.435        | 0.006 (0.002)    | 0.510 (0.174)    | 0 (0.000) |    12.06 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1734 | 2024-05-25 | 9 Pandas        | L   | 0.728      | -            | -                | -                | -         |    -6.45 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1778 | 2024-05-23 | Metizport       | W   | 0.712      | 0.435        | 0.037 (0.011)    | -                | 0 (0.000) |    14.47 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1850 | 2024-05-21 | System5         | W   | 0.702      | -            | -                | -                | 0 (0.000) |     6.01 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1912 | 2024-05-19 | DMS             | W   | 0.688      | 0.435        | -                | 0.446 (0.133)    | 0 (0.000) |    12.91 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1960 | 2024-05-18 | Verdant         | W   | 0.679      | 0.435        | 0.015 (0.004)    | -                | 0 (0.000) |    13.17 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1991 | 2024-05-17 | 777             | L   | 0.672      | -            | -                | -                | -         |   -13.95 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2010 | 2024-05-16 | GUN5            | L   | 0.668      | -            | -                | -                | -         |    -7.91 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2066 | 2024-05-15 | Rounds          | W   | 0.661      | -            | -                | -                | -         |     1.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2084 | 2024-05-15 | Nexus           | W   | 0.659      | 0.435        | 0.014 (0.004)    | -                | -         |     9.13 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2116 | 2024-05-14 | EYEBALLERS      | W   | 0.655      | 0.500        | 0.006 (0.002)    | 0.510 (0.167)    | -         |    12.14 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2157 | 2024-05-13 | MOUZ NXT        | L   | 0.645      | -            | -                | -                | -         |    -4.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2209 | 2024-05-11 | Viperio         | W   | 0.633      | -            | -                | -                | -         |     4.60 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2635 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.495      | 0.500        | 0.031 (0.008)    | 0.560 (0.139)    | -         |    10.74 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3140 | 2024-04-04 | 3DMAX           | L   | 0.387      | -            | -                | -                | -         |    -0.11 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3179 | 2024-04-03 | PARIVISION      | L   | 0.380      | -            | -                | -                | -         |    -2.07 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3257 | 2024-03-29 | B8              | W   | 0.348      | 0.500        | 0.165 (0.029)    | 0.912 (0.159)    | -         |     9.09 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3273 | 2024-03-28 | GUN5            | L   | 0.341      | -            | -                | -                | -         |    -3.70 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3726 | 2024-03-07 | Apeks           | L   | 0.201      | -            | -                | -                | -         |    -2.39 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,882.34)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.828 | $500.00        | $413.77         |
| 2024-05-26 |      0.734 | $2,000.00      | $1,468.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
