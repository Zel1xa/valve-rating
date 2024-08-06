### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  844.0<br />
<br />
Final Rank Value (844.0) = Starting Rank Value (813.9) + Head To Head Adjustments (30.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.181[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.9
- 400 + ( ( 0.202 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 813.9


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
|           36 |       18 | 2024-08-05 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.27 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           35 |      102 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.26 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |      109 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.65 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      186 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.63 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      233 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      319 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.69 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      348 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.50 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      369 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.34 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      439 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.43 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      554 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.361 (0.157)    | 0 (0.000) |    12.57 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      627 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.437 (0.190)    | 0 (0.000) |    16.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      813 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.023 (0.010)    | 0.940 (0.408)    | 0 (0.000) |    18.44 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1106 | 2024-06-14 | BIG             | L   | 0.848      | -            | -                | -                | -         |    -2.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1191 | 2024-06-11 | Rare Atom       | W   | 0.828      | 0.435        | 0.009 (0.003)    | 0.475 (0.171)    | 0 (0.000) |    12.01 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1212 | 2024-06-10 | Passion UA      | L   | 0.821      | -            | -                | -                | -         |    -6.52 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1319 | 2024-06-08 | Permitta        | L   | 0.809      | -            | -                | -                | -         |   -10.63 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1440 | 2024-06-06 | VP.Prodigy      | W   | 0.795      | 0.435        | 0.025 (0.009)    | 0.392 (0.135)    | 0 (0.000) |    14.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1577 | 2024-06-03 | EYEBALLERS      | W   | 0.775      | 0.435        | 0.005 (0.002)    | 0.499 (0.168)    | 0 (0.000) |    12.02 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1790 | 2024-05-25 | 9 Pandas        | L   | 0.716      | -            | -                | -                | -         |    -6.16 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1834 | 2024-05-23 | Metizport       | W   | 0.699      | -            | -                | -                | 0 (0.000) |     9.83 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1906 | 2024-05-21 | System5         | W   | 0.689      | -            | -                | -                | 0 (0.000) |     5.95 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1968 | 2024-05-19 | DMS             | W   | 0.675      | -            | -                | -                | 0 (0.000) |    12.84 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     2016 | 2024-05-18 | Verdant         | W   | 0.666      | 0.435        | 0.015 (0.004)    | -                | -         |    13.04 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     2047 | 2024-05-17 | 777             | L   | 0.660      | -            | -                | -                | -         |   -13.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2066 | 2024-05-16 | GUN5            | L   | 0.656      | -            | -                | -                | -         |    -7.69 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2122 | 2024-05-15 | Rounds          | W   | 0.648      | -            | -                | -                | -         |     1.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2140 | 2024-05-15 | Nexus           | W   | 0.646      | 0.435        | 0.014 (0.004)    | 0.457 (0.128)    | -         |     9.09 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2172 | 2024-05-14 | EYEBALLERS      | W   | 0.642      | 0.500        | 0.005 (0.002)    | 0.499 (0.160)    | -         |    11.86 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2213 | 2024-05-13 | MOUZ NXT        | L   | 0.633      | -            | -                | -                | -         |    -4.42 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2265 | 2024-05-11 | Viperio         | W   | 0.620      | -            | -                | -                | -         |     4.57 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2691 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.482      | 0.500        | 0.031 (0.008)    | 0.549 (0.132)    | -         |    10.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3196 | 2024-04-04 | 3DMAX           | L   | 0.374      | -            | -                | -                | -         |    -0.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3235 | 2024-04-03 | PARIVISION      | L   | 0.368      | -            | -                | -                | -         |    -1.91 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3313 | 2024-03-29 | B8              | W   | 0.335      | 0.500        | 0.164 (0.028)    | 0.933 (0.156)    | -         |     8.77 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3329 | 2024-03-28 | GUN5            | L   | 0.328      | -            | -                | -                | -         |    -3.53 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3782 | 2024-03-07 | Apeks           | L   | 0.188      | -            | -                | -                | -         |    -2.27 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,850.80)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.815 | $500.00        | $407.47         |
| 2024-05-26 |      0.722 | $2,000.00      | $1,443.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
