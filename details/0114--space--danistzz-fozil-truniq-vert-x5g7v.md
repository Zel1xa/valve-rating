### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
<br />
Final Rank Value:  830.8<br />
<br />
Final Rank Value (830.8) = Starting Rank Value (813.3) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.3
- 400 + ( ( 0.202 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 813.3


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
|           35 |       74 | 2024-08-02 | B8              | L   | 1.000      | -            | -                | -                | -         |    -4.21 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           34 |       81 | 2024-08-02 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -12.62 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           33 |      158 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.57 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |      205 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.43 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      291 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.59 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      320 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.51 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      341 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.23 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      411 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.33 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      526 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.365 (0.159)    | 0 (0.000) |    12.71 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      599 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | 0.003 (0.001)    | 0.446 (0.194)    | 0 (0.000) |    16.51 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      785 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.876 (0.381)    | 0 (0.000) |    18.41 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |     1078 | 2024-06-14 | BIG             | L   | 0.857      | -            | -                | -                | -         |    -2.18 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1163 | 2024-06-11 | Rare Atom       | W   | 0.837      | 0.435        | -                | 0.481 (0.175)    | 0 (0.000) |     7.90 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1184 | 2024-06-10 | Passion UA      | L   | 0.830      | -            | -                | -                | -         |    -6.77 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1291 | 2024-06-08 | Permitta        | L   | 0.818      | -            | -                | -                | -         |   -10.96 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1412 | 2024-06-06 | VP.Prodigy      | W   | 0.804      | 0.435        | 0.025 (0.009)    | 0.400 (0.140)    | 0 (0.000) |    14.61 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1549 | 2024-06-03 | EYEBALLERS      | W   | 0.784      | 0.435        | 0.005 (0.002)    | 0.509 (0.174)    | 0 (0.000) |    12.11 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1762 | 2024-05-25 | 9 Pandas        | L   | 0.725      | -            | -                | -                | -         |    -6.22 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1806 | 2024-05-23 | Metizport       | W   | 0.709      | -            | -                | -                | 0 (0.000) |     9.84 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1878 | 2024-05-21 | System5         | W   | 0.698      | -            | -                | -                | 0 (0.000) |     6.04 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1940 | 2024-05-19 | DMS             | W   | 0.684      | 0.435        | -                | 0.446 (0.133)    | 0 (0.000) |    12.94 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1988 | 2024-05-18 | Verdant         | W   | 0.675      | 0.435        | 0.015 (0.004)    | -                | 0 (0.000) |    13.19 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     2019 | 2024-05-17 | 777             | L   | 0.669      | -            | -                | -                | -         |   -13.81 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     2038 | 2024-05-16 | GUN5            | L   | 0.665      | -            | -                | -                | -         |    -7.79 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     2094 | 2024-05-15 | Rounds          | W   | 0.657      | -            | -                | -                | -         |     1.56 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     2112 | 2024-05-15 | Nexus           | W   | 0.655      | 0.435        | 0.014 (0.004)    | -                | -         |     9.16 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     2144 | 2024-05-14 | EYEBALLERS      | W   | 0.651      | 0.500        | 0.005 (0.002)    | 0.509 (0.166)    | -         |    12.01 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2185 | 2024-05-13 | MOUZ NXT        | L   | 0.642      | -            | -                | -                | -         |    -4.52 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2237 | 2024-05-11 | Viperio         | W   | 0.629      | -            | -                | -                | -         |     4.63 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2663 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.491      | 0.500        | 0.031 (0.008)    | 0.560 (0.138)    | -         |    10.73 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3168 | 2024-04-04 | 3DMAX           | L   | 0.384      | -            | -                | -                | -         |    -0.11 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3207 | 2024-04-03 | PARIVISION      | L   | 0.377      | -            | -                | -                | -         |    -2.01 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3285 | 2024-03-29 | B8              | W   | 0.344      | 0.500        | 0.165 (0.028)    | 0.951 (0.164)    | -         |     9.02 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3301 | 2024-03-28 | GUN5            | L   | 0.338      | -            | -                | -                | -         |    -3.62 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3754 | 2024-03-07 | Apeks           | L   | 0.198      | -            | -                | -                | -         |    -2.34 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,873.72)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.824 | $500.00        | $412.05         |
| 2024-05-26 |      0.731 | $2,000.00      | $1,461.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
