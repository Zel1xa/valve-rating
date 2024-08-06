### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [107](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [77]( ../standings_europe.md)<br />
<br />
Final Rank Value:  843.8<br />
<br />
Final Rank Value (843.8) = Starting Rank Value (813.3) + Head To Head Adjustments (30.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.180[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.3
- 400 + ( ( 0.201 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 813.3


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
|           36 |       15 | 2024-08-05 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.28 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           35 |       98 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.25 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |      105 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.65 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      182 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      229 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.53 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      315 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.70 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      344 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.50 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      365 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.35 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      435 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.43 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      550 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.361 (0.157)    | 0 (0.000) |    12.57 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      623 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.438 (0.190)    | 0 (0.000) |    16.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      809 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.023 (0.010)    | 0.901 (0.392)    | 0 (0.000) |    18.44 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1102 | 2024-06-14 | BIG             | L   | 0.850      | -            | -                | -                | -         |    -2.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1187 | 2024-06-11 | Rare Atom       | W   | 0.830      | 0.435        | 0.009 (0.003)    | 0.474 (0.171)    | 0 (0.000) |    12.04 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1208 | 2024-06-10 | Passion UA      | L   | 0.824      | -            | -                | -                | -         |    -6.55 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1315 | 2024-06-08 | Permitta        | L   | 0.811      | -            | -                | -                | -         |   -10.66 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1436 | 2024-06-06 | VP.Prodigy      | W   | 0.798      | 0.435        | 0.025 (0.009)    | 0.393 (0.136)    | 0 (0.000) |    14.51 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1573 | 2024-06-03 | EYEBALLERS      | W   | 0.778      | 0.435        | 0.005 (0.002)    | 0.500 (0.169)    | 0 (0.000) |    12.06 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1786 | 2024-05-25 | 9 Pandas        | L   | 0.718      | -            | -                | -                | -         |    -6.16 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1830 | 2024-05-23 | Metizport       | W   | 0.702      | -            | -                | -                | 0 (0.000) |     9.88 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1902 | 2024-05-21 | System5         | W   | 0.691      | -            | -                | -                | 0 (0.000) |     5.99 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1964 | 2024-05-19 | DMS             | W   | 0.678      | 0.435        | -                | 0.438 (0.129)    | 0 (0.000) |    12.90 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     2012 | 2024-05-18 | Verdant         | W   | 0.669      | 0.435        | 0.015 (0.004)    | -                | -         |    13.10 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     2043 | 2024-05-17 | 777             | L   | 0.662      | -            | -                | -                | -         |   -13.70 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2062 | 2024-05-16 | GUN5            | L   | 0.658      | -            | -                | -                | -         |    -7.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2118 | 2024-05-15 | Rounds          | W   | 0.651      | -            | -                | -                | -         |     1.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2136 | 2024-05-15 | Nexus           | W   | 0.649      | 0.435        | 0.014 (0.004)    | -                | -         |     9.11 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2168 | 2024-05-14 | EYEBALLERS      | W   | 0.645      | 0.500        | 0.005 (0.002)    | 0.500 (0.161)    | -         |    11.92 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2209 | 2024-05-13 | MOUZ NXT        | L   | 0.635      | -            | -                | -                | -         |    -4.43 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2261 | 2024-05-11 | Viperio         | W   | 0.623      | -            | -                | -                | -         |     4.60 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2687 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.485      | 0.500        | 0.031 (0.008)    | 0.550 (0.133)    | -         |    10.60 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3192 | 2024-04-04 | 3DMAX           | L   | 0.377      | -            | -                | -                | -         |    -0.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3231 | 2024-04-03 | PARIVISION      | L   | 0.370      | -            | -                | -                | -         |    -1.93 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3309 | 2024-03-29 | B8              | W   | 0.338      | 0.500        | 0.164 (0.028)    | 0.934 (0.158)    | -         |     8.85 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3325 | 2024-03-28 | GUN5            | L   | 0.331      | -            | -                | -                | -         |    -3.54 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3778 | 2024-03-07 | Apeks           | L   | 0.191      | -            | -                | -                | -         |    -2.28 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,857.05)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.817 | $500.00        | $408.72         |
| 2024-05-26 |      0.724 | $2,000.00      | $1,448.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
