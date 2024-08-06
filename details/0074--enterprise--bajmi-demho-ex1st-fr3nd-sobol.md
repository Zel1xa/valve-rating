### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  958.6<br />
<br />
Final Rank Value (958.6) = Starting Rank Value (919.0) + Head To Head Adjustments (39.6)<br />

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
|           62 |       12 | 2024-08-06 | Verdant           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.17 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           61 |      276 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    18.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      501 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.90 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      516 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.37 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      523 | 2024-07-22 | Illuminar         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.91 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      546 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.73 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      615 | 2024-07-19 | UNiTY             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.55 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      743 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.13 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      842 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.18 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      880 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      961 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    10.98 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1057 | 2024-06-16 | 3DMAX             | L   | 0.858      | -            | -                | -                | -         |    -1.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1145 | 2024-06-13 | PERA              | L   | 0.841      | -            | -                | -                | -         |   -12.16 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1162 | 2024-06-13 | Illuminar         | W   | 0.839      | 0.450        | -                | 0.340 (0.128)    | 0 (0.000) |    11.51 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1185 | 2024-06-12 | Sampi             | W   | 0.833      | 0.379        | -                | 1.000 (0.316)    | 0 (0.000) |    11.07 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1226 | 2024-06-10 | SINNERS           | W   | 0.820      | 0.379        | 0.037 (0.012)    | 0.800 (0.248)    | -         |    16.47 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1242 | 2024-06-10 | Gaimin Gladiators | W   | 0.818      | 0.450        | 0.037 (0.014)    | -                | -         |    15.15 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1281 | 2024-06-09 | ECLOT             | L   | 0.813      | -            | -                | -                | -         |    -5.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1324 | 2024-06-08 | Nexus             | W   | 0.807      | 0.450        | -                | 0.447 (0.162)    | -         |     7.98 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1408 | 2024-06-07 | Entropiq          | W   | 0.799      | -            | -                | -                | -         |     1.44 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1462 | 2024-06-06 | Illuminar         | L   | 0.793      | -            | -                | -                | -         |   -15.46 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1507 | 2024-06-05 | Verdant           | L   | 0.787      | -            | -                | -                | -         |   -13.31 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1524 | 2024-06-05 | Serbia            | L   | 0.786      | -            | -                | -                | -         |   -16.61 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1581 | 2024-06-04 | Johnny Speeds     | W   | 0.778      | 0.371        | 0.122 (0.035)    | 1.000 (0.288)    | -         |    21.01 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1603 | 2024-06-03 | UNiTY             | W   | 0.771      | -            | -                | -                | -         |    13.71 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1645 | 2024-06-01 | ARCRED            | L   | 0.760      | -            | -                | -                | -         |   -11.65 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1660 | 2024-06-01 | Permitta          | W   | 0.758      | 0.371        | 0.039 (0.011)    | 0.919 (0.258)    | -         |    12.18 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1698 | 2024-05-30 | RUSTEC            | W   | 0.747      | -            | -                | -                | -         |     1.27 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1714 | 2024-05-30 | brazylijski luz   | L   | 0.744      | -            | -                | -                | -         |   -14.33 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1727 | 2024-05-29 | FLuffy Gangsters  | W   | 0.741      | -            | -                | -                | -         |     2.81 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1753 | 2024-05-28 | Sampi             | W   | 0.733      | 0.379        | -                | 1.000 (0.278)    | -         |    11.56 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1834 | 2024-05-24 | Illuminar         | W   | 0.705      | -            | -                | -                | -         |     9.89 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1884 | 2024-05-22 | Entropiq          | W   | 0.693      | -            | -                | -                | -         |     1.25 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1970 | 2024-05-20 | ECSTATIC          | W   | 0.678      | -            | -                | -                | -         |     2.69 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2298 | 2024-05-10 | BetBoom           | L   | 0.612      | -            | -                | -                | -         |    -1.22 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2365 | 2024-05-07 | Permitta          | W   | 0.592      | 0.435        | 0.039 (0.010)    | 0.919 (0.236)    | -         |    10.61 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2379 | 2024-05-06 | B8                | L   | 0.586      | -            | -                | -                | -         |    -5.37 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2407 | 2024-05-04 | MOUZ NXT          | W   | 0.574      | 0.435        | 0.139 (0.035)    | 0.961 (0.240)    | -         |    12.68 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2468 | 2024-05-01 | ENCE Academy      | W   | 0.554      | -            | -                | -                | -         |     5.25 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2496 | 2024-04-30 | EYEBALLERS        | L   | 0.547      | -            | -                | -                | -         |    -8.40 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2532 | 2024-04-29 | Nexus             | L   | 0.538      | -            | -                | -                | -         |    -9.75 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2574 | 2024-04-27 | Permitta          | L   | 0.525      | -            | -                | -                | -         |    -6.57 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2592 | 2024-04-26 | Insilio           | L   | 0.519      | -            | -                | -                | -         |    -7.71 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2666 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.498      | -            | -                | -                | -         |    -7.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2731 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.478      | -            | -                | -                | -         |    -6.61 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2816 | 2024-04-18 | MOUZ NXT          | L   | 0.466      | -            | -                | -                | -         |    -4.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2828 | 2024-04-18 | Nexus             | W   | 0.465      | -            | -                | -                | -         |     6.14 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2854 | 2024-04-17 | ENCE              | L   | 0.459      | -            | -                | -                | -         |    -0.76 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2986 | 2024-04-11 | Sashi             | L   | 0.418      | -            | -                | -                | -         |    -3.15 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3030 | 2024-04-10 | AMKAL             | W   | 0.412      | 0.384        | 0.130 (0.020)    | -                | -         |     9.96 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3160 | 2024-04-06 | Sampi             | L   | 0.385      | -            | -                | -                | -         |    -6.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3249 | 2024-04-03 | Permitta          | W   | 0.367      | 0.384        | -                | 0.919 (0.129)    | -         |     6.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3309 | 2024-04-01 | BLEED             | W   | 0.352      | 0.384        | 0.089 (0.012)    | -                | -         |     6.58 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3748 | 2024-03-09 | kONO              | L   | 0.200      | -            | -                | -                | -         |    -4.03 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3760 | 2024-03-09 | Sampi             | L   | 0.199      | -            | -                | -                | -         |    -3.40 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3828 | 2024-03-06 | INGLORIOUS        | L   | 0.180      | -            | -                | -                | -         |    -5.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3834 | 2024-03-06 | Permitta          | L   | 0.179      | -            | -                | -                | -         |    -2.34 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3945 | 2024-03-02 | Sampi             | W   | 0.151      | -            | -                | -                | -         |     2.16 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4256 | 2024-02-16 | SAW               | L   | 0.054      | -            | -                | -                | -         |    -0.35 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4293 | 2024-02-15 | BetBoom           | L   | 0.046      | -            | -                | -                | -         |    -0.08 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4320 | 2024-02-14 | Natus Vincere     | L   | 0.041      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4332 | 2024-02-14 | AMKAL             | W   | 0.039      | -            | -                | -                | 1 (0.039) |     0.97 | bajmi, Demho, ex1st, fr3nd, TOAO    |

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
