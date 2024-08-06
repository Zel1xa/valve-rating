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
Final Rank Value (958.5) = Starting Rank Value (919.1) + Head To Head Adjustments (39.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.1
- 400 + ( ( 0.252 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 919.1


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
|           62 |        9 | 2024-08-06 | Verdant           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.17 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           61 |      273 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.00 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      498 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      513 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      520 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      543 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.73 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      612 | 2024-07-19 | UNiTY             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.55 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      740 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.13 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      839 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.18 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      877 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      958 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    10.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1054 | 2024-06-16 | 3DMAX             | L   | 0.859      | -            | -                | -                | -         |    -1.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1142 | 2024-06-13 | PERA              | L   | 0.841      | -            | -                | -                | -         |   -12.16 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1159 | 2024-06-13 | Illuminar         | W   | 0.839      | 0.450        | -                | 0.340 (0.128)    | 0 (0.000) |    11.50 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1182 | 2024-06-12 | Sampi             | W   | 0.833      | 0.379        | -                | 1.000 (0.316)    | 0 (0.000) |    11.07 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1223 | 2024-06-10 | SINNERS           | W   | 0.820      | 0.379        | 0.037 (0.012)    | 0.800 (0.248)    | -         |    16.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1239 | 2024-06-10 | Gaimin Gladiators | W   | 0.819      | 0.450        | 0.037 (0.014)    | -                | -         |    15.16 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1278 | 2024-06-09 | ECLOT             | L   | 0.813      | -            | -                | -                | -         |    -5.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1321 | 2024-06-08 | Nexus             | W   | 0.808      | 0.450        | -                | 0.447 (0.162)    | -         |     7.97 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1405 | 2024-06-07 | Entropiq          | W   | 0.799      | -            | -                | -                | -         |     1.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1459 | 2024-06-06 | Illuminar         | L   | 0.793      | -            | -                | -                | -         |   -15.48 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1504 | 2024-06-05 | Verdant           | L   | 0.788      | -            | -                | -                | -         |   -13.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1521 | 2024-06-05 | Serbia            | L   | 0.786      | -            | -                | -                | -         |   -16.61 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1578 | 2024-06-04 | Johnny Speeds     | W   | 0.778      | 0.371        | 0.122 (0.035)    | 1.000 (0.288)    | -         |    21.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1600 | 2024-06-03 | UNiTY             | W   | 0.771      | -            | -                | -                | -         |    13.72 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1642 | 2024-06-01 | ARCRED            | L   | 0.760      | -            | -                | -                | -         |   -11.68 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1657 | 2024-06-01 | Permitta          | W   | 0.758      | 0.371        | 0.039 (0.011)    | 0.919 (0.258)    | -         |    12.19 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1695 | 2024-05-30 | RUSTEC            | W   | 0.748      | -            | -                | -                | -         |     1.27 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1711 | 2024-05-30 | brazylijski luz   | L   | 0.745      | -            | -                | -                | -         |   -14.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1724 | 2024-05-29 | FLuffy Gangsters  | W   | 0.741      | -            | -                | -                | -         |     2.80 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1750 | 2024-05-28 | Sampi             | W   | 0.733      | 0.379        | -                | 1.000 (0.278)    | -         |    11.56 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1831 | 2024-05-24 | Illuminar         | W   | 0.706      | -            | -                | -                | -         |     9.88 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1881 | 2024-05-22 | Entropiq          | W   | 0.693      | -            | -                | -                | -         |     1.25 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1967 | 2024-05-20 | ECSTATIC          | W   | 0.679      | -            | -                | -                | -         |     2.70 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2295 | 2024-05-10 | BetBoom           | L   | 0.613      | -            | -                | -                | -         |    -1.22 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2362 | 2024-05-07 | Permitta          | W   | 0.592      | 0.435        | 0.039 (0.010)    | 0.919 (0.236)    | -         |    10.61 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2376 | 2024-05-06 | B8                | L   | 0.586      | -            | -                | -                | -         |    -5.37 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2404 | 2024-05-04 | MOUZ NXT          | W   | 0.574      | 0.435        | 0.139 (0.035)    | 0.962 (0.240)    | -         |    12.68 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2465 | 2024-05-01 | ENCE Academy      | W   | 0.554      | -            | -                | -                | -         |     5.25 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2493 | 2024-04-30 | EYEBALLERS        | L   | 0.547      | -            | -                | -                | -         |    -8.40 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2529 | 2024-04-29 | Nexus             | L   | 0.538      | -            | -                | -                | -         |    -9.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2571 | 2024-04-27 | Permitta          | L   | 0.525      | -            | -                | -                | -         |    -6.58 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2589 | 2024-04-26 | Insilio           | L   | 0.519      | -            | -                | -                | -         |    -7.71 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2663 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.498      | -            | -                | -                | -         |    -7.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2728 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.478      | -            | -                | -                | -         |    -6.62 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2813 | 2024-04-18 | MOUZ NXT          | L   | 0.467      | -            | -                | -                | -         |    -4.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2825 | 2024-04-18 | Nexus             | W   | 0.465      | -            | -                | -                | -         |     6.13 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2851 | 2024-04-17 | ENCE              | L   | 0.459      | -            | -                | -                | -         |    -0.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2983 | 2024-04-11 | Sashi             | L   | 0.418      | -            | -                | -                | -         |    -3.16 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3027 | 2024-04-10 | AMKAL             | W   | 0.412      | 0.384        | 0.130 (0.021)    | -                | -         |     9.97 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3157 | 2024-04-06 | Sampi             | L   | 0.385      | -            | -                | -                | -         |    -6.19 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3246 | 2024-04-03 | Permitta          | W   | 0.367      | 0.384        | -                | 0.919 (0.130)    | -         |     6.88 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3306 | 2024-04-01 | BLEED             | W   | 0.353      | 0.384        | 0.089 (0.012)    | -                | -         |     6.58 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3745 | 2024-03-09 | kONO              | L   | 0.200      | -            | -                | -                | -         |    -4.04 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3757 | 2024-03-09 | Sampi             | L   | 0.199      | -            | -                | -                | -         |    -3.40 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3825 | 2024-03-06 | INGLORIOUS        | L   | 0.180      | -            | -                | -                | -         |    -5.10 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3831 | 2024-03-06 | Permitta          | L   | 0.179      | -            | -                | -                | -         |    -2.35 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3942 | 2024-03-02 | Sampi             | W   | 0.152      | -            | -                | -                | -         |     2.16 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4253 | 2024-02-16 | SAW               | L   | 0.054      | -            | -                | -                | -         |    -0.35 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4290 | 2024-02-15 | BetBoom           | L   | 0.046      | -            | -                | -                | -         |    -0.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4317 | 2024-02-14 | Natus Vincere     | L   | 0.041      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4329 | 2024-02-14 | AMKAL             | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.97 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,563.11)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.866 | $5,000.00      | $4,327.78       |
| 2024-06-13 |      0.841 | $5,447.00      | $4,581.03       |
| 2024-06-06 |      0.791 | $3,000.00      | $2,374.17       |
| 2024-05-02 |      0.560 | $500.00        | $280.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
