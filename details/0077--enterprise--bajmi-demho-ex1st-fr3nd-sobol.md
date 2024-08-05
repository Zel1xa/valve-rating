### Roster Details<br />
Team Name: Enterprise<br />
Roster: bajmi, Demho, ex1st, fr3nd, Sobol<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
<br />
Final Rank Value:  944.6<br />
<br />
Final Rank Value (944.6) = Starting Rank Value (917.6) + Head To Head Adjustments (27.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.005[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 917.6
- 400 + ( ( 0.252 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 917.6


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
|           61 |      252 | 2024-07-30 | Rhyno             | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |    17.95 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           60 |      477 | 2024-07-23 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -11.88 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           59 |      492 | 2024-07-22 | DASH              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.42 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           58 |      499 | 2024-07-22 | Illuminar         | W   | 1.000      | 0.371        | -                | 0.347 (0.129)    | 0 (0.000) |    15.84 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           57 |      522 | 2024-07-21 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -14.74 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           56 |      591 | 2024-07-19 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    17.64 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           55 |      719 | 2024-07-17 | FORZE Reload      | L   | 1.000      | -            | -                | -                | -         |   -28.10 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           54 |      818 | 2024-07-15 | TNL               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.21 | bajmi, Demho, ex1st, fr3nd, hotd0g  |
|           53 |      856 | 2024-07-12 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -12.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           52 |      937 | 2024-07-08 | Revenant          | W   | 1.000      | 0.371        | 0.027 (0.010)    | -                | 0 (0.000) |    11.06 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           51 |     1033 | 2024-06-16 | 3DMAX             | L   | 0.865      | -            | -                | -                | -         |    -1.49 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           50 |     1121 | 2024-06-13 | PERA              | L   | 0.847      | -            | -                | -                | -         |   -12.13 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           49 |     1138 | 2024-06-13 | Illuminar         | W   | 0.845      | 0.450        | -                | 0.347 (0.132)    | 0 (0.000) |    11.53 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           48 |     1161 | 2024-06-12 | Sampi             | W   | 0.839      | 0.379        | 0.027 (0.009)    | 1.000 (0.318)    | 0 (0.000) |    11.05 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           47 |     1202 | 2024-06-10 | SINNERS           | W   | 0.826      | 0.379        | 0.037 (0.012)    | 0.809 (0.253)    | 0 (0.000) |    16.62 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           46 |     1218 | 2024-06-10 | Gaimin Gladiators | W   | 0.825      | 0.450        | 0.037 (0.014)    | -                | -         |    15.41 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           45 |     1257 | 2024-06-09 | ECLOT             | L   | 0.819      | -            | -                | -                | -         |    -5.03 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           44 |     1300 | 2024-06-08 | Nexus             | W   | 0.814      | 0.450        | -                | 0.458 (0.168)    | -         |     7.99 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           43 |     1384 | 2024-06-07 | Entropiq          | W   | 0.805      | -            | -                | -                | -         |     1.45 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           42 |     1438 | 2024-06-06 | Illuminar         | L   | 0.800      | -            | -                | -                | -         |   -15.66 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           41 |     1483 | 2024-06-05 | Verdant           | L   | 0.794      | -            | -                | -                | -         |   -13.38 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           40 |     1500 | 2024-06-05 | Serbia            | L   | 0.792      | -            | -                | -                | -         |   -16.76 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           39 |     1557 | 2024-06-04 | Johnny Speeds     | W   | 0.784      | 0.371        | 0.122 (0.035)    | 1.000 (0.291)    | -         |    21.16 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           38 |     1579 | 2024-06-03 | UNiTY             | W   | 0.777      | -            | -                | -                | -         |    13.93 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           37 |     1621 | 2024-06-01 | ARCRED            | L   | 0.766      | -            | -                | -                | -         |   -11.71 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           36 |     1636 | 2024-06-01 | Permitta          | W   | 0.764      | 0.371        | -                | 0.863 (0.244)    | -         |    11.83 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           35 |     1674 | 2024-05-30 | RUSTEC            | W   | 0.754      | -            | -                | -                | -         |     1.30 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           34 |     1690 | 2024-05-30 | brazylijski luz   | L   | 0.751      | -            | -                | -                | -         |   -14.34 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           33 |     1703 | 2024-05-29 | FLuffy Gangsters  | W   | 0.747      | -            | -                | -                | -         |     2.85 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           32 |     1729 | 2024-05-28 | Sampi             | W   | 0.739      | 0.379        | -                | 1.000 (0.280)    | -         |    11.69 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           31 |     1810 | 2024-05-24 | Illuminar         | W   | 0.712      | -            | -                | -                | -         |     9.93 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           30 |     1860 | 2024-05-22 | Entropiq          | W   | 0.699      | -            | -                | -                | -         |     1.28 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           29 |     1946 | 2024-05-20 | ECSTATIC          | W   | 0.685      | -            | -                | -                | -         |     2.76 | bajmi, Demho, ex1st, fr3nd, Sobol   |
|           28 |     2274 | 2024-05-10 | BetBoom           | L   | 0.619      | -            | -                | -                | -         |    -1.20 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           27 |     2341 | 2024-05-07 | Permitta          | W   | 0.598      | 0.435        | -                | 0.863 (0.224)    | -         |    10.32 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           26 |     2355 | 2024-05-06 | B8                | L   | 0.592      | -            | -                | -                | -         |    -5.42 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           25 |     2383 | 2024-05-04 | MOUZ NXT          | W   | 0.580      | 0.435        | 0.139 (0.035)    | 0.987 (0.249)    | -         |    12.86 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           24 |     2444 | 2024-05-01 | ENCE Academy      | W   | 0.560      | -            | -                | -                | -         |     5.36 | bajmi, Demho, ex1st, fr3nd, kadziu  |
|           23 |     2472 | 2024-04-30 | EYEBALLERS        | L   | 0.553      | -            | -                | -                | -         |    -8.48 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           22 |     2508 | 2024-04-29 | Nexus             | L   | 0.544      | -            | -                | -                | -         |    -9.91 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           21 |     2550 | 2024-04-27 | Permitta          | L   | 0.531      | -            | -                | -                | -         |    -7.08 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           20 |     2568 | 2024-04-26 | Insilio           | L   | 0.525      | -            | -                | -                | -         |    -7.83 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           19 |     2642 | 2024-04-23 | ALTERNATE aTTaX   | L   | 0.505      | -            | -                | -                | -         |    -7.31 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           18 |     2707 | 2024-04-20 | ALTERNATE aTTaX   | L   | 0.484      | -            | -                | -                | -         |    -6.71 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           17 |     2792 | 2024-04-18 | MOUZ NXT          | L   | 0.473      | -            | -                | -                | -         |    -4.87 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           16 |     2804 | 2024-04-18 | Nexus             | W   | 0.471      | -            | -                | -                | -         |     6.19 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           15 |     2830 | 2024-04-17 | ENCE              | L   | 0.465      | -            | -                | -                | -         |    -0.77 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           14 |     2962 | 2024-04-11 | Sashi             | L   | 0.424      | -            | -                | -                | -         |    -3.20 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           13 |     3006 | 2024-04-10 | AMKAL             | W   | 0.418      | 0.384        | 0.130 (0.021)    | -                | -         |    10.12 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           12 |     3136 | 2024-04-06 | Sampi             | L   | 0.391      | -            | -                | -                | -         |    -6.26 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           11 |     3225 | 2024-04-03 | Permitta          | W   | 0.373      | -            | -                | -                | -         |     6.54 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|           10 |     3285 | 2024-04-01 | BLEED             | W   | 0.359      | 0.384        | 0.090 (0.012)    | -                | -         |     6.74 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            9 |     3724 | 2024-03-09 | kONO              | L   | 0.206      | -            | -                | -                | -         |    -4.18 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            8 |     3736 | 2024-03-09 | Sampi             | L   | 0.205      | -            | -                | -                | -         |    -3.50 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            7 |     3804 | 2024-03-06 | INGLORIOUS        | L   | 0.186      | -            | -                | -                | -         |    -5.26 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            6 |     3810 | 2024-03-06 | Permitta          | L   | 0.185      | -            | -                | -                | -         |    -2.69 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            5 |     3921 | 2024-03-02 | Sampi             | W   | 0.158      | -            | -                | -                | -         |     2.25 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            4 |     4232 | 2024-02-16 | SAW               | L   | 0.060      | -            | -                | -                | -         |    -0.39 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            3 |     4269 | 2024-02-15 | BetBoom           | L   | 0.052      | -            | -                | -                | -         |    -0.09 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            2 |     4296 | 2024-02-14 | Natus Vincere     | L   | 0.048      | -            | -                | -                | -         |    -0.00 | bajmi, Demho, ex1st, fr3nd, TOAO    |
|            1 |     4308 | 2024-02-14 | AMKAL             | W   | 0.046      | -            | -                | -                | 1 (0.046) |     1.12 | bajmi, Demho, ex1st, fr3nd, TOAO    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,648.34)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-17 |      0.872 | $5,000.00      | $4,358.33       |
| 2024-06-13 |      0.847 | $5,447.00      | $4,614.32       |
| 2024-06-06 |      0.797 | $3,000.00      | $2,392.50       |
| 2024-05-02 |      0.566 | $500.00        | $283.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
