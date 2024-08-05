### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  843.3<br />
<br />
Final Rank Value (843.3) = Starting Rank Value (812.6) + Head To Head Adjustments (30.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.178[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.6
- 400 + ( ( 0.201 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 812.6


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
|           36 |       12 | 2024-08-05 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.30 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           35 |       95 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.24 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |      102 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.64 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      179 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.61 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      226 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.50 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      312 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.69 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      341 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.60 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      362 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.33 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      432 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.42 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      547 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.361 (0.157)    | 0 (0.000) |    12.59 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      620 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.438 (0.191)    | 0 (0.000) |    16.49 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      806 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.863 (0.375)    | 0 (0.000) |    18.30 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1099 | 2024-06-14 | BIG             | L   | 0.853      | -            | -                | -                | -         |    -2.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1184 | 2024-06-11 | Rare Atom       | W   | 0.833      | 0.435        | 0.009 (0.003)    | 0.474 (0.172)    | 0 (0.000) |    12.08 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1205 | 2024-06-10 | Passion UA      | L   | 0.826      | -            | -                | -                | -         |    -6.58 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1312 | 2024-06-08 | Permitta        | L   | 0.813      | -            | -                | -                | -         |   -10.84 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1433 | 2024-06-06 | VP.Prodigy      | W   | 0.800      | 0.435        | 0.025 (0.009)    | 0.393 (0.137)    | 0 (0.000) |    14.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1570 | 2024-06-03 | EYEBALLERS      | W   | 0.780      | 0.435        | 0.005 (0.002)    | 0.500 (0.170)    | 0 (0.000) |    12.09 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1783 | 2024-05-25 | 9 Pandas        | L   | 0.720      | -            | -                | -                | -         |    -6.16 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1827 | 2024-05-23 | Metizport       | W   | 0.704      | -            | -                | -                | 0 (0.000) |     9.93 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1899 | 2024-05-21 | System5         | W   | 0.694      | -            | -                | -                | 0 (0.000) |     6.01 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1961 | 2024-05-19 | DMS             | W   | 0.680      | 0.435        | -                | 0.438 (0.130)    | 0 (0.000) |    12.96 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     2009 | 2024-05-18 | Verdant         | W   | 0.671      | 0.435        | 0.015 (0.004)    | -                | -         |    13.15 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     2040 | 2024-05-17 | 777             | L   | 0.664      | -            | -                | -                | -         |   -13.74 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2059 | 2024-05-16 | GUN5            | L   | 0.660      | -            | -                | -                | -         |    -7.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2115 | 2024-05-15 | Rounds          | W   | 0.653      | -            | -                | -                | -         |     1.55 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2133 | 2024-05-15 | Nexus           | W   | 0.651      | 0.435        | 0.014 (0.004)    | -                | -         |     9.14 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2165 | 2024-05-14 | EYEBALLERS      | W   | 0.647      | 0.500        | 0.005 (0.002)    | 0.500 (0.162)    | -         |    11.96 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2206 | 2024-05-13 | MOUZ NXT        | L   | 0.637      | -            | -                | -                | -         |    -4.44 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2258 | 2024-05-11 | Viperio         | W   | 0.625      | -            | -                | -                | -         |     4.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2684 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.487      | 0.500        | 0.031 (0.008)    | 0.550 (0.134)    | -         |    10.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3189 | 2024-04-04 | 3DMAX           | L   | 0.379      | -            | -                | -                | -         |    -0.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3228 | 2024-04-03 | PARIVISION      | L   | 0.372      | -            | -                | -                | -         |    -1.94 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3306 | 2024-03-29 | B8              | W   | 0.340      | 0.500        | 0.165 (0.028)    | 0.935 (0.159)    | -         |     8.91 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3322 | 2024-03-28 | GUN5            | L   | 0.333      | -            | -                | -                | -         |    -3.56 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3775 | 2024-03-07 | Apeks           | L   | 0.193      | -            | -                | -                | -         |    -2.29 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,862.60)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.820 | $500.00        | $409.83         |
| 2024-05-26 |      0.726 | $2,000.00      | $1,452.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
