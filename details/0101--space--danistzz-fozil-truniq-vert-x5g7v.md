### Roster Details<br />
Team Name: Space<br />
Roster: danistzz, fozil, TruNiQ, Vert, X5G7V<br />
Global Rank: [101](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.1<br />
<br />
Final Rank Value (855.1) = Starting Rank Value (820.3) + Head To Head Adjustments (34.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.309[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.180[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 820.3
- 400 + ( ( 0.204 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 820.3


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
|           33 |        5 | 2024-07-31 | Nemiga          | L   | 1.000      | -            | -                | -                | -         |    -4.77 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           32 |       52 | 2024-07-30 | PERA            | L   | 1.000      | -            | -                | -                | -         |   -11.60 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           31 |      138 | 2024-07-28 | Endpoint        | L   | 1.000      | -            | -                | -                | -         |   -17.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           30 |      167 | 2024-07-26 | Permitta        | L   | 1.000      | -            | -                | -                | -         |   -15.75 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           29 |      188 | 2024-07-26 | Monte           | L   | 1.000      | -            | -                | -                | -         |    -9.30 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           28 |      258 | 2024-07-24 | CPH Wolves      | L   | 1.000      | -            | -                | -                | -         |   -18.59 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           27 |      373 | 2024-07-20 | CPH Wolves      | W   | 1.000      | 0.435        | 0.004 (0.002)    | 0.359 (0.156)    | 0 (0.000) |    12.48 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           26 |      446 | 2024-07-18 | DMS             | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    16.31 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           25 |      632 | 2024-07-15 | Permitta        | W   | 1.000      | 0.435        | 0.024 (0.011)    | 0.799 (0.347)    | 0 (0.000) |    17.89 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           24 |      925 | 2024-06-14 | BIG             | L   | 0.885      | -            | -                | -                | -         |    -2.85 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           23 |     1010 | 2024-06-11 | Rare Atom       | W   | 0.865      | 0.435        | -                | 0.397 (0.149)    | 0 (0.000) |     6.54 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           22 |     1031 | 2024-06-10 | Passion UA      | L   | 0.858      | -            | -                | -                | -         |    -7.43 | danistzz, fozil, H4SAN4TOR, Vert, X5G7V   |
|           21 |     1138 | 2024-06-08 | Permitta        | L   | 0.846      | -            | -                | -                | -         |   -11.95 | danistzz, fozil, H4SAN4TOR, TruNiQ, X5G7V |
|           20 |     1259 | 2024-06-06 | VP.Prodigy      | W   | 0.832      | 0.435        | 0.026 (0.009)    | 0.406 (0.147)    | 0 (0.000) |    14.73 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           19 |     1396 | 2024-06-03 | EYEBALLERS      | W   | 0.812      | 0.435        | 0.006 (0.002)    | 0.513 (0.181)    | 0 (0.000) |    12.37 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           18 |     1609 | 2024-05-25 | 9 Pandas        | L   | 0.753      | -            | -                | -                | -         |    -6.61 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           17 |     1653 | 2024-05-23 | Metizport       | W   | 0.737      | 0.435        | 0.038 (0.012)    | -                | 0 (0.000) |    15.05 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           16 |     1725 | 2024-05-21 | System5         | W   | 0.726      | -            | -                | -                | 0 (0.000) |     6.19 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           15 |     1787 | 2024-05-19 | DMS             | W   | 0.712      | 0.435        | -                | 0.447 (0.138)    | 0 (0.000) |    13.41 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           14 |     1835 | 2024-05-18 | Verdant         | W   | 0.703      | 0.435        | 0.015 (0.005)    | -                | 0 (0.000) |    13.66 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           13 |     1866 | 2024-05-17 | 777             | L   | 0.697      | -            | -                | -                | -         |   -14.46 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           12 |     1885 | 2024-05-16 | GUN5            | L   | 0.693      | -            | -                | -                | -         |    -8.38 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           11 |     1941 | 2024-05-15 | Rounds          | W   | 0.685      | -            | -                | -                | -         |     1.56 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|           10 |     1959 | 2024-05-15 | Nexus           | W   | 0.683      | 0.435        | 0.014 (0.004)    | -                | -         |     9.42 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            9 |     1991 | 2024-05-14 | EYEBALLERS      | W   | 0.679      | 0.500        | 0.006 (0.002)    | 0.513 (0.174)    | -         |    12.60 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            8 |     2032 | 2024-05-13 | MOUZ NXT        | L   | 0.670      | -            | -                | -                | -         |    -4.84 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            7 |     2084 | 2024-05-11 | Viperio         | W   | 0.657      | -            | -                | -                | -         |     4.75 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            6 |     2510 | 2024-04-20 | ALTERNATE aTTaX | W   | 0.519      | 0.500        | 0.032 (0.008)    | 0.564 (0.147)    | -         |    11.28 | danistzz, fozil, TruNiQ, Vert, X5G7V      |
|            5 |     3015 | 2024-04-04 | 3DMAX           | L   | 0.412      | -            | -                | -                | -         |    -0.12 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            4 |     3054 | 2024-04-03 | PARIVISION      | L   | 0.405      | -            | -                | -                | -         |    -2.30 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            3 |     3132 | 2024-03-29 | B8              | W   | 0.372      | 0.500        | 0.167 (0.031)    | 0.879 (0.164)    | -         |     9.80 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            2 |     3148 | 2024-03-28 | GUN5            | L   | 0.365      | -            | -                | -                | -         |    -4.05 | danistzz, fozil, TruNiQ, Vert, waterfaLLZ |
|            1 |     3601 | 2024-03-07 | Apeks           | L   | 0.225      | -            | -                | -                | -         |    -2.52 | enzero, fozil, TruNiQ, Vert, waterfaLLZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,943.59)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-09 |      0.852 | $500.00        | $426.02         |
| 2024-05-26 |      0.759 | $2,000.00      | $1,517.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
