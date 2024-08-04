### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Global Rank: [72](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.5<br />
<br />
Final Rank Value (946.5) = Starting Rank Value (889.9) + Head To Head Adjustments (56.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.368[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 889.9
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 889.9


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
|           54 |        0 | 2024-08-04 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -10.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |       26 | 2024-08-03 | 1WIN              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |       54 | 2024-08-02 | ARCRED            | L   | 1.000      | -            | -                | -                | -         |   -15.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |       91 | 2024-08-01 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.92 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |      134 | 2024-07-31 | Sashi             | L   | 1.000      | -            | -                | -                | -         |    -6.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |      176 | 2024-07-30 | 9 Pandas          | L   | 1.000      | -            | -                | -                | -         |   -11.14 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |      241 | 2024-07-28 | Metizport         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.29 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |      367 | 2024-07-24 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |    -8.40 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |      437 | 2024-07-22 | Rebels            | L   | 1.000      | -            | -                | -                | -         |   -13.72 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |      502 | 2024-07-20 | UNiTY             | W   | 1.000      | 0.371        | 0.025 (0.009)    | -                | 0 (0.000) |    15.08 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |      540 | 2024-07-19 | 9INE              | L   | 1.000      | -            | -                | -                | -         |   -17.11 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |      578 | 2024-07-18 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.510 (0.255)    | 0 (0.000) |    10.18 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |      698 | 2024-07-16 | KOI               | L   | 1.000      | -            | -                | -                | -         |    -9.88 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |      777 | 2024-07-14 | Permitta          | W   | 1.000      | 0.371        | 0.024 (0.009)    | 0.876 (0.325)    | 0 (0.000) |    15.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |      840 | 2024-07-10 | Preasy            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |      862 | 2024-07-09 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -11.65 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |      881 | 2024-07-08 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -27.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     1138 | 2024-06-10 | ARCRED            | W   | 0.836      | 0.372        | 0.041 (0.013)    | -                | 0 (0.000) |    10.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     1185 | 2024-06-09 | RUBY              | W   | 0.828      | 0.372        | 0.095 (0.029)    | 0.502 (0.155)    | 0 (0.000) |    10.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     1241 | 2024-06-08 | Zero Tenacity     | W   | 0.822      | 0.372        | 0.137 (0.042)    | 1.000 (0.306)    | 0 (0.000) |    17.90 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     1307 | 2024-06-07 | Aurora Young Blud | W   | 0.815      | 0.372        | -                | 0.420 (0.127)    | -         |     9.03 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     1510 | 2024-06-03 | RUBY              | L   | 0.789      | -            | -                | -                | -         |   -12.37 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     1567 | 2024-06-01 | 1WIN              | W   | 0.775      | 0.372        | 0.027 (0.008)    | 0.628 (0.181)    | -         |    13.95 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     1620 | 2024-05-30 | VP.Prodigy        | W   | 0.762      | 0.372        | 0.026 (0.007)    | -                | -         |    11.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     2276 | 2024-05-07 | RUBY              | L   | 0.608      | -            | -                | -                | -         |    -9.63 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     2295 | 2024-05-06 | Zero Tenacity     | L   | 0.602      | -            | -                | -                | -         |    -6.70 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     2299 | 2024-05-06 | BLEED             | L   | 0.600      | -            | -                | -                | -         |    -6.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     2344 | 2024-05-03 | Permitta          | W   | 0.581      | 0.435        | -                | 0.876 (0.221)    | -         |     8.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     2356 | 2024-05-03 | BetBoom           | L   | 0.579      | -            | -                | -                | -         |    -1.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     2391 | 2024-05-01 | OG                | W   | 0.569      | 0.435        | 0.139 (0.034)    | -                | -         |    12.10 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     2400 | 2024-05-01 | Nexus             | W   | 0.567      | -            | -                | -                | -         |     6.60 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     2442 | 2024-04-29 | HAVU              | L   | 0.554      | -            | -                | -                | -         |   -13.84 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     2478 | 2024-04-27 | ex-Guild Eagles   | W   | 0.542      | -            | -                | -                | -         |     6.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     2487 | 2024-04-27 | Permitta          | W   | 0.541      | 0.396        | -                | 0.876 (0.188)    | -         |     9.25 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     2506 | 2024-04-26 | ARCRED            | L   | 0.535      | -            | -                | -                | -         |    -9.66 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     2511 | 2024-04-26 | Enterprise        | W   | 0.534      | 0.396        | 0.039 (0.008)    | 0.625 (0.132)    | -         |     7.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     2547 | 2024-04-25 | MOUZ NXT          | W   | 0.526      | 0.435        | 0.139 (0.032)    | 1.000 (0.229)    | -         |    11.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     2572 | 2024-04-23 | EYEBALLERS        | W   | 0.515      | -            | -                | -                | -         |     7.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     2621 | 2024-04-21 | Permitta          | L   | 0.499      | -            | -                | -                | -         |    -6.78 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     3158 | 2024-04-03 | AMKAL             | L   | 0.382      | -            | -                | -                | -         |    -2.73 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     3199 | 2024-04-02 | ex-Guild Eagles   | W   | 0.376      | -            | -                | -                | -         |     4.43 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     3214 | 2024-04-02 | PARIVISION        | W   | 0.374      | -            | -                | -                | -         |     9.04 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     3441 | 2024-03-18 | Sashi             | L   | 0.274      | -            | -                | -                | -         |    -1.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     3500 | 2024-03-15 | CYBERSHOKE        | W   | 0.256      | -            | -                | -                | -         |     1.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     3572 | 2024-03-13 | INGLORIOUS        | W   | 0.242      | -            | -                | -                | -         |     0.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     3624 | 2024-03-11 | 1WIN              | W   | 0.228      | -            | -                | -                | -         |     3.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     3668 | 2024-03-09 | Fraud5            | W   | 0.215      | -            | -                | -                | -         |     1.37 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     3708 | 2024-03-07 | Sashi             | L   | 0.203      | -            | -                | -                | -         |    -1.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     3743 | 2024-03-06 | The Chosen Few    | W   | 0.196      | -            | -                | -                | -         |     1.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     3782 | 2024-03-05 | Johnny Speeds     | L   | 0.189      | -            | -                | -                | -         |    -0.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|            4 |     3789 | 2024-03-05 | Betera            | W   | 0.189      | -            | -                | -                | -         |     1.50 | faydett, FpSSS, Pipw, Polt, sugaR |
|            3 |     4326 | 2024-02-09 | Sashi             | L   | 0.021      | -            | -                | -                | -         |    -0.12 | faydett, FpSSS, Pipw, Polt, sugaR |
|            2 |     4335 | 2024-02-08 | ex-Guild Eagles   | W   | 0.016      | -            | -                | -                | -         |     0.20 | faydett, FpSSS, Pipw, Polt, sugaR |
|            1 |     4341 | 2024-02-08 | AMKAL             | L   | 0.015      | -            | -                | -                | -         |    -0.09 | faydett, FpSSS, Pipw, Polt, sugaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,428.61)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.836 | $7,000.00      | $5,849.86       |
| 2024-05-04 |      0.588 | $2,000.00      | $1,176.67       |
| 2024-03-25 |      0.322 | $1,250.00      | $402.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
