### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  942.7<br />
<br />
Final Rank Value (942.7) = Starting Rank Value (916.8) + Head To Head Adjustments (26.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 916.8
- 400 + ( ( 0.252 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 916.8


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
|           61 |      243 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.04 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      469 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.80 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      484 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      491 | 2024-07-22 | Illuminar         | W   | 1.000      | 0.371        | -                | 0.352 (0.130)    | 0 (0.000) |    15.87 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      514 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.67 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      583 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.68 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      711 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.06 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      810 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.23 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      848 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      929 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.12 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1025 | 2024-06-16 | 3DMAX             | L   | 0.866      | -            | -                | -                | -         |    -1.48 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1113 | 2024-06-13 | PERA              | L   | 0.848      | -            | -                | -                | -         |   -12.05 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1130 | 2024-06-13 | Illuminar         | W   | 0.846      | 0.450        | -                | 0.352 (0.134)    | 0 (0.000) |    11.58 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1153 | 2024-06-12 | Sampi             | W   | 0.841      | 0.379        | 0.027 (0.009)    | 1.000 (0.318)    | 0 (0.000) |    11.12 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1194 | 2024-06-10 | SINNERS           | W   | 0.827      | 0.379        | 0.037 (0.012)    | 0.794 (0.249)    | 0 (0.000) |    16.64 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1210 | 2024-06-10 | Gaimin Gladiators | W   | 0.826      | 0.450        | 0.037 (0.014)    | -                | -         |    15.53 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1249 | 2024-06-09 | ECLOT             | L   | 0.820      | -            | -                | -                | -         |    -4.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1292 | 2024-06-08 | Nexus             | W   | 0.815      | 0.450        | -                | 0.464 (0.170)    | -         |     8.08 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1376 | 2024-06-07 | Entropiq          | W   | 0.806      | -            | -                | -                | -         |     1.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1430 | 2024-06-06 | Illuminar         | L   | 0.801      | -            | -                | -                | -         |   -15.65 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1475 | 2024-06-05 | Verdant           | L   | 0.795      | -            | -                | -                | -         |   -13.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1492 | 2024-06-05 | Serbia            | L   | 0.794      | -            | -                | -                | -         |   -16.69 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1549 | 2024-06-04 | Johnny Speeds     | W   | 0.785      | 0.371        | 0.122 (0.036)    | 0.940 (0.274)    | -         |    21.24 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1571 | 2024-06-03 | UNiTY             | W   | 0.779      | -            | -                | -                | -         |    14.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1613 | 2024-06-01 | ARCRED            | L   | 0.767      | -            | -                | -                | -         |   -13.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1628 | 2024-06-01 | Permitta          | W   | 0.765      | 0.371        | -                | 0.873 (0.248)    | -         |    11.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1666 | 2024-05-30 | RUSTEC            | W   | 0.755      | -            | -                | -                | -         |     1.32 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1682 | 2024-05-30 | brazylijski luz   | L   | 0.752      | -            | -                | -                | -         |   -14.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1695 | 2024-05-29 | FLuffy Gangsters  | W   | 0.748      | -            | -                | -                | -         |     2.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1721 | 2024-05-28 | Sampi             | W   | 0.741      | 0.379        | -                | 1.000 (0.280)    | -         |    11.78 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1802 | 2024-05-24 | Illuminar         | W   | 0.713      | -            | -                | -                | -         |     9.99 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1852 | 2024-05-22 | Entropiq          | W   | 0.701      | -            | -                | -                | -         |     1.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1938 | 2024-05-20 | ECSTATIC          | W   | 0.686      | -            | -                | -                | -         |     1.28 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2266 | 2024-05-10 | BetBoom           | L   | 0.620      | -            | -                | -                | -         |    -1.19 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2333 | 2024-05-07 | Permitta          | W   | 0.599      | 0.435        | -                | 0.873 (0.227)    | -         |    10.32 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2347 | 2024-05-06 | B8                | L   | 0.593      | -            | -                | -                | -         |    -5.43 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2375 | 2024-05-04 | MOUZ NXT          | W   | 0.581      | 0.435        | 0.139 (0.035)    | 1.000 (0.253)    | -         |    12.88 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2436 | 2024-05-01 | ENCE Academy      | W   | 0.561      | -            | -                | -                | -         |     5.38 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2464 | 2024-04-30 | EYEBALLERS        | L   | 0.554      | -            | -                | -                | -         |    -8.49 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2500 | 2024-04-29 | Nexus             | L   | 0.545      | -            | -                | -                | -         |    -9.92 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2542 | 2024-04-27 | Permitta          | L   | 0.532      | -            | -                | -                | -         |    -7.11 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2560 | 2024-04-26 | Insilio           | L   | 0.527      | -            | -                | -                | -         |    -7.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2634 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.506      | -            | -                | -                | -         |    -7.33 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2699 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.486      | -            | -                | -                | -         |    -6.73 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2784 | 2024-04-18 | MOUZ NXT          | L   | 0.474      | -            | -                | -                | -         |    -4.88 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2796 | 2024-04-18 | Nexus             | W   | 0.472      | -            | -                | -                | -         |     6.22 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2822 | 2024-04-17 | ENCE              | L   | 0.467      | -            | -                | -                | -         |    -0.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2954 | 2024-04-11 | Sashi             | L   | 0.426      | -            | -                | -                | -         |    -3.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2998 | 2024-04-10 | AMKAL             | W   | 0.419      | 0.384        | 0.130 (0.021)    | -                | -         |    10.16 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3128 | 2024-04-06 | Sampi             | L   | 0.393      | -            | -                | -                | -         |    -6.25 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3217 | 2024-04-03 | Permitta          | W   | 0.374      | -            | -                | -                | -         |     6.56 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3277 | 2024-04-01 | BLEED             | W   | 0.360      | 0.384        | 0.090 (0.013)    | -                | -         |     6.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3716 | 2024-03-09 | kONO              | L   | 0.207      | -            | -                | -                | -         |    -4.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3728 | 2024-03-09 | Sampi             | L   | 0.206      | -            | -                | -                | -         |    -3.51 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3796 | 2024-03-06 | INGLORIOUS        | L   | 0.188      | -            | -                | -                | -         |    -5.29 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3802 | 2024-03-06 | Permitta          | L   | 0.186      | -            | -                | -                | -         |    -2.70 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3913 | 2024-03-02 | Sampi             | W   | 0.159      | -            | -                | -                | -         |     2.27 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4224 | 2024-02-16 | SAW               | L   | 0.061      | -            | -                | -                | -         |    -0.39 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4261 | 2024-02-15 | BetBoom           | L   | 0.053      | -            | -                | -                | -         |    -0.10 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4288 | 2024-02-14 | Natus Vincere     | L   | 0.049      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4300 | 2024-02-14 | AMKAL             | W   | 0.047      | -            | -                | -                | 1 (0.047) |     1.15 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,663.84)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.873 | $5,000.00      | $4,363.89       |
| 2024-06-13 |      0.848 | $5,447.00      | $4,620.37       |
| 2024-06-06 |      0.799 | $3,000.00      | $2,395.83       |
| 2024-05-02 |      0.568 | $500.00        | $283.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
