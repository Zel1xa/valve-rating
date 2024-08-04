### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
<br />
Final Rank Value:  829.6<br />
<br />
Final Rank Value (829.6) = Starting Rank Value (816.7) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 816.7
- 400 + ( ( 0.204 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 816.7


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
|           35 |       36 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |       44 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -18.20 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      119 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.90 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      166 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.61 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      252 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.67 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      281 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.57 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      302 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      372 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.59 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      487 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.363 (0.158)    | 0 (0.000) |    12.45 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      563 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    16.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      746 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.876 (0.381)    | 0 (0.000) |    18.09 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1038 | 2024-06-14 | BIG             | L   | 0.864      | -            | -                | -                | -         |    -2.26 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1123 | 2024-06-11 | Rare Atom       | W   | 0.844      | 0.435        | -                | 0.479 (0.176)    | 0 (0.000) |     7.81 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1144 | 2024-06-10 | Passion UA      | L   | 0.838      | -            | -                | -                | -         |    -7.24 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1251 | 2024-06-08 | Permitta        | L   | 0.825      | -            | -                | -                | -         |   -11.35 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1372 | 2024-06-06 | VP.Prodigy      | W   | 0.812      | 0.435        | 0.026 (0.009)    | 0.402 (0.142)    | 0 (0.000) |    14.42 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1509 | 2024-06-03 | EYEBALLERS      | W   | 0.792      | 0.435        | 0.006 (0.002)    | 0.510 (0.176)    | 0 (0.000) |    12.09 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1722 | 2024-05-25 | 9 Pandas        | L   | 0.732      | -            | -                | -                | -         |    -6.37 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1766 | 2024-05-23 | Metizport       | W   | 0.716      | 0.435        | 0.037 (0.012)    | -                | 0 (0.000) |    14.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1838 | 2024-05-21 | System5         | W   | 0.705      | -            | -                | -                | 0 (0.000) |     6.03 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1900 | 2024-05-19 | DMS             | W   | 0.691      | 0.435        | -                | 0.446 (0.134)    | 0 (0.000) |    12.97 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1948 | 2024-05-18 | Verdant         | W   | 0.682      | 0.435        | 0.015 (0.004)    | -                | 0 (0.000) |    13.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1979 | 2024-05-17 | 777             | L   | 0.676      | -            | -                | -                | -         |   -14.04 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     1998 | 2024-05-16 | GUN5            | L   | 0.672      | -            | -                | -                | -         |    -7.96 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2054 | 2024-05-15 | Rounds          | W   | 0.664      | -            | -                | -                | -         |     1.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2072 | 2024-05-15 | Nexus           | W   | 0.662      | 0.435        | 0.014 (0.004)    | -                | -         |     9.17 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2104 | 2024-05-14 | EYEBALLERS      | W   | 0.659      | 0.500        | 0.006 (0.002)    | 0.510 (0.168)    | -         |    12.19 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2145 | 2024-05-13 | MOUZ NXT        | L   | 0.649      | -            | -                | -                | -         |    -4.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2197 | 2024-05-11 | Viperio         | W   | 0.637      | -            | -                | -                | -         |     4.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2622 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.499      | 0.500        | 0.032 (0.008)    | 0.561 (0.140)    | -         |    10.81 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3127 | 2024-04-04 | 3DMAX           | L   | 0.391      | -            | -                | -                | -         |    -0.11 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3166 | 2024-04-03 | PARIVISION      | L   | 0.384      | -            | -                | -                | -         |    -2.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3244 | 2024-03-29 | B8              | W   | 0.351      | 0.500        | 0.165 (0.029)    | 0.913 (0.160)    | -         |     9.19 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3260 | 2024-03-28 | GUN5            | L   | 0.345      | -            | -                | -                | -         |    -3.74 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3712 | 2024-03-07 | Apeks           | L   | 0.205      | -            | -                | -                | -         |    -2.42 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,891.77)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.831 | $500.00        | $415.66         |
| 2024-05-26 |      0.738 | $2,000.00      | $1,476.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
