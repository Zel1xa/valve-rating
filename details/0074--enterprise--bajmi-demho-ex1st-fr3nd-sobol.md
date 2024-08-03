### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.4<br />
<br />
Final Rank Value (942.4) = Starting Rank Value (919.9) + Head To Head Adjustments (22.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.232[<sup>2</sup>](#table1)
- LAN Wins: 0.007[<sup>2</sup>](#table1)

The average of these factors is 0.254<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 919.9
- 400 + ( ( 0.254 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 919.9


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
|           61 |      168 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.05 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      394 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.58 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      409 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      416 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.91 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      439 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.64 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      508 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.17 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      633 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.06 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      730 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.23 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      767 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.94 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      846 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    10.77 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |      935 | 2024-06-16 | 3DMAX             | L   | 0.878      | -            | -                | -                | -         |    -1.60 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1010 | 2024-06-13 | PERA              | L   | 0.861      | -            | -                | -                | -         |   -12.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1027 | 2024-06-13 | Illuminar         | W   | 0.859      | 0.450        | -                | 0.363 (0.140)    | 0 (0.000) |    11.74 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1049 | 2024-06-12 | Sampi             | W   | 0.853      | 0.379        | 0.028 (0.009)    | 1.000 (0.323)    | 0 (0.000) |    11.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1087 | 2024-06-10 | SINNERS           | W   | 0.839      | 0.379        | 0.037 (0.012)    | 0.784 (0.249)    | 0 (0.000) |    16.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1103 | 2024-06-10 | Gaimin Gladiators | W   | 0.838      | 0.450        | 0.038 (0.014)    | 0.366 (0.138)    | -         |    15.77 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1141 | 2024-06-09 | ECLOT             | L   | 0.832      | -            | -                | -                | -         |    -5.12 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1182 | 2024-06-08 | Nexus             | W   | 0.827      | 0.450        | -                | 0.441 (0.164)    | -         |     8.18 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1263 | 2024-06-07 | Entropiq          | W   | 0.819      | -            | -                | -                | -         |     1.49 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1317 | 2024-06-06 | Illuminar         | L   | 0.813      | -            | -                | -                | -         |   -15.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1363 | 2024-06-05 | Verdant           | L   | 0.807      | -            | -                | -                | -         |   -13.57 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1379 | 2024-06-05 | Serbia            | L   | 0.806      | -            | -                | -                | -         |   -16.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1435 | 2024-06-04 | Johnny Speeds     | W   | 0.798      | 0.371        | 0.122 (0.036)    | 0.930 (0.275)    | -         |    21.42 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1457 | 2024-06-03 | UNiTY             | W   | 0.791      | -            | -                | -                | -         |    14.06 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1497 | 2024-06-01 | ARCRED            | L   | 0.780      | -            | -                | -                | -         |   -13.18 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1512 | 2024-06-01 | Permitta          | W   | 0.778      | 0.371        | -                | 0.887 (0.255)    | -         |    11.97 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1550 | 2024-05-30 | RUSTEC            | W   | 0.767      | -            | -                | -                | -         |     1.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1566 | 2024-05-30 | brazylijski luz   | L   | 0.764      | -            | -                | -                | -         |   -14.56 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1579 | 2024-05-29 | FLuffy Gangsters  | W   | 0.760      | -            | -                | -                | -         |     2.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1605 | 2024-05-28 | Sampi             | W   | 0.753      | 0.379        | -                | 1.000 (0.285)    | -         |    11.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1685 | 2024-05-24 | Illuminar         | W   | 0.725      | -            | -                | -                | -         |    10.13 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1735 | 2024-05-22 | Entropiq          | W   | 0.713      | -            | -                | -                | -         |     1.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1821 | 2024-05-20 | ECSTATIC          | W   | 0.698      | -            | -                | -                | -         |     1.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2148 | 2024-05-10 | BetBoom           | L   | 0.632      | -            | -                | -                | -         |    -1.22 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2214 | 2024-05-07 | Permitta          | W   | 0.611      | 0.435        | -                | 0.887 (0.236)    | -         |    10.48 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2228 | 2024-05-06 | B8                | L   | 0.606      | -            | -                | -                | -         |    -5.58 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2256 | 2024-05-04 | MOUZ NXT          | W   | 0.594      | 0.435        | 0.139 (0.036)    | 1.000 (0.258)    | -         |    12.98 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2317 | 2024-05-01 | ENCE Academy      | W   | 0.574      | -            | -                | -                | -         |     5.24 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2345 | 2024-04-30 | EYEBALLERS        | L   | 0.566      | -            | -                | -                | -         |    -8.69 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2381 | 2024-04-29 | Nexus             | L   | 0.558      | -            | -                | -                | -         |   -10.11 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2423 | 2024-04-27 | Permitta          | L   | 0.545      | -            | -                | -                | -         |    -7.33 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2440 | 2024-04-26 | Insilio           | L   | 0.539      | -            | -                | -                | -         |    -8.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2514 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.518      | -            | -                | -                | -         |    -7.57 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2579 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.498      | -            | -                | -                | -         |    -6.95 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2664 | 2024-04-18 | MOUZ NXT          | L   | 0.486      | -            | -                | -                | -         |    -5.21 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2676 | 2024-04-18 | Nexus             | W   | 0.485      | -            | -                | -                | -         |     6.38 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2702 | 2024-04-17 | ENCE              | L   | 0.479      | -            | -                | -                | -         |    -0.86 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2834 | 2024-04-11 | Sashi             | L   | 0.438      | -            | -                | -                | -         |    -3.26 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2878 | 2024-04-10 | AMKAL             | W   | 0.431      | 0.384        | 0.130 (0.022)    | -                | -         |    10.46 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3008 | 2024-04-06 | Sampi             | L   | 0.405      | -            | -                | -                | -         |    -6.43 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3097 | 2024-04-03 | Permitta          | W   | 0.386      | -            | -                | -                | -         |     6.74 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3157 | 2024-04-01 | BLEED             | W   | 0.372      | 0.384        | 0.092 (0.013)    | -                | -         |     7.04 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3588 | 2024-03-09 | kONO              | L   | 0.219      | -            | -                | -                | -         |    -4.48 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3600 | 2024-03-09 | Sampi             | L   | 0.219      | -            | -                | -                | -         |    -3.71 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3668 | 2024-03-06 | INGLORIOUS        | L   | 0.200      | -            | -                | -                | -         |    -5.65 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3674 | 2024-03-06 | Permitta          | L   | 0.199      | -            | -                | -                | -         |    -2.91 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3785 | 2024-03-02 | Sampi             | W   | 0.171      | -            | -                | -                | -         |     2.45 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4095 | 2024-02-16 | SAW               | L   | 0.073      | -            | -                | -                | -         |    -0.47 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4132 | 2024-02-15 | BetBoom           | L   | 0.065      | -            | -                | -                | -         |    -0.12 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4159 | 2024-02-14 | Natus Vincere     | L   | 0.061      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4171 | 2024-02-14 | AMKAL             | W   | 0.059      | -            | -                | -                | 1 (0.059) |     1.46 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,834.95)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.885 | $5,000.00      | $4,425.23       |
| 2024-06-13 |      0.861 | $5,447.00      | $4,687.19       |
| 2024-06-06 |      0.811 | $3,000.00      | $2,432.64       |
| 2024-05-02 |      0.580 | $500.00        | $289.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
