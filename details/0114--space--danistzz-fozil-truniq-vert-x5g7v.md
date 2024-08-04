### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  831.1<br />
<br />
Final Rank Value (831.1) = Starting Rank Value (813.2) + Head To Head Adjustments (17.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.2
- 400 + ( ( 0.202 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 813.2


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
|           35 |       69 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |       76 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      153 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.57 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      200 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.35 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      286 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.59 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      315 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.51 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      336 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.23 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      406 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.34 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      521 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.365 (0.158)    | 0 (0.000) |    12.70 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      594 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.446 (0.194)    | 0 (0.000) |    16.50 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      780 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.876 (0.381)    | 0 (0.000) |    18.41 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1073 | 2024-06-14 | BIG             | L   | 0.860      | -            | -                | -                | -         |    -2.18 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1158 | 2024-06-11 | Rare Atom       | W   | 0.840      | 0.435        | -                | 0.480 (0.175)    | 0 (0.000) |     7.92 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1179 | 2024-06-10 | Passion UA      | L   | 0.833      | -            | -                | -                | -         |    -6.80 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1286 | 2024-06-08 | Permitta        | L   | 0.820      | -            | -                | -                | -         |   -10.99 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1407 | 2024-06-06 | VP.Prodigy      | W   | 0.807      | 0.435        | 0.025 (0.009)    | 0.401 (0.141)    | 0 (0.000) |    14.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1544 | 2024-06-03 | EYEBALLERS      | W   | 0.787      | 0.435        | 0.006 (0.002)    | 0.509 (0.174)    | 0 (0.000) |    12.15 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1757 | 2024-05-25 | 9 Pandas        | L   | 0.727      | -            | -                | -                | -         |    -6.23 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1801 | 2024-05-23 | Metizport       | W   | 0.711      | -            | -                | -                | 0 (0.000) |     9.88 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1873 | 2024-05-21 | System5         | W   | 0.701      | -            | -                | -                | 0 (0.000) |     6.06 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1935 | 2024-05-19 | DMS             | W   | 0.687      | 0.435        | -                | 0.446 (0.133)    | 0 (0.000) |    12.98 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1983 | 2024-05-18 | Verdant         | W   | 0.678      | 0.435        | 0.015 (0.004)    | -                | 0 (0.000) |    13.23 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     2014 | 2024-05-17 | 777             | L   | 0.672      | -            | -                | -                | -         |   -13.86 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2033 | 2024-05-16 | GUN5            | L   | 0.667      | -            | -                | -                | -         |    -7.82 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2089 | 2024-05-15 | Rounds          | W   | 0.660      | -            | -                | -                | -         |     1.56 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2107 | 2024-05-15 | Nexus           | W   | 0.658      | 0.435        | 0.014 (0.004)    | -                | -         |     9.19 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2139 | 2024-05-14 | EYEBALLERS      | W   | 0.654      | 0.500        | 0.006 (0.002)    | 0.509 (0.167)    | -         |    12.06 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2180 | 2024-05-13 | MOUZ NXT        | L   | 0.645      | -            | -                | -                | -         |    -4.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2232 | 2024-05-11 | Viperio         | W   | 0.632      | -            | -                | -                | -         |     4.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2658 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.494      | 0.500        | 0.031 (0.008)    | 0.560 (0.138)    | -         |    10.79 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3163 | 2024-04-04 | 3DMAX           | L   | 0.386      | -            | -                | -                | -         |    -0.11 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3202 | 2024-04-03 | PARIVISION      | L   | 0.380      | -            | -                | -                | -         |    -2.03 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3280 | 2024-03-29 | B8              | W   | 0.347      | 0.500        | 0.165 (0.029)    | 0.912 (0.158)    | -         |     9.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3296 | 2024-03-28 | GUN5            | L   | 0.340      | -            | -                | -                | -         |    -3.64 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3749 | 2024-03-07 | Apeks           | L   | 0.200      | -            | -                | -                | -         |    -2.36 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,880.43)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.827 | $500.00        | $413.39         |
| 2024-05-26 |      0.734 | $2,000.00      | $1,467.04       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
