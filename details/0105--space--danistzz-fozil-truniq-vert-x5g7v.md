### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  854.1<br />
<br />
Final Rank Value (854.1) = Starting Rank Value (820.1) + Head To Head Adjustments (34.0)<br />

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
|           33 |       36 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -5.00 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |       84 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      171 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -16.83 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      200 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      221 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.88 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      291 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.48 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      409 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.360 (0.156)    | 0 (0.000) |    12.59 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      490 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    16.02 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      680 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.011)    | 0.801 (0.348)    | 0 (0.000) |    17.98 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |      964 | 2024-06-14 | BIG             | L   | 0.879      | -            | -                | -                | -         |    -3.09 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1050 | 2024-06-11 | Rare Atom       | W   | 0.859      | 0.435        | -                | 0.437 (0.163)    | 0 (0.000) |     6.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1072 | 2024-06-10 | Passion UA      | L   | 0.853      | -            | -                | -                | -         |    -7.70 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1181 | 2024-06-08 | Permitta        | L   | 0.840      | -            | -                | -                | -         |   -11.74 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1311 | 2024-06-06 | VP.Prodigy      | W   | 0.827      | 0.435        | 0.026 (0.009)    | 0.405 (0.145)    | 0 (0.000) |    14.72 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1451 | 2024-06-03 | EYEBALLERS      | W   | 0.807      | 0.435        | 0.006 (0.002)    | 0.512 (0.180)    | 0 (0.000) |    12.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1667 | 2024-05-25 | 9 Pandas        | L   | 0.747      | -            | -                | -                | -         |    -6.56 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1711 | 2024-05-23 | Metizport       | W   | 0.731      | 0.435        | 0.038 (0.012)    | -                | 0 (0.000) |    14.74 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1797 | 2024-05-21 | System5         | W   | 0.720      | -            | -                | -                | 0 (0.000) |     6.14 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1870 | 2024-05-19 | DMS             | W   | 0.706      | -            | -                | -                | 0 (0.000) |    13.19 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1919 | 2024-05-18 | Verdant         | W   | 0.698      | 0.435        | 0.015 (0.005)    | -                | 0 (0.000) |    13.67 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1950 | 2024-05-17 | 777             | L   | 0.691      | -            | -                | -                | -         |   -14.35 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     1969 | 2024-05-16 | GUN5            | L   | 0.687      | -            | -                | -                | -         |    -7.83 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2025 | 2024-05-15 | Rounds          | W   | 0.679      | -            | -                | -                | -         |     1.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2049 | 2024-05-15 | Nexus           | W   | 0.677      | 0.435        | 0.014 (0.004)    | 0.504 (0.148)    | -         |     9.37 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2081 | 2024-05-14 | EYEBALLERS      | W   | 0.674      | 0.500        | 0.006 (0.002)    | 0.512 (0.173)    | -         |    12.45 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2125 | 2024-05-13 | MOUZ NXT        | L   | 0.664      | -            | -                | -                | -         |    -5.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2177 | 2024-05-11 | Viperio         | W   | 0.652      | -            | -                | -                | -         |     4.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2614 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.514      | 0.500        | 0.032 (0.008)    | 0.563 (0.145)    | -         |    11.08 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3125 | 2024-04-04 | 3DMAX           | L   | 0.406      | -            | -                | -                | -         |    -0.12 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3169 | 2024-04-03 | PARIVISION      | L   | 0.399      | -            | -                | -                | -         |    -2.24 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3249 | 2024-03-29 | B8              | W   | 0.366      | 0.500        | 0.168 (0.031)    | 0.878 (0.161)    | -         |     9.64 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3265 | 2024-03-28 | GUN5            | L   | 0.360      | -            | -                | -                | -         |    -3.74 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3729 | 2024-03-07 | Apeks           | L   | 0.220      | -            | -                | -                | -         |    -2.50 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,929.27)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.846 | $500.00        | $423.16         |
| 2024-05-26 |      0.753 | $2,000.00      | $1,506.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
