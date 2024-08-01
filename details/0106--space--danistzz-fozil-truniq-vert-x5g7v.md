### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [106](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  854.8<br />
<br />
Final Rank Value (854.8) = Starting Rank Value (820.8) + Head To Head Adjustments (34.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 820.8
- 400 + ( ( 0.204 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 820.8


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
|           33 |       32 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.99 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |       80 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.73 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      167 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -16.83 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      196 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.68 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      217 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.88 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      287 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.50 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      405 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.360 (0.156)    | 0 (0.000) |    12.58 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      486 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    16.02 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      676 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.011)    | 0.801 (0.348)    | 0 (0.000) |    17.99 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |      960 | 2024-06-14 | BIG             | L   | 0.881      | -            | -                | -                | -         |    -3.09 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1046 | 2024-06-11 | Rare Atom       | W   | 0.861      | 0.435        | -                | 0.436 (0.163)    | 0 (0.000) |     6.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1068 | 2024-06-10 | Passion UA      | L   | 0.854      | -            | -                | -                | -         |    -7.71 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1177 | 2024-06-08 | Permitta        | L   | 0.841      | -            | -                | -                | -         |   -11.76 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1307 | 2024-06-06 | VP.Prodigy      | W   | 0.828      | 0.435        | 0.026 (0.009)    | 0.405 (0.146)    | 0 (0.000) |    14.74 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1447 | 2024-06-03 | EYEBALLERS      | W   | 0.808      | 0.435        | 0.006 (0.002)    | 0.513 (0.180)    | 0 (0.000) |    12.24 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1663 | 2024-05-25 | 9 Pandas        | L   | 0.748      | -            | -                | -                | -         |    -6.56 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1707 | 2024-05-23 | Metizport       | W   | 0.732      | 0.435        | 0.038 (0.012)    | -                | 0 (0.000) |    14.75 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1793 | 2024-05-21 | System5         | W   | 0.722      | -            | -                | -                | 0 (0.000) |     6.15 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1866 | 2024-05-19 | DMS             | W   | 0.708      | -            | -                | -                | 0 (0.000) |    13.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1915 | 2024-05-18 | Verdant         | W   | 0.699      | 0.435        | 0.015 (0.005)    | -                | 0 (0.000) |    13.69 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1946 | 2024-05-17 | 777             | L   | 0.693      | -            | -                | -                | -         |   -14.38 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     1965 | 2024-05-16 | GUN5            | L   | 0.688      | -            | -                | -                | -         |    -7.84 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2021 | 2024-05-15 | Rounds          | W   | 0.681      | -            | -                | -                | -         |     1.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2045 | 2024-05-15 | Nexus           | W   | 0.679      | 0.435        | 0.014 (0.004)    | 0.504 (0.149)    | -         |     9.38 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2077 | 2024-05-14 | EYEBALLERS      | W   | 0.675      | 0.500        | 0.006 (0.002)    | 0.513 (0.173)    | -         |    12.48 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2121 | 2024-05-13 | MOUZ NXT        | L   | 0.666      | -            | -                | -                | -         |    -5.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2173 | 2024-05-11 | Viperio         | W   | 0.653      | -            | -                | -                | -         |     4.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2610 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.515      | 0.500        | 0.032 (0.008)    | 0.564 (0.145)    | -         |    11.11 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3121 | 2024-04-04 | 3DMAX           | L   | 0.407      | -            | -                | -                | -         |    -0.12 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3165 | 2024-04-03 | PARIVISION      | L   | 0.401      | -            | -                | -                | -         |    -2.24 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3245 | 2024-03-29 | B8              | W   | 0.368      | 0.500        | 0.168 (0.031)    | 0.878 (0.161)    | -         |     9.68 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3261 | 2024-03-28 | GUN5            | L   | 0.361      | -            | -                | -                | -         |    -3.75 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3725 | 2024-03-07 | Apeks           | L   | 0.221      | -            | -                | -                | -         |    -2.51 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,932.74)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.848 | $500.00        | $423.85         |
| 2024-05-26 |      0.754 | $2,000.00      | $1,508.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
