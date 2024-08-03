### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
<br />
Final Rank Value:  837.2<br />
<br />
Final Rank Value (837.2) = Starting Rank Value (820.2) + Head To Head Adjustments (16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.189[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 820.2
- 400 + ( ( 0.205 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 820.2


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
|           34 |       30 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.45 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |       37 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -18.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |       97 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -5.10 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      143 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.95 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      229 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -18.00 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      258 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -16.70 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      279 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |   -10.29 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      349 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -19.02 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      464 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.376 (0.163)    | 0 (0.000) |    12.00 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      537 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.462 (0.201)    | 0 (0.000) |    15.95 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |      720 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.887 (0.385)    | 0 (0.000) |    17.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |      988 | 2024-06-14 | BIG             | L   | 0.866      | -            | -                | -                | -         |    -2.44 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1069 | 2024-06-11 | Rare Atom       | W   | 0.846      | 0.435        | -                | 0.495 (0.182)    | 0 (0.000) |     7.38 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           21 |     1090 | 2024-06-10 | Passion UA      | L   | 0.839      | -            | -                | -                | -         |    -7.63 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           20 |     1312 | 2024-06-06 | VP.Prodigy      | W   | 0.813      | 0.435        | 0.026 (0.009)    | 0.416 (0.147)    | 0 (0.000) |    14.41 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1447 | 2024-06-03 | EYEBALLERS      | W   | 0.793      | 0.435        | 0.006 (0.002)    | 0.528 (0.182)    | 0 (0.000) |    12.02 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1658 | 2024-05-25 | 9 Pandas        | L   | 0.734      | -            | -                | -                | -         |    -6.50 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1702 | 2024-05-23 | Metizport       | W   | 0.718      | 0.435        | 0.037 (0.012)    | -                | 0 (0.000) |    14.49 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1774 | 2024-05-21 | System5         | W   | 0.707      | -            | -                | -                | 0 (0.000) |     5.99 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1835 | 2024-05-19 | DMS             | W   | 0.693      | 0.435        | -                | 0.462 (0.139)    | 0 (0.000) |    12.92 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1883 | 2024-05-18 | Verdant         | W   | 0.684      | 0.435        | 0.015 (0.004)    | -                | 0 (0.000) |    13.19 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1914 | 2024-05-17 | 777             | L   | 0.678      | -            | -                | -                | -         |   -14.28 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     1933 | 2024-05-16 | GUN5            | L   | 0.674      | -            | -                | -                | -         |    -7.98 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     1989 | 2024-05-15 | Rounds          | W   | 0.666      | -            | -                | -                | -         |     1.53 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2007 | 2024-05-15 | Nexus           | W   | 0.664      | 0.435        | 0.014 (0.004)    | -                | -         |     9.15 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2039 | 2024-05-14 | EYEBALLERS      | W   | 0.660      | 0.500        | 0.006 (0.002)    | 0.528 (0.174)    | -         |    12.13 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2080 | 2024-05-13 | MOUZ NXT        | L   | 0.651      | -            | -                | -                | -         |    -4.80 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2132 | 2024-05-11 | Viperio         | W   | 0.638      | -            | -                | -                | -         |     4.58 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2556 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.500      | 0.500        | 0.032 (0.008)    | 0.580 (0.145)    | -         |    10.80 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3061 | 2024-04-04 | 3DMAX           | L   | 0.393      | -            | -                | -                | -         |    -0.12 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3100 | 2024-04-03 | PARIVISION      | L   | 0.386      | -            | -                | -                | -         |    -2.10 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3178 | 2024-03-29 | B8              | W   | 0.353      | 0.500        | 0.166 (0.029)    | 0.945 (0.167)    | -         |     9.22 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3194 | 2024-03-28 | GUN5            | L   | 0.346      | -            | -                | -                | -         |    -3.76 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3639 | 2024-03-07 | Apeks           | L   | 0.206      | -            | -                | -                | -         |    -2.47 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,896.05)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.833 | $500.00        | $416.52         |
| 2024-05-26 |      0.740 | $2,000.00      | $1,479.54       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
