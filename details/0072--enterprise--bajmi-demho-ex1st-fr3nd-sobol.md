### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  957.5<br />
<br />
Final Rank Value (957.5) = Starting Rank Value (918.5) + Head To Head Adjustments (39.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.228[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 918.5
- 400 + ( ( 0.252 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 918.5


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
|           62 |        3 | 2024-08-06 | Verdant           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.20 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           61 |      266 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    17.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      491 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      506 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.39 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      513 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.92 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      536 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.73 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      605 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.024 (0.009)    | -                | 0 (0.000) |    17.58 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      733 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.11 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      832 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.19 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      870 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.00 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      951 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1047 | 2024-06-16 | 3DMAX             | L   | 0.859      | -            | -                | -                | -         |    -1.46 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1135 | 2024-06-13 | PERA              | L   | 0.842      | -            | -                | -                | -         |   -12.13 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1152 | 2024-06-13 | Illuminar         | W   | 0.840      | 0.450        | -                | 0.340 (0.129)    | 0 (0.000) |    11.55 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1175 | 2024-06-12 | Sampi             | W   | 0.834      | 0.379        | 0.027 (0.009)    | 1.000 (0.316)    | 0 (0.000) |    11.09 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1216 | 2024-06-10 | SINNERS           | W   | 0.821      | 0.379        | 0.037 (0.012)    | 0.790 (0.245)    | -         |    16.49 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1232 | 2024-06-10 | Gaimin Gladiators | W   | 0.819      | 0.450        | 0.037 (0.014)    | -                | -         |    15.20 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1271 | 2024-06-09 | ECLOT             | L   | 0.814      | -            | -                | -                | -         |    -5.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1314 | 2024-06-08 | Nexus             | W   | 0.808      | 0.450        | -                | 0.447 (0.163)    | -         |     7.98 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1398 | 2024-06-07 | Entropiq          | W   | 0.800      | -            | -                | -                | -         |     1.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1452 | 2024-06-06 | Illuminar         | L   | 0.794      | -            | -                | -                | -         |   -15.46 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1497 | 2024-06-05 | Verdant           | L   | 0.788      | -            | -                | -                | -         |   -13.29 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1514 | 2024-06-05 | Serbia            | L   | 0.787      | -            | -                | -                | -         |   -16.65 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1571 | 2024-06-04 | Johnny Speeds     | W   | 0.779      | 0.371        | 0.122 (0.035)    | 1.000 (0.289)    | -         |    21.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1593 | 2024-06-03 | UNiTY             | W   | 0.772      | -            | -                | -                | -         |    13.77 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1635 | 2024-06-01 | ARCRED            | L   | 0.761      | -            | -                | -                | -         |   -11.67 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1650 | 2024-06-01 | Permitta          | W   | 0.759      | 0.371        | -                | 0.919 (0.258)    | -         |    12.00 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1688 | 2024-05-30 | RUSTEC            | W   | 0.748      | -            | -                | -                | -         |     1.28 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1704 | 2024-05-30 | brazylijski luz   | L   | 0.745      | -            | -                | -                | -         |   -14.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1717 | 2024-05-29 | FLuffy Gangsters  | W   | 0.742      | -            | -                | -                | -         |     2.82 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1743 | 2024-05-28 | Sampi             | W   | 0.734      | 0.379        | -                | 1.000 (0.278)    | -         |    11.57 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1824 | 2024-05-24 | Illuminar         | W   | 0.706      | -            | -                | -                | -         |     9.93 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1874 | 2024-05-22 | Entropiq          | W   | 0.694      | -            | -                | -                | -         |     1.26 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1960 | 2024-05-20 | ECSTATIC          | W   | 0.679      | -            | -                | -                | -         |     2.72 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2288 | 2024-05-10 | BetBoom           | L   | 0.613      | -            | -                | -                | -         |    -1.21 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2355 | 2024-05-07 | Permitta          | W   | 0.593      | 0.435        | -                | 0.919 (0.237)    | -         |    10.39 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2369 | 2024-05-06 | B8                | L   | 0.587      | -            | -                | -                | -         |    -5.37 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2397 | 2024-05-04 | MOUZ NXT          | W   | 0.575      | 0.435        | 0.139 (0.035)    | 0.962 (0.240)    | -         |    12.71 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2458 | 2024-05-01 | ENCE Academy      | W   | 0.555      | -            | -                | -                | -         |     5.28 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2486 | 2024-04-30 | EYEBALLERS        | L   | 0.548      | -            | -                | -                | -         |    -8.40 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2522 | 2024-04-29 | Nexus             | L   | 0.539      | -            | -                | -                | -         |    -9.78 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2564 | 2024-04-27 | Permitta          | L   | 0.526      | -            | -                | -                | -         |    -6.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2582 | 2024-04-26 | Insilio           | L   | 0.520      | -            | -                | -                | -         |    -7.73 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2656 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.499      | -            | -                | -                | -         |    -7.21 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2721 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.479      | -            | -                | -                | -         |    -6.62 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2806 | 2024-04-18 | MOUZ NXT          | L   | 0.467      | -            | -                | -                | -         |    -4.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2818 | 2024-04-18 | Nexus             | W   | 0.466      | -            | -                | -                | -         |     6.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2844 | 2024-04-17 | ENCE              | L   | 0.460      | -            | -                | -                | -         |    -0.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2976 | 2024-04-11 | Sashi             | L   | 0.419      | -            | -                | -                | -         |    -3.17 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3020 | 2024-04-10 | AMKAL             | W   | 0.413      | 0.384        | 0.130 (0.021)    | -                | -         |     9.99 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3150 | 2024-04-06 | Sampi             | L   | 0.386      | -            | -                | -                | -         |    -6.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3239 | 2024-04-03 | Permitta          | W   | 0.368      | 0.384        | -                | 0.919 (0.130)    | -         |     6.63 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3299 | 2024-04-01 | BLEED             | W   | 0.354      | 0.384        | 0.089 (0.012)    | -                | -         |     6.61 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3738 | 2024-03-09 | kONO              | L   | 0.201      | -            | -                | -                | -         |    -4.05 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3750 | 2024-03-09 | Sampi             | L   | 0.200      | -            | -                | -                | -         |    -3.42 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3818 | 2024-03-06 | INGLORIOUS        | L   | 0.181      | -            | -                | -                | -         |    -5.12 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3824 | 2024-03-06 | Permitta          | L   | 0.180      | -            | -                | -                | -         |    -2.50 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3935 | 2024-03-02 | Sampi             | W   | 0.152      | -            | -                | -                | -         |     2.17 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4246 | 2024-02-16 | SAW               | L   | 0.055      | -            | -                | -                | -         |    -0.36 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4283 | 2024-02-15 | BetBoom           | L   | 0.047      | -            | -                | -                | -         |    -0.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4310 | 2024-02-14 | Natus Vincere     | L   | 0.042      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4322 | 2024-02-14 | AMKAL             | W   | 0.040      | -            | -                | -                | 1 (0.040) |     0.99 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,573.44)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.866 | $5,000.00      | $4,331.48       |
| 2024-06-13 |      0.842 | $5,447.00      | $4,585.06       |
| 2024-06-06 |      0.792 | $3,000.00      | $2,376.39       |
| 2024-05-02 |      0.561 | $500.00        | $280.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
