### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.8<br />
<br />
Final Rank Value (956.8) = Starting Rank Value (918.6) + Head To Head Adjustments (38.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 918.6
- 400 + ( ( 0.252 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 918.6


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
|           62 |        1 | 2024-08-06 | Verdant           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.16 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           61 |      263 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    17.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      488 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      503 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.40 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      510 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      533 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.76 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      602 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.024 (0.009)    | -                | 0 (0.000) |    17.59 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      730 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.11 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      829 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.20 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      867 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      948 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1044 | 2024-06-16 | 3DMAX             | L   | 0.860      | -            | -                | -                | -         |    -1.46 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1132 | 2024-06-13 | PERA              | L   | 0.842      | -            | -                | -                | -         |   -12.11 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1149 | 2024-06-13 | Illuminar         | W   | 0.840      | 0.450        | -                | 0.340 (0.129)    | 0 (0.000) |    11.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1172 | 2024-06-12 | Sampi             | W   | 0.834      | 0.379        | 0.027 (0.009)    | 1.000 (0.316)    | 0 (0.000) |    10.97 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1213 | 2024-06-10 | SINNERS           | W   | 0.821      | 0.379        | 0.037 (0.012)    | 0.790 (0.246)    | -         |    16.50 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1229 | 2024-06-10 | Gaimin Gladiators | W   | 0.820      | 0.450        | 0.037 (0.014)    | -                | -         |    15.23 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1268 | 2024-06-09 | ECLOT             | L   | 0.814      | -            | -                | -                | -         |    -5.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1311 | 2024-06-08 | Nexus             | W   | 0.809      | 0.450        | -                | 0.447 (0.163)    | -         |     7.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1395 | 2024-06-07 | Entropiq          | W   | 0.800      | -            | -                | -                | -         |     1.43 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1449 | 2024-06-06 | Illuminar         | L   | 0.795      | -            | -                | -                | -         |   -15.59 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1494 | 2024-06-05 | Verdant           | L   | 0.789      | -            | -                | -                | -         |   -13.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1511 | 2024-06-05 | Serbia            | L   | 0.787      | -            | -                | -                | -         |   -16.66 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1568 | 2024-06-04 | Johnny Speeds     | W   | 0.779      | 0.371        | 0.122 (0.035)    | 1.000 (0.289)    | -         |    21.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1590 | 2024-06-03 | UNiTY             | W   | 0.772      | -            | -                | -                | -         |    13.78 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1632 | 2024-06-01 | ARCRED            | L   | 0.761      | -            | -                | -                | -         |   -11.67 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1647 | 2024-06-01 | Permitta          | W   | 0.759      | 0.371        | -                | 0.919 (0.258)    | -         |    11.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1685 | 2024-05-30 | RUSTEC            | W   | 0.749      | -            | -                | -                | -         |     1.28 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1701 | 2024-05-30 | brazylijski luz   | L   | 0.746      | -            | -                | -                | -         |   -14.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1714 | 2024-05-29 | FLuffy Gangsters  | W   | 0.742      | -            | -                | -                | -         |     2.82 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1740 | 2024-05-28 | Sampi             | W   | 0.734      | 0.379        | -                | 1.000 (0.278)    | -         |    11.58 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1821 | 2024-05-24 | Illuminar         | W   | 0.707      | -            | -                | -                | -         |     9.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1871 | 2024-05-22 | Entropiq          | W   | 0.694      | -            | -                | -                | -         |     1.26 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1957 | 2024-05-20 | ECSTATIC          | W   | 0.680      | -            | -                | -                | -         |     2.72 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2285 | 2024-05-10 | BetBoom           | L   | 0.614      | -            | -                | -                | -         |    -1.21 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2352 | 2024-05-07 | Permitta          | W   | 0.593      | 0.435        | -                | 0.919 (0.237)    | -         |    10.40 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2366 | 2024-05-06 | B8                | L   | 0.587      | -            | -                | -                | -         |    -5.37 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2394 | 2024-05-04 | MOUZ NXT          | W   | 0.575      | 0.435        | 0.139 (0.035)    | 0.962 (0.241)    | -         |    12.72 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2455 | 2024-05-01 | ENCE Academy      | W   | 0.555      | -            | -                | -                | -         |     5.29 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2483 | 2024-04-30 | EYEBALLERS        | L   | 0.548      | -            | -                | -                | -         |    -8.41 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2519 | 2024-04-29 | Nexus             | L   | 0.539      | -            | -                | -                | -         |    -9.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2561 | 2024-04-27 | Permitta          | L   | 0.526      | -            | -                | -                | -         |    -6.84 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2579 | 2024-04-26 | Insilio           | L   | 0.520      | -            | -                | -                | -         |    -7.75 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2653 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.500      | -            | -                | -                | -         |    -7.23 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2718 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.479      | -            | -                | -                | -         |    -6.64 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2803 | 2024-04-18 | MOUZ NXT          | L   | 0.468      | -            | -                | -                | -         |    -4.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2815 | 2024-04-18 | Nexus             | W   | 0.466      | -            | -                | -                | -         |     6.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2841 | 2024-04-17 | ENCE              | L   | 0.460      | -            | -                | -                | -         |    -0.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2973 | 2024-04-11 | Sashi             | L   | 0.419      | -            | -                | -                | -         |    -3.17 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3017 | 2024-04-10 | AMKAL             | W   | 0.413      | 0.384        | 0.130 (0.021)    | -                | -         |    10.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3147 | 2024-04-06 | Sampi             | L   | 0.386      | -            | -                | -                | -         |    -6.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3236 | 2024-04-03 | Permitta          | W   | 0.368      | 0.384        | -                | 0.919 (0.130)    | -         |     6.64 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3296 | 2024-04-01 | BLEED             | W   | 0.354      | 0.384        | 0.090 (0.012)    | -                | -         |     6.62 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3735 | 2024-03-09 | kONO              | L   | 0.201      | -            | -                | -                | -         |    -4.06 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3747 | 2024-03-09 | Sampi             | L   | 0.200      | -            | -                | -                | -         |    -3.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3815 | 2024-03-06 | INGLORIOUS        | L   | 0.181      | -            | -                | -                | -         |    -5.13 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3821 | 2024-03-06 | Permitta          | L   | 0.180      | -            | -                | -                | -         |    -2.51 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3932 | 2024-03-02 | Sampi             | W   | 0.153      | -            | -                | -                | -         |     2.17 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4243 | 2024-02-16 | SAW               | L   | 0.055      | -            | -                | -                | -         |    -0.36 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4280 | 2024-02-15 | BetBoom           | L   | 0.047      | -            | -                | -                | -         |    -0.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4307 | 2024-02-14 | Natus Vincere     | L   | 0.043      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4319 | 2024-02-14 | AMKAL             | W   | 0.041      | -            | -                | -                | 1 (0.041) |     1.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,578.61)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.867 | $5,000.00      | $4,333.33       |
| 2024-06-13 |      0.842 | $5,447.00      | $4,587.08       |
| 2024-06-06 |      0.792 | $3,000.00      | $2,377.50       |
| 2024-05-02 |      0.561 | $500.00        | $280.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
