### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.4<br />
<br />
Final Rank Value (945.4) = Starting Rank Value (918.6) + Head To Head Adjustments (26.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 918.6
- 400 + ( ( 0.253 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 918.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |      253 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    17.92 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      478 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      493 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.40 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      500 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.81 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      523 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.78 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      592 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.61 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      720 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.12 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      819 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.20 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      857 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      938 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1034 | 2024-06-16 | 3DMAX             | L   | 0.864      | -            | -                | -                | -         |    -1.49 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1122 | 2024-06-13 | PERA              | L   | 0.847      | -            | -                | -                | -         |   -12.16 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1139 | 2024-06-13 | Illuminar         | W   | 0.845      | 0.450        | -                | 0.347 (0.132)    | 0 (0.000) |    11.49 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1162 | 2024-06-12 | Sampi             | W   | 0.839      | 0.379        | 0.027 (0.009)    | 1.000 (0.318)    | 0 (0.000) |    11.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1203 | 2024-06-10 | SINNERS           | W   | 0.826      | 0.379        | 0.037 (0.012)    | 0.809 (0.253)    | 0 (0.000) |    16.58 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1219 | 2024-06-10 | Gaimin Gladiators | W   | 0.824      | 0.450        | 0.037 (0.014)    | -                | -         |    15.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1258 | 2024-06-09 | ECLOT             | L   | 0.818      | -            | -                | -                | -         |    -5.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1301 | 2024-06-08 | Nexus             | W   | 0.813      | 0.450        | -                | 0.458 (0.168)    | -         |     7.97 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1385 | 2024-06-07 | Entropiq          | W   | 0.805      | -            | -                | -                | -         |     1.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1439 | 2024-06-06 | Illuminar         | L   | 0.799      | -            | -                | -                | -         |   -15.69 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1484 | 2024-06-05 | Verdant           | L   | 0.793      | -            | -                | -                | -         |   -13.41 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1501 | 2024-06-05 | Serbia            | L   | 0.792      | -            | -                | -                | -         |   -16.77 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1558 | 2024-06-04 | Johnny Speeds     | W   | 0.784      | 0.371        | 0.122 (0.035)    | 1.000 (0.290)    | -         |    21.14 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1580 | 2024-06-03 | UNiTY             | W   | 0.777      | -            | -                | -                | -         |    13.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1622 | 2024-06-01 | ARCRED            | L   | 0.766      | -            | -                | -                | -         |   -11.73 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1637 | 2024-06-01 | Permitta          | W   | 0.764      | 0.371        | -                | 0.902 (0.255)    | -         |    11.96 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1675 | 2024-05-30 | RUSTEC            | W   | 0.753      | -            | -                | -                | -         |     1.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1691 | 2024-05-30 | brazylijski luz   | L   | 0.750      | -            | -                | -                | -         |   -14.38 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1704 | 2024-05-29 | FLuffy Gangsters  | W   | 0.747      | -            | -                | -                | -         |     2.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1730 | 2024-05-28 | Sampi             | W   | 0.739      | 0.379        | -                | 1.000 (0.280)    | -         |    11.67 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1811 | 2024-05-24 | Illuminar         | W   | 0.711      | -            | -                | -                | -         |     9.89 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1861 | 2024-05-22 | Entropiq          | W   | 0.699      | -            | -                | -                | -         |     1.27 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1947 | 2024-05-20 | ECSTATIC          | W   | 0.684      | -            | -                | -                | -         |     2.74 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2275 | 2024-05-10 | BetBoom           | L   | 0.618      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2342 | 2024-05-07 | Permitta          | W   | 0.598      | 0.435        | -                | 0.902 (0.234)    | -         |    10.48 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2356 | 2024-05-06 | B8                | L   | 0.592      | -            | -                | -                | -         |    -5.44 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2384 | 2024-05-04 | MOUZ NXT          | W   | 0.580      | 0.435        | 0.139 (0.035)    | 0.987 (0.249)    | -         |    12.82 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2445 | 2024-05-01 | ENCE Academy      | W   | 0.560      | -            | -                | -                | -         |     5.33 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2473 | 2024-04-30 | EYEBALLERS        | L   | 0.553      | -            | -                | -                | -         |    -8.49 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2509 | 2024-04-29 | Nexus             | L   | 0.544      | -            | -                | -                | -         |    -9.92 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2551 | 2024-04-27 | Permitta          | L   | 0.531      | -            | -                | -                | -         |    -6.89 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2569 | 2024-04-26 | Insilio           | L   | 0.525      | -            | -                | -                | -         |    -7.81 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2643 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.504      | -            | -                | -                | -         |    -7.33 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2708 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.484      | -            | -                | -                | -         |    -6.73 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2793 | 2024-04-18 | MOUZ NXT          | L   | 0.472      | -            | -                | -                | -         |    -4.88 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2805 | 2024-04-18 | Nexus             | W   | 0.471      | -            | -                | -                | -         |     6.17 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2831 | 2024-04-17 | ENCE              | L   | 0.465      | -            | -                | -                | -         |    -0.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2963 | 2024-04-11 | Sashi             | L   | 0.424      | -            | -                | -                | -         |    -3.21 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3007 | 2024-04-10 | AMKAL             | W   | 0.418      | 0.384        | 0.130 (0.021)    | -                | -         |    10.10 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3137 | 2024-04-06 | Sampi             | L   | 0.391      | -            | -                | -                | -         |    -6.26 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3226 | 2024-04-03 | Permitta          | W   | 0.372      | 0.384        | -                | 0.902 (0.129)    | -         |     6.72 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3286 | 2024-04-01 | BLEED             | W   | 0.358      | 0.384        | 0.090 (0.012)    | -                | -         |     6.72 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3725 | 2024-03-09 | kONO              | L   | 0.206      | -            | -                | -                | -         |    -4.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3737 | 2024-03-09 | Sampi             | L   | 0.205      | -            | -                | -                | -         |    -3.50 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3805 | 2024-03-06 | INGLORIOUS        | L   | 0.186      | -            | -                | -                | -         |    -5.25 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3811 | 2024-03-06 | Permitta          | L   | 0.185      | -            | -                | -                | -         |    -2.57 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3922 | 2024-03-02 | Sampi             | W   | 0.157      | -            | -                | -                | -         |     2.24 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4233 | 2024-02-16 | SAW               | L   | 0.060      | -            | -                | -                | -         |    -0.39 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4270 | 2024-02-15 | BetBoom           | L   | 0.052      | -            | -                | -                | -         |    -0.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4297 | 2024-02-14 | Natus Vincere     | L   | 0.047      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4309 | 2024-02-14 | AMKAL             | W   | 0.045      | -            | -                | -                | 1 (0.045) |     1.11 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,642.53)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.871 | $5,000.00      | $4,356.25       |
| 2024-06-13 |      0.847 | $5,447.00      | $4,612.05       |
| 2024-06-06 |      0.797 | $3,000.00      | $2,391.25       |
| 2024-05-02 |      0.566 | $500.00        | $282.99         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
