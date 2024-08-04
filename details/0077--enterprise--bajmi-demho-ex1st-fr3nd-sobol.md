### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  941.6<br />
<br />
Final Rank Value (941.6) = Starting Rank Value (916.9) + Head To Head Adjustments (24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.006[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 916.9
- 400 + ( ( 0.253 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 916.9


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
|           61 |      202 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.08 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      428 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.78 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      443 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      450 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.87 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      473 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.65 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      542 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.55 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      670 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.05 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      767 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.24 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      807 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.86 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      888 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.11 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |      984 | 2024-06-16 | 3DMAX             | L   | 0.873      | -            | -                | -                | -         |    -1.52 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1072 | 2024-06-13 | PERA              | L   | 0.855      | -            | -                | -                | -         |   -12.10 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1089 | 2024-06-13 | Illuminar         | W   | 0.853      | 0.450        | -                | 0.352 (0.135)    | 0 (0.000) |    11.66 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1112 | 2024-06-12 | Sampi             | W   | 0.847      | 0.379        | 0.027 (0.009)    | 1.000 (0.321)    | 0 (0.000) |    11.07 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1153 | 2024-06-10 | SINNERS           | W   | 0.834      | 0.379        | 0.037 (0.012)    | 0.757 (0.239)    | 0 (0.000) |    16.12 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1169 | 2024-06-10 | Gaimin Gladiators | W   | 0.833      | 0.450        | 0.038 (0.014)    | 0.351 (0.131)    | -         |    15.67 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1208 | 2024-06-09 | ECLOT             | L   | 0.827      | -            | -                | -                | -         |    -5.07 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1251 | 2024-06-08 | Nexus             | W   | 0.822      | 0.450        | -                | 0.465 (0.172)    | -         |     8.15 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1335 | 2024-06-07 | Entropiq          | W   | 0.813      | -            | -                | -                | -         |     1.49 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1389 | 2024-06-06 | Illuminar         | L   | 0.807      | -            | -                | -                | -         |   -15.82 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1434 | 2024-06-05 | Verdant           | L   | 0.802      | -            | -                | -                | -         |   -13.43 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1451 | 2024-06-05 | Serbia            | L   | 0.800      | -            | -                | -                | -         |   -16.82 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1508 | 2024-06-04 | Johnny Speeds     | W   | 0.792      | 0.371        | 0.122 (0.036)    | 0.902 (0.265)    | -         |    21.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1530 | 2024-06-03 | UNiTY             | W   | 0.785      | -            | -                | -                | -         |    13.98 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1572 | 2024-06-01 | ARCRED            | L   | 0.774      | -            | -                | -                | -         |   -13.11 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1587 | 2024-06-01 | Permitta          | W   | 0.772      | 0.371        | -                | 0.876 (0.251)    | -         |    11.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1625 | 2024-05-30 | RUSTEC            | W   | 0.762      | -            | -                | -                | -         |     1.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1641 | 2024-05-30 | brazylijski luz   | L   | 0.759      | -            | -                | -                | -         |   -14.41 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1654 | 2024-05-29 | FLuffy Gangsters  | W   | 0.755      | -            | -                | -                | -         |     2.89 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1680 | 2024-05-28 | Sampi             | W   | 0.747      | 0.379        | -                | 1.000 (0.283)    | -         |    11.87 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1761 | 2024-05-24 | Illuminar         | W   | 0.720      | -            | -                | -                | -         |    10.04 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1811 | 2024-05-22 | Entropiq          | W   | 0.707      | -            | -                | -                | -         |     1.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1897 | 2024-05-20 | ECSTATIC          | W   | 0.693      | -            | -                | -                | -         |     1.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2225 | 2024-05-10 | BetBoom           | L   | 0.627      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2292 | 2024-05-07 | Permitta          | W   | 0.606      | 0.435        | -                | 0.876 (0.231)    | -         |    10.43 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2306 | 2024-05-06 | B8                | L   | 0.600      | -            | -                | -                | -         |    -5.51 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2334 | 2024-05-04 | MOUZ NXT          | W   | 0.588      | 0.435        | 0.139 (0.036)    | 1.000 (0.256)    | -         |    12.98 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2395 | 2024-05-01 | ENCE Academy      | W   | 0.568      | -            | -                | -                | -         |     5.45 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2423 | 2024-04-30 | EYEBALLERS        | L   | 0.561      | -            | -                | -                | -         |    -8.55 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2459 | 2024-04-29 | Nexus             | L   | 0.552      | -            | -                | -                | -         |   -10.03 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2501 | 2024-04-27 | Permitta          | L   | 0.539      | -            | -                | -                | -         |    -7.21 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2519 | 2024-04-26 | Insilio           | L   | 0.533      | -            | -                | -                | -         |    -7.91 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2593 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.512      | -            | -                | -                | -         |    -7.44 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2658 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.492      | -            | -                | -                | -         |    -6.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2743 | 2024-04-18 | MOUZ NXT          | L   | 0.481      | -            | -                | -                | -         |    -4.99 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2755 | 2024-04-18 | Nexus             | W   | 0.479      | -            | -                | -                | -         |     6.29 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2781 | 2024-04-17 | ENCE              | L   | 0.473      | -            | -                | -                | -         |    -0.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2913 | 2024-04-11 | Sashi             | L   | 0.432      | -            | -                | -                | -         |    -3.27 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2957 | 2024-04-10 | AMKAL             | W   | 0.426      | 0.384        | 0.130 (0.021)    | -                | -         |    10.33 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3087 | 2024-04-06 | Sampi             | L   | 0.399      | -            | -                | -                | -         |    -6.35 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3176 | 2024-04-03 | Permitta          | W   | 0.381      | -            | -                | -                | -         |     6.67 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3236 | 2024-04-01 | BLEED             | W   | 0.367      | 0.384        | 0.091 (0.013)    | -                | -         |     6.93 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3675 | 2024-03-09 | kONO              | L   | 0.214      | -            | -                | -                | -         |    -4.34 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3687 | 2024-03-09 | Sampi             | L   | 0.213      | -            | -                | -                | -         |    -3.62 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3755 | 2024-03-06 | INGLORIOUS        | L   | 0.194      | -            | -                | -                | -         |    -5.49 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3761 | 2024-03-06 | Permitta          | L   | 0.193      | -            | -                | -                | -         |    -2.81 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3872 | 2024-03-02 | Sampi             | W   | 0.166      | -            | -                | -                | -         |     2.38 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4183 | 2024-02-16 | SAW               | L   | 0.068      | -            | -                | -                | -         |    -0.43 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4220 | 2024-02-15 | BetBoom           | L   | 0.060      | -            | -                | -                | -         |    -0.11 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4247 | 2024-02-14 | Natus Vincere     | L   | 0.055      | -            | -                | -                | -         |    -0.01 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4259 | 2024-02-14 | AMKAL             | W   | 0.054      | -            | -                | -                | 1 (0.054) |     1.32 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,758.43)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.880 | $5,000.00      | $4,397.80       |
| 2024-06-13 |      0.855 | $5,447.00      | $4,657.31       |
| 2024-06-06 |      0.805 | $3,000.00      | $2,416.18       |
| 2024-05-02 |      0.574 | $500.00        | $287.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
