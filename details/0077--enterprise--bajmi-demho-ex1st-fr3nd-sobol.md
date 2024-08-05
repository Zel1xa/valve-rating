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
Final Rank Value (942.7) = Starting Rank Value (917.4) + Head To Head Adjustments (25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.230[<sup>2</sup>](#table1)
- LAN Wins: 0.006[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.4
- 400 + ( ( 0.253 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 917.4


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
|           61 |      231 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      456 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.79 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      471 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      478 | 2024-07-22 | Illuminar         | W   | 1.000      | 0.371        | -                | 0.352 (0.130)    | 0 (0.000) |    15.86 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      501 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.70 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      570 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.68 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      698 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.06 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      797 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.23 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      835 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      916 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.09 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1012 | 2024-06-16 | 3DMAX             | L   | 0.869      | -            | -                | -                | -         |    -1.50 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1100 | 2024-06-13 | PERA              | L   | 0.852      | -            | -                | -                | -         |   -12.10 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1117 | 2024-06-13 | Illuminar         | W   | 0.850      | 0.450        | -                | 0.352 (0.135)    | 0 (0.000) |    11.60 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1140 | 2024-06-12 | Sampi             | W   | 0.844      | 0.379        | 0.027 (0.009)    | 1.000 (0.320)    | 0 (0.000) |    11.05 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1181 | 2024-06-10 | SINNERS           | W   | 0.831      | 0.379        | 0.037 (0.012)    | 0.797 (0.251)    | 0 (0.000) |    16.61 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1197 | 2024-06-10 | Gaimin Gladiators | W   | 0.829      | 0.450        | 0.038 (0.014)    | -                | -         |    15.62 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1236 | 2024-06-09 | ECLOT             | L   | 0.823      | -            | -                | -                | -         |    -5.02 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1279 | 2024-06-08 | Nexus             | W   | 0.818      | 0.450        | -                | 0.465 (0.171)    | -         |     8.09 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1363 | 2024-06-07 | Entropiq          | W   | 0.810      | -            | -                | -                | -         |     1.48 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1417 | 2024-06-06 | Illuminar         | L   | 0.804      | -            | -                | -                | -         |   -15.75 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1462 | 2024-06-05 | Verdant           | L   | 0.798      | -            | -                | -                | -         |   -13.38 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1479 | 2024-06-05 | Serbia            | L   | 0.797      | -            | -                | -                | -         |   -16.77 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1536 | 2024-06-04 | Johnny Speeds     | W   | 0.789      | 0.371        | 0.122 (0.036)    | 0.942 (0.275)    | -         |    21.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1558 | 2024-06-03 | UNiTY             | W   | 0.782      | -            | -                | -                | -         |    14.06 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1600 | 2024-06-01 | ARCRED            | L   | 0.771      | -            | -                | -                | -         |   -13.08 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1615 | 2024-06-01 | Permitta          | W   | 0.769      | 0.371        | -                | 0.876 (0.249)    | -         |    11.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1653 | 2024-05-30 | RUSTEC            | W   | 0.758      | -            | -                | -                | -         |     1.32 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1669 | 2024-05-30 | brazylijski luz   | L   | 0.755      | -            | -                | -                | -         |   -14.35 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1682 | 2024-05-29 | FLuffy Gangsters  | W   | 0.751      | -            | -                | -                | -         |     2.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1708 | 2024-05-28 | Sampi             | W   | 0.744      | 0.379        | -                | 1.000 (0.282)    | -         |    11.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1789 | 2024-05-24 | Illuminar         | W   | 0.716      | -            | -                | -                | -         |    10.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1839 | 2024-05-22 | Entropiq          | W   | 0.704      | -            | -                | -                | -         |     1.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1925 | 2024-05-20 | ECSTATIC          | W   | 0.689      | -            | -                | -                | -         |     1.28 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2253 | 2024-05-10 | BetBoom           | L   | 0.623      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2320 | 2024-05-07 | Permitta          | W   | 0.603      | 0.435        | -                | 0.876 (0.229)    | -         |    10.37 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2334 | 2024-05-06 | B8                | L   | 0.597      | -            | -                | -                | -         |    -5.47 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2362 | 2024-05-04 | MOUZ NXT          | W   | 0.585      | 0.435        | 0.139 (0.035)    | 1.000 (0.254)    | -         |    12.92 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2423 | 2024-05-01 | ENCE Academy      | W   | 0.565      | -            | -                | -                | -         |     5.40 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2451 | 2024-04-30 | EYEBALLERS        | L   | 0.557      | -            | -                | -                | -         |    -8.54 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2487 | 2024-04-29 | Nexus             | L   | 0.549      | -            | -                | -                | -         |    -9.99 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2529 | 2024-04-27 | Permitta          | L   | 0.536      | -            | -                | -                | -         |    -7.17 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2547 | 2024-04-26 | Insilio           | L   | 0.530      | -            | -                | -                | -         |    -7.89 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2621 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.509      | -            | -                | -                | -         |    -7.39 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2686 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.489      | -            | -                | -                | -         |    -6.79 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2771 | 2024-04-18 | MOUZ NXT          | L   | 0.477      | -            | -                | -                | -         |    -4.96 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2783 | 2024-04-18 | Nexus             | W   | 0.476      | -            | -                | -                | -         |     6.25 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2809 | 2024-04-17 | ENCE              | L   | 0.470      | -            | -                | -                | -         |    -0.79 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2941 | 2024-04-11 | Sashi             | L   | 0.429      | -            | -                | -                | -         |    -3.24 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     2985 | 2024-04-10 | AMKAL             | W   | 0.422      | 0.384        | 0.130 (0.021)    | -                | -         |    10.24 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3115 | 2024-04-06 | Sampi             | L   | 0.396      | -            | -                | -                | -         |    -6.30 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3204 | 2024-04-03 | Permitta          | W   | 0.377      | -            | -                | -                | -         |     6.61 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3264 | 2024-04-01 | BLEED             | W   | 0.363      | 0.384        | 0.091 (0.013)    | -                | -         |     6.85 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3703 | 2024-03-09 | kONO              | L   | 0.211      | -            | -                | -                | -         |    -4.27 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3715 | 2024-03-09 | Sampi             | L   | 0.210      | -            | -                | -                | -         |    -3.57 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3783 | 2024-03-06 | INGLORIOUS        | L   | 0.191      | -            | -                | -                | -         |    -5.38 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3789 | 2024-03-06 | Permitta          | L   | 0.190      | -            | -                | -                | -         |    -2.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3900 | 2024-03-02 | Sampi             | W   | 0.162      | -            | -                | -                | -         |     2.32 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4211 | 2024-02-16 | SAW               | L   | 0.065      | -            | -                | -                | -         |    -0.41 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4248 | 2024-02-15 | BetBoom           | L   | 0.056      | -            | -                | -                | -         |    -0.10 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4275 | 2024-02-14 | Natus Vincere     | L   | 0.052      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4287 | 2024-02-14 | AMKAL             | W   | 0.050      | -            | -                | -                | 1 (0.050) |     1.23 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,710.33)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.876 | $5,000.00      | $4,380.56       |
| 2024-06-13 |      0.852 | $5,447.00      | $4,638.52       |
| 2024-06-06 |      0.802 | $3,000.00      | $2,405.83       |
| 2024-05-02 |      0.571 | $500.00        | $285.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
