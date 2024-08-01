### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  854.1<br />
<br />
Final Rank Value (854.1) = Starting Rank Value (820.1) + Head To Head Adjustments (34.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.181[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 820.1
- 400 + ( ( 0.204 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 820.1


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
|           33 |       40 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -5.00 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |       87 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      173 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -16.82 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      202 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.67 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      223 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.87 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      293 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.48 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      411 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.360 (0.156)    | 0 (0.000) |    12.59 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      490 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    16.02 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      682 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.011)    | 0.801 (0.348)    | 0 (0.000) |    17.96 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |      966 | 2024-06-14 | BIG             | L   | 0.879      | -            | -                | -                | -         |    -3.09 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1052 | 2024-06-11 | Rare Atom       | W   | 0.859      | 0.435        | -                | 0.437 (0.163)    | 0 (0.000) |     6.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1074 | 2024-06-10 | Passion UA      | L   | 0.852      | -            | -                | -                | -         |    -7.70 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1183 | 2024-06-08 | Permitta        | L   | 0.840      | -            | -                | -                | -         |   -11.77 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1313 | 2024-06-06 | VP.Prodigy      | W   | 0.826      | 0.435        | 0.026 (0.009)    | 0.405 (0.145)    | 0 (0.000) |    14.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1453 | 2024-06-03 | EYEBALLERS      | W   | 0.806      | 0.435        | 0.006 (0.002)    | 0.512 (0.180)    | 0 (0.000) |    12.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1669 | 2024-05-25 | 9 Pandas        | L   | 0.747      | -            | -                | -                | -         |    -6.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1713 | 2024-05-23 | Metizport       | W   | 0.731      | 0.435        | 0.038 (0.012)    | -                | 0 (0.000) |    14.74 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1799 | 2024-05-21 | System5         | W   | 0.720      | -            | -                | -                | 0 (0.000) |     6.14 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1872 | 2024-05-19 | DMS             | W   | 0.706      | -            | -                | -                | 0 (0.000) |    13.19 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1921 | 2024-05-18 | Verdant         | W   | 0.697      | 0.435        | 0.015 (0.005)    | -                | 0 (0.000) |    13.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1952 | 2024-05-17 | 777             | L   | 0.691      | -            | -                | -                | -         |   -14.34 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     1971 | 2024-05-16 | GUN5            | L   | 0.687      | -            | -                | -                | -         |    -7.83 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2027 | 2024-05-15 | Rounds          | W   | 0.679      | -            | -                | -                | -         |     1.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2051 | 2024-05-15 | Nexus           | W   | 0.677      | 0.435        | 0.014 (0.004)    | 0.504 (0.148)    | -         |     9.36 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2083 | 2024-05-14 | EYEBALLERS      | W   | 0.673      | 0.500        | 0.006 (0.002)    | 0.512 (0.172)    | -         |    12.45 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2127 | 2024-05-13 | MOUZ NXT        | L   | 0.664      | -            | -                | -                | -         |    -5.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2179 | 2024-05-11 | Viperio         | W   | 0.651      | -            | -                | -                | -         |     4.70 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2616 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.513      | 0.500        | 0.032 (0.008)    | 0.563 (0.145)    | -         |    11.07 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3127 | 2024-04-04 | 3DMAX           | L   | 0.406      | -            | -                | -                | -         |    -0.12 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3171 | 2024-04-03 | PARIVISION      | L   | 0.399      | -            | -                | -                | -         |    -2.15 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3251 | 2024-03-29 | B8              | W   | 0.366      | 0.500        | 0.168 (0.031)    | 0.878 (0.161)    | -         |     9.63 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3267 | 2024-03-28 | GUN5            | L   | 0.359      | -            | -                | -                | -         |    -3.73 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3731 | 2024-03-07 | Apeks           | L   | 0.219      | -            | -                | -                | -         |    -2.50 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,928.58)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $500.00        | $423.02         |
| 2024-05-26 |      0.753 | $2,000.00      | $1,505.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
