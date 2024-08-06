### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.5<br />
<br />
Final Rank Value (958.5) = Starting Rank Value (919.0) + Head To Head Adjustments (39.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.0
- 400 + ( ( 0.252 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 919.0


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
|           62 |       10 | 2024-08-06 | Verdant           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.17 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           61 |      274 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    17.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      499 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      514 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      521 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      544 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.73 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      613 | 2024-07-19 | UNiTY             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.55 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      741 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.13 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      840 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.18 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      878 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      959 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    10.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1055 | 2024-06-16 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |    -1.46 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1143 | 2024-06-13 | PERA              | L   | 0.841      | -            | -                | -                | -         |   -12.15 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1160 | 2024-06-13 | Illuminar         | W   | 0.839      | 0.450        | -                | 0.340 (0.128)    | 0 (0.000) |    11.50 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1183 | 2024-06-12 | Sampi             | W   | 0.833      | 0.379        | -                | 1.000 (0.316)    | 0 (0.000) |    11.07 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1224 | 2024-06-10 | SINNERS           | W   | 0.820      | 0.379        | 0.037 (0.012)    | 0.800 (0.248)    | -         |    16.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1240 | 2024-06-10 | Gaimin Gladiators | W   | 0.818      | 0.450        | 0.037 (0.014)    | -                | -         |    15.15 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1279 | 2024-06-09 | ECLOT             | L   | 0.813      | -            | -                | -                | -         |    -5.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1322 | 2024-06-08 | Nexus             | W   | 0.807      | 0.450        | -                | 0.447 (0.162)    | -         |     7.98 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1406 | 2024-06-07 | Entropiq          | W   | 0.799      | -            | -                | -                | -         |     1.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1460 | 2024-06-06 | Illuminar         | L   | 0.793      | -            | -                | -                | -         |   -15.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1505 | 2024-06-05 | Verdant           | L   | 0.787      | -            | -                | -                | -         |   -13.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1522 | 2024-06-05 | Serbia            | L   | 0.786      | -            | -                | -                | -         |   -16.61 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1579 | 2024-06-04 | Johnny Speeds     | W   | 0.778      | 0.371        | 0.122 (0.035)    | 1.000 (0.288)    | -         |    21.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1601 | 2024-06-03 | UNiTY             | W   | 0.771      | -            | -                | -                | -         |    13.72 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1643 | 2024-06-01 | ARCRED            | L   | 0.760      | -            | -                | -                | -         |   -11.68 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1658 | 2024-06-01 | Permitta          | W   | 0.758      | 0.371        | 0.039 (0.011)    | 0.919 (0.258)    | -         |    12.18 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1696 | 2024-05-30 | RUSTEC            | W   | 0.747      | -            | -                | -                | -         |     1.27 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1712 | 2024-05-30 | brazylijski luz   | L   | 0.744      | -            | -                | -                | -         |   -14.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1725 | 2024-05-29 | FLuffy Gangsters  | W   | 0.741      | -            | -                | -                | -         |     2.81 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1751 | 2024-05-28 | Sampi             | W   | 0.733      | 0.379        | -                | 1.000 (0.278)    | -         |    11.55 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1832 | 2024-05-24 | Illuminar         | W   | 0.705      | -            | -                | -                | -         |     9.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1882 | 2024-05-22 | Entropiq          | W   | 0.693      | -            | -                | -                | -         |     1.25 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1968 | 2024-05-20 | ECSTATIC          | W   | 0.678      | -            | -                | -                | -         |     2.69 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2296 | 2024-05-10 | BetBoom           | L   | 0.612      | -            | -                | -                | -         |    -1.22 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2363 | 2024-05-07 | Permitta          | W   | 0.592      | 0.435        | 0.039 (0.010)    | 0.919 (0.236)    | -         |    10.60 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2377 | 2024-05-06 | B8                | L   | 0.586      | -            | -                | -                | -         |    -5.37 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2405 | 2024-05-04 | MOUZ NXT          | W   | 0.574      | 0.435        | 0.139 (0.035)    | 0.961 (0.240)    | -         |    12.68 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2466 | 2024-05-01 | ENCE Academy      | W   | 0.554      | -            | -                | -                | -         |     5.25 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2494 | 2024-04-30 | EYEBALLERS        | L   | 0.547      | -            | -                | -                | -         |    -8.40 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2530 | 2024-04-29 | Nexus             | L   | 0.538      | -            | -                | -                | -         |    -9.75 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2572 | 2024-04-27 | Permitta          | L   | 0.525      | -            | -                | -                | -         |    -6.57 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2590 | 2024-04-26 | Insilio           | L   | 0.519      | -            | -                | -                | -         |    -7.71 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2664 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.498      | -            | -                | -                | -         |    -7.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2729 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.478      | -            | -                | -                | -         |    -6.61 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2814 | 2024-04-18 | MOUZ NXT          | L   | 0.466      | -            | -                | -                | -         |    -4.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2826 | 2024-04-18 | Nexus             | W   | 0.465      | -            | -                | -                | -         |     6.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2852 | 2024-04-17 | ENCE              | L   | 0.459      | -            | -                | -                | -         |    -0.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2984 | 2024-04-11 | Sashi             | L   | 0.418      | -            | -                | -                | -         |    -3.15 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3028 | 2024-04-10 | AMKAL             | W   | 0.412      | 0.384        | 0.130 (0.020)    | -                | -         |     9.96 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3158 | 2024-04-06 | Sampi             | L   | 0.385      | -            | -                | -                | -         |    -6.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3247 | 2024-04-03 | Permitta          | W   | 0.367      | 0.384        | -                | 0.919 (0.129)    | -         |     6.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3307 | 2024-04-01 | BLEED             | W   | 0.352      | 0.384        | 0.089 (0.012)    | -                | -         |     6.58 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3746 | 2024-03-09 | kONO              | L   | 0.200      | -            | -                | -                | -         |    -4.03 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3758 | 2024-03-09 | Sampi             | L   | 0.199      | -            | -                | -                | -         |    -3.40 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3826 | 2024-03-06 | INGLORIOUS        | L   | 0.180      | -            | -                | -                | -         |    -5.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3832 | 2024-03-06 | Permitta          | L   | 0.179      | -            | -                | -                | -         |    -2.34 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3943 | 2024-03-02 | Sampi             | W   | 0.151      | -            | -                | -                | -         |     2.15 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4254 | 2024-02-16 | SAW               | L   | 0.054      | -            | -                | -                | -         |    -0.35 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4291 | 2024-02-15 | BetBoom           | L   | 0.046      | -            | -                | -                | -         |    -0.08 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4318 | 2024-02-14 | Natus Vincere     | L   | 0.041      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4330 | 2024-02-14 | AMKAL             | W   | 0.039      | -            | -                | -                | 1 (0.039) |     0.97 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,559.24)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.865 | $5,000.00      | $4,326.39       |
| 2024-06-13 |      0.841 | $5,447.00      | $4,579.51       |
| 2024-06-06 |      0.791 | $3,000.00      | $2,373.33       |
| 2024-05-02 |      0.560 | $500.00        | $280.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
