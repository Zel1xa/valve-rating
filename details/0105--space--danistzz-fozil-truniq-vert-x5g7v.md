### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [105](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [76]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.3<br />
<br />
Final Rank Value (848.3) = Starting Rank Value (816.2) + Head To Head Adjustments (32.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.177[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 816.2
- 400 + ( ( 0.202 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 816.2


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
|           36 |       21 | 2024-08-05 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.13 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           35 |      106 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.33 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |      113 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      190 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.72 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      237 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      323 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.67 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      352 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.45 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      373 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.51 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      443 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.61 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      558 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | -                | 0.353 (0.154)    | 0 (0.000) |    12.37 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      631 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    16.24 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      817 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.023 (0.010)    | 0.919 (0.399)    | 0 (0.000) |    18.23 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1110 | 2024-06-14 | BIG             | L   | 0.848      | -            | -                | -                | -         |    -2.28 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1195 | 2024-06-11 | Rare Atom       | W   | 0.828      | 0.435        | 0.009 (0.003)    | 0.464 (0.167)    | 0 (0.000) |    11.95 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1216 | 2024-06-10 | Passion UA      | L   | 0.821      | -            | -                | -                | -         |    -6.66 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1323 | 2024-06-08 | Permitta        | L   | 0.808      | -            | -                | -                | -         |   -10.81 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1444 | 2024-06-06 | VP.Prodigy      | W   | 0.795      | 0.435        | 0.025 (0.009)    | 0.383 (0.132)    | 0 (0.000) |    14.25 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1581 | 2024-06-03 | EYEBALLERS      | W   | 0.775      | 0.435        | 0.005 (0.002)    | 0.488 (0.164)    | 0 (0.000) |    11.96 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1794 | 2024-05-25 | 9 Pandas        | L   | 0.715      | -            | -                | -                | -         |    -6.32 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1838 | 2024-05-23 | Metizport       | W   | 0.699      | 0.435        | 0.036 (0.011)    | 0.434 (0.132)    | 0 (0.000) |    14.27 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1910 | 2024-05-21 | System5         | W   | 0.689      | -            | -                | -                | 0 (0.000) |     5.91 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1972 | 2024-05-19 | DMS             | W   | 0.675      | -            | -                | -                | 0 (0.000) |    12.77 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     2020 | 2024-05-18 | Verdant         | W   | 0.666      | 0.435        | 0.015 (0.004)    | -                | -         |    13.01 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     2051 | 2024-05-17 | 777             | L   | 0.659      | -            | -                | -                | -         |   -13.70 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2070 | 2024-05-16 | GUN5            | L   | 0.655      | -            | -                | -                | -         |    -7.75 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2126 | 2024-05-15 | Rounds          | W   | 0.648      | -            | -                | -                | -         |     1.52 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2144 | 2024-05-15 | Nexus           | W   | 0.646      | 0.435        | 0.014 (0.004)    | -                | -         |     9.07 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2176 | 2024-05-14 | EYEBALLERS      | W   | 0.642      | 0.500        | 0.005 (0.002)    | 0.488 (0.157)    | -         |    11.94 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2217 | 2024-05-13 | MOUZ NXT        | L   | 0.632      | -            | -                | -                | -         |    -4.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2269 | 2024-05-11 | Viperio         | W   | 0.620      | -            | -                | -                | -         |     4.53 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2695 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.482      | 0.500        | 0.031 (0.008)    | 0.537 (0.129)    | -         |    10.52 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3200 | 2024-04-04 | 3DMAX           | L   | 0.374      | -            | -                | -                | -         |    -0.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3239 | 2024-04-03 | PARIVISION      | L   | 0.367      | -            | -                | -                | -         |    -1.92 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3317 | 2024-03-29 | B8              | W   | 0.335      | 0.500        | 0.170 (0.029)    | 0.912 (0.153)    | -         |     8.77 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3333 | 2024-03-28 | GUN5            | L   | 0.328      | -            | -                | -                | -         |    -3.56 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3786 | 2024-03-07 | Apeks           | L   | 0.188      | -            | -                | -                | -         |    -2.27 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,850.10)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $500.00        | $407.33         |
| 2024-05-26 |      0.721 | $2,000.00      | $1,442.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
