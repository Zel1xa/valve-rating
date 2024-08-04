### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  941.2<br />
<br />
Final Rank Value (941.2) = Starting Rank Value (917.0) + Head To Head Adjustments (24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.006[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.0
- 400 + ( ( 0.253 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 917.0


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
|           61 |      194 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.08 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      420 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.78 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      435 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.48 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      442 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.86 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      465 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.67 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      534 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.55 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      662 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.04 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      759 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.25 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      799 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.85 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      880 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.12 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |      976 | 2024-06-16 | 3DMAX             | L   | 0.873      | -            | -                | -                | -         |    -1.53 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1064 | 2024-06-13 | PERA              | L   | 0.856      | -            | -                | -                | -         |   -12.17 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1081 | 2024-06-13 | Illuminar         | W   | 0.854      | 0.450        | -                | 0.352 (0.135)    | 0 (0.000) |    11.66 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1104 | 2024-06-12 | Sampi             | W   | 0.848      | 0.379        | 0.027 (0.009)    | 1.000 (0.321)    | 0 (0.000) |    11.05 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1145 | 2024-06-10 | SINNERS           | W   | 0.835      | 0.379        | 0.037 (0.012)    | 0.758 (0.239)    | 0 (0.000) |    16.10 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1161 | 2024-06-10 | Gaimin Gladiators | W   | 0.833      | 0.450        | 0.038 (0.014)    | 0.351 (0.132)    | -         |    15.62 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1200 | 2024-06-09 | ECLOT             | L   | 0.828      | -            | -                | -                | -         |    -5.09 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1243 | 2024-06-08 | Nexus             | W   | 0.822      | 0.450        | -                | 0.465 (0.172)    | -         |     8.15 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1327 | 2024-06-07 | Entropiq          | W   | 0.814      | -            | -                | -                | -         |     1.49 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1381 | 2024-06-06 | Illuminar         | L   | 0.808      | -            | -                | -                | -         |   -15.86 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1426 | 2024-06-05 | Verdant           | L   | 0.802      | -            | -                | -                | -         |   -13.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1443 | 2024-06-05 | Serbia            | L   | 0.801      | -            | -                | -                | -         |   -16.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1500 | 2024-06-04 | Johnny Speeds     | W   | 0.793      | 0.371        | 0.122 (0.036)    | 0.901 (0.265)    | -         |    21.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1522 | 2024-06-03 | UNiTY             | W   | 0.786      | -            | -                | -                | -         |    13.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1564 | 2024-06-01 | ARCRED            | L   | 0.775      | -            | -                | -                | -         |   -13.13 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1579 | 2024-06-01 | Permitta          | W   | 0.773      | 0.371        | -                | 0.876 (0.251)    | -         |    11.93 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1617 | 2024-05-30 | RUSTEC            | W   | 0.762      | -            | -                | -                | -         |     1.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1633 | 2024-05-30 | brazylijski luz   | L   | 0.759      | -            | -                | -                | -         |   -14.46 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1646 | 2024-05-29 | FLuffy Gangsters  | W   | 0.756      | -            | -                | -                | -         |     2.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1672 | 2024-05-28 | Sampi             | W   | 0.748      | 0.379        | -                | 1.000 (0.283)    | -         |    11.86 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1753 | 2024-05-24 | Illuminar         | W   | 0.720      | -            | -                | -                | -         |    10.05 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1803 | 2024-05-22 | Entropiq          | W   | 0.708      | -            | -                | -                | -         |     1.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1889 | 2024-05-20 | ECSTATIC          | W   | 0.693      | -            | -                | -                | -         |     1.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2217 | 2024-05-10 | BetBoom           | L   | 0.627      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2284 | 2024-05-07 | Permitta          | W   | 0.607      | 0.435        | -                | 0.876 (0.231)    | -         |    10.42 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2298 | 2024-05-06 | B8                | L   | 0.601      | -            | -                | -                | -         |    -5.52 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2326 | 2024-05-04 | MOUZ NXT          | W   | 0.589      | 0.435        | 0.139 (0.036)    | 1.000 (0.256)    | -         |    12.98 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2387 | 2024-05-01 | ENCE Academy      | W   | 0.569      | -            | -                | -                | -         |     5.45 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2415 | 2024-04-30 | EYEBALLERS        | L   | 0.562      | -            | -                | -                | -         |    -8.56 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2451 | 2024-04-29 | Nexus             | L   | 0.553      | -            | -                | -                | -         |   -10.04 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2493 | 2024-04-27 | Permitta          | L   | 0.540      | -            | -                | -                | -         |    -7.24 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2511 | 2024-04-26 | Insilio           | L   | 0.534      | -            | -                | -                | -         |    -7.96 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2585 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.513      | -            | -                | -                | -         |    -7.46 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2650 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.493      | -            | -                | -                | -         |    -6.86 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2735 | 2024-04-18 | MOUZ NXT          | L   | 0.481      | -            | -                | -                | -         |    -5.02 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2747 | 2024-04-18 | Nexus             | W   | 0.480      | -            | -                | -                | -         |     6.30 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2773 | 2024-04-17 | ENCE              | L   | 0.474      | -            | -                | -                | -         |    -0.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2905 | 2024-04-11 | Sashi             | L   | 0.433      | -            | -                | -                | -         |    -3.31 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2949 | 2024-04-10 | AMKAL             | W   | 0.427      | 0.384        | 0.130 (0.021)    | -                | -         |    10.35 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3079 | 2024-04-06 | Sampi             | L   | 0.400      | -            | -                | -                | -         |    -6.37 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3168 | 2024-04-03 | Permitta          | W   | 0.382      | -            | -                | -                | -         |     6.68 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3228 | 2024-04-01 | BLEED             | W   | 0.367      | 0.384        | 0.091 (0.013)    | -                | -         |     6.94 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3667 | 2024-03-09 | kONO              | L   | 0.215      | -            | -                | -                | -         |    -4.36 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3679 | 2024-03-09 | Sampi             | L   | 0.214      | -            | -                | -                | -         |    -3.64 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3747 | 2024-03-06 | INGLORIOUS        | L   | 0.195      | -            | -                | -                | -         |    -5.50 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3753 | 2024-03-06 | Permitta          | L   | 0.194      | -            | -                | -                | -         |    -2.82 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3864 | 2024-03-02 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     2.38 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4175 | 2024-02-16 | SAW               | L   | 0.069      | -            | -                | -                | -         |    -0.44 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4212 | 2024-02-15 | BetBoom           | L   | 0.061      | -            | -                | -                | -         |    -0.11 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4239 | 2024-02-14 | Natus Vincere     | L   | 0.056      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4251 | 2024-02-14 | AMKAL             | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.34 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,768.44)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.880 | $5,000.00      | $4,401.39       |
| 2024-06-13 |      0.856 | $5,447.00      | $4,661.22       |
| 2024-06-06 |      0.806 | $3,000.00      | $2,418.33       |
| 2024-05-02 |      0.575 | $500.00        | $287.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
