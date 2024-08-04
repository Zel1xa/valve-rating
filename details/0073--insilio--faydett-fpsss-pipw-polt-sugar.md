### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
<br />
Final Rank Value:  949.0<br />
<br />
Final Rank Value (949.0) = Starting Rank Value (891.6) + Head To Head Adjustments (57.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.6
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 891.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |        3 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       33 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |       62 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |       99 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      142 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      184 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.15 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      249 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      375 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      445 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      510 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    15.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      548 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.15 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      586 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |    10.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      706 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |    -9.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      785 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.876 (0.325)    | 0 (0.000) |    15.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      848 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      870 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      889 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1146 | 2024-06-10 | ARCRED            | W   | 0.835      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    10.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1193 | 2024-06-09 | RUBY              | W   | 0.828      | 0.372        | 0.095 (0.029)    | 0.502 (0.155)    | 0 (0.000) |    10.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1249 | 2024-06-08 | Zero Tenacity     | W   | 0.822      | 0.372        | 0.137 (0.042)    | 1.000 (0.306)    | 0 (0.000) |    17.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1315 | 2024-06-07 | Aurora Young Blud | W   | 0.815      | 0.372        | -                | 0.459 (0.139)    | -         |     9.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1518 | 2024-06-03 | RUBY              | L   | 0.788      | -            | -                | -                | -         |   -12.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1575 | 2024-06-01 | 1WIN              | W   | 0.774      | 0.372        | 0.027 (0.008)    | 0.707 (0.204)    | -         |    14.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1628 | 2024-05-30 | VP.Prodigy        | W   | 0.762      | 0.372        | 0.025 (0.007)    | -                | -         |    11.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2284 | 2024-05-07 | RUBY              | L   | 0.608      | -            | -                | -                | -         |    -9.65 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2303 | 2024-05-06 | Zero Tenacity     | L   | 0.601      | -            | -                | -                | -         |    -6.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2307 | 2024-05-06 | BLEED             | L   | 0.599      | -            | -                | -                | -         |    -6.33 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2352 | 2024-05-03 | Permitta          | W   | 0.581      | 0.435        | -                | 0.876 (0.221)    | -         |     8.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2364 | 2024-05-03 | BetBoom           | L   | 0.579      | -            | -                | -                | -         |    -1.23 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2399 | 2024-05-01 | OG                | W   | 0.568      | 0.435        | 0.139 (0.034)    | -                | -         |    12.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2408 | 2024-05-01 | Nexus             | W   | 0.567      | -            | -                | -                | -         |     6.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2450 | 2024-04-29 | HAVU              | L   | 0.553      | -            | -                | -                | -         |   -13.85 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2486 | 2024-04-27 | ex-Guild Eagles   | W   | 0.541      | -            | -                | -                | -         |     6.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2495 | 2024-04-27 | Permitta          | W   | 0.540      | 0.396        | -                | 0.876 (0.188)    | -         |     9.21 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2514 | 2024-04-26 | ARCRED            | L   | 0.534      | -            | -                | -                | -         |    -9.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2519 | 2024-04-26 | Enterprise        | W   | 0.533      | 0.396        | 0.039 (0.008)    | 0.625 (0.132)    | -         |     7.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2555 | 2024-04-25 | MOUZ NXT          | W   | 0.525      | 0.435        | 0.139 (0.032)    | 1.000 (0.228)    | -         |    10.97 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2580 | 2024-04-23 | EYEBALLERS        | W   | 0.515      | -            | -                | -                | -         |     7.51 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2629 | 2024-04-21 | Permitta          | L   | 0.499      | -            | -                | -                | -         |    -6.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3166 | 2024-04-03 | AMKAL             | L   | 0.382      | -            | -                | -                | -         |    -2.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3207 | 2024-04-02 | ex-Guild Eagles   | W   | 0.375      | -            | -                | -                | -         |     4.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3222 | 2024-04-02 | PARIVISION        | W   | 0.373      | -            | -                | -                | -         |     9.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3449 | 2024-03-18 | Sashi             | L   | 0.274      | -            | -                | -                | -         |    -1.86 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3508 | 2024-03-15 | CYBERSHOKE        | W   | 0.255      | -            | -                | -                | -         |     1.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3580 | 2024-03-13 | INGLORIOUS        | W   | 0.241      | -            | -                | -                | -         |     0.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3632 | 2024-03-11 | 1WIN              | W   | 0.228      | -            | -                | -                | -         |     3.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3676 | 2024-03-09 | Fraud5            | W   | 0.214      | -            | -                | -                | -         |     1.35 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3716 | 2024-03-07 | Sashi             | L   | 0.202      | -            | -                | -                | -         |    -1.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3751 | 2024-03-06 | The Chosen Few    | W   | 0.195      | -            | -                | -                | -         |     1.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3790 | 2024-03-05 | Johnny Speeds     | L   | 0.188      | -            | -                | -                | -         |    -0.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3797 | 2024-03-05 | Betera            | W   | 0.188      | -            | -                | -                | -         |     1.48 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4334 | 2024-02-09 | Sashi             | L   | 0.021      | -            | -                | -                | -         |    -0.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4343 | 2024-02-08 | ex-Guild Eagles   | W   | 0.015      | -            | -                | -                | -         |     0.18 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4349 | 2024-02-08 | AMKAL             | L   | 0.014      | -            | -                | -                | -         |    -0.08 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,421.26)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.835 | $7,000.00      | $5,844.84       |
| 2024-05-04 |      0.588 | $2,000.00      | $1,175.23       |
| 2024-03-25 |      0.321 | $1,250.00      | $401.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
