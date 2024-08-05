### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  844.1<br />
<br />
Final Rank Value (844.1) = Starting Rank Value (813.5) + Head To Head Adjustments (30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.180[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.5
- 400 + ( ( 0.202 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 813.5


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
|           36 |       13 | 2024-08-05 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.28 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           35 |       96 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.25 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |      103 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.67 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      180 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      227 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.53 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      313 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.70 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      342 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.50 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      363 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.35 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      433 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.44 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      548 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.361 (0.157)    | 0 (0.000) |    12.56 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      621 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.438 (0.191)    | 0 (0.000) |    16.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      807 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.902 (0.392)    | 0 (0.000) |    18.43 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1100 | 2024-06-14 | BIG             | L   | 0.852      | -            | -                | -                | -         |    -2.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1185 | 2024-06-11 | Rare Atom       | W   | 0.832      | 0.435        | 0.009 (0.003)    | 0.474 (0.172)    | 0 (0.000) |    12.05 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1206 | 2024-06-10 | Passion UA      | L   | 0.826      | -            | -                | -                | -         |    -6.57 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1313 | 2024-06-08 | Permitta        | L   | 0.813      | -            | -                | -                | -         |   -10.69 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1434 | 2024-06-06 | VP.Prodigy      | W   | 0.800      | 0.435        | 0.025 (0.009)    | 0.393 (0.137)    | 0 (0.000) |    14.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1571 | 2024-06-03 | EYEBALLERS      | W   | 0.780      | 0.435        | 0.005 (0.002)    | 0.500 (0.170)    | 0 (0.000) |    12.08 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1784 | 2024-05-25 | 9 Pandas        | L   | 0.720      | -            | -                | -                | -         |    -6.17 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1828 | 2024-05-23 | Metizport       | W   | 0.704      | -            | -                | -                | 0 (0.000) |     9.90 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1900 | 2024-05-21 | System5         | W   | 0.693      | -            | -                | -                | 0 (0.000) |     6.00 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1962 | 2024-05-19 | DMS             | W   | 0.679      | 0.435        | -                | 0.438 (0.129)    | 0 (0.000) |    12.93 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     2010 | 2024-05-18 | Verdant         | W   | 0.670      | 0.435        | 0.015 (0.004)    | -                | -         |    13.12 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     2041 | 2024-05-17 | 777             | L   | 0.664      | -            | -                | -                | -         |   -13.75 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2060 | 2024-05-16 | GUN5            | L   | 0.660      | -            | -                | -                | -         |    -7.73 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2116 | 2024-05-15 | Rounds          | W   | 0.652      | -            | -                | -                | -         |     1.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2134 | 2024-05-15 | Nexus           | W   | 0.650      | 0.435        | 0.014 (0.004)    | -                | -         |     9.13 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2166 | 2024-05-14 | EYEBALLERS      | W   | 0.647      | 0.500        | 0.005 (0.002)    | 0.500 (0.162)    | -         |    11.95 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2207 | 2024-05-13 | MOUZ NXT        | L   | 0.637      | -            | -                | -                | -         |    -4.45 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2259 | 2024-05-11 | Viperio         | W   | 0.625      | -            | -                | -                | -         |     4.61 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2685 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.487      | 0.500        | 0.031 (0.008)    | 0.550 (0.134)    | -         |    10.64 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3190 | 2024-04-04 | 3DMAX           | L   | 0.379      | -            | -                | -                | -         |    -0.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3229 | 2024-04-03 | PARIVISION      | L   | 0.372      | -            | -                | -                | -         |    -1.94 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3307 | 2024-03-29 | B8              | W   | 0.339      | 0.500        | 0.165 (0.028)    | 0.935 (0.159)    | -         |     8.89 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3323 | 2024-03-28 | GUN5            | L   | 0.333      | -            | -                | -                | -         |    -3.56 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3776 | 2024-03-07 | Apeks           | L   | 0.193      | -            | -                | -                | -         |    -2.30 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,861.56)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.819 | $500.00        | $409.62         |
| 2024-05-26 |      0.726 | $2,000.00      | $1,451.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
